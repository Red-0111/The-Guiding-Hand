# The-Guiding-Hand


## Walkthrough Video
[link](https://youtu.be/gaTFQSBCcrk)


## The Problem
Ever since the onset of covid, the world has heavily been depending on various forms of online communication in order to keep the flow of work going. For the first time ever, we experienced teaching via zoom, Microsoft teams and various other platforms.  
Understanding concepts without visual representation has never been easy and not all teachers or institutions can afford Edupen, iPads, or other annotation software.

## What it does
Our product aims at building a richer bridge between machines and humans than primitive text user interfaces or even GUIs (graphical user interfaces). It is alternative user interface for providing real-time data to a computer instead of typing with keys thereby reducing the amount of effort required to communicate over platforms.
When a user opens the Guiding Hand's website they see a button. On clicking the button they are led to our application. <br>
The application uses hand gestures to perform various functions. <br>
- 1 finger to draw on the screen. <br>
- 2 fingers to change pen color or select eraser. <br>
- 3 fingers to take a screenshot. <br>
- 4 fingers to clear the screen. <br>

## Tech Stacks Used
- ReactJS for the site <br>
- Python- libraries such as opencv, mediapipe, numpy, and pyscreenshot. <br>
- Flask to build the server that runs the Python application <br>



## How to Run the application
### Pre requisites:
NodeJs and Python need to be installed.

### To run the React Server
```
cd draw-app
```
```
npm install
```

```
(if any vulnerabilities)
npm audit fix 
```
```
npm install --save particles-bg
```
```
npm install styled-components
```
```
npm start
```
### To Run the Flask Server
#### Installing required Python Libraries

```
pip install Flask
```
```
pip install mediapipe
```
```
pip install numpy
```
```
pip install opencv-python
```
```
pip install pyscreenshot
```

#### Running the Flask Server
```
cd flaskapp
```
```
flask run
```

### Opening the Application

On performing the npm start command, a react server will open up. Click on the button on the site to start the application. (Ensure that camera access is enabled)
A Python window will open up. Enjoy using our interface!

## What's next for The Guiding Hand
- Adding more hand gestures for more features. <br>
- Allowing multiple people to draw on the same screen simultaneously. <br>
- Annotating over a shared screen. <br>
- Converting hand-drawn text on-screen to text and saving it in a document. <br>

## Images
![ssimg366](https://user-images.githubusercontent.com/73791717/136694944-c414acf1-329f-4335-9022-ae2096c69da7.png)
![Thumbnail](https://user-images.githubusercontent.com/73791717/136694950-e8d4aa33-0e7a-4f07-8124-72183e7f1034.png)
![img](https://user-images.githubusercontent.com/73791717/136694952-0cc93e71-41b4-416d-a6c5-959510faa705.png)

