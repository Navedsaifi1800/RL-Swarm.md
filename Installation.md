# Download Dependencies 
```
sudo apt update && sudo apt upgrade -y
```
```
sudo apt install git screen python3
```
```
sudo apt install python3.10-venv
```
```
sudo apt install nano
```
---

# Download Node
```
git clone https://github.com/0xmoei/chatbot-app.git
```
```
cd chatbot-app
```
---

# Create Python VW
```
python3 -m venv venv
```
```
source venv/bin/activate
```
---

## Install Some Configuration Files
```
pip install requests
```
---

# Connect Node to your API

```
nano chatbot.py
```
- PASTE YOUR API KEY here "YOUR_API_KEY_HERE"
- Use Arrows keys in the Terminal for Moving the Cursor
- After you have pasted your API,then Click CTRL button given in the Terminal, then Press X
- Then Press Y
- Then Hit Enter

![Image](https://github.com/user-attachments/assets/77026322-b3ea-4dba-b65e-7e65e80075e4)
![Image](https://github.com/user-attachments/assets/23fd2149-7ea6-4003-afe5-83a427f0fbd6)

# Now Run your Node
```
python3 chatbot.py
```
---

# To Start Node Next Day
```
cd chatbot-app
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
python3 chatbot.py
```
--- THE END ---
