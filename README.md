

# Doctor Strange Filter with Python

This project is a test of my skills in computer vision. The project was created using Mediapipe and OpenCV libraries and Python program language. As the name suggests, I tried to replicate the magic circles that appear on the palms of the popular MARVEL hero Dr. Strange when he casts a spell.

To summarize the working logic of the project, the script starts by detecting hand gestures from your device's camera and then calculates the midpoint of your palm and the openness of your palm with these points.  If your hand is open enough, a mask (the filter itself) is created using the previously given images and pasted onto the calculated midpoint.  

Of course, this was a very simple explanation. There are many things to know about perspective, rotating image objects and creating transparent objects during this project. I hope this project will help you to understand these topics :)

## Folder Structure

```
.
├── Models                    # Models to be used when creating the filter
|   ├── Inner Circles         # Circle models to be found on the inner side 
|   └── Outer Circles         # Circle models to be found on the outer side 
├── functions.py              
├── main.py                    
├── LICENSE
├── requirements.txt                   
└── README.md
```

## Setup

1. Clone this repostiory : `git clone https://github.com/Arslanex/Instagram-Mapping`
2. Instal requirements : `pip install -r requirements.txt`
3. Run main.py script : `python main.py`

