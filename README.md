# Discord_arxiv_webhook
This is a webhook that periodically posts the latest papers from arXiv to Discord.
I used some AI to create this.

You can run this either on GitHub Actions or in a local environment.
When running it in a local environment, configure the `.env` file as follows:

DISCORD_WEBHOOK_URL= your URL
DEEPL_API_KEY= your API KEY

When running this on GitHub Actions, please refer to the `arxiv.yaml` file in the `.github/workflows` directory.
I’m still learning how to use GitHub Actions, so I had an AI write this for me.

The development environment is as follows:

Python 3.13.13
certifi==2026.6.17
charset-normalizer==3.4.7
feedparser==6.0.12
idna==3.18
packaging==26.0
python-dotenv==1.2.2
PyYAML==6.0.3
requests==2.34.2
setuptools==82.0.1
sgmllib3k==1.0.0
urllib3==2.7.0
wheel==0.46.3