# Detection of Fake and Clone Accounts of Twitter

This project aims to detect fake and clone accounts on Twitter using machine learning algorithms. The project leverages supervised learning and distance-measure algorithms to classify accounts based on their activity and profile data.

## Overview

With the increasing number of fake and clone accounts on social media platforms, it has become crucial to develop automated systems to detect such accounts. This project implements machine learning models to classify Twitter accounts as fake or legitimate. The models analyze various features extracted from the account's activity and profile data.

## Installation

To run this project, you need to install the required Python packages. You can install these packages using `pip`.

### Method 1

Use the following commands to install the required packages:

```bash
pip install Flask==1.1.1
pip install gunicorn==19.9.0
pip install itsdangerous==1.1.0
pip install Jinja2==2.10.1
pip install MarkupSafe==1.1.1
pip install Werkzeug==0.15.5
pip install numpy>=1.9.2
pip install scipy>=0.15.1
pip install scikit-learn>=0.18
pip install matplotlib>=1.4.3
pip install pandas>=0.19
pip install flask-cors==3.0.9
```

### Method 2

Alternatively, use the following commands to install specific versions of some key packages:

```bash
pip install scikit-learn==0.23.1
pip install Flask==2.0.1
pip install Werkzeug==2.2.2
pip install pandas==1.1.5
pip install matplotlib==3.4.3
pip install numpy==1.19.5
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/faizahmed09/Detection-of-Fake-and-Clone-Accounts-of-Twitter.git
   cd Detection-of-Fake-and-Clone-Accounts-of-Twitter
   ```

2. **Install the dependencies:**

   Follow the installation steps mentioned above.

3. **Run the application:**

   ```bash
   python app.py
   ```

   Or if you are using `gunicorn`:

   ```bash
   gunicorn app:app
   ```

4. **Access the application:**

   Open your web browser and navigate to `http://127.0.0.1:5000/`.

## Technologies Used

- **Python**: The primary programming language used for the project.
- **Flask**: A micro web framework for building web applications.
- **scikit-learn**: A machine learning library for building and training models.
- **pandas**: A library for data manipulation and analysis.
- **numpy**: A library for numerical computations.
- **matplotlib**: A plotting library for creating visualizations.
- **flask-cors**: A Flask extension for handling Cross-Origin Resource Sharing (CORS).

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to submit a pull request or open an issue.

### Steps to Contribute

1. **Fork the repository.**
2. **Create a new branch:**

   ```bash
   git checkout -b feature-branch
   ```

3. **Make your changes and commit them:**

   ```bash
   git commit -m "Add some feature"
   ```

4. **Push to the branch:**

   ```bash
   git push origin feature-branch
   ```

5. **Submit a pull request.**

## Acknowledgements

- [scikit-learn documentation](https://scikit-learn.org/stable/)
- [Flask documentation](https://flask.palletsprojects.com/)
- [pandas documentation](https://pandas.pydata.org/)
- [numpy documentation](https://numpy.org/)
- [matplotlib documentation](https://matplotlib.org/)
```
