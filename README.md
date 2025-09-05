# SymptoMed

SymptoMed is a portfolio project that helps users explore medical and supplement data.  
It will integrate the **OpenFDA API** to fetch drug information and combines it with a custom supplements database to provide insights tailored to user profiles.  

## Features (planned)
- 🔍 Search for medications by symptoms (via OpenFDA API)  
- 💊 View key details: purpose, warnings, dosage, and uses  
- 🧩 Personalized recommendations based on user profile (age, conditions, supplements, etc.)  
- 🔐 User authentication (with JWT/Passport) + demo login options  
- ☁️ Deployed on Render with MongoDB Atlas backend  

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express  
- **Database**: MongoDB Atlas (Mongoose ODM)  
- **APIs**: [OpenFDA Drug API](https://open.fda.gov/apis/drug/) + custom supplements API  
- **Authentication**: JWT, Passport.js, bcrypt  
