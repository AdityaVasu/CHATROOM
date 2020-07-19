<h1>RealTime Chat Application - LetsChat</h1>

<ul>
<li>It is a Realtime Scalable Chat application which supports multiple user at the same time.</li>
<li>FrontEnd - HTML, CSS</li>
<li>BackEnd - JavaScript, Node.js</li>
<li>Used Socket.io module for a two-way connection between client and server</li>
<li>FrontEnd includes a navigation bar, Chat window and a form submit button for sending the messages.</li>
<li>Structure is prepared by using HTML</li>
<li>Styling is given by using CSS</li>
<li>Added Client sided JavaScript for the purpose of playing with DOM elements.</li>
<li>First of all stored all the DOM elements in a respectives JS variable.</li>
<li>Used Audio file (ting.mp3) which gives notification on receiving the message</li>
<li>Everytime a new user tries to join, first of all ask his/her name and let the server know</li>
<li>If a new user joins, receive the event from the server using eventListner</li>
<li>Receive message from server using receive function</li>
<li>If a user leaves the chat, tell all the other users that this user has left the chat</li>
<li>Server Side JavaScript will handle the Socket IO connections</li>
<li>If a new user joins, let the other users connected with server know</li>
<li>If someone sends the message, broadcast it to other people</li>
<li>If someone leaves the chat, let others know</li>
</ul>
