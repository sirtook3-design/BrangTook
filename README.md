## အသုံးပြုနည်း (Installation)

Termux ထဲတွင် အောက်ပါ command များကို တစ်ဆင့်ချင်း ရိုက်ထည့်ပါ-

### ၁။ လိုအပ်သော package များ သွင်းခြင်း
```bash
pkg update && pkg upgrade -y
pkg install git python -y

git clone https://github.com/sirtook3-design/BrangTook.git


cd BrangTook

python brangtook.pyc


သတိပြုရန်
​ဤ script ကို Python 3.13 ဖြင့် compile လုပ်ထားသောကြောင့် အသုံးပြုသူ၏ ဖုန်းတွင်လည်း Python 3.13 ရှိရန် လိုအပ်ပါသည်။
​အကယ်၍ Error တက်ပါက pkg install python ဖြင့် Python နောက်ဆုံး version ကို update လုပ်ပေးပါ။
