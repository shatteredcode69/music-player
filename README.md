README for Music Player Project
🎵 Music Player by Abbas Qureshi
This is a simple Music Player built using Python's tkinter for the graphical user interface (GUI) and pygame for audio playback. The application allows users to play, pause, stop, and navigate through .mp3 files in a specified directory. It also includes volume control functionality.

📋 Features

Play Music: Select and play .mp3 files from a predefined folder.
Pause/Resume Music: Pause the currently playing track and resume it.
Stop Music: Stop the currently playing track.
Next/Previous Track: Navigate to the next or previous track in the playlist.
Volume Control: Increase or decrease the volume of the music.
Dynamic Playlist: Automatically loads all .mp3 files from the specified folder.


🛠️ Technologies Used

Python: Programming language used to build the application.
tkinter: For creating the graphical user interface.
pygame: For handling audio playback.


🚀 How to Run the Project
Prerequisites

Install Python (version 3.7 or higher).
Install the required Python libraries:

pygame
tkinter (comes pre-installed with Python).



Installation Steps


Clone this repository:
git clone https://github.com/your-username/music-player.git



Navigate to the project directory:
cd music-player



Install the required dependencies:
pip install pygame



Place your .mp3 files in the folder specified in the rootpath variable in the code. By default, it is set to:
C:\Users\w312\Downloads\Music

You can change this path in the code if needed.


Run the application:
python music_player.py




🎮 How to Use

Playlist: The application automatically loads all .mp3 files from the specified folder into the playlist.
Play a Song: Select a song from the playlist and click the Play button.
Pause/Resume: Click the Pause button to pause the song. Click it again to resume.
Stop: Click the Stop button to stop the song.
Next/Previous: Use the Next and Previous buttons to navigate through the playlist.
Volume Control: Use the Volume Up and Volume Down buttons to adjust the volume.


📂 Project Structure
music-player/
│
├── music_player.py       # Main Python script for the music player
├── previous.png          # Image for the "Previous" button
├── stop.png              # Image for the "Stop" button
├── play.png              # Image for the "Play" button
├── pause.png             # Image for the "Pause" button
├── next.png              # Image for the "Next" button
├── volumeup.png          # Image for the "Volume Up" button
├── volumedown.png        # Image for the "Volume Down" button
└── README.md             # Project documentation


🛑 Known Issues

File Path Issues: Ensure the rootpath variable points to a valid directory containing .mp3 files.
Image Loading: Ensure all button images (e.g., play.png, pause.png) are in the same directory as the script.


🤝 Contributing
Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

📧 Contact
For any questions or suggestions, please contact Abbas Qureshi at [durranimeeqat@gmail.com].

Enjoy the music! 🎶
