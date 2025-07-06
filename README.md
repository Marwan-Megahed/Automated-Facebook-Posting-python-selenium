
# Facebook Automation using Selenium 🧠🤖

This project demonstrates how to automate login and posting on Facebook using **Selenium WebDriver** with Python. It simulates human-like interaction by logging into a Facebook account and posting a status update using automated keyboard and mouse control.

## 📌 Features

- Logs into Facebook using provided email and password  
- Waits for elements to load using `WebDriverWait` and `ExpectedConditions`  
- Clicks on the post input box and types a message with slight delay between characters (to mimic real typing)  
- Submits the post using Selenium actions

## 🚀 Technologies Used

- **Python 3**  
- **Selenium WebDriver**  
- **Firefox + GeckoDriver**  


## ⚙️ Requirements

```bash
pip install selenium 
```

Also ensure:
- You have Firefox installed
- `geckodriver.exe` is in the project directory or your system PATH

## 📄 How to Use

1. Replace `enter email` and `enter password` in the code with your Facebook credentials  
2. Modify the post content inside the `text = "..."` line  
3. Run the notebook or script  
4. The bot will log in and post your status update automatically

> ⚠️ **Disclaimer**: Automating interactions with platforms like Facebook may violate their terms of service. This project is for educational purposes only.
