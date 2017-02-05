# [TabChi v3.1](https://telegram.me/MemberPlus_tm)

<p align="center"> ![http://member-adder.ir/img/member+.png](http://member-adder.ir/img/member+.png)

TG-CLI based broadcasting bot!

* * * * *

  ##Install

```
git clone https://github.com/sajjad-021/TabChi.git
cd TabChi
chmod 777 install.sh
./install.sh
```

***
 
   ##Create a bot

```
python3 creator.py
```         

Enter Tabchi ID : 111
Enter id of tabchi in "ID" part (it can be anything but should be unique)

Enter Full Sudo ID : 123456    
Enter your telegram Id in "Full Sudo ID" part
---(you can see your account Id Number in [@UserInfoBot](https://telegram.me/userinfobot)])---

Then

```
screen ./tabchi-111.sh
```

* *  
         
##Anti crash

```
tmux new-session -s script "bash tabchi-111.sh -t"
```

* *

##Stay Online

after run bot, you must send messege from the bot in the [@TgMessengerBot](https://telegram.me/TgMessengerBot)
This is for stay online your bot and dely result 

* *    

##Run agin

You can stop the script by pressing Control+C in the script session. Alternatively, you can tmux kill-session -t script or also killing all tmux processes killall tmux

```
killall screen
killall tmux
tmux new-session -s script "bash tabchi-111.sh -t"
```

##Help and more

/pm <userid> <text>
ارسال <text> به <userid> بطور مارک داون

/block <userid>
بلاک کردن <userid> از خصوصی ربات

/unblock <userid>
آن بلاک کردن <userid> از خصوصی ربات

/panel
پنل مدیریت ربات

/addsudo <userid>
اضافه کردن <userid> به صاحبان ربات

/remsudo <userid>
حذف <userid> از صاحبان ربات

/bc <text>
ارسال <text> به همه چت ها

/fwd <all/users/gps/sgps> (on reply)
فوروارد پیام به همه/کاربران/گروه ها/سوپر گروه ها

/lua <str>
پردازش <str> به عنوان کد لوا

/echo <text>
باز گرداندن <text>

/addedmsg <on/off>
اگر روشن باشد بعد ازارسال مخاطب در گروه پیامی مبنی بر ذخیره شدن شماره مخاطب

/setaddedmsg <text>
شخصی سازی متن ذخیره شده

/markread <on/off>
⁧روشن یا خاموش کردن بازدید پیام ها

/setanswer '<word>'  <text>
تنظیم <text> به عنوان جواب اتوماتیک <word>

 نکته:‌<word> باید داخل '' باشد

/delanswer <word>
حذف جواب مربوط به <word>

/answers
لیست جواب های اتوماتیک

/addmembers
اضافه کردن اعضای ربات به گروه

/links
دریافت لینک های ذخیره شده توسط ربات

/contactlist
دریافت مخاطبان ذخیره شده توسط ربات


##Developers

*[open by (sajjad_021)](https://telegram.me/sajjad_021)
*[channel (MemberPlus_TM)](https://telegram.me/MemberPlus_TM)

###Powered by [MemberPlus_TM](https://telegram.me/MemberPlus_TM)

Enjoy Your New Bot!
