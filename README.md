# SustainableEats

## Overview
SustainableEats is a project designed to predict optimal food preparation quantities to minimize waste in restaurants, hotels, and large events. By analyzing food usage and wastage patterns, the model provides accurate predictions, helping establishments reduce waste, save costs, and promote sustainability in the food industry.

## Features
- Prediction of food wastage amounts.
- Graphical representation of food wastage predictions.
- User-friendly interface for interaction.

## Prerequisites
- Python 3.x
- Flask
- Bootstrap 4.0
- Required Python packages listed in `requirements.txt`

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/SustainableEats.git
    cd SustainableEats
    ```

2. **Create a virtual environment and activate it:**
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

## Project Structure
```plaintext
SustainableEats/
│
├── static/
│   ├── favicon/
│   │   ├── apple-touch-icon.png
│   │   ├── favicon-32x32.png
│   │   ├── favicon-16x16.png
│   │   └── site.webmanifest
│   ├── images/
│   │   ├── home.jpg
│   │   └── index.jpg
│   └── css/
│       └── style.css
│
├── templates/
│   ├── home.html
│   └── result.html
│
├── app.py
├── requirements.txt
└── README.md
...

## Running the Application

1. **Start the Flask application:**
    ```sh
    python app.py
    ```

2. **Open your browser and navigate to:**
    ```
    http://127.0.0.1:5000/
    ```

## Output
- **Homepage**: Displays the project overview and navigation options.
- **Prediction Page**: Shows the predicted food wastage and graphical representation.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

