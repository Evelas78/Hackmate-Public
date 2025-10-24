<h1>HackMate</h1>
<h4>Statement of Work: </h4>
HackMate is a platform that is designed to help hackathon participants find other teammates. Whether they are looking for other beginners with similar experience or team members who are highly skilled, HackMate provides a platform that is able to simplify  forming a team. Through providing a user profile that includes a person’s skills, level of experience, availability, and more, HackMate ensures that users can connect with people that complement their goals and abilities.

<br><h4>Team Members:</h4>
- Earl Velasquez 
- Vaishali Sathiyachalam
- Naomi Ntuli
- Hrishikesh Srirangam
- Dhakshin Parimalakumar
- Ifrah Zainab
- Saivishaal Sureshkannan
- Rajit Goel

---

## How to Run the Application:

### Prerequisites
Before running the application, ensure you have the following installed on your system:
- [Node.js (LTS)](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Git](https://git-scm.com/) (optional, for cloning the repository)
- [Visual Studio Code (VSCode)](https://code.visualstudio.com/)
- [MongoDB](https://www.mongodb.com/)
### 1. Clone the Repository
Open a terminal and run the following command to clone the repository:
```bash
git clone https://github.com/Evelas78/HackMate-Public.git
```
### 2. Naviagte to the Project Directory
Open two terminals and move into the project folder on both terminals:
```bash
cd /workspaces/HackMate-Main
```
### 3. Install Dependencies
Install the dependencies needed for both frontend and backend (one on each terminal):
```bash
# Navigate to the backend folder and download its dependencies
cd backend
npm install

# Navigate to the frontend folder and download its dependencies
cd frontend
npm install
```
### 4. Set up .env
Create a MongoDB cluster then create .env
```bash
# Navigate to the backend folder and create a .env file
MONGO_URI= (Mongodb+srv://(your info))
PORT=3000
JWT_SECRET=(Your own)
```

### 4. Start the Servers
Start the frontend and backend servers on their respective terminals:
```bash
# Run this line on the backend terminal then the frontend terminal
npm run dev
```

### 5. Open the Application
If not already prompted to open the site, navigate to [http://localhost:5173/](http://localhost:5173/) on your local browser.
