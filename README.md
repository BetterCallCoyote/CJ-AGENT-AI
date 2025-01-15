# CJ_AiAgent: A Humorous Crypto Twitter Bot Powered by AI

Welcome to **CJ_AiAgent**, a Twitter bot that generates hilarious cryptocurrency-related tweets with the street-smart humor of Carl "CJ" Johnson from **GTA San Andreas**. Not only does the bot post funny tweets, but it also interacts with the crypto community by commenting on tweets from selected accounts, throwing support or playful "hate" in true CJ fashion.

---

## 🚀 Features

- **Automated Tweets**: The bot posts cryptocurrency-related tweets automatically every 30 minutes.
- **Humorous Style**: Tweets are generated in the irreverent, street-smart tone of Carl "CJ" Johnson, adding humor to the crypto space.
- **Support & Hate Comments**: The bot can interact with selected crypto accounts by leaving either supportive or "hate" comments on their latest tweets.
- **OpenAI-Powered**: Using GPT-3 (or GPT-4), the bot generates tweets intelligently based on a set prompt.

---

## 🎥 Demo

Here's an example of a tweet the bot could generate:

> "Man, cryptos are like Big Smoke's appetite - they just keep gettin' bigger, and you never know when they gonna crash! Big Smoke would've loved this shit, spendin' all his crypto on Cluckin' Bell meals, sayin', 'All you had to do was follow the damn chart, CJ!' 🚀 #crypto"

The bot can also interact with Twitter accounts from the crypto community, leaving comments like:

> "Yo, @Bitcoin, you're crushing it in the crypto game! 🚀 Keep it up, homie! #CryptoKing"

Or some playful "hate":

> "Man, @Crypto_Messiah, your crypto game is weaker than Big Smoke's appetite. 😂 Time to step it up! #WeakHustle"

---

## 🛠️ How It Works

1. **Automated Tweets**: Every 30 minutes, the bot generates and posts a new tweet about the crypto market using OpenAI's GPT model.
2. **Interaction with Crypto Accounts**: The bot checks the latest tweets from specific accounts in the crypto community and comments with either support or playful hate.
3. **Generated Comments**: The comments are dynamically created based on the account being interacted with, and they are either supportive or mocking in true CJ style.

---

## ⚙️ Setup Instructions

### Prerequisites

Before you start, make sure you have:

- **Python 3.x** installed.
- **Twitter Developer API credentials**: You can get these from the [Twitter Developer Portal](https://developer.twitter.com/).
- **OpenAI API key**: Sign up and get your key from [OpenAI](https://beta.openai.com/signup/).

### Obtaining Twitter API Keys

To interact with the Twitter API, you need to create a Twitter Developer account and get API keys. Here’s how you can do that:

1. Go to [Twitter Developer Portal](https://developer.twitter.com/).
2. Log in or create an account.
3. Create a new **Project** and **App**.
4. In the app settings, go to the **Keys and Tokens** tab.
5. You’ll need the following credentials:
   - **API Key**
   - **API Secret Key**
   - **Access Token**
   - **Access Token Secret**

### Installation

1. **Clone the Repository**:
   Open your terminal and run:
   ```bash
   git clone https://github.com/yourusername/CJ_AiAgent.git
   cd CJ_AiAgent

2. **Install Dependencies: Install the required Python libraries:**

`bash
pip install tweepy openai`


3. **Set Up API Keys:** Open the script `(cj_aigenerator.py)` and replace the following placeholders with your actual credentials:

**Twitter API Keys:**

`python
- **consumer_key = 'YOUR_API_KEY'**
- **consumer_secret = 'YOUR_API_SECRET'**
- **access_token = 'YOUR_ACCESS_TOKEN'**
- **ccess_token_secret = 'YOUR_ACCESS_TOKEN_SECRET'`**


**OpenAI API Key:**

`python
openai.api_key = 'YOUR_OPENAI_API_KEY'

4. **Run the Bot: Once everything is set up, run the bot with the following command:**

'bash
python cj_aigenerator.py'

**The bot will start generating tweets and interacting with the community every 30 minutes!`**

### 🔧 Customization
You can customize the following in the script:

1. **Crypto Accounts to Interact With:**
Modify the positive_accounts and negative_accounts lists to specify the Twitter accounts you want the bot to interact with. Add any Twitter handles relevant to the crypto community.

Example:

`python
positive_accounts = ['@Bitcoin', '@ethereum', '@Solana']
negative_accounts = ['@Crypto_Messiah', '@BrockPierce']`


2. **Tweet Frequency:**
By default, the bot posts a new tweet every 30 minutes (1800 seconds). If you want to change this, simply modify the 'time.sleep(1800)' value in the script to your preferred interval.

### 💬 Support
If you have any questions or need help setting up the bot, feel free to open an issue on the GitHub repository.

