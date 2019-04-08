'''
# coding=UTF-8
import requests
data = {'q': "类库",
        "from":"Auto",
        "to":"Auto"}
hearders = {
"Accept": "application/json, text/javascript, */*; q=0.01",
"Content-Type": "application/x-www-form-urlencoded; charset=UTF-8",
"Origin": "https://ai.youdao.com",
"Referer": "https://ai.youdao.com/product-fanyi.s",
"User-Agent": "Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.86 Safari/537.36"
}
res = requests.post("https://aidemo.youdao.com/trans", data=data)
print res.text
'''
