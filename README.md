<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2022012445杨晓轩</title>
    <style>
        *{
            padding: 0;
            margin: 0;
        }
       #container{
        height: 600px;
        width: 900px;
        margin: 0 auto;
       
       }
       #head{
        height: 50px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        margin: 5px;
       }
       #body{
        height: 400px;
        background-color:bisque;
        margin: 5px;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
       }
       #footer{
        height: 50px;
        background-color:rgb(84, 157, 240);
       }
       .btn{
        height: 40px;
        width: 100px;
       font-size: large;
       background-color: rgb(99, 171, 239);
       }
       .box{
        height: 390px;
        width: 410px;
        border: 2px solid rgb(84, 157, 240);
       }
       a:link{
        text-decoration: none;
       }
    </style>
</head>
<body>
    <div id="container">
        <br>
        <div id="head">
             <img src="picture/校徽.jpg">
             <h1 style="color: rgb(65, 103, 220);">校园卡网费充值</h1>
        </div>
        <div id="body">
            <div class="box">
                <h2 style="color:rgb(84, 157, 240) ;text-align: center;">校园卡充值</h2><br>
                <form>
                姓名：&nbsp;
                <input type="text" style="height: 20px;" name="userName"><br><br>
                学号：&nbsp;
                <input type="text" style="height: 20px;" name="userNum"><br><br>
                充值金额：&nbsp;
                50元<input type="radio" name="money" checked="checked"/>
                100元<input type="radio"  name="money"/>
                150元<input type="radio"  name="money"/>
                200元<input type="radio"  name="money"/><br><br>
                支付方式：&nbsp;<br>
                    微信支付<input type="radio" name="pay" checked="checked"/>
                    支付宝支付<input type="radio" name="pay"/><br>
                    云闪付&nbsp;&nbsp;&nbsp;<input type="radio" name="pay"/>
                    银行卡支付<input type="radio" name="pay"/> <br><br>
                支付密码：&nbsp;
                <input type="password" style="height: 20px;" name="userPsd"><br><br>&nbsp;&nbsp;
                <input type="submit" value="确认充值" class="btn" name="submitBtn">&nbsp;&nbsp;
                <input type="reset" value="重置信息" class="btn">
                </form>
            </div>
            <div class="box">
                <form>
                    <h2 style="color:rgb(84, 157, 240) ;text-align: center;">网费充值</h2><br>
                 姓名：&nbsp;
                <input type="text" style="height: 20px;" name="userName"><br><br>
                学号：&nbsp;
                <input type="text" style="height: 20px;" name="userNum"><br><br>
                充值金额：&nbsp;
                20元<input type="radio" name="money" checked="checked"/>
                40元<input type="radio"  name="money"/>
                60元<input type="radio"  name="money"/>
                100元<input type="radio"  name="money"/><br><br>
                支付方式：&nbsp;<br>
                    微信支付<input type="radio" name="pay" checked="checked"/>
                    支付宝支付<input type="radio" name="pay"/><br>
                    云闪付&nbsp;&nbsp;&nbsp;<input type="radio" name="pay"/>
                    银行卡支付<input type="radio" name="pay"/> <br><br>
                支付密码：&nbsp;
                <input type="password" style="height: 20px;" name="userPsd"><br><br>&nbsp;&nbsp;
                <input type="submit" value="确认充值" class="btn" name="submitBtn">&nbsp;&nbsp;
                <input type="reset" value="重置信息" class="btn">
                </form>
               <p style="font-size: 95%;color: rgb(65, 103, 220);">
                *注每月系统将自动扣除网络费用20元,请及时充值！
               </p>
                
            </div>
        </div>

        <div id="footer" style="color: black;font-size: 95%;">
            注意完善个人信息
            <br>
            <a href="https://www.nenu.edu.cn/">点击此处了解更多...</a>
        </div>
    </div>

</body>
</html>
