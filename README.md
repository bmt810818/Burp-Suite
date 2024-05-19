# 1. SELECT URL
- Proxy -> Intercept -> Open browser

# 2. CHECK HISTORY
- Proxy -> HTTP history

## 2.1. Create highlight tag: 
- Right click -> Highlight

## 2.2. Create Intruder: 
- Right click -> Send To Intruder

# 3. INTRUDER:
## 3.1. How to Dynamic data configuration?
- Suppose, I want to configure data: "stored XSS(1)", "stored XSS(2)", "javascript:alert(1)" for filed "trackingUrl" Burp Suite automatically tests the API with this data
- Intruder -> Settings -> Grep - Match
- Example: fill "trackingUrl"
- Intruder -> Payload setting [Simple list]
- Example: fill "javascript:alert(1)" + "stored XSS(1)" + "stored XSS(2)"

# 4. Create Organizer
