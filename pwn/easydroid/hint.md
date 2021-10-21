题目：Have you watched the live sharing on 10.12？



hint: The principle of the vulnerability is introduced at https://bytedance.feishu.cn/file/boxcnWibqpknk3S708qerqHoxiP



And some tips: 1. You should get the flag through local vulnerability first, and then transmit it through the network(You should add `<uses-permission android:name="android.permission.INTERNET"/>` and `android:usesCleartextTraffic="true"` in AndroidManifest.xml). 2. You should use the avd simulator to test locally, so you can better debug the exploit, please pay attention to the Android SDK version matching. 3. You should create a new android project, the package name matches the one in server.py, such as com.bytectf.pwneasydroid .

