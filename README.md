# Twitter Bot Using OpenAI GPT-3 API

⚠️Warning: Twitter stopped supporting the free API, so this bot is no longer alive :(

Twitter Bot that posts random facts on Twitter via API. Requires that you generate a Twitter OAuth token for the new v2 API

Currently running on Twitter as @YourRandomFact, hosted on AWS Lambda. 

## Create zip package for Lambda

``` bash
pip install -r requirements.txt -t ./package
zip -r pkg.zip package/* lambda_function.py
```
