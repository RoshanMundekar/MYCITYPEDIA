
# Smart City Web Application

A web-based application developed using Python, Flask, MySQL, HTML, and CSS to provide comprehensive information about a city. This application helps newcomers and residents to find information about tourism, education, hospitals, hotels, and local businesses, all in one platform.

---

## Features

- User Registration and Authentication
- City Guide Information
  - Tourism spots
  - Hotels and Restaurants
  - Educational Institutions (Schools, Colleges, Universities)
  - Hospitals and Healthcare facilities
- Admin Dashboard
  - Manage city data
  - Generate daily/weekly/monthly reports
- Barcode-based Time Slot Booking for selected services
- Mobile-friendly and responsive design

---

## Technology Stack

- **Frontend:** HTML, CSS
- **Backend:** Python, Flask
- **Database:** MySQL
- **Development Environment:** Anaconda Navigator, Spyder

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/RoshanMundekar/MYCITYPEDIA.git
cd MYCITYPEDIA
```

2. Create a virtual environment (using conda or venv):

```bash
conda create -n project python=3.10
conda activate project
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Set up the MySQL database:

- Create a database named `smart_city`
- Import the SQL schema from `database.sql` (if provided)

5. Run the Flask application:

```bash
python app.py
```

6. Open your browser at `http://127.0.0.1:5000/`

---

## Project Structure

```
MYCITYPEDIA/
├── app.py
├── templates/
├── static/
├── screenshot/
│   ├── homepage.png
│   ├── tourism_page.png
│   └── hotel_page.png
├── requirements.txt
├── README.md
└── database.sql
```

---

## Screenshots

![Homepage](screenshot/1.jpg)  
![Homepage](screenshot/2.jpg)  
![Homepage](screenshot/3.jpg)  
![Homepage](screenshot/4.jpg)  
![Homepage](screenshot/5.jpg)  
![Homepage](screenshot/6.jpg)  
![Homepage](screenshot/7.jpg)  
![Homepage](screenshot/8.jpg)  
![Homepage](screenshot/9.jpg)  
![Homepage](screenshot/10.jpg)  
![Homepage](screenshot/11.jpg)  
![Homepage](screenshot/12.jpg) 
![Homepage](screenshot/13.jpg)  
![Homepage](screenshot/14.jpg)  
![Homepage](screenshot/15.jpg) 
> Replace with your actual screenshot file names

---

## Future Enhancements

- Integration with AR/VR for virtual city exploration
- Real-time traffic, weather, and event updates
- Personalized recommendations using Machine Learning
- Social interaction and user-generated reviews

---

## Author

**Submitted By:**  
[Your Name]  
B. Tech, Computer Engineering  
XYZ OF ENGINEERING, 2016-2017  

**Guide:**  
Mrs. [Guide Name]

---

## License

This project is for academic purposes only.
