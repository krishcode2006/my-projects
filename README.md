<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>currency converter</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
    integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
  <div class="container">
    <h2>Currency Converter</h2>
    <form>
      <div class="amount">
        <p>Enter Amount</p>
        <input type="number" value="100" id="amount" />
      </div>
      <div class="dropdown">
        <div class="from">
          <p>FROM</p>
          <div class="select-container">
            <img src="https://flagsapi.com/US/flat/64.png" />
            <select name="from">
              <option value="USD">USD</option>
              <option value="INR">INR</option>
              <option value="EUR">EUR</option>
              <option value="AUD">AUD</option>
            </select>
          </div>
        </div>
        <i class="fa-solid fa-right-left"></i>
        <div class="to">
          <p>TO</p>
          <div class="select-container">
            <img src="https://flagsapi.com/IN/flat/64.png" />
            <select name="to">
              <option value="USD">USD</option>
              <option value="INR" selected>INR</option>
              <option value="EUR">EUR</option>
              <option value="AUD">AUD</option>
            </select>
          </div>
        </div>
      </div>
      <div class="msg">1USD = 80INR</div>
      <button>Get Exchange Rate</button>
    </form>
  </div>

  <script src="script.js"></script>
</body>

</html>
