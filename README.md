# remote-play
Remote-play uses *pyautogui* to press keyboard shortcuts to control your media. It uses *fastapi* to serve a minimal UI to your mobile device.

Can be used with various players like Hotstar, Amazon Prime, Netflix, etc.

Remote-play supports basic functionalities like Pause/Play, Mute, Volume control, Seeking and also comes with a touchpad with mouse cursor movement and left-mouse button support by tapping.

# Using remote-play
Clone the repository
```bash
git clone https://github.com/shubham1172/remote-play.git
cd remote-play
```

Install requirements
```
pip3 install -r requirements.txt
```

Start the web-server
```
uvicorn main:app --reload --host 0.0.0.0
```

Get your PC's IP address from `ipconfig`. Go to <ipaddr>:8000 on your phone's browser.

**Note**: Make sure that your media player is an active window.

![Screenshot](/docs/screenshot.jpeg)