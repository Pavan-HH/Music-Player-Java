# Music-Player-Java


 Java Music Player

 Features

 **Play** – Start or resume the audio
 **Stop** – Pause/stop playback
 **Reset** – Restart the track from the beginning
 **Quit** – Close the player safely



Technologies Used

* **Java 17+**
* **Javax.sound.sampled** package
* **Scanner** for user input handling

---

 Project Structure

```
java-music-player/
│
├── src/
│   └── MusicPlayer.java
│
└── audio/
    └── song.wav  (your .wav file)
```

---

 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/java-music-player.git
   cd java-music-player
   ```

2. **Add your audio file**

   * Place your `.wav` file in the `src` folder (or any path you prefer).
   * Update the file path in the code:

     ```java
     String filePath = "src\\your-audio-file.wav";
     ```

3. **Compile and run**

   ```bash
   javac src/MusicPlayer.java
   java -cp src MusicPlayer
   ```

4. **Use commands in terminal**

   ```
   P = Play
   S = Stop
   R = Reset
   Q = Quit
   ```

---

 Notes

* Supports only **.wav** files (due to Java Sound API limitation).
* Ensure your system’s Java version supports `javax.sound.sampled`.
* If you get `FileNotFoundException`, check your file path and name carefully.

---

Example Output

```
P = Play
S = Stop
R = Reset
Q = Quit
Enter your choice: P
Playing audio...
Enter your choice: S
Audio stopped
Enter your choice: Q
Bye!
```

---

What You Learn

* Handling audio streams in Java
* Using `AudioInputStream`, `Clip`, and exception handling
* Basic terminal-based UI logic with `Scanner`

