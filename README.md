# Whats_Script_Sender
Whatsapp Script sender for scammers or just for fun

# 🎥 WhatsApp Web Script Sender – Automatically Send Movie Scripts

This JavaScript script allows you to automatically send long text content (such as movie scripts, books, lyrics, or any plain text) line by line in an open **WhatsApp Web** conversation.

It works directly from your browser's developer console and simulates typing and sending messages like a human.

---

## ⚠️ Warning About the "Send" Button

WhatsApp Web updates its code frequently. If the script stops working, it's likely because the **selector for the send button has changed**.

### 🕹️ Send Button Selectors Used:

- ✅ **Previous selector**:
  ```
  main.querySelector(`[data-testid="send"]`) || main.querySelector(`[data-icon="send"]`)

  ```

- ✅ **Current selector**:
  ```
  main.querySelector(`button[aria-label='Send']`) || main.querySelector(`[data-icon="wds-ic-send-filled"]`)
  ```

##What to Do If It Breaks
1. Right-click the "Send" button in WhatsApp Web.

2. Click Inspect.

3. Look for the updated aria-label, data-icon, or similar attributes.

4. Replace the selector line in the script with the new values.

##How to Use This Script
Open WhatsApp Web in your browser and select a chat.

1. Press F12 or Ctrl + Shift + I (Windows/Linux) or Cmd + Option + I (Mac) to open Developer Tools.

2. Go to the Console tab.

3. In this GitHub repository:

4. Open the script.js file.

5. Click the "Raw" button to view it in plain text.

6. Copy the entire script.

7. Paste it into the console (F+12 and find the console).

8. Press Enter.

✅ The script will automatically start sending the text line by line into the conversation.

##NOTE
You can modify how fast the script sends each message. The default delay is 250 milliseconds.
FIND:
```
await new Promise(resolve => setTimeout(resolve, 250));
```
And there you go! Enjoy.
