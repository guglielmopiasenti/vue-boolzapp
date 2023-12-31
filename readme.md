## Milestone 1

- Replication of the graphics with the possibility of having messages written by the user (green) and by the interlocutor (white) by assigning two different CSS classes
- Dynamic display of the contact list: using the v-for directive, display the name and image of each contact

## Milestone 2

- Dynamic display of messages: using the v-for directive, display all messages relating to the active contact within the conversation panel
- Contact Click shows the conversation of the clicked contact

## Milestone 3

- Adding a message: the user writes a text at the bottom and by typing "enter" the text is added to the thread above, as a green message
- Answer from the interlocutor: each time a message is entered, the user will receive an "ok" as an answer, which will appear after 1 second.

## Milestone 4

- User search: by writing something in the input on the left, only contacts whose name contains the letters entered are displayed (e.g. Marco, Matteo Martina -> I write "mar", only Marco and Martina remain).

## Milestone 5 - optional

- Delete message: by clicking on the message, a drop-down menu appears which allows you to delete the selected message.

# PROCEDURE

1. Logging "Vue ok," and the Vue object to the console using console.log().
2. . A Vue application is created using createApp() and an object literal is passed as its configuration.
3. Method responsible for adding a new message. It performs the following steps:
   - Check if the newMessage is not empty. If it's empty, the method returns early and does nothing.
   - Create a new message object (newMessage) with properties: id, date, message, and status.
   - Append the newMessage object to the messages array of the selected contact.
   - Clears the newMessage input by setting it to an empty string.
