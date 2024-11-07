# Recipe and Food Recommendation System using Machine Learning

This project implements a K-Nearest Neighbors (KNN) algorithm to recommend recipes based on user-inputted nutrients and ingredients. It also includes a Flask web application where users can type in their desired nutrients and ingredients to receive personalized recipe recommendations.

## Features

- **Recipe Recommendation**: Get personalized recipe recommendations based on the nutrients and ingredients you input.
- **Machine Learning**: Utilizes the K-Nearest Neighbors (KNN) algorithm for accurate recommendations.
- **Web Interface**: User-friendly Flask web application for easy interaction.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/delosreyesjohnpaul/Recipe-and-Food-Recomendation-System-using-Machine-Learning.git
   cd Recipe-and-Food-Recomendation-System-using-Machine-Learning
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:
   ```bash
   flask run
   ```

2. Open your web browser and go to `http://127.0.0.1:5000`.

3. Enter the desired nutrients and ingredients to receive recipe recommendations.

## Project Structure

- `app.py`: The main Flask application file.
- `models.py`: Contains the KNN model for the recommendation system.
- `templates/`: HTML templates for the web interface.
- `static/`: Static files like CSS and images.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
