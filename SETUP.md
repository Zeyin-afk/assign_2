# Quick Setup Guide

## Step 1: Install Dependencies
```bash
npm install
```

## Step 2: Create .env File
Create a file named `.env` in the assignment2 folder with the following content:

```env
OPENWEATHER_API_KEY=your_openweather_api_key_here
NEWS_API_KEY=your_news_api_key_here
PORT=3000
```

### Getting API Keys:

**OpenWeather API:**
1. Go to https://openweathermap.org/api
2. Sign up for a free account
3. Navigate to "API keys" section
4. Copy your API key
5. Replace `your_openweather_api_key_here` in .env file

**News API:**
1. Go to https://newsapi.org/
2. Sign up for a free account
3. Copy your API key from the dashboard
4. Replace `your_news_api_key_here` in .env file

## Step 3: Start the Server
```bash
npm start
```

## Step 4: Open in Browser
Navigate to: http://localhost:3000

## Testing API Endpoints

You can test the API endpoints directly:

1. **Weather**: http://localhost:3000/api/weather?city=London
2. **News**: http://localhost:3000/api/news?city=London
3. **Combined**: http://localhost:3000/api/data?city=London

Or use Postman to test these endpoints.

