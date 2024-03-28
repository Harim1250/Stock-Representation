## LIVE STOCKE PREDICTION PROJECT.
IN THIS LIVE-STOCK-PREDICTOR I USED THE REACT.JS COMPONENTS SUCH AS USERSTATE HOOCK AND OTHER COMPONENTS FILES.

USED THE API FOR THE RENDERING THE DATA THROUGH THE FETCH API FUNCTION IN JSON FORMAT.
async fetchStock() { 
        try {
            const API_KEY = 'RBW6DOQ94ODZI9HK'; // Replace 'YOUR_API_KEY' with your actual API key
            const StockSymbol = 'IBM';
            const API_CALL = `https://www.alphavantage.co/query?function=TIME_SERIES_DAILY_ADJUSTED&symbol=IBM&apikey=demo`;
            
            const response = await fetch(API_CALL);
            if (!response.ok) {
                throw new Error('Failed to fetch data');
            }
            const data = await response.json();

MULTICOMPANIES STOCKS LIST LIKE GOOGLE, FACEBOOK, JPMorgan.
 PROJECT DEPLOIED LINK ->
