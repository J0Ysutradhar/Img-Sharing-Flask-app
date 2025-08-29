# MyPic - Image Sharing Website
App is live https://mypics4u.onrender.com/
[![image.png](https://mypics.metaxsoul.store/uploads/2025-08-29_132225.858240mypics.metaxsoul.store_iPhone_14_Pro_Max.png)](https://postimg.cc/JtMj0HJK)
MyPic is a web application for sharing images for free. The website allows users to upload images and provides a link to access the uploaded images. The website is authored by Joy Sutradhar.

## Features

- Upload images in various formats (PNG, JPG, JPEG, GIF)
- View uploaded images
- Copy link to the uploaded image for easy sharing

## Technologies Used

- Flask (Python web framework)
- HTML, CSS, Bootstrap (for frontend design)
- JavaScript (for copy link functionality)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/J0Ysutradhar/Img-Sharing-Flask-app.git
    cd mypic
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Create the `uploads` directory:

    ```bash
    mkdir uploads
    ```

## Configuration

1. Set the secret key and upload folder in app.py:

    ```python
    app.config['UPLOAD_FOLDER'] = 'uploads'
    app.secret_key = 'supersecretkey'
    ```

## Running the Application

1. Run the Flask application:

    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000` to access the application.

## Project Structure

-  app.py: The main Flask application file.
- `requirements.txt`: Contains the list of Python packages required for the project.
- `templates/`: Contains the HTML templates for the application.
- `uploads/`: Directory where uploaded images are stored.

## Usage

1. Open the application in your web browser.
2. Use the upload form to select and upload an image.
3. After uploading, a link to the uploaded image will be provided.
4. Use the "Copy" button to copy the link to the clipboard for easy sharing.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

Joy Sutradhar (aka metasoul)
