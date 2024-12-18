Discord Webhook Messenger with IP Logger
This is a simple website that allows users to send messages to a Discord webhook while logging their IP address for safety purposes.

Look at the UI and functionality here ! https://vloqus.github.io/WebhookIPPuller/

Features

User Input: Users can type a message into a textbox and send it to a specified Discord webhook.

IP Logging: The user's public IP address is automatically fetched and included in the message sent to the webhook.

Dynamic Feedback: The interface provides real-time feedback (e.g., "Message sent successfully" or error messages).

User-Friendly Design: A simple and responsive interface with a clean layout.

Retrieves the user's timezone using Intl.DateTimeFormat().resolvedOptions().timeZone.

Fetches browser details (e.g., user agent string) using navigator.userAgent.


Installation
Download or clone this repository:
git clone https://github.com/vloqus/webhookippuller.git

Configuration

1- Replace the placeholder YOUR_WEBHOOK_URL in the index.html file with your Discord webhook URL:

 const webhookUrl = "YOUR_WEBHOOK_URL";

2- Save your changes.

Usage
1- Open the webpage in your browser.

2- Enter a message in the textbox.

3- Click the "Send" button.

4- The message, along with the user's IP address, will be sent to the specified Discord webhook.


Example Output in Discord
When a user sends a message, the Discord webhook will receive:

Message: This is a test message

IP: 123.45.67.89

Timezone: America/New_York

Browser: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36



