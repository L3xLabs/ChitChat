# ChitChat - End-to-End Encrypted Messaging Application

Welcome to *ChitChat*, a feature-rich, secure messaging platform with end-to-end encryption and multi-media support. Our application is designed to provide seamless one-on-one and group communication, with additional integrations for external messaging services like WhatsApp. The platform supports real-time communication and collaboration features, making it ideal for personal and professional use.

## Features

•⁠  ⁠*One-on-One Chats*: Invite others for a direct chat. To initiate the conversation, simply add the recipient's name and send the first message, as this triggers the invite on their end.
•⁠  ⁠*Group Chats*: Create groups for easy collaboration. You can also host group audio and video calls with additional features like screen sharing, call-specific chat, and more.
•⁠  ⁠*Media Sharing*: Send images, voice notes, locations, and polls, all securely encrypted.
•⁠  ⁠*End-to-End Encryption*: All messages and media are fully encrypted for secure communication.
•⁠  ⁠*VOIP (Audio/Video Calls)*: Enjoy high-quality voice and video calls, both one-on-one and in groups. One-on-one calls offer screen sharing, and all calls are routed through a locally deployed TURN server for better connectivity.
•⁠  ⁠*Group Audio/Video Calls with Jitsi*: Group calls are powered by Jitsi, offering features such as screen sharing and in-call chat.
•⁠  ⁠*WhatsApp Bridge*: ChitChat supports WhatsApp integration, allowing you to send and receive WhatsApp messages directly from our client.

## Getting Started

Visit *[ChitChat](https://chitchat.l3xlabs.com)* to sign in or create an account.

### How to Use:

1.⁠ ⁠*Create an Account*: Sign up with your credentials and log in.
2.⁠ ⁠*Start a Chat*:
   - *One-on-One Chat*: Add a person's name and send the first message to invite them to chat.
   - *Group Chat*: Create a group and invite others to join. You can also initiate group audio or video calls.
3.⁠ ⁠*Sending Media*: Attach and send media files, voice notes, location, and polls through the chat interface.
4.⁠ ⁠*Voice & Video Calls*:
   - *One-on-One Calls*: Initiate audio or video calls with an option to share your screen.
   - *Group Calls*: Host group audio/video calls using Jitsi, featuring screen sharing, call-specific chat, and more.
5.⁠ ⁠*WhatsApp Bridge Setup*:
   - Message *@whatsappbot:l3xlabs.com* to begin setup.
   - Once in chat with the bot, send a message (e.g., "Hello"), and the bot will guide you through the WhatsApp bridge setup process.
   
   This feature allows you to manage all your WhatsApp messages through ChitChat.

### Recommended Browser & Network:
•⁠  ⁠For the best experience, we recommend using *Google Chrome* and a *mobile data connection*. Public or college Wi-Fi networks may cause issues with some features.

## Infrastructure & Deployment

Setting up ChitChat locally is not possible. To deploy the application, you will need:

1.⁠ ⁠A remote server or a server with a static IP.
2.⁠ ⁠A domain name.
3.⁠ ⁠An S3-compatible object store (for storing media).

Once you have the necessary infrastructure, you can set up the services by cloning the *chitchat-infra* repository and configuring the services using the provided configuration files.

---

We hope you enjoy using ChitChat! For any support or feedback, feel free to reach out.
