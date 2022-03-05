- 👋 Hi, I’m @Airbus95
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Airbus95/Airbus95 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
function testFunction() {
  var sheet = SpreadsheetApp.getActive();
  
  //getDisplayValue() method Returns the displayed value of the top-left cell in the range.
  var data1 = sheet.getRange("A2").getDisplayValue();
  var data2 = sheet.getRange("A3").getDisplayValue();
  var data3 = sheet.getRange("A4").getDisplayValue();
  
  Logger.log(data1); // 12,345.00 --- string type
  Logger.log(data2); // 1,500.50 --- string type
  Logger.log(data3); // 1,234,567.67 --- string type
  
}
