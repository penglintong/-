hostname = *.jd.com，*。*.jd.com，*.jd.hk，*。*.jd.hk，jingxi.com，*.jingxi.com，*.scncykt.com

https://plogin.m.jd.com/cgi-bin/mm/(domlogin|dosmslogin) url script-response-header https://raw.githubusercontent.com/id77/QuantumultX/master/Script/unHttpOnly.js

# web切换jd cookie
^https?:\/\/.{0,27}\。？jd\.(com|hk)\/?((?!\.(js|json|gif|webp|dpg|flv|mp3|mp4)))*$ url script-response-body https://raw.githubusercontent.com/id77/QuantumultX/master/Script/jd_hd.js
^https?:\/\/。*\.jingxi\.com\/?((?!\.(js|json|gif|flv|mp3|mp4)))*$ url script-response-body https://raw.githubusercontent.com/id77/QuantumultX/master/Script/jd_hd.js
