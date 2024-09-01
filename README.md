# Cafe & Wifi Finder <img src=https://cdn-icons-png.flaticon.com/128/1079/1079108.png >

This is a Flask web application that allows users to find and add cafes that are suitable for remote working. The application features cafes with Wi-Fi and power outlets, making it easier for users to find the best spots for remote work.

## Features

- **List of Cafes**: View a list of cafes with important details such as location, Wi-Fi availability, power outlets, and coffee prices.
- **Add New Cafes**: Easily add new cafes to the database through a simple form.
- **Delete Cafes**: Remove cafes from the list if they no longer meet the criteria.
- **Responsive Design**: The application is responsive and works on a variety of devices.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework.
- **SQLite**: A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- **HTML/CSS**: For the front-end structure and styling.
- **Jinja2**: A templating engine for Python, used to render dynamic HTML pages.

## Installation

To run this application locally, follow these steps:

### Prerequisites

- Python 3.x installed on your machine.
- Git installed on your machine.

### Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/cafe-wifi-finder.git
    cd cafe-wifi-finder
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

    On Windows:
    ```bash
    venv\Scripts\activate
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the SQLite database:**
    - The application uses an SQLite database (`cafes.db`). If you're starting fresh, the database will be created automatically when you run the application. 

5. **Run the application:**
    ```bash
    python main.py
    ```

6. **Access the application:**
    - Open your browser and go to `http://localhost:5000/`.


## Usage

### Home Page

- The home page lists all cafes currently in the database, displaying key details such as:
  - Name
  - Location
  - Availability of Wi-Fi, power outlets, and toilets
  - Coffee price
- You can delete a cafe by clicking the "Delete" button.

### Adding a New Cafe

- Navigate to the "Add a New Cafe" page using the "Add New Cafe" button on the home page.
- Fill out the form with the cafe's details and submit.
- The new cafe will appear on the home page list.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- This project was built as a demonstration of Flask's capabilities.
- Inspired by similar platforms like [LaptopFriendly](https://laptopfriendly.co/).
