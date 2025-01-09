
# Flask Blog API

This is a simple blog API built with Flask. It includes user authentication, post creation, updating, and deletion functionalities.

## Requirements

- Python 3.x
- Flask
- Flask-Login
- Flask-SQLAlchemy
- Werkzeug

## Setup

1. **Clone the repository**:
   ```sh
   git clone https://github.com/Apurvastha/Flask-blog-api.git
   cd Flask-blog-api

2. **Create a virtual environment**:
   ```sh
   python -m venv venv

3. **Activate the virtual environment**:
   ```sh
   venv\Scripts\activate

4. **Install the dependencies**
   ```ah
   pip install -r requirements.txt

## Running the Application

1. **Run the flask application**

   ```
   python app.py

2. **Access the API**
   ```
   You can access the API endpoints by visiting `http://localhost:5000` in your web

## API Endpoints

### Authentication

- **Register**: `POST /auth/register`
- **Login**: `POST /auth/login`
- **Logout**: `POST /auth/logout`

### Posts

- **Create Post**: `POST /posts`
- **Update Post**: `PUT /posts/<post_id>`
- **Delete Post**: `DELETE /posts/<post_id>`
- **Get Post**: `GET /posts/<post_id>`
- **Get All Posts**: `GET /posts`
- **Paginate Posts**: `GET /posts?page=<page_number>&per_page=<per_page>`