# Antino_eHackathon
Project submission for the Antino eHackathon

# The Problem
In India, more than Six Crore people suffer from hearing problems, and more than Ten Crore people suffer from speech related problems to some order.
- A Majority of communication-impared population use the *ASL or ISL, but the non-signers struggle to communicate with them.
- Existing solutions like human interpreters or text-based methods are not always accessible or efficient, and sometimes impractical
- Existing organizations only aim to promote and normalize ASL (for eg. "signs-ai" by nvidia) and they fail to provide inclusivity due to lack of a proper dataset. 
> The observation was made that the needs of those troubled by communication barriers are not always catered. So, there exists a need for a real-time, speech assistant solution powered by modern AI-technologies such as vision model.

# The Big Idea
**Sonara** is a web-based accessibility platform, designed to provide inclusivity to people with communication-impairments of varying orders.
- The project features real-time ASL-to-speech and speech-to-ASL conversion, through video-call. It also speech-recognition, ASL-tutoring and custom gesture recognition as additional features.
- Sonara will recognize various signs using the live web-cam footage, to detect the holistic landmarks on the hands, face and body and use those points as data to translate it into text (or to speech) using LSTM.
> Sonara aims to bring the people a quality of life application, and enabling seamless-communication for all, no matter their predicament.


# Steps to Install and Run the model (same as in installation.md)

**1. Clone the repository**
- open the terminal in the folder intended to clone the repository in.
- paste `git clone https://github.com/ParamAhuja/Antino_eHackathon.git` and enter.
- after the repository is cloned, open the folder with a code editor like VS code with permission to access the webcam.

**2. Install the requirements**
- open the terminal in the same folder as the project and paste `pip install -r requirements.txt` and enter.

**3. Run the project**
- simply run the python program file named "ASL.py".
- the webcam window will pop-up, press "q" on keyboard to exit the window.

## IMPORTANT INSTRUCTIONS:
1. python version `Python 3.10.0`
2. If using locally on a code editor, make sure to provide access to the webcam.
3. If using an online notebook editor, make sure to use one that provides webcam accessibility.