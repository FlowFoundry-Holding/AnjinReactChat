<!-- markdownlint-disable MD030 -->

# Anjin Embed React

React library to display flowise chatbot on your website

![Flowise](https://github.com/FlowiseAI/FlowiseChatEmbed/blob/main/images/ChatEmbed.gif?raw=true)

## Install

```bash
npm install anjin-embed anjin-embed-react
```

or

```bash
yarn add anjin-embed anjin-embed-react
```

## Import

Full Page Chat

```tsx
import { FullPageChat } from "anjin-embed-react";

const App = () => {
  return (
    <FullPageChat
      chatflowid="your-chatflow-id"
      apiHost="http://localhost:3000"
    />
  );
};
```

Popup Chat

```tsx
import { BubbleChat } from "anjin-embed-react";

const App = () => {
  return (
    <BubbleChat chatflowid="your-chatflow-id" apiHost="http://localhost:3000" />
  );
};
```
