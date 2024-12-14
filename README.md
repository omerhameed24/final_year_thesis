# final_year_thesis
# Sketch Based Image Retrieval

This repository contains the codebase for **Sketch Based Image Retrieval (SBIR)**, a final year thesis project that implements a system for retrieving images based on sketch inputs. The project is divided into two main parts:

1. **Backend**: The core logic and algorithms for image retrieval.
2. **Frontend**: The user interface for interacting with the system.

---

## Project Overview

Sketch Based Image Retrieval (SBIR) allows users to  to give input in one of thetwo ways, Either he/she can draw the sketch onthe sketch pad present in our application orhe/she can upload a sketch which is already drawn.The system then process the sketch and displays the top matching results of natural images Elaborating the retrieval of the natural image, the uploaded or drawn sketch is first available in base 64 format which is then converted in png format in backend .The png image is passed as a query against our dataset of sketch and natural images and the systemextracts the features and retrieves the corresponding natural image in json array and that array is displayed as an output in front end.

---

## Repository Links

- **Backend Repository**: [Sketch Based Image Retrieval - Backend](https://github.com/omerhameed24/Sketch-Based-Image-Retrieval-Backend)
  - Contains the code for:
    - Preprocessing sketches and images
    - Feature extraction and matching algorithms
    - Model training and evaluation
    - API endpoints for the frontend to interact with the backend

- **Frontend Repository**: [Sketch Based Image Retrieval - Frontend](https://github.com/omerhameed24/Sketch-based-Image-Retrieval-frontend)
  - Contains the code for:
    - User interface design
    - Sketch canvas for drawing input
    - Displaying search results
    - Communication with the backend through APIs

---

## Features

- **Intuitive Input**: Draw sketches directly in the web interface.
- **Accurate Matching**: Advanced algorithms to find relevant images.
- **Interactive Results**: View and refine the search results easily.

---

## Installation and Setup

### Prerequisites
- **Backend**:
  - Python (>=3.8)
  - Required libraries listed in `requirements.txt` (refer to the backend repository)
- **Frontend**:
  - Node.js (>=14.x)
  - React or similar framework (refer to the frontend repository)

### Steps
1. Clone both repositories.
   ```bash
   git clone https://github.com/your-username/sketch-based-image-retrieval-backend.git
   git clone https://github.com/your-username/sketch-based-image-retrieval-frontend.git
   ```

2. Set up the backend:
   - Navigate to the backend directory.
   - Install dependencies and start the server.
   ```bash
   cd sketch-based-image-retrieval-backend
   pip install -r requirements.txt
   python app.py
   ```

3. Set up the frontend:
   - Navigate to the frontend directory.
   - Install dependencies and start the development server.
   ```bash
   cd sketch-based-image-retrieval-frontend
   npm install
   npm start
   ```

4. Access the application:
   - Open your browser and navigate to the frontend URL (usually `http://localhost:4200`).

---

## Usage

1. Open the web application.
2. Draw a sketch using the provided canvas.
3. Submit the sketch.
4. View the retrieved image results and refine your search if needed.

---

## Technologies Used

- **Backend**:
  - Python
  - Flask/Django (or any other framework)
  - OpenCV, TensorFlow, or PyTorch for image processing and model handling

- **Frontend**:
  - Angular 
  - HTML/CSS for UI design

---

## Future Work

- Integration of more advanced models for sketch recognition.
- Expansion of the dataset for better results.
- Implementation of feedback mechanisms to improve search accuracy.

---

## Contributions

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Open a pull request.

---

## Acknowledgments

Special thanks to our advisors, professors, and all those who supported this project.

---

## Contact

For questions or collaboration, feel free to reach out:
- **Name**: Muhammad Omer
- **Email**: omerhameed68@gmail.com
