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
```

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

-![image](https://github.com/BRUNDAVANAMSUREKHA/SUSTAINABLEEATS/assets/122956099/f39673a0-6f1a-4c6f-bff5-1f5c46c2e96c)

- **Prediction Page**: Shows the quantity check form to enter the details of the food,event,season,type of food,no of guests,prepared food quantity,etc..,

-![image](https://github.com/BRUNDAVANAMSUREKHA/SUSTAINABLEEATS/assets/122956099/cbd37488-2fd3-4d5f-9801-45b3adfa3cca)

- **Result Page**: Shows the predicted food wastage and graphical representation
  
-![image](https://github.com/BRUNDAVANAMSUREKHA/SUSTAINABLEEATS/assets/122956099/03a9a4b9-d59a-46a7-8704-1f629724f078)

-![image](https://github.com/BRUNDAVANAMSUREKHA/SUSTAINABLEEATS/assets/122956099/bd9d3b5d-e1ef-4500-9f35-08df1dcce8ef)

- **Contact Page**: Provides information to contact the project team.

-![image](https://github.com/BRUNDAVANAMSUREKHA/SUSTAINABLEEATS/assets/122956099/bbcccf0e-a3e6-4da8-841c-217366195732)

- **about Page**: Accessible via the footer link on the homepage, provides details about the project team.

-![image](https://github.com/BRUNDAVANAMSUREKHA/SUSTAINABLEEATS/assets/122956099/2f962263-5e70-41e3-8b31-62f90870e0da)


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

