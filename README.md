# GeoJunior

GeoJunior is an educational web application designed to help children learn geography through interactive quizzes and engaging content. This project integrates various frontend and backend technologies to provide a smooth and dynamic user experience.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Development & Collaboration Tools](#development--collaboration-tools)
  - [Testing and Security](#testing-and-security)
  - [Design and Usability](#design-and-usability)
- [Project Setup](#project-setup)
- [Contributing](#contributing)
- [License](#license)

## Features

- Interactive quizzes to test and enhance children's geography knowledge.
- Dynamic content updates without page reloads for a seamless experience.
- User-friendly interface designed specifically for children.
- Secure backend to manage user data and quiz information efficiently.

## Technologies Used

### Frontend

**ReactJS**
- **Used For:** Building user interface components.
- **Purpose:** Enables dynamic content updates without reloading the page, enhancing user experience by providing a smooth interactive experience.

**HTML & CSS**
- **Used For:** Structuring and styling the web pages.
- **Purpose:** HTML provides the structure of the website, while CSS ensures the pages are visually appealing, and suitable for children.

### Backend

**Flask**
- **Used For:** Web framework to create server-side routes and handlers.
- **Purpose:** Manages server requests, routes, and renders pages, acting as the backbone for server-side logic and page delivery.

**SQLAlchemy**
- **Used For:** Object Relational Mapping (ORM) to interact with the database.
- **Purpose:** Simplifies database transactions and ensures that Python code can be written without SQL injection vulnerabilities.

**SQLite**
- **Used For:** Database to store user data and quiz information.
- **Purpose:** Provides a lightweight database solution without the need for a separate server, ideal for development and smaller applications.

**Flask-Migrate**
- **Used For:** Handling database migrations.
- **Purpose:** Assists in managing database schema changes over time, essential for evolving applications without losing data.

**Python**
- **Used For:** Primary programming language for backend development.
- **Purpose:** Python serves as the foundation for writing the server-side code in the GeoJunior project, interacting with Flask for server logic and SQLAlchemy for database management.

### Development & Collaboration Tools

**Trello**
- **Used For:** Task management.
- **Purpose:** Helps the team keep track of tasks, progress, and deadlines, ensuring that all aspects of the project are progressing as planned.

**Slack**
- **Used For:** Team communication.
- **Purpose:** Facilitates quick and effective communication among team members, important for coordination and resolving issues swiftly.

**Gantt Chart**
- **Used For:** Project scheduling and management.
- **Purpose:** Visualizes the project timeline and dependencies.

### Testing and Security

**Unit Testing**
- **Used For:** Testing individual units of code.
- **Purpose:** Ensures that each component functions correctly in isolation, helping to catch bugs early in the development process.

**Integration Testing**
- **Used For:** Testing the integration of different components.
- **Purpose:** Confirms that separate parts of the application work together as expected.

**Validation Testing**
- **Used For:** Ensuring user inputs are correctly processed.
- **Purpose:** Protects the application against improper inputs that could cause errors or security issues.

### Design and Usability

**UI/UX Principles**
- **Used For:** Designing the user interface and experience.
- **Purpose:** Ensures that the application is easy to navigate and engaging for children, incorporating elements like vibrant colors and simple layouts to appeal to the young audience.

## Project Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/aarong21/geo-junior.git
    cd geojunior
    ```

2. Set up the backend:
    ```bash
    cd backend
    python -m venv venv
    source venv/bin/activate (or venv\Scripts\activate on Windows)
    pip install -r requirements.txt
    flask db upgrade
    flask run
    ```

3. Set up the frontend:
    ```bash
    cd frontend
    npm install
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Contributing

We welcome contributions from the community! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is not licensed.
