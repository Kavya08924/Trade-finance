# Trade-finance

Transparent, tamper-evident tracking of trade finance artifacts with ledger-style explorer and risk insights 



Trade Finance Blockchain Explorer



Transparent, tamper-evident tracking of trade finance artifacts (Letters of Credit, invoices, shipping documents) with a ledger-style explorer and risk insights.



🚀 Features



Document repository with hashing



Ledger explorer for lifecycle events



Transaction history viewer



Risk scoring \& anomaly detection



Secure API for backend integration



Frontend dashboard for quick insights



🏗️ Tech Stack

Backend



FastAPI



Python



Uvicorn



Frontend



React / Vite



JavaScript



Database



SQLite / PostgreSQL (optional)



Blockchain Layer



Custom lightweight ledger + hashing



📁 Folder Structure

Trade-finance/

│

├── backend/

│   ├── app/

│   ├── requirements.txt

│   ├── docker-compose.yml

│   ├── env.example

│   └── .gitignore

│

├── frontend/

│   ├── src/

│   ├── package.json

│   └── .gitignore

│

└── README.md



⚙️ Backend Setup

cd backend

python -m venv venv

source venv/Scripts/activate

pip install fastapi uvicorn

pip freeze > requirements.txt

uvicorn app.main:app --reload



🎨 Frontend Setup

cd frontend

npm install

npm run dev



📌 API Endpoints (Basic)

Method	Route	Description

GET	/	API health check

POST	/transactions	Add trade transaction

GET	/transactions/{id}	Retrieve transaction

GET	/blocks	Ledger blocks

