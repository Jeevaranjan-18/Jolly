# Simple Flask Web Application

A clean and modern Flask web application with a responsive UI.

## Features

- 🏠 Home page with interactive greeting functionality
- 📚 About page with project information
- 🎨 Modern, gradient-based UI design
- 📱 Fully responsive layout
- 🔌 RESTful API endpoint

## Project Structure

```
.
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── templates/
│   ├── index.html        # Home page
│   └── about.html        # About page
└── README.md             # This file
```

## Installation

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

1. Start the Flask development server:
```bash
python app.py
```

2. Open your browser and navigate to:
```
http://localhost:5000
```

## API Endpoints

### GET /
Returns the home page

### GET /about
Returns the about page

### POST /api/greet
Accepts a JSON payload with a name and returns a personalized greeting.

**Request:**
```json
{
  "name": "John"
}
```

**Response:**
```json
{
  "message": "Hello, John!"
}
```

## Technologies Used

- **Flask** - Python web framework
- **HTML5** - Markup
- **CSS3** - Styling with gradients and animations
- **JavaScript** - Client-side interactivity

## Customization

Feel free to modify the styles in the `<style>` sections of the HTML templates or add new routes in `app.py` to extend the functionality.

## License

This is a simple example project - feel free to use and modify as needed!
