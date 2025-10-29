🌿 EcoMine
Rewarding people for doing good for the planet.
Ecomine is a web platform where users can upload proof of their eco-friendly actions — like planting trees, recycling, or saving energy — and earn EcoCoins once verified. These coins can then be redeemed for rewards or donated toward global sustainability causes.

🌱 Inspiration
Most eco-friendly actions go unnoticed. I wanted to create something that makes people feel good about doing good — motivating individuals to take small, meaningful steps toward a greener future.

💡 What It Does
Users perform a green activity (e.g., plant a tree, recycle, etc.)
Upload proof (photo or description)
Admin reviews and approves/rejects the proof
Approved users earn EcoCoins
Coins can be redeemed for rewards or donated

🧠 Features
User Login / Register
Proof Upload & Verification
EcoCoin Wallet System
Reward Redemption
Global Impact Dashboard
Admin Panel for Proof Approval
Leaderboard & Community Stats

🛠️ Built With
Frontend: HTML5, CSS3, JavaScript, Bootstrap
Backend: Python (Flask)
Database: MySQL (with SQLAlchemy ORM)
Libraries: Chart.js, Flask-Login
Hosting: Render / XAMPP

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/30tan05/EcoMine
cd ecomine

2️⃣ Set Up Virtual Environment
python -m venv venv
venv\Scripts\activate   # For Windows
source venv/bin/activate  # For Mac/Linux

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Configure Database

Update your MySQL credentials in app.py:

app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql://root:yourpassword@localhost/ecomine'


Then, create the database:

flask shell
>>> from app import db
>>> db.create_all()
>>> exit()

5️⃣ Run the App
flask run


Open your browser and go to:
👉 http://127.0.0.1:5000

🧩 Folder Structure
ecomine/
│
├── static/               # CSS, JS, images
├── templates/            # HTML files
├── app.py                # Main Flask app
├── models.py             # Database models
├── requirements.txt      # Dependencies
└── README.md             # Project documentation

🏆 Accomplishments
Built a full-stack eco-reward platform from scratch
Integrated backend verification and reward logic
Designed a clean, easy-to-use interface for users and admins

📚 What I Learned
Flask & SQLAlchemy integration
Managing user authentication and data flow
Building impact-driven, gamified experiences

🚀 What’s Next
AI-based proof verification
Mobile app version
Brand partnerships for real rewards
Global leaderboards & sustainability challenges

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to modify.
