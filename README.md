Music Controller
Music Controller is a web application built using Django and React. It allows users to create and join music rooms, where they can control the playback of music by voting to skip a song or pause/play the music.

The project is split into two main parts:

Backend: The backend is built using Django and provides RESTful APIs for handling user authentication, room creation/joining, and controlling the music playback.

Frontend: The frontend is built using React and allows users to create/join rooms, control the music playback, and vote to skip songs.

Installation
To run this project locally, you need to have Python 3.x and Node.js installed on your machine.

Clone the repository: git clone https://github.com/your-username/music-controller.git
Navigate to the backend folder and install the required Python packages: pip install -r requirements.txt
Run the Django server: python manage.py runserver
Open another terminal window and navigate to the frontend folder
Install the required Node packages: npm install
Start the React development server: npm start
Usage
Once the Django and React servers are running, you can access the web application in your browser at http://localhost:3000.

You can create a new room or join an existing room using a room code. Once you are in a room, you can control the music playback and vote to skip songs.

Contributing
If you want to contribute to this project, feel free to submit a pull request. Please ensure that your code follows the existing code style and that all tests pass before submitting the pull request.

License
This project is licensed under the MIT License. You can see the details in the LICENSE file.
