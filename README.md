# curl_ping

```
curl -o /dev/unll -s -w  "\n"HTTP返回碼：%{http_code}"\n"對端IP地址：%{remote_ip}"\n"應用連線時間：%{time_appconnect}"\n"TCP連線時間：%{time_connect}"\n"DNS解析時間：%{time_namelookup}"\n"準備傳送時間：%{time_pretransfer}"\n"開始傳送時間：%{time_starttransfer}"\n""\n"總時間：%{time_total}"\n"  https://www.google.com
```
