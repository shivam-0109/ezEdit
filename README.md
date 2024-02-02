<div align="center">
  <h1>ezEdit</h1>
  <p>
    <strong>Enjoy hands-free voice editing</strong>
  </p>

ezEdit Empower Individuals with Hands-Free Photo Editing via voice
</div>


# Features

- **Completely voice-based**
- **Load any image directly from any folder**
- **Change Brightness of image**
- **Change Saturation of image**
- **Rotate the image flexibly**
- **Change contrast of image**
- **Sharpen the image**
- **blur the image**
- **Save the image**

# Local installation

1. Clone the repository

  First, you need to clone the repository

  ```
  git clone https://github.com/shivam-0109/ezEdit.git
  ```

2. Change Path

Change all the directories from ```C:/Users/singh/Downloads/Image-Editing-Using-Voice-Commands-1/elements2.0Images/xyz.png``` in  `ezEdit.py` to the absolute path in your local computer.


3. Install Dependencies

Install the project's dependencies:

```
pip install tk flask pygame Pillow SpeechRecognition pocketsphinx pynput pyaudio pyttsx3 nltk keyboard tkfontchooser
```

4. Make a Registry Entry .

    i)  Click on `windows key + r` and type `regedit` and click ok.
   
    ii) Go to `HKEY_CLASSES_ROOT\*\shell` -> Right-click on the `shell` key, choose `New > Key` and set the name to "Edit With ezEdit".  
  
    iii) Right-click on the `key -> New > Key` .  
  
    iv)  Name it `command`   
  
    v) Set the value to the following command, replacing ```C:\Path\To\Your\Python\python.exe``` and ```C:\Path\To\Your\Script\myscript.py``` with your Python executable and script path:
    ```"C:\Path\To\Your\Python\python.exe" "C:\Path\To\Your\Script\ezEdit.py```
  

5) Right-click on any image -> Click on "Edit With ezEdit".
   
7) The program will be up and running now.


# Contributors

* Hardik Malani
* Shivam Kumar Singh
* Abilaash S
* Paras Atal
