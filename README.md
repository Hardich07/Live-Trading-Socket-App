<!--  Project Summary -->
This project is a real-time  trading data platorm that fetches live trade data and historical OHLCV (Open, High, Low, Close, Volume) data from multiple exchanges, including Binance, Bybit, KuCoin, and MEXC.

The project consists of two main components:----

1️ Backend (Node.js, Socket.io, Express.js) – Fetches and processes trading data.
2️ Frontend (Next.js, React.js, DataTables) – Displays data in a user-friendly interface.


<!-- backend Summary -->
 Backend (Node.js + WebSocket Server)
* Built using Express.js and Socket.io
* Fetches real-time trade data from Binance, Bybit, KuCoin, and MEXC
* Fetches historical OHLCV (candlestick) data
* Uses WebSockets to push live trade updates to the frontend

<!-- frontend Summary -->
 Frontend (Next.js + React.js)
Displays OHLCV data in an interactive DataTable
Real-time updates for trade data using WebSockets
Dropdown filters to select exchanges and markets (Spot/Futures)
Styled with Tailwind CSS for a clean, modern look


<!--  Key Features -->
✅ Multi-Exchange Support – Fetches data from Binance, Bybit, KuCoin, and MEXC
✅ Live Trade Updates – WebSocket-powered real-time trade streaming
✅ Historical OHLCV Data – Displays historical candlestick data
✅ Filter by Exchange & Market – User can switch between Spot & Futures markets
✅ Interactive DataTables – Sortable, searchable, and paginated data


<!-- Install Dependencies -->
cd backend
npm install

<!-- Frontend -->
cd frontend
npm install

<!-- Start Backend -->
cd backend
npm start

<!-- Start Frontend -->
cd frontend
npm run dev



<!--  Demo Walkthrough for Client -->
1- Explain Purpose – The platform monitors live trade data and fetches OHLCV history from multiple crypto exchanges.
2- Show Exchange & Market Selection – Dropdown to switch between Binance, Bybit, KuCoin, and MEXC (Spot/Futures).
3- Live Trade Updates – Real-time trade data updates dynamically using WebSockets.
4- Historical OHLCV Table – Displays past trade data (open, high, low, close, volume).
5- Performance & Optimization – Uses React.js hooks (useState, useEffect, useMemo) for efficient rendering.


<!--  Future Improvements:  We can implement below pointers for better Implementation -->

Add chart visualization for better data representation
Implement user authentication for a personalized experience
Integrate more exchanges & API optimizations

<!-- Developer comment -->
Due to office work load and lack of time , I am Not able to work to much on UI part , 
I Just try to implement this using my own past experience and And other website for references.
 



