# cleartrace
Here's a **detailed and structured README.md** file tailored for your hackathon project. It includes all necessary sections to make your project presentable and easy to understand for judges or collaborators.

---

# **OSINT and Cybersecurity Risk Assessment Web Application**

This project is a **Flask-based web application** that uses **Open-Source Intelligence (OSINT)** tools and **email risk analysis** to help users understand their digital footprint and protect sensitive data. It provides actionable insights into email-related threats, helps users identify online vulnerabilities, and offers solutions for data removal.

---

## **Problem Statement**
With the rise of data breaches and phishing attacks, individuals and organizations face increasing risks of cyber threats. There is a lack of easy-to-use tools for:
1. Assessing the risks associated with their email addresses.
2. Removing sensitive data from the internet.
3. Educating users about common cybersecurity threats.

---

## **Solution**
This web application:
1. Combines OSINT tools and email risk analysis services to provide a comprehensive risk assessment for an email address.
2. Offers both **manual** and **automated** data removal options for compromised or sensitive data.
3. Educates users about cybersecurity risks through an interactive quiz.

---

## **Features**

### **1. OSINT Analysis**
- Integrates OSINT tools such as:
  - **theHarvester**: Gathers emails, subdomains, and IP addresses.
  - **SpiderFoot**: Performs in-depth reconnaissance of email and domain data.
  - **Holehe**: Finds accounts associated with an email ID.
  - **Sherlock**: Identifies social media profiles linked to an email.

### **2. Email Risk Assessment**
- Uses APIs for:
  - **Have I Been Pwned (HIBP)**: Checks if an email ID is part of known data breaches.
  - **EmailRep.io**: Evaluates email reputation and risk level.

### **3. Data Removal Assistance**
- **Manual Instructions**:
  - Provides step-by-step guides and platform links to delete data.
  - Saves instructions in a downloadable `manual_removal.txt` file.
- **Automated Removal**:
  - Sends removal requests to supported platforms and logs the process in `automated_removal.txt`.

### **4. Cybersecurity Quiz**
- An educational quiz covering:
  - Malicious websites.
  - Phishing attacks.
  - Fake websites.
  - Corrupted devices.

---

## **Project Workflow**

### **1. Enter Email Address**
Users provide an email address on the homepage.

### **2. View Results**
The app displays:
- OSINT results from integrated tools.
- Email risk details from HIBP and EmailRep.

### **3. Choose Data Removal Options**
- View and download manual removal instructions.
- Initiate automated removal requests for selected platforms.

### **4. Take the Cybersecurity Quiz**
Users can test their knowledge of cybersecurity threats through an interactive quiz.

---

## **Technology Stack**

### **Backend**:
- **Python**: Flask framework.
- Integrated OSINT tools and external APIs.

### **Frontend**:
- HTML, CSS, and Bootstrap (optional for styling).

### **Hosting Options**:
- Replit
- PythonAnywhere
- Render

---

## **Installation**

### **Prerequisites**:
- Python 3.8 or later.

### **Steps**:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/osint-cybersecurity-app.git
   cd osint-cybersecurity-app
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   python app.py
   ```

4. **Open in Browser**:
   - Navigate to `http://127.0.0.1:5000`.

---

## **File Structure**
```
osint-cybersecurity-app/
├── app.py                # Main Flask application
├── scripts/              # Helper scripts
│   ├── ct.py             # OSINT tools integration
│   ├── data_removal.py   # Data removal logic
├── templates/            # HTML templates
│   ├── index.html        # Homepage
│   ├── results.html      # OSINT results
│   ├── remove_data.html  # Data removal options
│   ├── removal_status.html # Automated removal results
├── static/               # Static assets (CSS, JS, etc.)
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
├── .gitignore            # Ignored files (e.g., API keys, cache)
```

---

## **Usage**

### **1. OSINT Analysis**
- Run multiple OSINT tools.
- View email-related online presence and vulnerabilities.

### **2. Email Risk Assessment**
- View breach details and reputation scores.
- Identify potential threats to an email.

### **3. Data Removal**
- Download `manual_removal.txt` for platform-specific removal instructions.
- View `automated_removal.txt` for logs of removal requests.

### **4. Cybersecurity Quiz**
- Test knowledge about phishing, malicious websites, and more.

---

## Screenshots

1. Homepage:
   - Input email for OSINT and risk analysis.

2. Results Page:
   - Display results from OSINT tools, HIBP, and EmailRep.

3. Data Removal Options**:
   - Manual and automated removal workflows.

4. Quiz Page:
   - Interactive questions on cybersecurity topics.

---
