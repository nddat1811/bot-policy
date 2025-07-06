# Bot - Manage mail

# 🤖 Discord Gmail Bot

## ✉️ Manage Gmail right from Discord!

**Gmail Bot** is a powerful Discord bot that lets you:

- Connect and authenticate your Gmail account  
- Read unread emails  
- View full email content by index  
- Delete unread emails, ads, or even entire inbox  
- Add custom labels to emails  
- Check and empty your trash folder  

> All actions are done inside Discord, securely and easily.  
> No need to switch tabs or share your credentials.  

---

## 🔐 Security & Privacy

- The bot uses **Google OAuth 2.0**, so **you authorize Gmail access yourself**
- **No password is ever saved**, and **no unauthorized access** is possible
- Authentication tokens are securely stored **per user**, using encryption and isolation
- You can **revoke access anytime** here:  
  👉 https://myaccount.google.com/permissions

---

## ⚙️ How to Use

1. Type `/connect_gmail` in any Discord channel  
2. The bot will DM you an **authorization link**  
3. Sign in with Gmail and copy the **auth code**  
4. Send `/auth <code>` back to the bot  
5. Once verified, you're ready to go with commands like:
   - `/read_unread` → View list of unread emails  
   - `/detail 1` → Show full content of email #1  
   - `/del_ads` → Delete all promotional emails  
   - `/tag Work` → Label inbox emails with "Work"

---

## 🧰 Technologies Used

- Python 3.x  
- `discord.py` – Discord bot framework  
- `google-api-python-client` – Gmail API integration  
- `oauthlib`, `pickle` – Token management and secure storage  
- Google Cloud Console – For public OAuth registration

---

## 📜 Privacy Policy & Terms

See full policy here:  
[**Privacy Policy & Terms of Use**](https://www.notion.so/Bot-Manage-mail-2286dfedf9d580af9e77f812d2fa8cda?pvs=21)

- We never store passwords  
- Only token-based access per user  
- Users can delete their access anytime
