# Face Recognition and Event Management

This project is a Python-based application that combines face recognition using the DeepFace library with event management functionality. It allows you to take a photo using your computer's camera, verify the face in the photo against a database of registered faces, and then manage event-related data, such as participant details and attendance records.

## Table of Contents

1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Functionality](#functionality)
5. [File Structure](#file-structure)
6. [Contributing](#contributing)
7. [License](#license)

## Project Description

The project comprises the following key functionalities:

- **Face Recognition**: The application uses the DeepFace library to capture a photo of a person's face using their computer's camera and compares it to a database of registered faces. If a matching face is found, it identifies the individual.

- **Event Management**: The system manages event-related data in CSV files. It records participant details, such as name, student ID, course, contact number, email, and registration date.

- **Database Structure**: The project maintains a root folder containing subfolders for each registered individual. Within these subfolders, individual photos are stored, each named uniquely to represent the person.

- **Event CSV Files**: The project stores event-related data in CSV files. The main event file contains the registration details of participants, while the metadata file records the face data used for verification.

## Installation

To use this project, follow these installation steps:

1. Clone the project from the GitHub repository: `https://github.com/your-repo/project-name.git`

2. Navigate to the project directory using your terminal or command prompt.

3. Create a Python virtual environment (optional but recommended):
`python -m venv venv`
`source venv/bin/activate`
4. Install the required dependencies:
`pip install -r requirements.txt`
5. Run the project:

## Usage

Once the project is running, you can use the following functionalities:

1. **Face Recognition**: Use the 'c' key to capture a photo of your face using the camera. The application will attempt to match the face to a registered user.

2. **Event Management**: The project maintains event-related data in CSV files. You can set headers, append data, and fetch data from these files. It also checks for unique values and fetches rows with specific conditions.

3. **Participant Registration**: If your face is not recognized as a registered user, you can provide your details (name, student ID, course, contact number, and email) to register for the event. The application will create a subfolder with your student ID and store your photo within it.

## Functionality

The project provides the following main functionalities:

- **Face Recognition**: The application uses the DeepFace library to compare a captured face with registered faces.

- **Event Data Management**: The system can manage participant details and event records. You can set headers, append data, fetch data, and check for unique values.

- **Participant Registration**: If your face is not recognized, you can provide your details to register for the event. Your photo is stored in a subfolder with your student ID.

- **User Interaction**: The project allows interaction through the command line to capture photos and manage event-related data.

## File Structure

- `main.py`: The main script to run the project.
- `requirements.txt`: Lists the project dependencies.
- `event_data/`: Directory to store event-related data files.
- `root_folder/`: Directory to store registered users' face data in subfolders.
- `readme.md`: This documentation file.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the project repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request to the original repository.

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it.

