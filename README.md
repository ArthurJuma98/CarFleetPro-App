# 🚗 CarFleetPro

CarFleetPro is a cutting-edge web application designed to transform the car trading experience in Kenya and beyond. Whether you're buying or selling, CarFleetPro offers a seamless, secure, and transparent platform to help you find the perfect vehicle or connect with trustworthy buyers.

---

## 📌 Technologies Used

- **Backend**: [Python](https://www.python.org/), [Django](https://www.djangoproject.com/)
- **Frontend**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML), [Tailwind CSS](https://tailwindcss.com/)
- **Database**: [SQLite](https://www.sqlite.org/index.html) (default Django DB for development)
- **Templating Engine**: Django Templates

---

## 🎯 About the App

CarFleetPro is built to address the challenges of traditional car trading platforms by offering:

- **Improved safety protocols**
- **Transparent vehicle listings**
- **User-centric interface**
- **Advanced search functionality**

Our goal is to make car buying and selling a stress-free, accessible, and enjoyable experience for all users.

---

## 🚀 Mission

To redefine the car trading experience by providing a safe, transparent, and community-driven platform that connects buyers and sellers with ease. We aim to become the go-to destination for car enthusiasts, dealers, and everyday users.

---

## ✨ Key Features

### ✅ User-Friendly Interface  
Clean, responsive design built with Tailwind CSS for an intuitive experience across all devices.

### ✅ Transparent Listings  
Each car listing includes detailed specifications, pricing, condition notes, and seller verification to help users make informed decisions.

### ✅ Safety First  
Built with robust user authentication and secure transaction handling to protect users and their data.

### ✅ Smart Search & Filters  
Advanced filtering allows users to easily browse listings by make, model, year, price range, fuel type, and more.

### ✅ Category-Based Navigation  
- Locally Used Cars  
- Newly Imported Cars  
- Foreign Used Cars  

### ✅ Scalable Architecture  
Built on Django with extensibility in mind — ready to integrate features like payments, reviews, and dealer dashboards.

---

## 🔐 Security & Privacy

- Encrypted password handling (via Django's auth system)
- Secure form submissions and CSRF protection
- Protection against SQL injection and common web vulnerabilities

---

## 📷 Screenshots

*()*

---

## 🛠️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/ArthurJuma98/CarFleetPro-App.git
cd CarFleetPro

# Create virtual environment
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the development server
python manage.py runserver
