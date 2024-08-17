**WhatsApp Chat Analyzer**
**Overview**
The WhatsApp Chat Analyzer extracts insights from WhatsApp chat data, offering statistics and visualizations to understand conversation patterns.

**Features**
Message Count: Total messages by each participant.
Word Frequency: Commonly used words.
Active Hours: Time distribution of messages.
Media Sharing: Count of images, videos, etc.
Sentiment Analysis: Sentiment trends over time.
Emojis: Most used emojis.

**Installation**
1.Clone the repository: git clone https://github.com/JyothsnaThangudu/WhatsApp_Chat_Analysis.git
2.Navigate to the project directory:
cd WhatsApp_Chat_Analysis
3.(Optional) Create a virtual environment:
python -m venv myenv
source myenv/bin/activate  # On Windows: `myenv\Scripts\activate`
4.Install dependencies:
pip install -r requirements.txt

**Usage**
1.Export your WhatsApp chat as a .txt file.
2.Run the analyzer:
python analyze.py --file path_to_your_chat_file.txt
3.View results in the terminal and output directory.
