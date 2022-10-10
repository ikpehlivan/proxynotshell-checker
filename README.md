# proxynotshell-checker

Add IPs in `vulnerable.txt` file

`python proxynotshellcheck.py`

## List of Dork

` http.favicon.hash:1768726119 (Shodan) `

` http.component:"outlook web app" (Shodan) `

` http.component:"outlook web app" ssl:"hybrid" (Shodan) `

` tag.name:"microsoft_exchange" prot7:http http.status_code:200 (Netlas.io) `

` same_service(http://services.http.response.favicons.name: */owa/auth/* and services.http.response.html_title={"Outlook Web App", "Outlook"}) (Censys) `

[Credit @Smokee](https://github.com/smokeme/ProxyNotShell)
