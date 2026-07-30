# MultiCamPong (MCP)
### RU: Это переосмысленная версия классического пинг-понга, в которой для управления линией используется камера, а для голосового общения с друзьями — микрофон!
### EN: This is game reimagined of classic ping-pong and used camera for control the line, microphone for voicechat with friends!
### Рекомендуется играть на пк с вебкамерой! 💻
### Game recommended for PC with webcam! 💻
![Скриншот игры](https://github.com/user-attachments/assets/6a1d1f6a-8d3a-44ce-9c36-a93c4f97942d)

## Как играть? / How to play?
### 🇷🇺 Русский
1. Откройте игру: [https://ruslanmyslivets.github.io/multiplayerpong/](https://ruslanmyslivets.github.io/multiplayerpong/)
2. Разрешите браузеру камеру и микрофон.
3. Управляйте левой ракеткой, сводя и разводя **большой и указательный пальцы** перед камерой.
4. Чтобы играть вдвоём:
   - **Хост** нажимает «Создать предложение», копирует SDP (кнопка 📋) и отправляет другу.
   - **Гость** вставляет SDP в нижнее поле, нажимает «Принять предложение и ответить», затем копирует **свой SDP** (кнопка 📤) и отправляет хосту.
   - **Хост** вставляет ответ гостя и нажимает «Принять ответ».
5. После подключения начнётся игра. Язык интерфейса можно сменить кнопкой с флагом.

### 🇬🇧 English
1. Open the game: [https://ruslanmyslivets.github.io/multiplayerpong/](https://ruslanmyslivets.github.io/multiplayerpong/)
2. Allow browser access to camera and microphone.
3. Control the left paddle by moving your **thumb and index finger**.
4. To play with a friend:
   - **Host** clicks "Create Offer", copies the SDP (📋 button) and sends it to the guest.
   - **Guest** pastes the SDP into the lower field, clicks "Accept Offer & Answer", then copies **their SDP** (📤 button) and sends it back to the host.
   - **Host** pastes the answer and clicks "Accept Answer".
5. The game will start once both players' hands are detected. Switch language with the flag button.

---

## 🛠 Технологии / Technologies
- Handpose
- PeerJS
- WebRTC
- HTML5 Canvas
