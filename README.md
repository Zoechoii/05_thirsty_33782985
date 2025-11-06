# 05_thirsty_33782985 - Thirsty Student Shop

A web application for a drinks shop built with Node.js, Express, and EJS templating engine.

## About

The Beverage Shop is an online platform that sells various types of drinks including beer, wine, soft drinks, and hot drinks. This application demonstrates the use of EJS templating, form handling, and dynamic content rendering.

## Features

### Core Features
- **Dynamic Product Display**: Browse drink categories on the home page
- **Multiple Shop Locations**: View information about different branch locations and their managers
- **Search Functionality**: Search for products by keyword and category
- **User Registration**: Register with first name, last name, and email
- **Customer Survey**: Complete a survey about drinking preferences

### Technical Features
- EJS templating for dynamic HTML rendering
- Express.js routing
- Form handling with GET and POST methods
- CSS styling for a clean, modern interface
- Responsive design

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/05_thirsty_33782985.git
cd 05_thirsty_33782985
```

2. Install dependencies:
```bash
npm install
```

## Usage

1. Start the server:
```bash
node index.js
```

2. Open your browser and navigate to:
```
http://localhost:8000
```

## Routes

| Route | Method | Description |
|-------|--------|-------------|
| `/` | GET | Home page with product categories |
| `/about` | GET | About page with shop locations and managers |
| `/search` | GET | Search form |
| `/register` | GET | Registration form |
| `/survey` | GET | Customer survey form |
| `/survey_result` | POST | Survey results display |

## Project Structure
```
05_thirsty_33782985/
├── index.js              # Main server file
├── package.json          # Project dependencies
├── routes/
│   └── main.js          # Route handlers and data
├── views/               # EJS templates
│   ├── index.ejs
│   ├── about.ejs
│   ├── search.ejs
│   ├── register.ejs
│   ├── survey.ejs
│   └── survey_result.ejs
└── public/
    └── css/
        └── style.css    # Stylesheet
```

## Technologies Used

- **Node.js**: JavaScript runtime
- **Express.js**: Web application framework
- **EJS**: Embedded JavaScript templating
- **HTML5**: Markup
- **CSS3**: Styling

## Data Structure

The application stores shop data including:
- Shop name
- Product categories (Beer, Wine, Soft Drinks, Hot Drinks)
- Shop locations with manager names and addresses

## Form Handling

### GET Method (Search)
Form data is sent via query string in the URL:
```
/search_result?search_text=beer&category=drinks
```

### POST Method (Registration & Survey)
Form data is sent in the request body for secure transmission of user information.

## Author

Student ID: 33782985

## License

This project is part of a university assignment.
