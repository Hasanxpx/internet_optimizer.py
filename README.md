# internet_optimizer.py

📥 Installation and Setup:

```bash
# 1. Install Termux from F-Droid
# 2. Open Termux and run:
pkg update && pkg upgrade
pkg install python
pip install psutil speedtest-cli

# 3. Get root access:
su

# 4. Save code to file:
nano internet_optimizer.py
# (Paste code then Ctrl+X → Y → Enter)

# 5. Run:
python internet_optimizer.py
```

⭐ Available Features:

🔧 MTU Features (requires root):

· ✅ Manual MTU value change
· ✅ Automatic MTU optimization
· ✅ Test different MTU values
· ✅ Display available network interfaces

📊 Data Monitoring:

· ✅ Daily data usage tracking
· ✅ Set daily usage limits
· ✅ Detailed consumption reports
· ✅ Live data usage monitoring

🚀 Speed Testing:

· ✅ Download/upload speed test
· ✅ Ping and latency measurement
· ✅ Automatic best server selection
· ✅ Detailed easy-to-read results

⚙️ Additional Features:

· ✅ User-friendly interface
· ✅ Automatic data saving
· ✅ Full rooted device support
· ✅ Works on all Android versions

🎯 Usage Tips:

1. Run as root for full feature access
2. Start with MTU 1500 then test downwards
3. Set usage limits according to your data plan
4. Continuous monitoring to avoid exceeding limits

⚠️ Important Notes:

· Some carriers may override MTU settings
· Changes may require occasional reboots
· Keep your original settings for backup

---

🎮 Quick Start Guide - دليل البدء السريع

For Rooted Devices - للأجهزة المروتة:

```bash
su
python internet_optimizer.py
# اختر 4 لتحسين MTU تلقائياً
# Choose 4 for auto MTU optimization
```

For Non-Rooted - للأجهزة غير المروتة:

```bash
python internet_optimizer.py
# يمكنك استخدام الميزات الأساسية
# You can use basic features
```

لاختبار السرعة - For Speed Test:

```bash
# اختر 2 من القائمة
# Choose 2 from the menu
```

لمراقبة البيانات - For Data Monitoring:

```bash
# اختر 1 ثم حدد الفترة
# Choose 1 then set interval
```

---

📞 الدعم - Support

إذا واجهتك مشاكل:

· ✅ تأكد من صلاحية root
· ✅ جرب إعادة تشغيل Termux
· ✅ تحقق من تثبيت جميع المكتبات

If you encounter issues:

· ✅ Verify root access
· ✅ Try restarting Termux
· ✅ Check all libraries are installed

---

البرنامج مصمم خصيصاً لهواتف أندرويد المروتة ويعمل على تحسين تجربة الإنترنت بشكل ملحوظ!

The program is specifically designed for rooted Android phones and significantly improves internet experience!

____________________

📥 التثبيت والإعداد:

```bash
# 1. تثبيت Termux من F-Droid
# 2. فتح Termux وتشغيل الأوامر:
pkg update && pkg upgrade
pkg install python
pip install psutil speedtest-cli

# 3. الحصول على صلاحية root:
su

# 4. حفظ الكود في ملف:
nano internet_optimizer.py
# (لصق الكود ثم Ctrl+X → Y → Enter)

# 5. التشغيل:
python internet_optimizer.py
```

⭐ المميزات المتاحة:

🔧 ميزات MTU (تتطلب root):

· ✅ تغيير قيمة MTU يدوياً
· ✅ تحسين تلقائي لأفضل قيمة MTU
· ✅ اختبار قيم MTU المختلفة
· ✅ عرض الواجهات الشبكية المتاحة

📊 مراقبة البيانات:

· ✅ تتبع الاستخدام اليومي للبيانات
· ✅ تحديد حد يومي للاستخدام
· ✅ تقارير استهلاك مفصلة
· ✅ مراقبة حية للبيانات المستخدمة

🚀 اختبار السرعة:

· ✅ اختبار سرعة التحميل والرفع
· ✅ قياس Ping وزمن الاستجابة
· ✅ اختيار أفضل سيرفر تلقائياً
· ✅ نتائج مفصلة وسهلة القراءة

⚙️ إضافات أخرى:

· ✅ واجهة مستخدم سهلة
· ✅ حفظ البيانات تلقائياً
· ✅ دعم كامل للهواتف المروتة
· ✅ عمل على جميع إصدارات أندرويد

🎯 نصائح الاستخدام:

1. تشغيل كـroot للحصول على كامل الميزات
2. بدء بقيمة MTU 1500 ثم الاختبار نزولاً
3. ضبط حد الاستخدام حسب باقة الإنترنت
4. المراقبة المستمرة لتجنب تجاوز الحدود

⚠️ ملاحظات مهمة:

· بعض مشغلي الشبكات قد يتجاوزون إعدادات MTU
· التغييرات قد تحتاج إعادة تشغيل أحياناً
· احتفظ بإعداداتك الأصلية للرجوع إليها


واجهات الجوال (Mobile Data):

· rmnet0 إلى rmnet7 - واجهات بيانات الجوال (SIM)
· هذه الواجهات مسؤولة عن اتصال الإنترنت عبر شبكة الجوال

واجهات الواي فاي (WiFi):

· wlan0 - الواجهة الرئيسية للواي فاي
· swlan0 - واجهة الواي فاي الثانوية أو الخاصة

🎯 نصائح للاستخدام:

لتحسين اتصال الجوال:

```bash
# تغيير MTU لواجهات rmnet (لتحسين بيانات SIM)
# اختر واجهة rmnet0 أو rmnet1 (عادةً الرئيسية)
# القيم المناسبة: 1500, 1492, 1472
```

لتحسين اتصال الواي فاي:

```bash
# تغيير MTU لواجهة wlan0
# القيم المناسبة: 1500, 1492
```

⚙️ كيفية التحديد:

1. اعرض الواجهات النشطة:

```bash
# لمعرفة الواجهة المستخدمة حالياً:
ip route show | grep default
```

2. اختبر كل واجهة:

```bash
# اختبر سرعة كل واجهة
# ركز على الواجهة التي تعطي أفضل أداء
```

3. غير إعدادات MTU:

```bash
# مثال لتغيير wlan0:
ip link set dev wlan0 mtu 1500

# مثال لتغيير rmnet0:
ip link set dev rmnet0 mtu 1472
```

---

🇺🇸 In English

📡 Network Interface Types:

Mobile Data Interfaces:

· rmnet0 to rmnet7 - Mobile data interfaces (SIM)
· These handle internet connection through cellular network

WiFi Interfaces:

· wlan0 - Main WiFi interface
· swlan0 - Secondary or special WiFi interface

🎯 Usage Tips:

For Mobile Data Optimization:

```bash
# Change MTU for rmnet interfaces (SIM data)
# Choose rmnet0 or rmnet1 (usually main)
# Suitable values: 1500, 1492, 1472
```

For WiFi Optimization:

```bash
# Change MTU for wlan0 interface
# Suitable values: 1500, 1492
```

⚙️ How to Identify:

1. Show Active Interfaces:

```bash
# To find currently used interface:
ip route show | grep default
```

2. Test Each Interface:

```bash
# Test speed on each interface
# Focus on the one with best performance
```

3. Change MTU Settings:

```bash
# Example for wlan0:
ip link set dev wlan0 mtu 1500

# Example for rmnet0:
ip link set dev rmnet0 mtu 1472
```

---

🛠️ Practical Commands - أوامر عملية

للعثور على الواجهة النشطة - Find Active Interface:

```bash
# الطريقة الأسرع:
ip route get 8.8.8.8 | grep -oP 'dev \K\S+'

# أو:
netstat -rn | grep '^0.0.0.0' | awk '{print $8}'
```

لاختبار سرعة واجهة معينة - Test Specific Interface:

```bash
# لاختبار سرعة rmnet0:
ping -I rmnet0 8.8.8.8

# لاختبار سرعة wlan0:
ping -I wlan0 8.8.8.8
```

لتغيير MTU للواجهات - Change MTU for Interfaces:

```bash
# لجميع واجهات rmnet (بيانات الجوال):
for i in {0..7}; do
    ip link set dev rmnet$i mtu 1472
done

# للواي فاي:
ip link set dev wlan0 mtu 1500
```

---

📊 Recommended MTU Values - قيم MTU الموصى بها

For Mobile Data (rmnet):

· 4G/LTE: 1500 or 1472
· 3G: 1500 or 1492
· 2G: 1500

For WiFi (wlan0):

· Most routers: 1500
· PPPoE: 1492
· VPN: 1500 or lower

---

🔍 How to Test Which Interface is Active:

Method 1: Check Default Route

```bash
ip route show default
```

Method 2: Monitor Traffic

```bash
# Monitor traffic on rmnet0:
iftop -i rmnet0

# Monitor traffic on wlan0:
iftop -i wlan0
```

Method 3: Check Connection Status

```bash
# Check if interface has IP address:
ip addr show rmnet0
ip addr show wlan0
```

---

💡 Pro Tips - نصائح احترافية:

1. Focus on Active Interface:

```bash
# Don't change all interfaces
# Find which one is actually being used
# Then optimize only that one
```

2. Test Before Change:

```bash
# Test current speed first
# Change MTU gradually
# Test after each change
```

3. Keep Original Settings:

```bash
# Note original MTU values
# So you can revert if needed
# Use: ip link show | grep mtu
```

Start by identifying which interface is currently active, then optimize its MTU setting for best performance!

ابدأ بتحديد الواجهة النشطة حالياً، ثم قم بتحسين إعدادات MTU للحصول على أفضل أداء!
