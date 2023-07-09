# Leap-Motion-Based-AI-Mouse-with-Virtual-Voice-Assistant
<details>
<summary>Neutral Gesture</summary>
 <figure>
  
  <figcaption>This gesture is performed by placing the entire palm in front of the screen. The purpose of it is to stop the execution of the previous gesture. </figcaption>
</figure>
</details>
 

<details>
<summary>Peace Gesture</summary>
  
  <figcaption>This gesture is performed by making a V sign with the index and middle finger. It is used to move the cursor across the screen. The faster you move the peace sign across the screen, the faster the cursor moves.
.</figcaption>
</details>

<details>
<summary>Left Index finger up gesture</summary>

 <figcaption>Maintaining the peace gesture, and then putting the middle finger down and bringing it back up mimics the right click operation.
</figcaption>
</details>

<details>
<summary>Middle finger up gesture</summary>

 <figcaption>Maintaining the peace gesture, and then putting the index finger down and bringing it back up mimics the left click operation.
</figcaption>
</details>

<details>
<summary>Double Click</summary>

 <figcaption>Making the peace sign, joining the index and middle fingers and releasing them would perform double click.</figcaption>
</details>

<details>
<summary>Right hand pinch gesture</summary>

 <figcaption>This gesture made by joining the tips of the index finger and thumb of the right hand is used to perform the scrolling function. Both horizontal and vertical scrolling has been enabled in this implementation.</figcaption>
</details>

<details>
<summary>Drag and Drop</summary>

 <figcaption>Making the peace sign and curling the fingers at the starting location would pick the file. Releasing the fingers at the desired end location would drop the file there.  
</figcaption>
</details>

<details>
<summary>Closed Fist gesture</summary>

 <figcaption>Moving a closed fist across a set of items would perform multi-item selection of those items.
</figcaption>
</details>

<details>
<summary>Left hand Pinch Gesture - Audio </summary>

 <figcaption>Making the pinch gesture with the left hand and moving it up or down vertically would increase or decrease the system volume. 
</figcaption>
</details>

<details>
<summary>Left hand Pinch Gesture - Brightness </summary>

 <figcaption>Making the pinch gesture with the left hand and moving it left or right horizontally would increase or decrease the system brightness. </figcaption>
</details>

### Voice Assistant ( ***Siri*** ):
<details>
<summary>Launch / Stop  Gesture Recognition</summary>

<ul>
  <li>
    <code> Siri Launch Gesture Recognition </code><br>
    Turns on webcam for hand gesture recognition.
  </li>
  <li>
    <code> Siri Stop Gesture Recognition </code><br>
    Turns off webcam and stops gesture recognition.
    (Termination of Leap Motion Module can also be done via pressing <code>Enter</code> key in webcam window)
   </li>
</ul>
</details>

<details>
<summary>Google Search</summary>
<ul>
  <li>
    <code>Siri search {text_you_wish_to_search}</code><br>
    Opens a new tab on Firefox/ Chrome Browser if it is running, else opens a new window. Searches the given text on Google.
  </li>
</ul>
</details>

<details>
<summary>Find a Location on Google Maps</summary>
  <ol>
    <li> 
      <code>Siri Find a Location</code><br>
      Asks for the location to be searched.
    </li>
    <li> 
      <code>{Location_you_wish_to_find}</code><br>
      Finds the required location on Google Maps in a new Firefox/ Chrome tab.
    </li>
  </ol>
</details>

<details>
<summary>File Navigation</summary>

  <ul>
    <li>
      <code>Siri list files</code> / <code> Siri list </code><br>
      Will list the files and respective file_numbers in your Current Directory (by default C:)
    </li>
    <li>  
      <code> Siri open {file_number} </code><br>
      Opens the file / directory corresponding to specified file_number.
    </li>
    <li>
      <code>Siri go back </code> / <code> Siri back </code><br>
      Goes back to Parent Directory and lists the files.
    </li>
  </ul>
</details>

<details>
<summary>Current Date and Time</summary>
  <ul>
    <li>
      <code>Siri date </code><br>
      <code> Siri time </code><br>
      Returns the current date and time.
    </li>
  </ul>
</details>


<details>
<summary>Sleep / Wake up Siri</summary>

  <ul>
    <li>
      Sleep<br>
      <code> Siri bye </code><br>
      Pauses voice command execution till the assistant is woken up.
    </li>
    <li>
      Wake up<br>
      <code> Siri wake up </code><br>
      Resumes voice command execution.
    </li>
  </ul>
</details>

<details>
<summary>Exit</summary>
  <ul>
      <li>
      <code> Siri Exit </code> <br>
      Terminates the voice assistant thread. 
    </li>
  </ul>
</details>



# Getting Started
  
  Step 1: 
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Step 2:
  ```bash
  conda activate gest
  ```
  
  Step 3:
  ```bash
  pip install -r requirements2.txt
  ```
  
 
  
  Step 4:
  ``` 
  cd to the GitHub Repo till src folder
  ```
  Command may look like: `cd C:\Users\.....\Leap-Motion-Based-Virtual-Mouse\src`
  
  Step 5:
  
  For running Voice Assistant:
  ```bash 
  python Proton.py
  ```
  ( You can enable Gesture Recognition by using the command "Siri Launch Gesture Recognition" )
  
  Or to run only Gesture Recognition without the voice assistant:
  
  Uncomment last 2 lines of Code in the file `Gesture_Controller.py`
  ```bash 
  python Gesture_Controller.py
  ```
  


