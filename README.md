{
  "Version": "42",
  "ReleaseNotes": "Atualização disponível",
  "UrlUpdate": "https://github.com/rtmtip/script/raw/refs/heads/main/install.py",
  "Sms": "",
  "EmailFeedback": "",
  "UrlContato": "",
  "UrlTermos": "",
  "CheckUser": "true",
  "Udp": [
    {
      "Porta": "7300"
    }
  ],
  "Servers": [
    {
      "Name": "42-BR",
      "TYPE": "PREMIUM",
      "FLAG": "br.png",
      "ServerIP": "185.194.204.66",
      "CheckUser": "http://2804:5364:7000:1:1:1:f9cd:63d2:5353/checkUser",
      "ServerPort": "80",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
  "Networks": [
    {
      "Name": "🟣 VIVO",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: 185.194.204.66[crlf]Connection: Upgrade[crlf]User-Agent: [ua][crlf]Upgrade: Websocket[crlf][crlf]",
      "SNI": "185.194.204.66",
      "TlsIP": "185.194.204.66",
      "ProxyIP": "185.194.204.66",
      "ProxyPort": "80",
      "Info": "Proxy"     
    }
  ]
}
