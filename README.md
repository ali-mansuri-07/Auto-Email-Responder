# Auto-Email-Responder

Automatic email responding application:

<h2>https://github.com/ali-mansuri-07/Auto-Email-Responder</h2>

##  Prerequisites
<p>Before you begin, make sure you have the following:</p>

- Node.js installed on your machine
- A Gmail account for testing and development purposes
- Access to the Gmail API
- Installation
- To set up the Challenge app, follow these steps:

## Clone the repository:

## Copy code
### `git clone https://github.com/ali-mansuri-07/Auto-Email-Responder.git`

## Navigate to the project directory:
Install the dependencies:

### `npm install`
# Set up Google API credentials:

- Go to the Google Cloud Console.
- Create a new project or select an existing project.
- Enable the Gmail API for your project.
- Create OAuth 2.0 credentials and download the JSON file.
- Rename the downloaded JSON file to credentials.json.
- Place the credentials.json file in the root directory of the project.
- Configuration
- Before running the app, you need to configure the following settings:

## Gmail Account:

- Open the credentials.json file in the root directory.
- Replace "VARIABLES" with your auth keys.
- Save the file.
- Random Intervals:

- Open the index.js file in the root directory.
- Adjust the values of "minInterval" and "maxInterval" according to your desired random intervals in seconds.
- Save the file.
- Usage
- To start the app, run the following command in the project directory:


### `node index.js`
The app will continuously check for new emails in your Gmail mailbox and send replies to emails that have no prior replies. It will also add a label to the email and move it to the labeled category.

Notes
The app uses the Gmail API and requires authentication with your Gmail account. Upon starting the app for the first time, it will prompt you to authenticate and authorize access to your Gmail account.
The first time you run the app, it may take a few seconds to set up the necessary authentication credentials.
The app will run indefinitely until you manually stop it by pressing Ctrl + C in the terminal.
Conclusion
Congratulations! You have successfully set up and used the Challenge app. It will automatically respond to first-time email threads in your Gmail mailbox while you enjoy your vacation. Feel free to customize the email reply content and explore additional features you may want to add to enhance the app's functionality.
