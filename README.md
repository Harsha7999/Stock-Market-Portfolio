# Stock-Market-Portfolio
HTML code :

<!DOCTYPE html>
<html>
<head>
  <title>Stock Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <link rel="stylesheet" href="style6.css">
</head>
<body>
  <header>
    <h1>Stock Portfolio</h1>
  </header>
  
  <main>
    <table>
      <thead>
        <tr>
          <th>Stock Name</th>
          <th>Company Name</th>
          <th>Shares</th>
          <th>Price (USD)</th>
          <th>Total Value</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>AAPL</td>
          <td>Apple Inc.</td>
          <td>15,787,154,000</td>
          <td><span class="price-increase">$186.68 <i class="fas fa-arrow-up"></i></span></td>
          <td>$2.08 T</td>
        </tr>
        <tr>
          <td>GOOGL</td>
          <td>Alphabet Inc.</td>
          <td>12,781,000,000</td>
          <td><span class="price-decrease">$122.34 <i class="fas fa-arrow-down"></i></span></td>
          <td>$1.56 T</td>
        </tr>
        <tr>
          <td>MSFT</td>
          <td>Microsoft Corporation</td>
          <td>7,441,000,000</td>
          <td><span class="price-increase">$335.02 <i class="fas fa-arrow-up"></i></span></td>
          <td>$2.94 T</td>
        </tr>
		<td>KRX</td>
          <td>Samsung Electronics Co Ltd.</td>
          <td>6,792,669,250</td>
          <td><span class="price-decrease">$72,400 <i class="fas fa-arrow-down"></i></span></td>
          <td>$481.64 T</td>
		  </tr>
		  <tr>
		   <td>TATA</td>
          <td>TATA MOTORS</td>
          <td>764,866,397</td>
          <td><span class="price-increase">$6.89 <i class="fas fa-arrow-up"></i></span></td>
          <td>$2.03 T</td>
        </tr>
        <tr>
		 <td>BMW</td>
          <td>Bavarian Motor Works</td>
          <td>644,000,000</td>
          <td><span class="price-increase">$1.32 <i class="fas fa-arrow-up"></i></span></td>
          <td>$72.09 B</td>
        </tr>
        <tr>
		 <td>VOW3</td>
          <td>AUDI</td>
          <td>47,005,000</td>
          <td><span class="price-decrease">$133.10 <i class="fas fa-arrow-down"></i></span></td>
          <td>$17.18 B</td>
        </tr>
        <tr>
		 <td>MBG</td>
          <td>Mercedes Benz Group AG</td>
          <td>1,069,837,447</td>
          <td><span class="price-increase">$77.35 <i class="fas fa-arrow-up"></i></span></td>
          <td>$87.49 B</td>
        </tr>
        <tr>
		 <td>RR</td>
          <td>Rolls-Royce PLC</td>
          <td>19,918,038</td>
          <td><span class="price-increase">$196.19 <i class="fas fa-arrow-up"></i></span></td>
          <td>$35.69 B</td>
        </tr>
        <tr>
		 <td>FERRARI</td>
          <td>Ferrari NV</td>
          <td>181,953,498</td>
          <td><span class="price-increase">$307.05 <i class="fas fa-arrow-up"></i></span></td>
          <td>$55.78 B</td>
        </tr>
        <tr>
		<td>ASM</td>
          <td>Aston Martin</td>
          <td>698,757,075</td>
          <td><span class="price-decrease">$133.04 <i class="fas fa-arrow-down"></i></span></td>
          <td>$3.05 B</td>
        </tr>
        <tr>
      </tbody>
    </table>
  </main>
</body>
</html>
<p>NOTE : Green arrow <td><span class="price-increase"> INCREMENT<i class="fas fa-arrow-up"></i></span></td></p>
<p>       Red arrow <td><span class="price-decrease"> DCREMENT<i class="fas fa-arrow-down"></i></span></td></p></p>
</p>NOTE : T = Trillion/s , B = Billion/s , Cr = Crore/s , L = Lakhs.

<h2 style="text-align:right;">Contact Details :</h2>
<h2 style="text-align:right;">Phone.No : 9995612253</h2>
<h2 style="text-align:right;">E-mail : abc123@gmail.com</h2>

CSS code :

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: url(stock.jpg) center;
  color: #ffffff ;
}

header {
  background-color: #622A0F;
  padding: 20px;
}

h1 {
  text-align: center;
  color: #fff;
  font-size: 24px;
}

main {
  margin: 20px;
}

table {
  width: 100%;
  border-collapse: collapse;
  background-color: #000000;
  border-radius: 4px;
  overflow: hidden;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

th, td {
  padding: 12px;
  text-align: left;
}

th {
  background-color: #997950;
  color: #fff;
}

tbody tr:nth-child(even) {
  background-color: #000000;
}

tbody tr:hover {
  background-color: #999999 ;
}

.price-increase {
  color: green;
}
.price-decrease {
  color: red;
}
@media (max-width: 600px) {
  h1 {
    font-size: 20px;
  }
  
  table {
    box-shadow: none;
  }
  
  th, td {
    padding: 8px;
  }
