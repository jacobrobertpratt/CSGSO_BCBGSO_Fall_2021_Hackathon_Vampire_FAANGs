# CSGSO_BCBGSO_Fall_2021_Hackathon_Vampire_FAANGs
CSGSO_BCBGSO_Fall_2021_Hackathon_Vampire_FAANGs

# AIWriter
AIWriter is a web app that takes an input prompt (a couple sentences), and generates an essay using that initial prompt. To do this, AIWriter uses the GPT-2 algorithm from OpenAI. GPT-2 is a large transformer-based language model with 1.5 billion parameters, trained on a dataset. OpenAI created a new dataset which emphasizes diversity of content, by scraping content from the Internet. In order to preserve document quality, they used only pages which have been curated/filtered by humans—specifically. They also used outbound links from Reddit which received at least 3 karma.

## How to run the web app
Install Python 3.5+ and pip on your local machine <br>
Run :- <br>
pip install flask <br>
pip install torch <br>
pip install transformers <br>

Navigate to the webapp_flask directory in the terminal <br>
Run:- <br>
export FLASK_APP=aiwriter <br>
flask run <br>

Open http://127.0.0.1:5000/

## Presentation
https://docs.google.com/presentation/d/1emkij1G_xTqJrTIFCHZW1r24YZlv8Ouk6TEfmoYmjdc/edit?usp=sharing
