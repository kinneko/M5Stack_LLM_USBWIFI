# M5Stack_LLM_USBWIFI

M5Stack LLMモジュールをお使いでデバッグモジュールをお持ちでない場合、adbからのドライバのビルドは結構しんどいことになります。  
手元で動作しているTP-Link TL-WN725N(Realtek RTL8188EUS)向けに、ビルド済みのドライバを置いておきます。  
unnecessary_mac80211にある8188eu.koは、単体で動作するドライバですがやや古いものです。  
mac80211supportにあるドライバは、LLMモジュールと同じバージョンのLinux kernelに含まれるMAC80211に対応したドライバをビルドしたものです。  

ビルド手順や組み込み方法などは、下記の薄い本のほうに書いてあります。  
『M5Stack LLMモジュール使ってみた - 基本編 -』　https://kinneko.booth.pm/items/6429476

---

M5Stack社が、kernelのソースコードを公開してくれることを願っております。
