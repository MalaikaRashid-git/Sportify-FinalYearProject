# Sportify-FinalYearProject
  Dividing our project into 2 main parts
├── frontend/ # Frontend (React)
├── backend/ # Backend (Node.js + Express)
We follow a **feature-branch workflow** to ensure clean collaboration and reduce merge conflicts.
| `main`      | Production-ready final code             |
| `frontend`  | Main working branch for UI development  |
| `backend`   | Main working branch for API/backend|

🔹 Feature Branches
All new features should be developed in dedicated branches created from the relevant main branch (`frontend` or `backend`).
Examples:
- `backend-login` – Implements user login API
- `backend-db` – Database schema setup
- `frontend-navbar` – Navbar component
- `frontend-auth-ui` – Login/Signup pages

  Workflow for Team Members
  git clone <repo-url>
  cd Sportify-FinalYearProject
  
git checkout backend          # or frontend
git pull origin backend       # update your local branch
git checkout -b backend-login # create feature branch
# Do your work
git add .
git commit -m "backend: added login API"
git push origin backend-login

 Create Pull Request
 Go to GitHub
 Compare & create Pull Request: backend-login → backend
 Get your PR reviewed and merged

