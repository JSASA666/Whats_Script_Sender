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
