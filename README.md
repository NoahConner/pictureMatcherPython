
```markdown
# Image Matching Project

This project sets up a Python application that runs on port 8000 and uses the DELF model to match images.

## Setup and Installation

1. **Install Dependencies**

   Ensure you have a `requirements.txt` file. Install the dependencies using:

   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Server**

   Start the server using:

   ```bash
   python image.py
   ```

   The server will run on `http://localhost:8000`.

## Usage

To test the server, use the following `curl` command to send a POST request with an image file and an array of image names to match against:

```bash
curl -X POST -F "file=@path/to/your/image.jpg" -F "image_names=[\"image1.jpg\", \"image2.jpg\"]" http://localhost:8000/match
```

Replace `path/to/your/image.jpg` with the path to the image file you want to test and adjust the image names as needed.
```

This README provides basic setup and usage instructions for your project. Adjust the email and other details as needed.
