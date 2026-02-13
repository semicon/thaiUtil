🚀 link
https://semicon.github.io/thaiUtil/thaiUtil.js

⭐ CDN thaiUtil
<script src="https://cdn.jsdelivr.net/gh/semicon/thaiUtil/thaiUtil.min.js"></script>

✅ ตัวอย่างใช้งาน (Google Apps Script / Web)


  <script>
    
  const todayFull = ThaiUtil.formatThaiDateFull(new Date());
    
  const todayShort = ThaiUtil.formatThaiDateShort(new Date());
    
  const moneyNumber = ThaiUtil.formatThaiCurrency(1250);
    
  const moneyText = ThaiUtil.bahtText(1250);
    
  console.log(todayFull);
    
  console.log(todayShort);
    
  console.log(moneyNumber);
    
  console.log(moneyText);
    
  </script>

🎯 ตัวอย่างผลลัพธ์
วันพฤหัสบดี ที่ ๑๒ กุมภาพันธ์ พ.ศ. ๒๕๖๙
๑๒ ก.พ. ๒๕๖๙
๑,๒๕๐.๐๐
หนึ่งพันสองร้อยห้าสิบบาทถ้วน
