# Music Player Application

## Overview

This Music Player application allows users to manage a playlist of songs. Built in Java, the application utilizes various data structures to handle songs efficiently. The features of the application include adding, deleting, and searching songs, as well as sorting and playing them. The recently played songs are managed using a stack, while the playlist is stored using a doubly linked list.

## Features

- **Add New Song**: Add a new song to the playlist.
- **Delete Song**: Remove a song from the playlist either by searching for it or by specifying its position.
- **Display Playlist**: View all the songs in the playlist.
- **Total Songs**: Count the total number of songs in the playlist.
- **Search Song**: Search for a song in the playlist.
- **Play Song**: Play a specified song and add it to the recently played list.
- **Recently Played List**: View the list of recently played songs (managed using a stack).
- **Last Played**: Show the last played song.
- **Sorted Playlist**: Sort the playlist alphabetically and display the sorted list.
- **Add From File**: Load songs from a file and add them to the playlist.

## Data Structures Used

- **Doubly Linked List**: Used to store the playlist. Each song node has pointers to the next and previous songs, allowing efficient insertion and deletion.
- **Stack**: Used to manage the recently played songs. The most recently played song is always on top.
- **Queue**: Although not explicitly implemented in this version, the concept of a queue can be utilized for features like playlist management.

## How to Run

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/music-player.git
    cd music-player
    ```

2. **Compile the Application**:
    ```bash
    javac PlaylistManager.java
    ```

3. **Run the Application**:
    ```bash
    java PlaylistManager
    ```

4. **Interact with the Application**:
    Follow the prompts to add, delete, search, play, and manage your playlist.

## File Structure

- `PlaylistManager.java`: Main application file containing the logic for managing the playlist and recently played songs.
- `playlist.txt`: A text file used to persistently store the playlist.

## Example Usage

1. **Add a New Song**:
    - Enter the song name when prompted.
2. **Delete a Song**:
    - Choose to delete by search or by position.
3. **Play a Song**:
    - Specify the song name to play and add it to the recently played stack.
4. **Sort Playlist**:
    - The playlist is sorted alphabetically and displayed.

## Contributing

Feel free to open issues or submit pull requests if you have improvements or suggestions. 



**Note**: Ensure that `playlist.txt` is present in the same directory as the `PlaylistManager.java` file for reading and writing the playlist.
   first you need to run the application.

