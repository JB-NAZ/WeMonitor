# **WeMonitor(Front-end only ver)**

WeMonitor is a web-based health monitoring application designed to simplify the recording and analysis of vital health data. It aims to address the inconvenience of manual health journaling by providing an intuitive, accessible, and comprehensive digital solution.

## **Motivation & Background**

The project was inspired by a personal experience in May 2024, when a teacher was hospitalized with a heart condition and struggled with manually recording daily body temperature and blood pressure due to impaired vision and the difficulty of handwriting. This highlighted a critical need for an IT-based solution to alleviate these challenges.

## **Features**

WeMonitor offers a range of features to help users easily track and understand their health:

* **Vital Data Recording:** Effortlessly input and manage various vital signs including Blood Pressure, Glucose, Sleep, Body Weight, Body Temperature, and Heart Rate.  
* **Intuitive UI/UX:** Designed with ease of use in mind, ensuring data is easy to see, simple to operate, and eliminates the need for manual writing.  
* **Status Indicators:** Visual cues using color changes (Default, Good, Caution, Danger) to quickly identify health status based on vital readings (e.g., BMI for weight, specific ranges for blood pressure and glucose).  
* **Customizable Dashboard:** Users can reorder their vital cards based on preference for quick access to their most important health metrics.  
* **Smart Data Entry:**  
  * **OCR Integration (Google Vision API):** Automatically scan and extract numerical data from physical health devices (like blood pressure monitors) using image recognition.  
  * **Google Fit API Integration:** Seamlessly pull health data from Google Fit to enrich the user's profile.  
* **Health Analytics Dashboard (Chart.js):** Visualize historical health data through interactive charts, such as Blood Pressure History and Temperature History, allowing users to track trends over time.  
* **AI Health Analysis & Recommendations (Gemini API):** Provides comprehensive health analysis and personalized recommendations based on recorded vital data.  
* **Daily Reminders:** Users receive daily email reminders to ensure consistent data input, helping them stay on track with their health monitoring.  
* **Data Export:** Easily export all recorded health data into various formats, including Excel, PDF, and CSV.  
* **User Management:** Secure user authentication via Google Sign-in.

## **Technologies Used**

* **Frontend:** HTML, CSS, JavaScript  
* **Backend:** PHP, MySQL, Apache  
* **APIs & Libraries:**  
  * Google Vision API (for OCR)  
  * Google Fit API (for health data integration)  
  * Gemini API (for AI health analysis and recommendations)  
  * Chart.js (for data visualization)  
  * Figma (for UI/UX design and prototyping)  
  * Material Icons & Google Fonts (for visual consistency and aesthetics)

## **Getting Started**

*(Current github files do not include the backend logic, so unfortunately the steps below are not currenly working, feel free to pass this).*

1. **Backend Setup:**  
   * Configure your Apache web server to serve the PHP files.  
   * Set up a MySQL database and import the necessary schema (not provided in the presentation).  
   * Update database connection details in the PHP configuration.  
2. **API Keys:**  
   * Obtain API keys for Google Vision API, Google Fit API, and Gemini API.  
   * Insert your API keys into the relevant configuration files (not specified in the presentation).  
3. **Launch:**  
   * Access the application through your web server.

## **Future Enhancements**

* Further refine the AI analysis to provide more personalized and actionable insights.  
* Expand integration with more health devices.  
* Implement advanced notification systems.  
* Explore mobile application development for native experiences.