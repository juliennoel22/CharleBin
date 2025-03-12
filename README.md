# CharleBin

CharleBin is a web application that allows users to send encrypted messages securely. Users can set a password for their messages, choose an expiration date, and enable options like automatic deletion after reading. Messages are stored locally in the browser until expiration.

## Features

- **Message Encryption**: Messages are encrypted before being sent, ensuring security during transmission.
- **Password Protection**: Optionally, a password can be added to enhance security.
- **Expiration Date**: Users can set an expiration date for each message. After this date, the message will be inaccessible.
- **Automatic Deletion After Reading**: An option to delete the message after it has been read is available.
- **Intuitive Interface**: A simple interface allows users to preview the message before sending.

## Requirements

- A modern browser that supports JavaScript.
- PHP 7.4 or later to run the backend if you wish to host the application on your own server.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/juliennoel22/CharleBin.git
   ```
2. Navigate to the project folder:
   ```bash
   
    cd CharleBin
    ```
   
3. Install dependencies:
    ```bash
    composer install
    ```
   
4. Start the application on a local server:
    - Using PHP's built-in server:
      ```bash
      php -S localhost:8000
      ```
    - Or deploy the project on your server following your hosting provider's setup instructions.


## Usage

1. **Create a Message**: Enter the text in the input field. You can add a password and set an expiration date if needed.
2. **Send a Message**: Click "Send" to generate a link containing your encrypted message.
3. **Access the Message**: Share the link with the recipient. The message will only be accessible if the password is correct and the expiration date has not passed.
4. **Additional Options**: You can choose to delete the message after reading by enabling the "Delete after reading" option






