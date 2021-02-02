# 如何使用

## 最低需求

首先確定電腦有安裝至少python 3.9.0

安裝 tweepy

去推特申請開發者帳號 並建立 API key, API secret, Access Token, Access Secret

打開檔案並修改下面的代碼
```
consumer_key = '換成你自己的' #<- API Key
consumer_secret = '換成你自己的' #<- API Token
access_token = '換成你自己的'
access_secret = '換成你自己的'
```

## 執行

```
$> python3 twitterCrawler.py
```

## twitterCrawler.py

簡易的Twitter crawler, 使用Twitter Search API

## twitterTimeline.py
簡易的Twitter timeline 爬蟲, 使用Twitter user_timeline