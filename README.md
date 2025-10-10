# C.L.A.I.M.S. - Computer Laboratory Assets and InventoryManagement System
> A modular system built using multiple multiple services for scalability and flexibility.  
> This repository serves as the **root documentation and entry point** for the services that the project uses
---
## Overview
- This project is designed using a **microservices architecture** setup where each service handles a specific domain function.  
- Each service is independently deployable and communicates via REST APIs or message queues.
---
## Technologies Used
| Layer                | Technology                    |
| -------------------- | ----------------------------- |
| **Frontend**         | React JS + Vite + Bootstrap 5 |
| **Backend**          | Flask (Python)                |
| **Database**         | MySQL                         |
| **Authentication**   | JWT, bcrypt, HttpOnly Cookies |
| **API Gateway**      | Nginx                         |
| **Containerization** | Docker + Coolify              |
| **Version Control**  | Git + GitHub                  |
| **CI/CD**            | GitHub Actions (Optional)     |

---
## Services
| Service               | Description                                                      | Repository                                                            |
| --------------------- | ---------------------------------------------------------------- | --------------------------------------------------------------------- |
| **Website**           | Serves the content for the web application                       | [Github Repository](https://github.com/bleunar/capstone-frontend-web) |
| **Authentication**    | Handles user authentication, authorization using JSON Web Tokens | [Github Repository](https://github.com/bleunar/capstone-backend-auth) |
| **Inventory Service** | Tracks assets, equipment, and inventory data                     | [Github Repository](https://github.com/bleunar/capstone-backend-api)  |
| **Database**          | Centralized data access, migrations, and backups                 | None                                                                  |
