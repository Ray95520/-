# -<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>儲蓄型保險模擬器</title>
  <link rel="stylesheet" href="styles.css"> <!-- 引用外部CSS樣式 -->
</head>
<body>
  <div class="container">
    <h1>儲蓄型保險模擬器</h1>

    <!-- 模擬器表單 -->
    <form id="insuranceForm">
      <label for="annualPremium">年繳保費 (元):</label>
      <input type="number" id="annualPremium" name="annualPremium" required>

      <label for="paymentPeriod">繳費年期:</label>
      <input type="number" id="paymentPeriod" name="paymentPeriod" required>

      <label for="interestRate">年利率 (%):</label>
      <input type="number" id="interestRate" name="interestRate" required>

      <button type="submit">計算</button>
    </form>

    <!-- 顯示結果 -->
    <div id="results">
      <p>預計總儲蓄金額：<span id="totalSavings"></span> 元</p>
    </div>
  </div>

  <script src="script.js"></script> <!-- 引用外部JavaScript邏輯 -->
</body>
</html>
