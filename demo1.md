
<details> 
    <summary>展开查看</summary>   
        
    [id]: <http://example.com/>  "Optional Title Here"
 
        * [api](#2.18.1)
        * [Request Headers](#2.18.2)
        * [Request Method](#2.18.3)
        * [Request Body](#2.18.4)
        * [Request Demo](#2.18.5)
        * [Response Body](#2.18.6)
        * [Response Demo](#2.18.7)
        * [123](www.baidu.com)
        
</details>

<details open>
    <summary>订单中心</summary> 
    <a href>我的活动</a>
    <dd><a href="#2.18.1">我的订单</a></dd>
    <dd><a href>我的活动</a></dd>
    <dd><a href>评价晒单</a></dd>
    <dd><a href>购物助手</a></dd>
    <p>This is <a href="http://example.com/" title="Title">
an example</a> inline link.</p>
See my [About](/about/) page for details.   


</details>







* [IM API](#40)
   * [2.18 GETBETINFO 索取投注信息](#d2.18)
        * [2.18.1 api](#d2.18.1)
        * [2.18.2 Request Headers](#d2.18.2)
        * [2.18.3 Request Method](#d2.18.3)
        * [2.18.4 Request Body](#d2.18.4)
        * [2.18.5 Request Demo](#d2.18.5)
        * [2.18.6 Response Body](#2.18.6)
        * [2.18.7 Response Demo](#2.18.7)
   * [2.19 PLACEBET 投注](#2.19)
        * [api](#2.19.1)
        * [Request Headers](#2.19.2)
        * [Request Method](#2.19.3)
        * [Request Body](#2.19.4)
        * [Request Demo](#2.19.5)
        * [Response Body](#2.19.6)
        * [Response Demo](#2.19.7)
   * [标题3](#43)
   * [标题4](#44)



---
---

<h2 id="d2.18"> 2.18 GETBETINFO 索取投注信息 描述:此 API 常用于实际投注前索取最后的投注信息, 调用在会员投注时点击一个特定选项.. 访问频率限制: 5 秒</h2>

<h3 id="d2.18.1"> 2.18.1 /api/Imd/InplayMatrix/GETBETINFO</h3>

<h3 id="d2.18.2"> 2.18.2 Request Headers</h3>

```
[
    "Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9",
    "Content-Type": "application/json",
    "User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4",
    "Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8"
]
```
<h3 id="d2.18.3"> 2.18.3 Request Method: Post</h3>

<h3 id="d2.18.4"> 2.18.4 Request Body</h3>

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

<h3 id="d2.18.5"> 2.18.5 请求示例</h3>

```
{
    "ReturnNearestHandicap": false,
    "Token": "TY327N02,0fe035fa-1b7c-4579-a799-bc1bcc4d2d41",
    "WagerSelectionInfos": [
        {
            "RefId": 0,
            "MarketlineId": 1339089608,
            "PeriodId": 1,
            "OutrightTeamId": 0,
            "Odds": 1.99,
            "Handicap": 8.5,
            "BetTypeId": 1,
            "OddsType": 3,
            "EventId": 67130891,
            "WagerSelectionId": 4321524422,
            "SportId": 2,
            "BetTypeSelectionId": 1
        }
    ],
    "MemberCode": "TY327N02",
    "WagerType": 1,
    "timeStamp": 1677130305.3538871
}

```

<h3 id="2.18.6"> 2.18.6 返回结果</h3>


[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

<h3 id="2.18.7"> 2.18.7 返回示例</h3>

```
{
    "refreshTime": 1677130366,
    "isSuccess": true,
    "errorCode": 10000,
    "message": "",
    "location": "",
    "data": {
        "WagerSelectionInfos": [
            {
                "Status": 381,
                "EventId": 67130891,
                "MarketlineId": 1339089608,
                "BetTypeId": 1,
                "MarketlineStatusId": 1,
                "WagerSelectionId": 4321524422,
                "Handicap": 8.5,
                "BetTypeSelectionId": 1,
                "OutrightTeamId": 0,
                "HomeScore": null,
                "AwayScore": null,
                "OddsType": 3,
                "Odds": 2.0,
                "RefId": 0,
                "SportId": 2,
                "Market": 3,
                "Specifiers": ""
            }
        ],
        "BetSetting": [
            {
                "MaxStakeAmount": 2500.0,
                "MinStakeAmount": 5.0,
                "NoOfCombination": 0,
                "ComboSelection": 0,
                "EstimatedPayoutAmount": 1.0,
                "RefId": 0
            }
        ],
        "ServerTime": "2023-02-23 13:31:45",
        "StatusCode": 100,
        "StatusDesc": "Success"
    }
}

```

---


---

## 2.19 PLACEBET 投注 描述:此 API 常用于展示各投注项目.当会员在确认投注时将被调用.
<h3 id="2.19"> 2.19 PLACEBET 投注 描述:此 API 常用于展示各投注项目.当会员在确认投注时将被调用.</h3>

### /api/Imd/InplayMatrix/PLACEBET
<h3 id="2.19.1"> 2.19.1 /api/Imd/InplayMatrix/PLACEBET</h3>




#### Request Headers
<h3 id="2.19.2"> 2.18.2 Request Headers</h3>

```
["User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", 
"Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", 
"Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9", 
"Content-Type": "application/json"]
```

#### Request Method: Post
<h3 id="2.19.3"> 2.18.3 Request Method: Post</h3>


####  请求参数
<h3 id="2.19.4"> 2.18.4 Request Body</h3>

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 请求示例：
<h3 id="2.19.5"> 2.18.5 Request Demo</h3>

```
{}

```

<h3 id="2.19.6"> 2.18.6 Response Body</h3>

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串


#### 返回示例：
<h3 id="2.19.7"> 2.18.7 Response Demo</h3>

```
{}

```

---


---

## 2.20 GETBETLIST 索取投注明细 描述:此 API 常用于检索会员在各场赛事中未结算的投注.在一般情况下, 投注未得到结算出于赛事还没完毕, 但依然存在一些场合投注先得到结算 (投注处于作废或取消状态被视为已结算无论赛事是否完毕)

### 2.20.1 /api/Imd/InplayMatrix/GETBETLIST


#### 2.20.2 Request Headers

```
[
    "Content-Type": "application/json,application/json-patch+json",
    "Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9",
    "Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8",
    "Accept": "text/plain",
    "User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4",
    "Authorization": "Bearer eyJhbGciOiJSUzI1NiIsImtpZCI6IkYyNjlDMUNBOEI4N0YyNDE1MUQwMEE4NzI5MTZCN0EwOEM4RUJGQUQiLCJ0eXAiOiJKV1QiLCJ4NXQiOiI4bW5CeW91SDhrRlIwQXFIS1JhM29JeU92NjAifQ.eyJuYmYiOjE2NzcwNTE3OTYsImV4cCI6MTY3NzEzODc5NiwiaXNzIjoiaHR0cDovL3pkaWRlbnRpdHlzZXJ2ZXIuemhzZXJ2aWNlIiwiYXVkIjpbImh0dHA6Ly96ZGlkZW50aXR5c2VydmVyLnpoc2VydmljZS9yZXNvdXJjZXMiLCJhcGlzIl0sImNsaWVudF9pZCI6ImNvbXByZWhlbnNpdmUuYXBpcyIsInN1YiI6IlpkLkNvbXByZWhlbnNpdmUuVG9rZW4iLCJhdXRoX3RpbWUiOjE2NzcwNTE3OTYsImlkcCI6ImxvY2FsIiwiYWNjb3VudGlkIjoiMTQyODM1Iiwic3lzdGVtdHlwZSI6IjQxIiwiaXNzdXBlcmFkbWluIjoiRmFsc2UiLCJzY29wZSI6WyJhcGlzIiwib2ZmbGluZV9hY2Nlc3MiXSwiYW1yIjpbInBhc3N3b3JkIl19.aooH-5ARYDLOlAKrb_-FrVQoMIsII82WS4SDxXdJ9uP0oIDEJMkR91LejjLH_LXPc1HXfWzUPwXW41T-gnbGB5ERiJF0OSbZLu5jla77kr3xZ-m_cgPdKuUeRCdrQQUaZn5TVxGHmDXMwjGfCZEKZsjEcTqDM5eYsNVjcBzcm6zbtAyjg07B4sbbE22QLdQS6DRFOOdmvMvngzM4tBaq2KDENNwdGkPE4_2_Y2ck0fc24K7ON5jtqBxdVzjn7imcPdBlg82uu9gNKE0cdvlY54ooollHv2S4UxiIwtiJY4MGxFx0G_fpNvDVDxZd8xi3SUM5jnshJG7te8w8zb5c-g"
]
```

#### 2.20.3 Request Method: Post

#### 2.20.4 请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
memberCode			|String		|R			|请求报文头
languageCode					|String		|R			|FB登录后token，没有登录则为空字符串
token			|String		|R			|请求报文头
betConfirmationStatus					|List		|R			|FB登录后token，没有登录则为空字符串
TimeStamp			|Int		|R			|请求报文头


#### 2.20.5 请求示例：

```
{
    "memberCode": "TY327N02",
    "languageCode": "CHS",
    "token": "TY327N02,0fe035fa-1b7c-4579-a799-bc1bcc4d2d41",
    "betConfirmationStatus": [
        2
    ],
    "TimeStamp": 1677130476.0278029
}

```

#### 2.20.6 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 2.20.7 返回示例：

```
{
    "refreshTime": 1677130536,
    "isSuccess": true,
    "errorCode": 10000,
    "message": "",
    "location": "",
    "data": {
        "WagerList": [
            
        ],
        "ServerTime": "2023-02-23 13:34:36",
        "StatusCode": 100,
        "StatusDesc": "Success"
    }
}

```

---


---

## 2.21 GETSTATEMENT 索取投注账目 描述:此 API 常用于索取会员所有已结算/进行交易的投注明细, 无论投注中的赛事是否完毕. 访问频率限制: 每 2 秒 1 次（一样的请求参数）
### /api/Imd/InplayMatrix/GETSTATEMENT



#### Request Headers

```
["User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", 
"Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", 
"Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9", 
"Content-Type": "application/json"]
```

#### Request Method: Post

####  请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 请求示例：

```
{}

```

#### 2.1.2 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 返回示例：

```
{}

```

---


---

## 2.22 GETBALANCE 索取余额 描述:此 API 常用在检索会员的余额.
### /api/Imd/InplayMatrix/GETBALANCE


#### Request Headers

```
["User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", 
"Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", 
"Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9", 
"Content-Type": "application/json"]
```

#### Request Method: Post

####  请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 请求示例：

```
{}

```

#### 2.1.2 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 返回示例：

```
{}

```

---


---

## 2.23 GETPENDINGWAGERSTATUS 索取待处理投注状态 描述:此 API 用于检索待处理投注状态.
### /api/Imd/InplayMatrix/GETPENDINGWAGERSTATUS



#### Request Headers

```
["User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", 
"Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", 
"Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9", 
"Content-Type": "application/json"]
```

#### Request Method: Post

####  请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 请求示例：

```
{}

```

#### 2.1.2 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 返回示例：

```
{}

```

---

---

## 2.24 GETANNOUNCEMENT 索取通告 描述:此 API 常用于检索通告.所有在前 31 天内上传过的通告将被检索.这将不包括任何被屏蔽的

#### 2.24.1 /api/Imd/InplayMatrix/GETANNOUNCEMENT

#### 2.24.2 Request Headers

```
[
    "Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9",
    "User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4",
    "Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8",
    "Content-Type": "application/json"
]
```

#### 2.24.3 Request Method: Post

#### 2.24.4 请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 2.24.5 请求示例：

```
{
    "timeStamp": 1677132233.8817921,
    "OrderBy": 2
}

```

#### 2.24.6 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 2.24.7 返回示例：

```
{}

```

---


---

## 2.28 GETFAVOURITEEVENT 索取所有滚球赛事资料 描述:此 API 用于检索所有收藏赛事的赛事及赔率信息.
### 2.28.1 /api/Imd/InplayMatrix/GETFAVOURITEEVENT

#### 2.28.2 Request Headers

```
[
    "Authorization": "Bearer eyJhbGciOiJSUzI1NiIsImtpZCI6IkYyNjlDMUNBOEI4N0YyNDE1MUQwMEE4NzI5MTZCN0EwOEM4RUJGQUQiLCJ0eXAiOiJKV1QiLCJ4NXQiOiI4bW5CeW91SDhrRlIwQXFIS1JhM29JeU92NjAifQ.eyJuYmYiOjE2NzcwNTE3OTYsImV4cCI6MTY3NzEzODc5NiwiaXNzIjoiaHR0cDovL3pkaWRlbnRpdHlzZXJ2ZXIuemhzZXJ2aWNlIiwiYXVkIjpbImh0dHA6Ly96ZGlkZW50aXR5c2VydmVyLnpoc2VydmljZS9yZXNvdXJjZXMiLCJhcGlzIl0sImNsaWVudF9pZCI6ImNvbXByZWhlbnNpdmUuYXBpcyIsInN1YiI6IlpkLkNvbXByZWhlbnNpdmUuVG9rZW4iLCJhdXRoX3RpbWUiOjE2NzcwNTE3OTYsImlkcCI6ImxvY2FsIiwiYWNjb3VudGlkIjoiMTQyODM1Iiwic3lzdGVtdHlwZSI6IjQxIiwiaXNzdXBlcmFkbWluIjoiRmFsc2UiLCJzY29wZSI6WyJhcGlzIiwib2ZmbGluZV9hY2Nlc3MiXSwiYW1yIjpbInBhc3N3b3JkIl19.aooH-5ARYDLOlAKrb_-FrVQoMIsII82WS4SDxXdJ9uP0oIDEJMkR91LejjLH_LXPc1HXfWzUPwXW41T-gnbGB5ERiJF0OSbZLu5jla77kr3xZ-m_cgPdKuUeRCdrQQUaZn5TVxGHmDXMwjGfCZEKZsjEcTqDM5eYsNVjcBzcm6zbtAyjg07B4sbbE22QLdQS6DRFOOdmvMvngzM4tBaq2KDENNwdGkPE4_2_Y2ck0fc24K7ON5jtqBxdVzjn7imcPdBlg82uu9gNKE0cdvlY54ooollHv2S4UxiIwtiJY4MGxFx0G_fpNvDVDxZd8xi3SUM5jnshJG7te8w8zb5c-g",
    "Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8",
    "Content-Type": "application/json,application/json-patch+json",
    "User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4",
    "Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9",
    "Accept": "text/plain"
]
```

#### 2.28.3 Request Method: Post

#### 2.28.4 请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 2.28.5 请求示例：

```
{
    "languageCode": "CHS",
    "Token": "TY327N02,fb2bebe4-2ac1-402e-a4aa-250393448bf5",
    "timeStamp": 1677131702,
    "IncludeGroupEvents": false,
    "OddsType": 3,
    "MemberCode": "TY327N02",
    "SportIds": [
        2
    ]
}

```

#### 2.28.6 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 2.28.7 返回示例：

```
{}

```

---


---

2？
## 2.29 ADDFAVOURITEEVENT 加收藏赛事 描述:此 API 用于加收藏赛事
### /api/Imd/InplayMatrix/ADDFAVOURITEEVENT

Request Headers: ["User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", "Content-Type": "application/json,application/json-patch+json", "Accept": "text/plain", "Authorization": "Bearer eyJhbGciOiJSUzI1NiIsImtpZCI6IkYyNjlDMUNBOEI4N0YyNDE1MUQwMEE4NzI5MTZCN0EwOEM4RUJGQUQiLCJ0eXAiOiJKV1QiLCJ4NXQiOiI4bW5CeW91SDhrRlIwQXFIS1JhM29JeU92NjAifQ.eyJuYmYiOjE2NzcwNTE3OTYsImV4cCI6MTY3NzEzODc5NiwiaXNzIjoiaHR0cDovL3pkaWRlbnRpdHlzZXJ2ZXIuemhzZXJ2aWNlIiwiYXVkIjpbImh0dHA6Ly96ZGlkZW50aXR5c2VydmVyLnpoc2VydmljZS9yZXNvdXJjZXMiLCJhcGlzIl0sImNsaWVudF9pZCI6ImNvbXByZWhlbnNpdmUuYXBpcyIsInN1YiI6IlpkLkNvbXByZWhlbnNpdmUuVG9rZW4iLCJhdXRoX3RpbWUiOjE2NzcwNTE3OTYsImlkcCI6ImxvY2FsIiwiYWNjb3VudGlkIjoiMTQyODM1Iiwic3lzdGVtdHlwZSI6IjQxIiwiaXNzdXBlcmFkbWluIjoiRmFsc2UiLCJzY29wZSI6WyJhcGlzIiwib2ZmbGluZV9hY2Nlc3MiXSwiYW1yIjpbInBhc3N3b3JkIl19.aooH-5ARYDLOlAKrb_-FrVQoMIsII82WS4SDxXdJ9uP0oIDEJMkR91LejjLH_LXPc1HXfWzUPwXW41T-gnbGB5ERiJF0OSbZLu5jla77kr3xZ-m_cgPdKuUeRCdrQQUaZn5TVxGHmDXMwjGfCZEKZsjEcTqDM5eYsNVjcBzcm6zbtAyjg07B4sbbE22QLdQS6DRFOOdmvMvngzM4tBaq2KDENNwdGkPE4_2_Y2ck0fc24K7ON5jtqBxdVzjn7imcPdBlg82uu9gNKE0cdvlY54ooollHv2S4UxiIwtiJY4MGxFx0G_fpNvDVDxZd8xi3SUM5jnshJG7te8w8zb5c-g", "Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", "Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9"]

Request Body: {"languageCode":"CHS","timeStamp":1677131665.748841,"MemberCode":"TY327N02","sportId":2,"Token":"TY327N02,fb2bebe4-2ac1-402e-a4aa-250393448bf5","EventIds":[67130891]}

Request Method: POST

{"refreshTime":1677131726,"isSuccess":true,"errorCode":10000,"message":"","location":"","data":{"ServerTime":"2023-02-23 13:54:26","StatusCode":100,"StatusDesc":"Success"}}


#### Request Headers

```
["User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", 
"Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", 
"Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9", 
"Content-Type": "application/json"]
```

#### Request Method: Post

####  请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 请求示例：

```
{}

```

#### 2.1.2 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 返回示例：

```
{}

```

---


---

2?
## 2.30 REMOVEFAVOURITEEVENT 删除收藏赛事 描述:此 API 用于删除收藏赛事.
### /api/Imd/InplayMatrix/REMOVEFAVOURITEEVENT

Request Headers: ["Accept": "text/plain", "Content-Type": "application/json,application/json-patch+json", "Authorization": "Bearer eyJhbGciOiJSUzI1NiIsImtpZCI6IkYyNjlDMUNBOEI4N0YyNDE1MUQwMEE4NzI5MTZCN0EwOEM4RUJGQUQiLCJ0eXAiOiJKV1QiLCJ4NXQiOiI4bW5CeW91SDhrRlIwQXFIS1JhM29JeU92NjAifQ.eyJuYmYiOjE2NzcwNTE3OTYsImV4cCI6MTY3NzEzODc5NiwiaXNzIjoiaHR0cDovL3pkaWRlbnRpdHlzZXJ2ZXIuemhzZXJ2aWNlIiwiYXVkIjpbImh0dHA6Ly96ZGlkZW50aXR5c2VydmVyLnpoc2VydmljZS9yZXNvdXJjZXMiLCJhcGlzIl0sImNsaWVudF9pZCI6ImNvbXByZWhlbnNpdmUuYXBpcyIsInN1YiI6IlpkLkNvbXByZWhlbnNpdmUuVG9rZW4iLCJhdXRoX3RpbWUiOjE2NzcwNTE3OTYsImlkcCI6ImxvY2FsIiwiYWNjb3VudGlkIjoiMTQyODM1Iiwic3lzdGVtdHlwZSI6IjQxIiwiaXNzdXBlcmFkbWluIjoiRmFsc2UiLCJzY29wZSI6WyJhcGlzIiwib2ZmbGluZV9hY2Nlc3MiXSwiYW1yIjpbInBhc3N3b3JkIl19.aooH-5ARYDLOlAKrb_-FrVQoMIsII82WS4SDxXdJ9uP0oIDEJMkR91LejjLH_LXPc1HXfWzUPwXW41T-gnbGB5ERiJF0OSbZLu5jla77kr3xZ-m_cgPdKuUeRCdrQQUaZn5TVxGHmDXMwjGfCZEKZsjEcTqDM5eYsNVjcBzcm6zbtAyjg07B4sbbE22QLdQS6DRFOOdmvMvngzM4tBaq2KDENNwdGkPE4_2_Y2ck0fc24K7ON5jtqBxdVzjn7imcPdBlg82uu9gNKE0cdvlY54ooollHv2S4UxiIwtiJY4MGxFx0G_fpNvDVDxZd8xi3SUM5jnshJG7te8w8zb5c-g", "User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", "Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", "Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9"]

Request Body: {"sportId":2,"timeStamp":1677132123.3103042,"Token":"TY327N02,fb2bebe4-2ac1-402e-a4aa-250393448bf5","MemberCode":"TY327N02","languageCode":"CHS","EventIds":[67494575]}

Request Method: POST

Response Body: {"refreshTime":1677132184,"isSuccess":true,"errorCode":10000,"message":"","location":"","data":{"ServerTime":"2023-02-23 14:02:03","StatusCode":100,"StatusDesc":"Success"}}


#### Request Headers

```
["User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", 
"Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", 
"Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9", 
"Content-Type": "application/json"]
```

#### Request Method: Post

####  请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 请求示例：

```
{}

```

#### 2.1.2 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 返回示例：

```
{}

```

---


---

## 2.32 SUBMITBUYBACK 提交回购 描述:此 API 常用于为提前兑现提交的回购请求.当一个代码成功响应, 等于回购请求已成功地提交处理.
### /api/Imd/InplayMatrix/SUBMITBUYBACK


#### Request Headers

```
["User-Agent": "DBJ2 qSportProduce/2.1.7 (tw.ho.196pro; build:6; iOS 16.2.0) Alamofire/5.6.4", 
"Accept-Encoding": "br;q=1.0, gzip;q=0.9, deflate;q=0.8", 
"Accept-Language": "zh-Hans-US;q=1.0, en;q=0.9", 
"Content-Type": "application/json"]
```

#### Request Method: Post

####  请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串

#### 请求示例：

```
{}

```

#### 2.1.2 返回结果

[详情看FB文档](https://doc.newsportspro.com/apidoc_app.html#%E8%8E%B7%E5%8F%96%E8%B5%9B%E4%BA%8B%E5%88%97%E8%A1%A8%E4%BF%A1%E6%81%AF)

参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
refreshTime			|String		|R			|请求报文头
isSuccess					|String		|R			|FB登录后token，没有登录则为空字符串
errorCode					|String		|R			|FB登录后token，没有登录则为空字符串
message					|String		|R			|FB登录后token，没有登录则为空字符串
location					|String		|R			|FB登录后token，没有登录则为空字符串
data					|String		|R			|FB登录后token，没有登录则为空字符串

#### 返回示例：

```
{}

```

---

---
##
###


---

####  请求参数
参数名称						|类型		|出现要求	|描述  
:----						|:---		|:------	|:---	
Header						|&nbsp;		|R			|请求报文头
&emsp;Authorization					|string		|R			|FB登录后token，没有登录则为空字符串


---

<table>
<thead>
<tr class="header">
<th style="text-align: left;">FIELD</th>
<th style="text-align: left;">TYPE</th>
<th style="text-align: left;">DESC</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">success</td>
<td style="text-align: left;">boolean</td>
<td style="text-align: left;"><font i18n="api.v1-match-getList.resp.success">成功的标志，true / false</font></td>
</tr>
<tr class="even">
<td style="text-align: left;">code</td>
<td style="text-align: left;">integer</td>
<td style="text-align: left;"><font i18n="api.v1-match-getList.resp.code">返回码</font></td>
</tr>
</tbody>
</table>









