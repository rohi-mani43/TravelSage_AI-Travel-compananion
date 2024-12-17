# TravelSage:AI Powered Travel-compananion
Description
The AI-Powered Blockchain Travel Companion is an innovative web application that integrates artificial intelligence and blockchain technologies to provide travelers with personalized trip planning and secure payment processing. This project combines Flask, AI-driven recommendations, and Ethereum blockchain for a seamless and efficient travel experience.
Key Features:
1.	User Registration & Authentication
Secure user registration and login with password hashing.
2.	AI-Generated Travel Plans
o	Personalized travel itineraries based on user preferences like destination, budget, and duration.
o	AI-generated recommendations include weather information, must-visit locations, transportation options, food suggestions, and safety tips.
3.	Weather Integration
Real-time weather updates powered by OpenWeatherMap API.
4.	Blockchain Payments
o	Secure travel payments using Ethereum on the Sepolia test network.
o	Integration with smart contracts for recording payment transactions.
5.	Database Management
SQLite database to store user details, travel plans, and transaction histories.
________________________________________
Technologies Used
•	Backend: Flask (Python)
•	AI Integration: Gemini AI API
•	Blockchain: Ethereum, Web3.py, Infura
•	Database: SQLite
•	Weather API: OpenWeatherMap
•	Frontend: HTML, CSS
•	Other Libraries:
o	requests for HTTP API calls
o	google.generativeai for AI integration
o	geopy for geolocation services
o	cryptography for secure encryption
o	dotenv for environment variables
o	werkzeug.security for password hashing
________________________________________
Prerequisites
1.	Python 3.x installed.
2.	Install required libraries:
bash
Copy code
pip install flask sqlite3 web3 requests geopy python-dotenv cryptography google-generativeai
3.	Ethereum Testnet Account: Use the Sepolia Testnet for blockchain testing.
4.	API Keys:
o	Gemini AI API Key: Obtain from Google AI Services.
o	OpenWeatherMap API Key: Sign up here.
o	Infura Project ID: Register on Infura.
5.	Create a .env file to store sensitive information:
env
Copy code
SECRET_KEY=your_secret_key_here
GEMINI_API_KEY=your_gemini_api_key_here
OPENWEATHER_API_KEY=your_openweather_api_key_here
INFURA_PROJECT_ID=your_infura_project_id_here
SMART_CONTRACT_ADDRESS=your_smart_contract_address_here
ENCRYPTION_KEY=your_encryption_key_here
________________________________________
Setup Instructions
1.	Clone the Repository:
bash
Copy code
git clone https://github.com/your-username/travel-companion.git
cd travel-companion
2.	Initialize the Database: Run the following script to create the SQLite database and tables:
bash
Copy code
python -c "from your_app_name import init_db; init_db()"
3.	Run the Flask App: Start the development server:
bash
Copy code
python your_app_name.py
Access the app at http://127.0.0.1:5000.
________________________________________
Project Structure
bash
Copy code
travel-companion/
│
├── templates/               # HTML Templates (index.html, register.html, login.html, etc.)
├── static/                  # Static files (CSS, JS)
├── .env                     # Environment variables
├── your_app_name.py         # Main Flask app file
├── travel_companion.db      # SQLite database file
└── README.md                # Project documentation
________________________________________
Usage
1.	Register & Login:
o	New users can sign up by providing a username, password, and mobile number.
o	Existing users can log in to access personalized travel planning.
2.	Plan a Trip:
o	Enter your destination, budget, travel duration, and interests.
o	AI will generate a day-by-day itinerary, estimated costs, and recommendations.
3.	View Weather Updates:
Real-time weather information is displayed alongside the travel plan.
4.	Make Payments:
o	Use blockchain-powered secure payments via Ethereum.
o	Transactions are recorded on the Sepolia testnet and can be tracked using the transaction hash.
_______________________________________
Deployment
To deploy the app, consider hosting on platforms like Heroku, AWS, or DigitalOcean. Make sure to set your environment variables securely on the server.
________________________________________
Acknowledgements
•	Google Gemini AI
•	OpenWeatherMap API
•	Infura for Ethereum
•	Flask, Web3.py, and Geopy Libraries
________________________________________
Author
•	Peruri Rohith Manikanta
•	Email: rohithmanikantaperuri@gmail.com
•	LinkedIn:https://www.linkedin.com/in/rohith-manikanta-peruri-a3323b2b8/
________________________________________
License
This project is licensed under the MIT License.
Feel free to fork, modify, and use it as needed.
________________________________________
Let me know if you'd like me to refine this further!
