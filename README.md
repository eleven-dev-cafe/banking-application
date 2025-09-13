# 🏦 Banking Application (Parent Repository)

This repository acts as the **parent repo** for the complete Banking Application project.  
It contains **two submodules**:

- **Backend** – Spring Boot project (`banking-backend-app`)  
- **Frontend** – Android app (`banking-frontend-app`)

Both are tracked as Git submodules for easier version control and synchronization.

<br>

## 📂 Repository Structure

```bash
banking-application/
├── banking-backend-app/            # Spring Boot backend with REST APIs & JWT security
├── banking-frontend-app/           # Android app (Java/XML) for users and admins
└── README.md                       # You are here
```
<br>

## 🚀 Features
- Full Banking Solution
  - Account Management (Create, View, Update)
  - Transactions (Deposit, Withdraw, Transfer)
  - Role-based Access (Admin, Manager, Super Admin)
- Secure Authentication
  - JWT-based login for backend APIs
- Frontend & Backend Separation
  - Independent development with shared parent repo
  - Easy CI/CD pipeline integration
 
<br>

## 🛠️ Setup Instructions
#### 1️⃣ Clone the Parent Repository with Submodules
```bash
git clone --recurse-submodules https://github.com/eleven-dev-cafe/banking-application.git
```
If you already cloned without --recurse-submodules, run:
```bash
git submodule update --init --recursive
```

#### 2️⃣ Run Backend (Spring Boot)
```bash
cd backend
./mvnw spring-boot:run
```

#### 3️⃣ Run Frontend (Android App)
- Open your-bank-frontend/ in Android Studio
- Build and run on an emulator or physical device.

#### 🔄 Keeping Submodules Updated
To pull latest changes from backend/frontend:
```bash
git submodule update --remote --merge
```
<br>

## 👨‍💻 Developer

`Gyarsilal Solanki`
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/gyarsilal-solanki) [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/gyarsilalsolanki011) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/itz_gsl_tiger)
- [![WhatsApp](https://img.shields.io/badge/WhatsApp-%2325D366.svg?logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send/?phone=919111852267) [![Gmail](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:gyarsilalsolanki011@gmail.com)


Join us to discuss ideas, share feedback, and coordinate contributions:  
[![Join Discord](https://img.shields.io/discord/1405808666179014697?color=4CBB17&label=Join%20Us%20on%20Discord&logo=discord&logoColor=blue)](https://discord.gg/Zrc9x3ts)

***If you find this project helpful, consider giving it a ⭐ to support!***
