# Flower Count Project

This project includes a backend API, a frontend web application, and a mobile application for flower counting. Follow the instructions below to set up and run each component.

## Table of Contents

- [Backend](#backend)
- [Frontend](#frontend)
- [Mobile Application](#mobile-application)
- [Design Decisions and Challenges](#design-decisions-and-challenges)

## Backend

The backend is built using FastAPI and provides an API for processing images.

### Prerequisites

- Python 3.8+
- Pip

### Setup

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Justinekemhe/Flower-Count-Project-App.git
    cd Flower-Count-Project-App/Image-Applicaton Backend and Front End
    ```


2. **Run the API:**

    ```bash
    uvicorn main:app --host 127.0.0.1 --port 8000 --reload
    ```

    The API will be available at `http://127.0.0.1:8000`.
![Capture3](https://github.com/user-attachments/assets/c4f02ac9-4733-4734-b319-d17be0350503)


   

4. **Test the API:**

    You can test the endpoints using tools like Postman or directly via the Swagger UI at `http://127.0.0.1:8000/docs`.

## Frontend

The frontend is a web application built using HTML, CSS, and JavaScript.

### Prerequisites

- A modern web browser

### Setup

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Justinekemhe/Flower-Count-Project-App.git
    cd Flower-Count-Project-App/frontend
    ```

2. **Run the Frontend:**

   Run python -m http.server 8001
   Open the `index.html` file in a web browser. Ensure that the backend API is running before testing the frontend.
    Login information
![alt text](image.png)

![image](https://github.com/user-attachments/assets/d3533b48-9e92-4ede-89df-c6f945a7d74d)

![image](https://github.com/user-attachments/assets/ef070d21-704b-467e-9546-48554d8ca683)

![image](https://github.com/user-attachments/assets/e9214451-6bc1-4f91-978b-12660469cbf1)

![image](https://github.com/user-attachments/assets/e325c1db-d519-4025-b232-480a1e485850)

![image](https://github.com/user-attachments/assets/668478b9-a52c-4940-94ff-932f93771f08)


## Mobile Application

The mobile application is built using Flutter.

### Prerequisites

- Flutter SDK
- Dart

### Setup

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Justinekemhe/Flower-Count-Project-App.git
    cd Flower-Count-Project-App/mobile
    ```

2. **Install Dependencies:**

    ```bash
    flutter pub get
    ```

3. **Run the Application:**

    Ensure you have an emulator running or a physical device connected, then use:

    ```bash
    flutter run
    ```

    The app will be available on your emulator or connected device.
   ![mobile app](https://github.com/user-attachments/assets/5d4c1fa9-0800-4b38-90a9-c925865c36d5)


## Design Decisions and Challenges

### Design Decisions

- **Backend:** Used FastAPI for its high performance and ease of use in creating RESTful APIs. Integrated Hugging Face Transformers for image processing.
- **Frontend:** Utilized Bootstrap for responsive design and clean UI. Designed for user-friendly interaction with the backend API.
- **Mobile Application:** Built with Flutter for cross-platform support, allowing the app to run on both Android and iOS with a single codebase.

### Challenges Faced

- **Backend Integration:** Handling image file uploads and processing asynchronously was complex. Resolved by using FastAPI's built-in support for asynchronous operations.
- **Frontend and Mobile Sync:** Ensuring consistent communication between the frontend and backend involved dealing with CORS issues and testing API responses.
- **Mobile Development:** Implementing camera functionality and image processing required integrating several Flutter packages and handling device-specific issues.
