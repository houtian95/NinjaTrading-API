## PyNinjaTrader_API - Drag & Drop C# Connector(DLL) for strategies coded in C# in combination with MT4/5 brokers.

The PyNinjaTrader_API is a connection/interface between C# strategy(Visual Studio, VS code, NT8,...) and a MT4/5 terminal. In priciple for all C# coding as long as external DDL's can be imported.
The functionality is an anology to our wel known Pytrader_API used by many user strategies coded in python.
Besides the DLL an EA is needed for MT4 and MT5 terminal. These are also part of the system.
The demo version has full functionality for the following instruments: EURUSD, AUDCHF, NZDCHF, GBPNZD and USDCAD. Dax is added as index instrument in the demo.
The functionality is documented in an .pdf file.


The DLL can be added to your system of choice as a reference.
A MT4 or MT5 terminal must be running. The appropriate EA must be runnng in one chart. Socket server port and for licensed version 
the folder with the authentication indicator must be filled in. In demo the system is working full functioning for the above mentioned instrument.
The authentication indicator can be acquired via MQL5 Markets.

The socket communication is very fast (interrupt based). The execution time of the function depends on the function and selected broker.
The MT terminal acts as server and the PyNinjaTrader_API as client, so always question / answer.


## Feature list.:
* Connect to MT4 / MT5 broker.
* Check connection.
* Retrieve static and dynamic account info.
* Enable / disable auto trading(protection).
* Retrieve tick data.
* Retrieve bar / candle data.
* Get instrument info.
* Check tradebility of instrument.
* Open pending and market orders.
* Change settings like, stoploss, takeprofit of orders / positions.
* Close positions, delete pending orders
* And many more now and to come
