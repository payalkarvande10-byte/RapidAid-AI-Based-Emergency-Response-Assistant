# **RapidAid – AI Powered Emergency First Aid Assistant**

RapidAid is a web-based emergency first aid assistance platform designed to provide instant medical guidance during emergencies. It offers AI-powered first aid instructions, multilingual support, emergency contact management, panic alerts, and admin monitoring.

**Live Demo:** https://rapidai-emergency-ai-assistant.onrender.com/

Built using **Python Flask**, **SQLite/MySQL**, and **Vanilla JavaScript**.

---

# **Features**

## **User Features**

### **Emergency First Aid Guidance**

* Burns
* Bleeding
* Fractures
* Choking
* Heart Attack
* Drowning

### **AI-Assisted Guidance**

* Smart emergency advice based on the situation.

### **Multilingual Support**

* English
* Hindi
* Marathi

### **Emergency Calling**

* Ambulance (108)
* Police (100)
* Fire Brigade (101)

### **Emergency Contact Management**

* Add, update, and delete contacts.

### **Panic Mode**

* Sends emergency SMS alerts to saved contacts.

### **History Tracking**

* Stores all emergency sessions for future reference.

---

## **Admin Features**

* User Management
* Panic Logs Monitoring
* System Dashboard
* User Details Tracking

---

# **Tech Stack**

## **Backend**

* Python
* Flask
* Flask-CORS
* SQLite / MySQL
* PyMySQL

## **Frontend**

* HTML
* CSS
* JavaScript

## **AI Integration**

* Hugging Face API

## **Messaging Service**

* Twilio API

---

# **Installation**

## **1. Clone the Repository**

```bash
git clone <your-github-repo-link>
cd rapidaid
```

## **2. Create Virtual Environment**

```bash
python -m venv venv
```

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

## **3. Install Dependencies**

```bash
pip install -r requirements.txt
```

## **4. Setup Environment Variables**

Create `.env` file:

```env
SECRET_KEY=your_secret_key
TWILIO_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_auth_token
TWILIO_PHONE=your_twilio_phone_number
HF_API_KEY=your_huggingface_api_key
```

## **5. Run the Application**

```bash
python app.py
```

Application will run on:

```bash
http://localhost:5000
```

---

# **Author**

Developed by **Payal Karvande**

---

# **License**

This project is for educational and academic purposes.
