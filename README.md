
# XSS (Cross Site Scripting)
XSS Parameters are input fields or query parameters in web applications that are vulnerable to Cross-Site Scripting (XSS) attacks. These parameters can be exploited if the application improperly handles or fails to sanitize user input. Attackers inject malicious scripts, which can be executed in the victim’s browser.
### XSS Parameter

| Example             
| ----------------- 
| ?q=search-term
| ?name=John
| ?id=11

### XSS Payload
| Payload
| -----------------
| <script>alert(1)</script>
| <img src=# onerror='alert(1)'>
