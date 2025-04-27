# Hyperbolic
Got it — here's your **Hyperbolic Node Run Guide**, cleaned up a little for easier reading and following:

---

# 🚀 Hyperbolic Node Run Guide

✅ **No need for a high-end PC or laptop** —  
✅ **You can even run it on a mobile phone!**

---

## 1. For Mobile Users:
- **Download this app** to run Linux on Android:  
  [Ulauncher (ULA)](https://play.google.com/store/apps/details?id=tech.ula&pli=1)

---

## 2. Create Your Hyperbolic Dashboard:
- Sign up here: [Hyperbolic Dashboard](https://app.hyperbolic.xyz/)

---

## 3. Register Your Phone Number

---

## 4. Download Necessary Dependencies:
Run these commands one by one:
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install git screen python3
sudo apt install python3.10-venv
sudo apt install nano
```

---

## 5. Download Node Files:
```bash
git clone https://github.com/0xmoei/chatbot-app.git
cd chatbot-app
```

---

## 6. Set Up Python Environment:
```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 7. Install Required Python Libraries:
```bash
pip install requests
```

---

## 8. Connect Your Node to Hyperbolic Dashboard:
- Open `chatbot.py` file:
  ```bash
  nano chatbot.py
  ```
- Go to your Hyperbolic Dashboard → Settings → Copy your **API Key**.
- Find `"YOUR_API_KEY_HERE"` inside `chatbot.py`, and replace it with your actual API Key.

> ⌨ **Tips inside Nano editor:**  
> - Move with Arrow keys ➡️⬅️  
> - Save changes: **CTRL + X**, then press **Y**, then **Enter**.

---

## 9. Run Your Node:
```bash
python3 chatbot.py
```

---

## 📅 To Start Your Node the Next Day:
Each time you reboot or return:
```bash
cd chatbot-app
python3 -m venv venv
source venv/bin/activate
python3 chatbot.py
```

---

# 🎉 Done! Your Hyperbolic Node is now running!

---

Would you also like me to format this into a **PDF** or a **small checklist** version if you want it even handier? 📋🚀
