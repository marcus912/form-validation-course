# form-validation-course

A JavaScript course for beginners to learn form validation.

## Project Overview

This is a travel booking form built with HTML and CSS, designed to teach form validation concepts. The form includes various input types, proper semantic HTML, and accessibility features.

## Features

- Responsive travel booking form
- Multiple input types (text, email, tel, number, textarea, radio, select)
- Proper form validation with HTML5 attributes
- Clean and modern UI with custom styling
- Accessibility improvements (lang attribute, proper input types, meta tags)

## Running the Project

### Using Docker (Recommended)

1. **Start the server:**
   ```bash
   docker compose up -d
   ```

2. **Access the form:**
   Open your browser and navigate to [http://localhost:8080](http://localhost:8080)

3. **Stop the server:**
   ```bash
   docker compose down
   ```

4. **View logs:**
   ```bash
   docker compose logs -f
   ```

5. **Rebuild after changes:**
   ```bash
   docker compose up -d --build
   ```

### Without Docker

Simply open `index.html` in your web browser.

## Project Structure

```
form-validation-course/
├── index.html          # Main HTML form
├── style.css           # Form styling
├── Dockerfile          # Docker configuration for nginx
├── docker-compose.yml  # Docker Compose configuration
├── .dockerignore       # Docker ignore file
└── README.md           # This file
```

## Form Fields

The form includes the following sections:
- Passenger contact information (name, email, phone)
- Address details
- Number of travelers (adults and children)
- Travel preferences (type, destination, hotel)
- Room details
- Transportation options
- Special instructions and activities
- Travel insurance option

## Technologies Used

- HTML5
- CSS3
- Docker
- Nginx (Alpine Linux)
