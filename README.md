# p10wifidislay
i have made a wifi based p10 display

step-1 ye jo mera wifi display hai ye 5G wale band par connect nahi hoga. ye 2.4Ghz wale band par connect hota hai. 
step-2 sabse pahle apne mobile ko esp32_config ke hotspot se connect kar lo esp32 ke. uske bad apne laptop ko mobile ke hotspot se connect 
       kar lo.
step-3 iske bad postman ko open karo aur http://192.168.4.1/setWifi      {body: "ssid":"Redmi10", "password":"1234abcd"}
step-4 iske bad postman ko open karo aur http://esp32.local/setData      {body: "value":"56"}
step-5 iske bad postman ko open karo aur http://esp32.local/setWifi      {body: "ssid":"Redmi10", "password":"1234abcd"}
