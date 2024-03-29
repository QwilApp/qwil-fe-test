# Qwil Front-End Interview Take Home Challenge

Thank you for applying to Qwil. We'd like you to write a component that can be used in a chat application. The component displays a list of chats that can be filtered based on attributes of the chat. In the resources folder you can find a sample UI - the chatlist component is highlighted in red.

This repo includes a base application generated by create-react-app. We have used TypeScript but you are welcome to use a plain JavaScript app if you prefer. Feel free to fork this repo for your submission.

## Functional Requirements

1. The solution should be delivered as an app runnable in the browser
2. The component displays a list of chats
3. For each chat, the component should display:
   - The name of the chat,
   - The author of the last message in the chat,
   - The avatar of the last sender of the chat,
   - The time the last message was received,
   - The first line of the last message.
4. The component must allow the user to filter their chats between active and archived chats
5. The component must allow the user to select a specific chat and indicate this selected state in the UI.
6. The component must have a hover state (can be the same as the selected state)

You are free to use whatever 3rd party libs you like and adopt any CSS methodology to manage styling.

## Testing

We would like you to write some tests but you are free to decide what functionality you think it is worth testing,

## API

In this repo, we have used `json-server` which can be used to construct a simple REST API. You will need to first globally install `json-server` and the command, `yarn api` will spin up a REST API on port 3001.

Available endpoints are:

- /GET chats which returns a list of chats
- /GET avatars which returns a list of avatars.
- /GET avatars/${avatarId} returns an avatar object including a URL.
