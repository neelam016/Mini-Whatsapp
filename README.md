# Mini-Whatsapp clone


A simple chat web app built with Node.js, Express, MongoDB, and EJS that supports sending text messages and uploading images. Inspired by WhatsApp's minimalist design and real-time chatting experience.

**Features**

Create, edit, and delete chats

Upload and send images with messages

View chat timestamps

Confirmation dialog before deleting chats

Responsive and clean UI with CSS styling


**Tech Stack**

Node.js & Express for server and routing

MongoDB with Mongoose for database

EJS for templating

Multer for file uploads

Method Override for HTTP verbs (PUT, DELETE) support in forms

CSS for styling

**Installation & Setup**
Clone the repo

git clone https://github.com/your-username/mini-whatsapp.git
cd mini-whatsapp


Install dependencies

npm install


Start MongoDB

Make sure MongoDB is installed and running on your machine at default port 27017.

Run the app

node app.js


Open your browser

Navigate to http://localhost:8080/chats
 to start chatting!

**Usage**

Click New Chat to create a message.

Fill in sender, receiver, message, and optionally upload an image.

View all chats on the main page.

Edit or delete chats with buttons next to each message.

Deleting prompts a confirmation dialog.

**Folder Structure**
mini-whatsapp/
│
├── models/
│   └── chat.js          # Mongoose schema for chats
├── public/
│   ├── app.js           # Frontend JS for delete confirmation
│   ├── style.css        # CSS styles
│   └── uploads/         # Uploaded images stored here
├── views/
│   ├── index.ejs        # Main chats listing
│   ├── new.ejs          # New chat form
│   └── edit.ejs         # Edit chat form
├── app.js               # Main Express app
└── package.json         # Node dependencies

**Dependencies**

express

ejs

mongoose

multer

method-override

**License**

MIT License © Neelam
