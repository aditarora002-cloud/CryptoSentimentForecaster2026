Just built my another end-to-end AI/ML project — Crypto Sentiment Forecaster!

I combined real-time crypto prices, news sentiment analysis, and LSTM forecasting into one clean web app.

What it does:
• Live prices in ₹ (INR) or $
• Analyzes recent news and gives sentiment score (Positive/Negative/Neutral)
• Predicts next 7 days price with uncertainty range
• Shows backtesting so you can judge how good the model is
• Clean, beginner-friendly UI with explanations

Tech Stack:
• Python + Streamlit
• PyTorch (LSTM model)
• Hugging Face (sentiment analysis)
• CoinGecko API + Cointelegraph RSS
• Deployed on Render

Biggest challenge? 
Making heavy libraries (torch + transformers) work on free cloud platforms and handling sparse news data. Learned a lot about deployment, caching, and making ML projects production-friendly.
