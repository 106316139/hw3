<html>
<head>
<style>
body {
  background-image: url("https://pic.pimg.tw/hamilton29/1378663715-3261696543_n.jpg");
}
</style>
</head>
<body>
<form id="orderForm1" action="http://203.64.84.113/x/RQ_RS.aspx" method="post"  name="form1" >
<h1 style="color:Green;text-align: center;">皮膚科申請預約</h1>

姓名:
<input type="text" id="name" name="姓名"><br><br>

性別:
<input type="radio" id="gender" name="性別" value="male" checked> 男
<input type="radio" id="gender" name="性別" value="female"> 女<br><br>

email:
<input type="text" id="email" name="email"><br><br>

電話:
<input type="text" id="phone" name="電話"><br><br>

生日(例 1998-12-30):
<input type="text" id="birthbay" name="生日"><br><br>

選擇日期:
<select id="date" name="選擇日期">
<option value="星期一"selected>星期一</option>
<option value="星期二">星期二</option>
<option value="星期三">星期三</option>
<option value="星期四">星期四</option>
<option value="星期五">星期五</option>
</select><br><br>

選擇時間:
<select id="time" name="選擇時間">
<option value="早上"selected>早上</option>
<option value="中午">下午</option>
<option value="晚上">晚上</option>
</select><br><br>

選擇類型:
<select id="detype" name="選擇類型">
<option value="醫學皮膚病學"selected>醫學皮膚病學</option>
<option value="化妝品皮膚病學">化妝品皮膚病學</option>
<option value="初級衛生保健">初級衛生保健</option>
</select><br><br>
<textarea name="問題與評論">Questions/Comments</textarea><br><br>
<input type="submit" value="確認送出">
<button onclick="myFunction()">Try it</button>

<script>
var patient= {"name":"Chalmers","telecom":12345678,
"gender": "male", "birthDate": "1974-12-25"};
function myFunction() {
alert(patient);
</script>
</form>
</body>
</html>
