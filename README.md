<!-- # SecuriCash 🔐

💰 Initially, banks were considered the economic middle channel only to lend money and
accept deposits from the population. But, with the implementation of privatisation and
globalisation policy, the banking sector has been rapidly adopting advanced technolo-
gies. Maintaining millions of transactions daily involves a great deal of data. This
data needs to be accessible to all branches around the clock. Cloud Computing is the
most convenient way to provide on-demand access to a shared pool of computational re-
sources over the network. And therefore, Banks are moving towards Cloud Computing.

☁️ The major drawback is that since the resources are available over the network, there
is a high probability of bad actors exploiting vulnerabilities in the cloud infrastructure.
This project deals with methods for the banks to identify security misconfigurations in
the cloud infrastructure and prevent any attacks.

![image](https://user-images.githubusercontent.com/56017960/176991538-e6705e44-06ce-4e8b-b4ce-06d297917334.png)

***

# Relevant Design 
![image](https://user-images.githubusercontent.com/56017960/176991561-ab9f1af2-6568-4eef-89a0-1b78dda3664f.png)

![image](https://user-images.githubusercontent.com/56017960/176991569-bf478a2a-3ab9-4046-b992-5bf6f587ea95.png)

***

## Project Setup 🔧

1. Clone the repo

   ```sh
   git clone https://github.com/KamparaVyshnavi/SecureCloud.git
   ```
2. Install NPM packages

   ```sh
   npm install
   ```
3. Create a .env file using the template .env.template and add values accordingly.
   
### Usage

1.  Switch to the Backend folder and run the backend server

    ```sh 
    npm start 
    ```
    
2.  Switch to the Frontend folder and run the frontend server

    ```sh 
    npm start 
    ```
    
    Make sure you start the Backend server before the Frontend server to avoid unnecessary errors.
*** -->


# SecuriCash 🔐

💰 Initially, banks were considered the economic middle channel only to lend money and accept deposits from the population. But, with the implementation of privatisation and globalisation policy, the banking sector has been rapidly adopting advanced technologies. Maintaining millions of transactions daily involves a great deal of data. This data needs to be accessible to all branches around the clock. Cloud Computing is the most convenient way to provide on-demand access to a shared pool of computational resources over the network. Therefore, banks are moving towards Cloud Computing.

☁️ The major drawback is that since the resources are available over the network, there is a high probability of bad actors exploiting vulnerabilities in the cloud infrastructure. This project deals with methods for banks to identify security misconfigurations in cloud infrastructure and prevent potential attacks.

![image](https://user-images.githubusercontent.com/56017960/176991538-e6705e44-06ce-4e8b-b4ce-06d297917334.png)

---

# Relevant Design

![image](https://user-images.githubusercontent.com/56017960/176991561-ab9f1af2-6568-4eef-89a0-1b78dda3664f.png)

![image](https://user-images.githubusercontent.com/56017960/176991569-bf478a2a-3ab9-4046-b992-5bf6f587ea95.png)

---

## Tech Stack

* Frontend: React
* Backend: Node.js, Express.js
* Database: MongoDB
* Authentication: JWT (RSA-based)
* Email Service: Nodemailer

---

## Project Setup 🔧

### 1. Clone the Repository

```bash
git clone <repository-url>
cd Secure-Cash
```

### 2. Install Dependencies

Backend:

```bash
cd backend
npm install
```

Frontend:

```bash
cd frontend
npm install --legacy-peer-deps
```

### 3. Configure Environment Variables

Create a `.env` file inside the `backend` directory and configure the required environment variables:

```env
NODE_ENV=development
PORT=8000

DEV_DATABASE_URL=mongodb://localhost:27017/securecash

PUBLIC_KEY=<your_public_key>
PRIVATE_KEY=<your_private_key>

EMAIL=<your_email>
PASS=<your_email_password>
```

### 4. Generate RSA Keys

From the `backend/services` directory:

```bash
node keys.service.js generate
```

This generates:

```text
id_rsa_pub.pem
id_rsa_priv.pem
```

Use the generated keys in the backend `.env` file.

### 5. Start MongoDB

Ensure MongoDB is running locally before starting the backend server.

---

## Running the Application 🚀

### Start Backend

```bash
cd backend
npm start
```

Backend runs on:

```text
http://localhost:8000
```

### Start Frontend

```bash
cd frontend
npm start
```

Frontend runs on:

```text
http://localhost:3000
```

Start the backend server before launching the frontend.

---

## Features

* User Registration & Authentication
* JWT-Based Authorization
* Email Verification Support
* Cloud Security Misconfiguration Detection
* Account Monitoring & Scanning
* Plugin-Based Security Checks

---
