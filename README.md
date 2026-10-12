# 🍎 Calorie Estimation of Food and Beverages

A machine learning-based web application that identifies food items from images and estimates their calorie content using **Deep Learning and the MobileNet architecture**.

This project combines image classification, nutritional data, and a web interface to help users explore the estimated calorie and nutritional content of different foods and beverages.

## ✨ Features

- **Food Image Recognition:** Predicts food categories from uploaded images using a trained deep learning model.
- **Calorie Estimation:** Displays estimated calorie information for recognized food items.
- **Nutritional Information:** Provides nutritional details such as protein, fat, carbohydrates, calcium, and vitamins when available in the dataset.
- **Web-Based Interface:** Provides a browser-based interface built with Flask and HTML templates.
- **Image Upload:** Allows users to upload food images for analysis.
- **Machine Learning Integration:** Uses a saved TensorFlow/Keras model for food classification.

## 🛠️ Technologies Used

- **Python** — Core application logic.
- **TensorFlow / Keras** — Deep learning model loading and prediction.
- **MobileNet** — Image classification architecture.
- **Flask** — Web application framework.
- **HTML and CSS** — Frontend structure and styling.
- **NumPy** — Numerical operations.
- **CSV** — Storage and retrieval of nutritional information.

## 🧠 How It Works

The application follows these general steps:

1. **Upload an Image:** The user uploads an image of a food item.
2. **Preprocess the Image:** The image is prepared for the trained model.
3. **Food Classification:** The saved deep learning model predicts the food category.
4. **Calorie Estimation:** The predicted category is associated with calorie information.
5. **Nutritional Lookup:** The application retrieves available nutritional details from its dataset.
6. **Display Results:** The application presents the prediction and estimated nutritional information through the web interface.

## 🚀 Getting Started

### Prerequisites

Install the following before running the project:

- Python 3
- pip
- A web browser

### 1. Clone the Repository

```bash
git clone https://github.com/Abdul0015/Calorie-estimation-of-food-and-beverages.git
```

### 2. Navigate to the Project Directory

```bash
cd Calorie-estimation-of-food-and-beverages
```

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Activate it on macOS or Linux:

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python app.py
```

Open the local address displayed in your terminal. For a typical Flask development setup, this may be `http://127.0.0.1:5000/`.

**Note:** The application requires the pretrained `food.h5` model, the `nutrition101.csv` dataset, and the expected template and static directories. Ensure these files are present in their required locations.

## 📁 Project Structure

```text
Calorie-estimation-of-food-and-beverages/
│
├── app.py                  # Flask application and prediction logic
├── get_nutrition_data.py   # Nutrition data processing
├── food.h5                 # Trained deep learning model
├── nutrition101.csv        # Nutritional information dataset
├── requirements.txt        # Python dependencies
│
├── templates/              # HTML templates for the web interface
├── model/                  # Model-related files
├── BASE PAPER/             # Reference research material
├── SRS/                    # Software requirements documentation
│
├── REQUIREMENTS.pdf        # Project requirements
└── README.md               # Project documentation
```

## 🎯 What I Learned

Through this project, I gained practical experience with:

- Understanding deep learning for image classification.
- Working with the MobileNet architecture.
- Loading and using trained TensorFlow/Keras models.
- Building web applications using Flask.
- Handling uploaded images in a web application.
- Connecting machine learning predictions with nutritional datasets.
- Reading structured data from CSV files.
- Integrating a machine learning model with a web-based user interface.

## 🔮 Future Improvements

- Improve food classification accuracy using a larger and more diverse dataset.
- Expand support for regional foods and beverages.
- Provide more detailed nutritional information.
- Improve the user interface and mobile responsiveness.
- Add portion-size estimation for more personalized calorie estimates.
- Evaluate model performance using appropriate classification metrics.
- Deploy the application so users can access it online.

## ⚠️ Disclaimer

This application provides **estimated** calorie and nutritional information for educational and demonstration purposes. Actual nutritional values vary depending on ingredients, portion sizes, preparation methods, and serving quantities. The results should not be used as a substitute for professional dietary or medical advice.

## 👨‍💻 Author

**Abdul**

GitHub: [@Abdul0015](https://github.com/Abdul0015)

Project Repository: [Calorie Estimation of Food and Beverages](https://github.com/Abdul0015/Calorie-estimation-of-food-and-beverages)

---

⭐ If you find this project interesting, consider giving the repository a star!
