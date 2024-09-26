## City Wanderer

**City Wanderer** is your perfect companion for exploring new cities. Pick a city, choose landmarks you'd love to visit, and let the app create the best route for your adventure. Whether you're walking, biking, or just curious, City Wanderer will guide you through the city's must-see spots in the most efficient way. Discover hidden gems, save time, and enjoy the journey!

### How to Use the City Wanderer App

1. Choose a City 🏙️
2. Select Landmarks 🏛️
3. Generate Your Route 🛣️
4. Get detailed descriptions of the selected landmarks using AI. 🤖
5. Start Your Adventure! 🚀

You'll need

- a Mapbox access token--[get it here](https://docs.mapbox.com/help/getting-started/access-tokens/)
- your Cloudflare Account ID (the number/character sequence following https://dash.cloudflare.com/ when you login)
- a Cloudflare Workers AI API key (in your Cloudflare account dashboard, click AI on the lefthand side under R2, then <em>Use REST API</em>, then <em>Create a Workers AI API token</em>)
- Create .local.env file in the root directory just like .test.env, and fill in the values for the keys in the .local.env file.:

Download the `requirements.txt` and run `pip install`. Some main libraries this app uses includes LangChain, markdown, pandas, geopy, requests, streamlit, streamlit_searchbox, folium, typing, uuid, streamlit_folium, and folium.plugins (among others.)

Run on the command line with `streamlit run app.py`.
