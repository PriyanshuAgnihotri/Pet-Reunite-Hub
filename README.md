
# Pet-Reunite-Hub

### Live Demo
[https://pet-reunite-hub-ten.vercel.app](https://pet-reunite-hub-ten.vercel.app)

---

##  Overview
**Pet-Reunite-Hub** is a full-stack application designed to help reunite lost pets with their owners. Users can post listings for lost or found pets, browse existing posts, and contact one another to facilitate safe reunions.

---

##  Features
- **User Authentication**: Secure registration and login flow for users.
- **Lost/Found Listings**: Users can create, edit, and browse pet listings with descriptions and images.
- **Search & Filters**: Filter listings by location, pet type, or status (lost/found).
- **Direct Contact**: Connect through messaging or contact forms to coordinate reunions.
- **Responsive Design**: Works smoothly across devices.

---

##  Tech Stack

| Layer        | Technologies                        |
|--------------|--------------------------------------|
| Frontend     | JavaScript, React (assumed), HTML, CSS |
| Backend      | Node.js (Express), RESTful API (assumed) |
| Database     | MongoDB or similar (assumed)          |
| Hosting      | Vercel (frontend), possibly Heroku/Netlify (backend) |
| Other Tools  | File upload support (images), environment variables |

---

##  Project Structure
- `pet-frontend-master/`: Frontend application code
- `Pet-Backend-main/`: Backend API and database models
- Optionally, shared configuration or deployment files

---

##  Setup & Running Locally

```bash
# Clone the repo
git clone https://github.com/PriyanshuAgnihotri/Pet-Reunite-Hub.git
cd Pet-Reunite-Hub

# Frontend
cd pet-frontend-master
npm install
npm run start

# Backend
cd ../Pet-Backend-main
npm install
npm run dev  # or `npm start`

# Visit http://localhost:3000 (frontend) and http://localhost:5000 (backend)
