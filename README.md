<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Nifty & BankNifty Dashboard</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #f0f0f0;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #00ffd1;
    }
    .section {
      background: #1e1e1e;
      margin: 20px auto;
      padding: 20px;
      border-radius: 10px;
      max-width: 700px;
    }
    iframe {
      width: 100%;
      height: 400px;
      border: none;
    }
  </style>
</head>
<body>
  <h1>Nifty & BankNifty Dashboard</h1>

  <div class="section">
    <h2>Live Nifty Chart</h2>
    <iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_1&symbol=NSE:NIFTY&interval=15&hidesidetoolbar=1&symboledit=1&saveimage=1&toolbarbg=f1f3f6&studies=[]&theme=dark"></iframe>
  </div>

  <div class="section">
    <h2>Live BankNifty Chart</h2>
    <iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_2&symbol=NSE:BANKNIFTY&interval=15&hidesidetoolbar=1&symboledit=1&saveimage=1&toolbarbg=f1f3f6&studies=[]&theme=dark"></iframe>
  </div>
</body>
</html>
