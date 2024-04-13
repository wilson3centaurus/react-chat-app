# JS Chat Website 💬


A real-time chat app powered by Python, FastAPI, React JS, and Chat Engine. Users can authenticate, create group chats, send messages, and share attachments. The backend handles authentication and chat functionality, while Chat Engine provides websockets for seamless communication.

## 1. Clone this repository

Ensure you have Node.js and npm installed on your machine
```
git clone https://github.com/wilson3centaurus/react-chat-app/
```

## 1. Add `.env` file

Add your `.env` file in the `frontend` folder, add the following with your [ChatEngine.io](ChatEngine.io) Project ID (instead of `XXXX`)

```
VITE_CHAT_ENGINE_PROJECT_ID=XXXX
```

## 2. Install the python required packages in `requiremnets` file

Within your root folder `react-chat-app` cd into backend and run the following line:

```
pip install -r requirements.txt 
```

## 3. Add your `ChatEngine.io` Private key

Within your `backend` folder, add the following with your [ChatEngine.io](ChatEngine.io) Private Key on line 15 (instead of `XXXX`)

```
PRIVATE_KEY = "XXXX"
```

## 4. Run the code!

```
npm install # to install all packages
npm run dev # to start the website
```

Then, your website will be running at http://localhost:5173/


## Screenshots
<img src="https://github.com/wilson3centaurus/react-chat-app/assets/107620180/8b650094-e962-44f3-a5b2-bc7a758d0d14" alt="Screenshot 2024-04-13 122928" width="900">
<img src="https://github.com/wilson3centaurus/react-chat-app/assets/107620180/c34c27d1-4b21-45f0-9dfb-9578d267ed00" alt="Screenshot 2024-04-13 122747" width="900">

## Author
### Tafadzwa Wilson Sedze [Github link](https://github.com/wilson3centaurus/)
