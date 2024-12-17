# GDG-Aqaba-workshop

Copy this SCSS to `app.comoponent.scss`

```scss
html,
body {
  font-family: "Google Sans", "Helvetica Neue", sans-serif;
  margin: 5px;
  display: flex;
  flex-direction: column;
  height: 100%;
  font-size: 16px;
}

h1 {
  font-family: "Google Sans", "Helvetica Neue", sans-serif;
  flex-grow: 1;
  margin: auto;
  text-align: center;
  align-items: center;
  font-size: 50px;
  text-align: center;
  color: rgb(217, 41, 100);
}
img {
  width: 200px;
  height: auto;
}

.chat-input {
  display: grid;
  grid-template-columns: 1fr auto;
}
.chat-container {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  background-color: #f0f0f0;
  padding: 20px;
  height: 95vh;
  border-radius: 15px;
}
.chat-header {
  display: flex;
  align-items: center;
  justify-content: center;
}
.logo-container {
  margin-right: 20px;
}
.chat-history {
  flex-grow: 1;
  overflow-y: auto;
  padding: 10px;
}
.chat-message {
  font-family: "Google Sans", "Helvetica Neue", sans-serif;
  font-size: 18px;
  color: #333;
  background-color: #0bafe5;
  padding: 10px;
  border-radius: 5px;
  margin-bottom: 10px;
}
.chat-message.sent p {
  background-color: #e0e0e0;
}
.chat-message.received {
  justify-content: flex-start;
  align-items: flex-end;
  font-size: 18px;
}
.chat-message p {
  padding: 10px;
  border-radius: 5px;
  background-color: #fff;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
  font-size: 14px;
}
.chat-message.sent p {
  background-color: #e0e0e0;
}
.chat-input {
  display: flex;
  height: 10px;
  padding-bottom: 50px;
}
#message-input {
  flex-grow: 1;
  padding: 30px;
  border: 1px solid #ccc;
  border-radius: 45px;
  grid-column: 2;
  margin-right: 10px;
  font-size: 14px;
  color:rgb(31, 31, 31)
}
#send-button {
  padding: 30px 50px;
  background-color: rgb(14, 179, 141);
  color: white;
  border: none;
  border-radius: 45px;
  display: flex;
  font-size: 18px;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}
.responses {
  padding-left: 10px;
  padding-top: 10px;
}

.messages {
  padding-bottom: 10px;
  border: 1px solid rgba(0, 0, 0, 0.1098039216);
  padding: 10px;
  border-radius: 10px;
  font-size: 14px;
  line-height: 2;
  margin-bottom: 10px;
}

.question{
  color: rgb(17, 17, 17);
  background: #fdfdfff8;
  font-family: "Google Sans", "Helvetica Neue", sans-serif;
  font-size: 18px;
}

.answer {
  color: rgb(13, 13, 13);
  background: rgb(115, 191, 249);
  font-family: "Google Sans", "Helvetica Neue", sans-serif;
  font-size: 18px;
}
#send-button:disabled {
  background-color: grey;
  cursor: not-allowed;
}
.warning {
  margin-top: 5px;
  font-family: "Google Sans", "Helvetica Neue", sans-serif;
  text-align: center;
  font-weight:400;
  font-size: .75rem;
  line-height: 1rem;
  letter-spacing: .1px;
  color: rgb(87, 91, 95);
}
.loading-indicator {
  text-align: center;
  font-weight: bold;
}

```
