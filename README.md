# HNG Stage 0 Backend API

This is a simple public API developed as part of the HNG Stage 0 task. The API provides basic information such as the registered email, current date and time in ISO 8601 format, and the GitHub repository URL.

## Features
- Returns email, current UTC datetime, and GitHub repository URL in JSON format.
- Deployed to a publicly accessible endpoint.
- CORS handling enabled for cross-origin requests.
- Fast response time (<500ms).

## Live API Endpoint
[https://hng-stage0-backend-api-94ho.vercel.app/](https://hng-stage0-backend-api-94ho.vercel.app/)

## Technologies Used
- **Programming Language**: Python
- **Framework**: FastAPI
- **Deployment**: Vercel

## API Documentation
### **GET /**
Returns basic information in JSON format.

#### **Request**
```http
GET https://hng-stage0-backend-api-94ho.vercel.app/
```

#### **Response Format**
```json
{
  "email": "sccsmartcode@gmail.com",
  "current_datetime": "2025-01-29T21:15:30.123456Z",
  "github_url": "https://github.com/SCCSMARTCODE/hng-stage0-backend-api"
}
```

## Setup Instructions
### **Clone the Repository**
```sh
git clone https://github.com/SCCSMARTCODE/hng-stage0-backend-api.git
cd hng-stage0-backend-api
```

### **Install Dependencies**
Ensure you have Python installed, then install required dependencies:
```sh
pip install -r requirements.txt
```

### **Run the Application Locally**
```sh
python app.py
```

### **Test Locally**
Once running, open your browser or use Postman to access:
```http
http://127.0.0.1:8001/
```

## Deployment
This project is deployed on **Vercel**. To deploy manually:
1. Install Vercel CLI:
   ```sh
   npm install -g vercel
   ```
2. Deploy the project:
   ```sh
   vercel
   ```

## Hiring Links
Looking for backend developers? Check out:
- [Python Developers](https://hng.tech/hire/python-developers)
- [C# Developers](https://hng.tech/hire/csharp-developers)
- [Golang Developers](https://hng.tech/hire/golang-developers)
- [PHP Developers](https://hng.tech/hire/php-developers)
- [Java Developers](https://hng.tech/hire/java-developers)
- [Node.js Developers](https://hng.tech/hire/nodejs-developers)

## License
This project is open-source and available under the MIT License.