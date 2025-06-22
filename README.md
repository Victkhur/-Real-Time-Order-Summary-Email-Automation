# 🚀 AI-Powered Email Automation via Google Sheets, OpenAI & Gmail (n8n)

## 🧩 Problem

Manually crafting and sending emails based on updates in spreadsheets is time-consuming, error-prone, and inefficient—especially when working with dynamic data like customer feedback, order records, or reports. Teams often struggle to keep stakeholders informed in real-time, leading to missed updates or delayed communication.

---

## ✅ Solution

This **n8n** workflow automates the entire process:

* **Monitors Google Sheets** for updates in real-time
* **Uses OpenAI** to intelligently generate context-based messages
* **Sends emails via Gmail** instantly and automatically

No manual writing. No delays. Just smart, timely communication.

---

## ⚙️ How It Works

### 1. 🔁 Google Sheets Trigger

* **Trigger**: `anyUpdate`
* Detects changes (new input or edits) in your specified Google Sheet.

### 2. 🧠 OpenAI (ChatGPT)

* **Action**: Uses a language model to generate a professional message.
* **Example prompt**: "Summarize the row details and write an email update to the client."

### 3. 📩 Gmail

* **Action**: Sends the generated message to a predefined email address or stakeholder.

---

## 🛠 Use Cases

* 🗓️ Auto-generate meeting summaries from notes
* 🛒 Notify clients when orders are updated in a sheet
* 🧾 Weekly performance summaries for your team
* 📊 Real-time project status updates to stakeholders

---

## 🖼️ Workflow Screenshot

![screenshot-1747051139782](https://github.com/user-attachments/assets/00155340-9f13-4993-94fd-3d7515478748)


---

## 🧰 Requirements

* Self-hosted [n8n](https://n8n.io) (v1.97 or above)
* Connected accounts:

  * Google Sheets
  * OpenAI (API Key)
  * Gmail

---

## 📬 Example Output

> "Hi Team,
> A new update was made to the sales report: John Doe closed a \$5,000 deal.
> Please check the sheet for full details.
> – AI Assistant"

---

## 👨‍💻 Built With

* [n8n](https://n8n.io) – Low-code workflow automation
* [OpenAI](https://openai.com/) – Generative AI
* [Gmail](https://www.google.com/gmail/) – Email delivery


