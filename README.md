# IPO Web Application & REST API Development

## Project Overview
This project is for developing an **IPO Web Application** along with a **REST API** for **Bluestock Fintech**. The application will provide IPO-related information, including company details, issue details, listing details, and real-time updates.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Project Setup](#project-setup)
- [Development Guidelines](#development-guidelines)
- [Task Management](#task-management)
- [Resources](#resources)
- [Contributors](#contributors)

## Objectives
- Build a web application that displays IPO-related information to users.
- Develop a REST API to provide IPO data.
- Ensure high-quality, industry-standard code.
- Maintain data security and integrity.

## Tech Stack
### Backend
- **SDK:** Python (3.12.3)
- **Framework:** Django (5.0.6)
- **API Framework:** Django REST Framework (3.15.1)
- **Database:** PostgreSQL
- **Tools:** Postman (for API testing), Git & GitHub (for version control)

### Frontend
- **Technologies:** HTML, CSS, JavaScript (Plain, no Node.js)
- **Framework:** Bootstrap 5
- **IDE:** Visual Studio Code (VS Code)

## Features
The IPO Web Application will include:
- **Company Information**: Logo, Name
- **IPO Details**: Price Band, Open/Close Date, Issue Size, Issue Type
- **Listing Details**: Listing Date, Status, IPO Price, Listing Price, Listing Gain
- **Market Updates**: Current Market Price (CMP), Current Return
- **Downloadable Documents**: RHP PDF, DRHP PDF

## Project Setup
1. **Clone the Repository**
   ```bash
   git clone <repo-link>
   cd <repo-folder>
   ```
2. **Setup Virtual Environment**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use: env\Scripts\activate
   ```
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run Migrations**
   ```bash
   python manage.py migrate
   ```
5. **Run the Development Server**
   ```bash
   python manage.py runserver
   ```
6. **Open in Browser**
   - Visit `http://127.0.0.1:8000/` to access the application.

## Development Guidelines
- Follow the system design on **[Figma](https://www.figma.com/board/g9bjreevYNJkfMuwRacyaP/System-Design?node-id=0-1)**.
- Write **clean, modular, and well-documented** code.
- Implement **data validation and security best practices**.
- Test all features rigorously before pushing code.
- Use **Postman** for API testing.

## Task Management
- Use **Nomon** for assigning and tracking tasks.
- Developers must **report daily work status** to the Team Lead.
- Team Lead should **report progress every 7 days** to Mr. Yash Kale.
- If any developer needs to change roles, they must obtain permission from the Team Lead.

## Resources
- **UI/UX Design**: [Figma Link](https://www.figma.com/design/IyF5MKCS7GP2ChFBOiWXAK/bluestock-fintech-ui-ux-team?node-id=0-1)
- **System Design**: [Figma Board](https://www.figma.com/board/g9bjreevYNJkfMuwRacyaP/System-Design)
- **Assets (Logo, SVG, PNG, etc.)**: [Google Drive](https://drive.google.com/drive/folders/1yH9Y_mIqqEkZXtzhqHSuFtEwFOr8BXH5?usp=drive_link)

## Contributors
| Name | Email | Role |
|------|------|------|
| Anshul Sharma | sasansanshul@gmail.com | Team Lead |
| Sankalp Kumar | sankalp249@gmail.com | Co-Team Lead |
| Abhishek Kumar | itzabhi1114@gmail.com | Developer |
| M. Thanmai | thanmaimajjiga124@gmail.com | Developer |
| Addlin Vini V N | vini21032004@gmail.com | Developer |
| Harshit Soni | mailtoh.soni@gmail.com | Developer |
| Khalid Faisal | khalidfaisal0123@gmail.com | Developer |
| Movva Deekshitha | deekshithamovva@gmail.com | Developer |

## License
This project is licensed under the **Bluestock Fintech License**. Unauthorized use, reproduction, or distribution is prohibited.

---
_Clone this repository and start contributing!_

