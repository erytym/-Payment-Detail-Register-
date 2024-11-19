
# Payment Detail Register

Payment-Detail-Register is a full-stack application built using Angular (frontend) and ASP.NET Core (backend). The application provides functionality to manage payment details, including creating, reading, updating, and deleting payment information in a secure and efficient manner.

This project demonstrates best practices in web development, including clean architecture, modular design, and secure data handling.


## Setup Instructions

Clone the Repository:

```bash
  https://github.com/erytym/-Payment-Detail-Register-.git
```

Restore Dependencies:

```bash
dotnet restore
dotnet run
npm install
ng serve


```
Directory Structure:

```bash
frontend/
├── src/
│   ├── app/
│   │   ├── components/
│   │   ├── services/
│   │   ├── models/
│   │   └── app.module.ts
│   ├── assets/
│   └── environments/
└── angular.json

```
API Endpoints:

```bash
Endpoint	                HTTP Method	Description
/api/paymentdetails	        GET	Retrieve all payment details
/api/paymentdetails/{id}	GET	Retrieve a specific payment detail
/api/paymentdetails	POST	Add a new payment detail
/api/paymentdetails/{id}	PUT	Update a payment detail
/api/paymentdetails/{id}	DELETE	Delete a payment detail
```

## Screenshots

Overview:


![Screenshot (63)](https://github.com/user-attachments/assets/ed3e937e-8bdf-475e-8c98-70d69ce0cfd9)

![Screenshot (64)](https://github.com/user-attachments/assets/9471f570-72da-4bce-93dc-b82f35a71ee3)
