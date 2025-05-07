# Fake News Detector

A Streamlit application that uses Google's Gemini AI to detect fake news and analyze news content for authenticity.

## Features
- News content analysis
- Fake news detection
- User authentication
- Analysis history
- Modern UI with dark theme

## Local Development

1. Clone the repository:
```bash
git clone <your-repo-url>
cd <your-repo-name>
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file and add your Gemini API key:
```
GEMINI_API_KEY=your_api_key_here
```

4. Run the application:
```bash
streamlit run new.py
```

## Deployment

### Streamlit Cloud
1. Fork this repository
2. Go to [share.streamlit.io](https://share.streamlit.io/)
3. Connect your GitHub account
4. Deploy the application
5. Add your Gemini API key in the secrets section

### Heroku
1. Create a Heroku account
2. Install Heroku CLI
3. Run:
```bash
heroku create
git push heroku main
```

## Environment Variables
- `GEMINI_API_KEY`: Your Google Gemini API key

## Contributing
Feel free to submit issues and enhancement requests!

## License
This project is licensed under the MIT License.

