# 🎮 Custom Cheat Engine 🎮

<div>

  <p>A custom Cheat Engine supporting multiple value type memory grab and insertion. Multithreading used for search, as well as UI/process thread separation. Allows process selection via active processes or active windows (NOTE: This project is not liable for misuse in online multiplayer video game environments. Please check a game's terms of service before using this this software)</p>

  <p><b>Note!!!</b> This cheat engine currently only runs on Windows devices.</p>
</div>

<div>
   <h2>Table of Contents</h2>
  <ul>
    <li><a href="#Setup">How to Setup</a></li>
    <li><a href="#Features">Features</a></li>
    <li><a href="Limitations">Limitations</a></li>
  </ul>
</div>

<div>
  <h2 id="Setup">How to Setup</h2>

  <ol>
    <div>
    <hr>
    <img src="Readme_Image's/Instruct_One.jpg" alt="Folder 3" style="max-width:100%;">
    <hr>
    <li><b>To download the Cheat Engine, click the <>code button on the right-hand side of the repository</b></li>
    </div>
    <div>
    <hr>
    <img src="Readme_Image's/Instruct_Two.jpg" alt="Folder 3" style="max-width:100%;">
    <hr>
    <li><b>On the drop-down menu, select the bottom option to download the repository as a Zip</b></li>
    </div>
    <div>
    <hr>
    <img src="Readme_Image's/Instruct_Four.jpg" alt="Folder 3" style="max-width:100%;">
    <hr>
    <li><b>Extract the Custom-Cheat_Engine-main folder to wherever on your pc (Probably Documents or Desktop)</b></li>
    </div>
    <div>
    <hr>
    <img src="Readme_Image's/Instruct_Five.jpg" alt="Folder 3" style="max-width:100%;">
    <hr>
    <li><b>Inside of the folder, the first file should be the .exe application called Custom_Cheat_Engine. Open the application -> Below will be a few notes on the applications features and a short showcase of how to use it</b></li>
    </div>
  </ol>
</div>
<hr>
      
<div>
  <h2 id="Features">Features</h2>
  <img src="Readme_Image's/Feature_One.jpg" alt="Folder 3" style="max-width:100%;">#
  <hr>
  <p>Above is the complete look of the cheat engine:</p>
  <ul>
    <li>Buttons <b>"By Window"</b> and <b>"By Process"</b> allow the selection of specific processes/windows with which to start the memory reading differential algorithm. Clicking on the drop-down box and selecting said process will update the process id label on the right hand side</li>
  <hr>
  <img src="Readme_Image's/Feature_Three.jpg" alt="Folder 3" style="max-width:100%;">  
  <hr>
  <p>Search for value is where you can select the data type for searching memory locations in the process. The data types include:</p>
    <ul>
      <li><b>Signed Integer 32-bit</b></li>
      <li><b>Unsigned Integer 32-bit</b></li>
      <li><b>Signed Integer 64-bit</b></li>
      <li><b>Unsigned Integer 64-bit</b></li>
      <li><b>Float</b></li>
      <li><b>Double</b></li>
    </ul>
    <li>When clicking the search button, the first step of the differential search occurs. A list of memory locations (if any), is sent back to the user, where additional searches will shave down the list till only a few memory locations remain or the list is empty</li>
    <li>clearSearch clears a given differential search, so you may restart the process of searching again</li>
  <hr>
  <img src="Readme_Image's/Feature_Seven.jpg" alt="Folder 3" style="max-width:100%;">  
  <hr>
  <li>Memory pointers will be pasted in the scroll box at the bottom of the cheat engine. The "Memory Pointer Found:" prints out the total discovered memory pointers of the current differential search sequence. A progress bar also tracks how long the process memory scan is taking.</li>
  <li>Memory addresses can be clicked on, and copied using Ctrl + c for later</li>
  <hr>
  <img src="Readme_Image's/Feature_Six.jpg" alt="Folder 3" style="max-width:100%;">  
  <hr>
  <li>Now you have your memory pointer, you can paste it inside the "Enter Memory Location:" box. The write to memory will allow writing a specific arithmetic value, based on the type you selected during that specific search process. Write will alter the value in memory.</li>
  </ul>
  <hr>

<p><b>A short example GIF below -></b></p>
</div>

<div>
  <hr>
  https://github.com/user-attachments/assets/0c3078a6-54d0-4873-a5d1-63b2b0ec488e
</div>
