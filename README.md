# Intro
__________
ဒီ Tool လေးက Psiphon ကို Termux နဲ့ Tun2tap app တို့ကို သုံးပြီး unlimited speed ရအောင် လုပ်ပေးတဲ့ Tool ဖြစ်ပါတယ်
____________________________

# Download
____________

ပထမအဆင့်အနေနဲ့ လိုအပ်တဲ့ app တွေကို အောက်ပါ link တွေကနေ ဒေါင်းလုတ် ယူပါ
__________________
🟢Download Termux
__________________
https://f-droid.org/packages/com.termux/

____________________
🟢Tun2tap Download
____________________
https://play.google.com/store/apps/details?id=com.newtoolsworks.tun2tap

________________________________
🟢Download  psiphon Brainfuck
________________________________
https://t.me/fastssh_myanmar/1063811

သို့မဟုတ်

https://github.com/victorgeel/Termux-Psiphon-/archive/refs/heads/main.zip

__________________
# Tutorial Video 
__________________
🟢Tutorial Video 
___________________
https://t.me/fastssh_myanmar/1063703

___________________
🟢Updated Command
___________________

https://t.me/fastssh_myanmar/1063811

____________________
# Cmd List
_____________________

🟢 တစ်ကြောင်းစီ copy&paste ပါ အကုန် ကူးထည့်ရင် Error ရှိတတ်တယ်

_______________________

$ termux-setup-storage

$ cd */shared && cp -f psiphon-pro-go.zip $HOME && exit


__________________________________

# 💜 Reopen Termux Terminal 💜
__________________________________

$ mkdir bf 

$ unzip -o -d bf psiphon-pro-go.zip && rm -rf  psiphon-pro-go.zip

______________
# Run psiphon 
______________

$ chmod 700 bf && cd bf

$ ./brainfuck-psiphon-pro-go -c 1 -l 0 -t 4 -tw 8
_____________
_____________

🟢 နောက်ဆုံး cmd မှာ ပါတဲ့

./brainfuck-psiphon-pro-go -c 1 -l 0 🟢-r jp🟢 -t 4 -tw 8

-r jp ဆိုတာ ကိုယ်ချိတ်ချင်တဲ့ နိုင်ငံ ကို ရွေးတာ
jp မှာ တခြား sg , us , in , hk အစရှိသည် ကိုယ်ကြိုက်ရာ ပြောင်းရေးပြီး ချိတ်ပါ 
ချိတ်ရမြန်ချင်ရင် random ထားဖို့
-r jp ဆိုတာကို ဖျက်ပါ

•ချိတ်တာကို ဖြုတ်မယ်ဆို Ctr+c နှိပ်ပါ

•Terminal က ထွက်မယ်ဆို  Ctr+d &  Enter နှိပ်ပါ

•အသစ်ပြန် run မယ်ဆို နောက်ဆုံး cmd.  

$ cd br 

$ ./brainfuck-psiphon-pro-go -c 1 -l 0 -r jp -t 4 -tw 8

 ကို ကူးထည့်ပြီး ပြန်စပါ
 

# !!!!  Enjoy.  !!!!!!!
