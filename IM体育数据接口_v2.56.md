IPIS Mobile

Inplay Matrix 体育赔率整合规格

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Version 2.56 

**11/3/2022** 

本文档中所包括的资料和信息是唯一并归 Inplay Matrix 财产所有及得到严格保密。 若未经 Inplay Matrix 事先的书面许可，不得复制，重新制作，披露，分发，传播或流传此文件里提及 到的信息内容

版本修订记录



|版本** |修订日期** |操作者** |修订内容** |
| - | - | - | - |
|2.27 |7/11/2019 ||<p>- 删除 GetEventInfo </p><p>- 删除 GetDeltaEventInfo </p><p>- 加上 GetEventInfoMBT </p><p>- 加上 GetDeltaEventInfoMBT </p><p>- 加上 GetMLInfoOBT </p><p>- 加上 GetDeltaMLInfoOBT </p>|
|2.28 |17/12/2019 ||<p>- 加上 GetLiveStreamingInfo API </p><p>- 为赛事对象加上 “LiveStreaming”的响应参数</p><p>. </p><p>- 在 GetDeltaMLInfoOBT 的响应参数中加上新操作 “移除所有盘口” (ID=13) </p><p>- 把 EventGroupTypeId = 0 从赛事组别类型 ID 中删 除 </p><p>- 在 GetLiveResults API 加上 EventGroupTypeIds 响应 参数 </p><p>- 在 GetCompletedResults API 加上 </p><p>“EventGroupID” 和“EventGroupTypeID” 的响应 参数 </p>|
|2.29 |10/2/2020 ||<p>- 加上 GetFavouriteEvent API. </p><p>- 加上 AddFavouriteEvent API. </p><p>- 加上 RemoveFavouriteEvent API. </p><p>- 加上 GetMemberByToken API. </p><p>- 加上 Currency Code Appendix. </p>|
|2.30 |10/3/2020 ||<p>- 加上 GetCompanyById API. </p><p>- 在 GetAnnouncement API 加上 “OrderBy” 的请求 参数 </p>- 加上滚球时间段附录|
|2.31 |7/4/2020 ||<p>- 加上秘鲁索尔货币</p><p>- 加上西班牙文</p><p>- 为赛事相关的 api 增加了 ExtraInfo 和 HasCorner 响 应参数 </p><p>- 删除亚洲 9 号球,沙滩排球,台球和赛车的体育 ID </p>|
|2.32 |20/4/2020 ||- 从语言编码中删除繁体， 日本，韩文|
|2.33 |25/6/2020 ||<p>- 把 IsBetTradeOpen 的响应参数从赛事对象上删除</p><p>- 加上 IPIS 版本 附录 </p><p>- 在赛事对象上加上 BetTypeNameList </p><p>- 加上乒乓球体育 ID </p><p>- 新增乒乓球赛事组别类型 ID </p><p>- 为乒乓球的请求参数加上 BestOfN 和 ExtraInfo </p><p>- 在 GetFavouriteEvent API 加上 IncludeGroupEvents 的请求参数</p>|
|2.34 |27/7/2020 ||<p>- 删除新加坡货币</p><p>- 加上 USDT 加密货币 </p>|
|2.35 |2/9/2020 ||<p>- 加上虚拟足球英国联赛和虚拟足球西班牙友谊赛</p><p>- 为所有与赛事相关的 api 添加“SourceId”响应参 数 </p><p>- 为 GetCompletedResults/GetBetList/GetStatement 加上 “SourceId” 响应参数 </p><p>- 为 GetBetList/GetStatement 加上“BetResettled” 响 应参数 </p>|
|2.36 |15/9/2020 ||<p>- 新增网球赛事组别类型 ID。 </p><p>- 新增网球滚球时间段</p><p>。 </p><p>- 新增网球的 Server, BestOfN, HPoints, APoints 参数 在 ExtraInfo。 </p>|
||||<p>- GetBetList/GetStatement: 新增 WagerItemCancelReason 参数值 (101 = Abandoned 賽事終止)。 </p><p>- GetCompletedResults: 新增 ”CancelReason” 响应参 数。 </p><p>- 新增 Search API。 </p>|
|2.37 |28/9/2020 ||- 对于已售出的投注，无论是否赛事已经结算， BetSettlementStatus=1 |
|2.38 |26/10/2020 ||<p>- GetMLInfoOBT: 新增 ”Market” 响应参数。 </p><p>- 新增“虚拟足球西班牙联赛”和“虚拟足球意大 利联赛”体育。</p>|
|2.39 |18/12/2020 ||-新增毫比特货币. |
|2.40 |11/1/2021 ||<p>- 新增“金融投注”体育。 </p><p>- 新增“OverallScore” 响应参数在 GetCompletedResults 和 GetBetList/GetStatement API。 </p>|
|2.41 |1/2/2021 ||<p>- 新增以太坊货币. </p><p>- 删除”HasNews”和”BRTournamentID” 响应参数。 </p>|
|2.42 |5/3/2021 ||<p>- 加密货币支持 4 位小数。 </p><p>- IPIS 版本 1 将于 2021-03-09 到期。 </p><p>- 新增“BettingStyle” 响应参数在 GetUserPreference API。 </p><p>- 新增“BettingStyle” 请求参数在 UpdateUserPreference API。 </p><p>- 新增“上半场”， “下半场”和“加时赛” 赛事 组别类型。</p><p>- 新增“RelatedScores” 响应参数在 GetCompletedResults API。 </p>|
|2.43 |19/3/2021 ||- 新增“BetTradeSuccessDateTime” 响应参数在 GetBetList / GetStatement API。 <p>-新增货币. |
|2.44 |12/4/2021 ||<p>- 新增“EventIds”和“CompetitionIds”请求参 数在 GetOutrightEvents API。 </p><p>- 新增“ComboAutoAccept”和“LanguageCode”请 求参数在 GetUserPrefernces API。 </p><p>- 新增“ComboAutoAccept”和“LanguageCode” 响 应参数在 UpdateUserPreferences API。 </p><p>- 新增定位类型 60，以指示投注类型全名在 GetLocalizations 和 GetDeltaLocalizations API。 </p><p>- 新增“IdList” 和“BTNameCodeList”和</p><p>“LanguageCodeList”请求参数在 GetLocalizations 和 GetDeltaLocalizations API。 </p><p>- 新增“RefId” 请/响应参数在 GetBetInfo API。 </p>|
|2.45 |26/4/2021 ||<p>- 新增“Market”请求参数在 GetFavouriteEvent API。 </p><p>- 新增“WinningTeamList”, “WinningTeamId”, “WinningTeamName” 响应参数在 GetBetList/GetStatement API。 </p><p>- 新增“Programme”, “ProgrammeId”, “ProgrammeName”响应参数在 GetCompletedResults API。 </p><p>- 新增“Programme”, “ProgrammeId”, “ProgrammeName”响应参数在 GetEventInfoMBT API。 </p>|
|2.46 |10/5/2021 ||- 新增“ProgrammeIds”请求参数 在”GetFavouriteEvent” API。 |
|2.47 |27/5/2021 ||<p>- 新增“ORCount”响应参数在 GetAllSportCount API。 </p><p>- 新增“Programme”, “ProgrammeId”, “ProgrammeName”响应参数在 GetOutrightEvents API。 </p>|
||||<p>- 在 GetStatement API 的“开始日期”，仅允许 31 天前）。 </p><p>- 在 GetStatement API，只允许每 2 秒 1 次调用的频 率。 </p>|
|2.48 |8/6/2021 ||-在 GetStatement API，只允许每 2 秒 1 次调用的频 率（一样的请求参数）。 |
|2.49 |11/8/2021 ||- 新增“Outcome”响应参数在 GetBetList/GetStatement API。 |
|2.50 |6/9/2021 ||<p>- 新增状态编码(1200: 投注被拒) 在 PlaceBet API。 </p><p>- 新增中国元货币(CNY) 。 </p><p>- 新增加密货币瑞波币 (XRP), 比特币现金(BCH), 莱特 币 (LTC), 柚子币 (EOS), 波场币 (TRX), 恒星币 (XLM), 达世币 (DSH), 大零币 (ZEC), 阿拉贡 (ALG), 哈希图币 (HBA), 比特币黄金 (BTG) 。 </p>|
|2.51 |1/10/2021 ||- 新增巴基斯坦卢比货币(PKR) 。 |
|2.52 |28/10/2021 ||<p>- 新增”WagerItemCancelReason” 值 (4=其他：危 险,5=其他：系统超时) 。 </p><p>- 新增状态编码 501(用户无访问权限) 。 </p>|
|2.53 |7/12/2021 ||- 新增“CompetitionList”响应参数在 GetAllSportCount API。 |
|2.54 |10/1/2022 ||<p>- 新增“PreviousClose”, “TodayOpen”, “TodayHighest”, “TodayLowest” 和“CurrentIndex”响应参数在赛事相</p><p>关的 API。 </p><p>- 新增“BetTypeId”响应参数在 GetBetInfo API。 </p>|
|2.55 |11/2/2022 ||<p>- 新增响应参数在 PlaceBet API. </p><p>- 沙滩排球从 Sportid 40 中排除。 </p><p>- 删除 MYR, PHP, TWD 货币。 </p>|
|2.56 |11/3/2022 ||- 新增赛事顺序附录。 |
目录 **![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.001.png)**

[目录 ............................................................................................................................................ 7 ](#_page6_x69.00_y98.00)[1  简介 ..................................................................................................................................... 9 ](#_page8_x69.00_y73.00)[2  拉模式界面 ........................................................................................................................ 10 ](#_page9_x69.00_y73.00)

1. [GetAllSportCount 索取所有体育计数........................................................................... 10 ](#_page9_x69.00_y198.00)
1. [GetAllCompetitionCount 索取所有竞赛计数 ................................................................ 15 ](#_page14_x69.00_y708.00)
1. [GetEventInfoMBT 索取赛事和主要玩法资料 ............................................................... 19 ](#_page18_x69.00_y488.00)
1. [GetDeltaEventInfoMBT 索取 Delta 赛事和主要玩法详情 .......................................... 29 ](#_page28_x69.00_y73.00)
1. [GetMLInfoOBT 索取其他玩法资料............................................................................... 32 ](#_page31_x69.00_y135.00)
1. [GetDeltaMLInfoOBT 索取 Delta 其他玩法详情 .......................................................... 47 ](#_page46_x69.00_y514.00)
1. [GetSelectedEventInfo 索取赛事选项资料 .................................................................... 50 ](#_page49_x69.00_y159.00)
1. [GetVSEventInfo 索取虚拟赛事列表 ............................................................................. 51 ](#_page50_x69.00_y566.00)
1. [GetDeltaVSEventInfo 索取 Delta 虚拟赛事列表 ........................................................... 53 ](#_page52_x69.00_y317.00)
1. [GetVSEventDetails 索取虚拟赛事资料 ......................................................................... 55 ](#_page54_x69.00_y97.00)
1. [GetOutrightEvents 索取优胜冠军赛事 ........................................................................ 56 ](#_page55_x69.00_y400.00)
1. [GetDeltaOutrightEventInfo 索取 Delta 优胜冠军赛事 ................................................ 63 ](#_page62_x69.00_y562.00)
1. [GetLiveResults 索取现场赛果 ...................................................................................... 67 ](#_page66_x69.00_y280.00)
1. [GetLocalizations 索取定位 ........................................................................................... 69 ](#_page68_x69.00_y476.00)
1. [GetDeltaLocalizations 索取 Delta 定位 ...................................................................... 71 ](#_page70_x69.00_y571.00)
1. [GetCompletedResults 索取完整赛果............................................................................ 73 ](#_page72_x69.00_y667.00)
1. [LogOut 退出 ............................................................................................................... 79 ](#_page78_x69.00_y612.00)
1. [GetBetInfo 索取投注信息 ............................................................................................ 81 ](#_page80_x69.00_y145.00)
1. [PlaceBet 投注 .............................................................................................................. 86 ](#_page85_x69.00_y195.00)
1. [GetBetList 索取投注明细 ............................................................................................ 92 ](#_page91_x69.00_y306.00)
1. [GetStatement 索取投注账目 ..................................................................................... 100 ](#_page99_x69.00_y525.00)
1. [GetBalance 索取余额 ............................................................................................... 102 ](#_page101_x69.00_y121.00)
1. [GetPendingWagerStatus 索取待处理投注状态........................................................... 103 ](#_page102_x69.00_y386.00)
1. [GetAnnouncement 索取通告 .................................................................................... 105 ](#_page104_x69.00_y302.00)
1. [GetMemberByToken 索取会员信息 .......................................................................... 107 ](#_page106_x108.00_y354.00)
1. [GetUserPreferences 索取用户自定义 ....................................................................... 108 ](#_page107_x69.00_y675.00)
1. [UpdateUserPreferences 更新用户自定义 .................................................................. 111 ](#_page110_x69.00_y197.00)
1. [GetFavouriteEvent 索取所有收藏赛事 ....................................................................... 113 ](#_page112_x69.00_y508.00)
29. [AddFavouriteEvent 加收藏赛事 ................................................................................. 115 ](#_page114_x69.00_y403.00)
29. [RemoveFavouriteEvent 删除收藏赛事 ....................................................................... 116 ](#_page115_x69.00_y722.00)
29. [GetDeltaBetTrade 提前兑现 Delta.............................................................................. 118 ](#_page117_x108.00_y462.00)
29. [SubmitBuyBack 提交回购 ......................................................................................... 120 ](#_page119_x69.00_y214.00)
29. [GetLiveStreamingInfo 索取赛事直播资料 ................................................................. 122 ](#_page121_x69.00_y73.00)
29. [GetCompanyById 以 CompanyID 索取公司设定 ......................................................... 123 ](#_page122_x69.00_y656.00)

[3  附录 ................................................................................................................................. 126 ](#_page125_x69.00_y73.00)

1. [语言编码 .................................................................................................................. 126 ](#_page125_x69.00_y107.00)
1. [货币 编码 ................................................................................................................. 126 ](#_page125_x69.00_y303.00)
1. [体育 ID .................................................................................................................... 127 ](#_page126_x69.00_y570.00)
1. [赛事组别类型 ID ..................................................................................................... 128 ](#_page127_x69.00_y449.00)
1. [滚球时间段............................................................................................................... 129 ](#_page128_x69.00_y268.00)
1. [赛事顺序 .................................................................................................................. 130 ](#_page129_x69.00_y73.00)
1. [连串过关选项 ........................................................................................................... 130 ](#_page129_x69.00_y406.00)
1. [时区.......................................................................................................................... 131 ](#_page130_x69.00_y214.00)
1. [团队图标 .................................................................................................................. 131 ](#_page130_x69.00_y691.00)
1. [状态编码............................................................................................................... 132 ](#_page131_x69.00_y245.00)
1. [IPIS 版本 ................................................................................................................... 134 ](#_page133_x69.00_y482.00)

**1**  简介![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.002.png)

本文件概述由 Inplay Matrix 体育检索信息的技术行为要求以展示其体育博彩界面. 此外, 对信息 交换, 信息结构, 接口中的呼叫方式和使用参数列表, 使用返回代码解释响应及交易请求与响应 的示例提供有关详情

请知悉本文件仅适用于开发用户界面方式. 此规格必须与主要的体育整合规格并用, 其中可找到 其他整合功能如登录, 投注等.. 

![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.003.jpeg)

**2**  拉模式界面![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.002.png)

拉模式界面是一个提供检索相关资料需求的沟通渠道以呈现全部体育博彩投注功能至体育博彩 用户界面. 各可用方式及其细节根据以下描述详情.   

1. **GETALLSPORTCOUNT** 索取所有体育计数

描述** 

此 API 常用于检索目前为每项体育提供的赛事计数. 特定赛事组类的赛事计数亦可能在适用的 情况的返回. 目前, 角球赛事计数将被返回于足球下. 

访问频率限制: 20 秒 请求** 



|范围** |数据类型** |强制性** |描述** |
| - | - | - | - |
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟|
|LanguageCode |String |Yes |为本地名称返回的语言|
|IsCombo |Boolean |Yes |指出请求是连串过关赛事或者非连串过关赛事。<p>当IsCombo提交null时，将返回连串过关计数和 非连串过关计数。 |


响应** 

|范围** |数据类型** |空值** |描述** |
| - | - | - | - |
|StatusCode |Int |No |指出请求状态编码.|
|StatusDesc |String |No |状态编码的描述含义.|
|SportId |Int |No |指出体育项目. 参考附录3.3.|
|SportName |String |No |体育项目名称在指定请求中返回相应语言.|
|Order Number |Short |No |体育项目序号.|
|Count |Int |No |体育赛事计数.|
|EarlyFECount |Int |No |早盘盘口的体育定时赛事计数.|
|TodayFECount |Int |No |今日盘口的体育定时赛事计数.|
|RBFECount |Int |No |滚球盘口的体育定时赛事计数.|
|ORCount |Int |No |冠军赛事计数。 |
|IsCombo |Boolean |No |指出计数是连串过关赛事或者非连串过关赛事。|
|IsHasLive |Boolean |No |指出目前是否提供滚球赛事. |
|EventGroupTypes |List |No |赛事组别类型清单|
|-  EventGroupTypeId |Int |No |指出赛事组别类型。参考附录3.4。|
|-  Count |Int |No |赛事组别类型的赛事计数|
|-  EarlyFECount |Int |No |早盘盘口的体育/组别类型定时赛事计数.|
|-  TodayFECount |Int |No |今日盘口的体育/组别类型定时赛事计数.|
|-  RBFECount |Int |No |滚球盘口的体育/组别类型定时赛事计数.|
|-  ORCount |Int |No |冠军赛事计数。 |
|-  IsHasLive |Boolean |No |指出目前是否给赛事组别类型提供滚球赛事.|
|ProgrammeList |List |No |ProgrammeIds 清单 |
|-  ProgrammeId |Int |No |指出特定的竞赛程序|
|-  ProgrammeName |String |No |程序名称在指定请求中返回相应语言.|
|-  Count |Int |No |程序的赛事计数.|
|-  EarlyFECount |Int |No |早盘盘口的体育/程序定时赛事计数.|
|-  TodayFECoun t |Int |No |今日盘口的体育/程序定时赛事计数. |
|-  RBFECount |Int |No |滚球盘口的体育/程序定时赛事计数.|
|-  ORCount |Int |No |冠军赛事计数。 |
|-  IsHasLive |Boolean |No |指出目前是否给程序提供滚球赛事.|
|CompetitionList |List |No |竞赛 清单 |
|- CompetitionId |Int |No |指出特定的竞赛|
|- CompetitionName |String |No |竞赛名称在指定请求中返回相应语言.|
|- Count |Int |No |竞赛的赛事计数.|
|- EarlyFECount |Int |No |早盘盘口的体育/竞赛定时赛事计数.|
|- TodayFECount |Int |No |今日盘口的体育/竞赛定时赛事计数.|
|- RBFECount |Int |No |滚球盘口的体育/竞赛定时赛事计数.|
|- ORCount |Int |No |冠军赛事计数。 |
|- IsHasLive |Boolean |No |指出目前是否给竞赛提供滚球赛事.|
|StatusCode |Int |No |指出请求状态编码.|
|StatusDesc |String |No |状态编码的描述含义.|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 1: GetAllSportCount Request* 

![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.004.png)

{ 

`    `"TimeStamp": "I9HjmhexYGF6EcGy8NQI4Ts9R/9fxPIcHJdrEpq1ocY=",     "LanguageCode": "eng", 

`    `"IsCombo": "false" 

} 

请求** 

*Table 2: GetAllSportCount Response* 

{ 

`    `"SportCount": [ 

`        `{ 

`            `"SportId": 1, 

`            `"SportName": "Soccer", 

`            `"OrderNumber": 1, 

`            `"EventGroupTypes": [ 

`                `{ 

`                    `"EventGroupTypeId": 1,                     "Count": 57, 

`                    `"EarlyFECount": 40, 

`                    `"TodayFECount": 9, 

`                    `"RBFECount": 6, 

`                    `"ORCount": 2, 

`                    `"IsHasLive": true 

`                `}, 

`                `{ 

`                    `"EventGroupTypeId": 2, 

`                    `"Count": 1, 

`                    `"EarlyFECount": 1, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"EventGroupTypeId": 3, 

`                    `"Count": 4, 

`                    `"EarlyFECount": 4, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `} 

`            `], 

`            `"ProgrammeList": [ 

`                `{ 

`                    `"ProgrammeId": 314, 

`                    `"ProgrammeName": "Olympics",                     "Count": 13, 

`                    `"EarlyFECount": 12, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 1, 

`                    `"IsHasLive": false 

`                `} 

`            `], 

`            `"CompetitionList": [ 

`                `{ 

`                    `"CompetitionID": 124, 

`                    `"CompetitionName": "\*England Premier League",                     "Count": 7, 

`                    `"EarlyFECount": 6, 

`                    `"TodayFECount": 1, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"CompetitionID": 115, 

`                    `"CompetitionName": "\*Spain La Liga", 

`                    `"Count": 3, 

`                    `"EarlyFECount": 1, 

`                    `"TodayFECount": 1, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 1, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"CompetitionID": 133, 

`                    `"CompetitionName": "\*Italy Serie A", 

`                    `"Count": 3, 

`                    `"EarlyFECount": 3, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"CompetitionID": 219, 

`                    `"CompetitionName": "\*UEFA Champions League",                     "Count": 1, 

`                    `"EarlyFECount": 1, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"CompetitionID": 129, 

`                    `"CompetitionName": "\*Germany Bundesliga 1", 

`                    `"Count": 1, 

`                    `"EarlyFECount": 1, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `} 

`            `], 

`            `"IsCombo": false, 

`            `"IsHasLive": true, 

`            `"EarlyFECount": 45, 

`            `"TodayFECount": 9, 

`            `"ORCount": 2, 

`            `"RBFECount": 6, 

`            `"Count": 62 

`        `}, 

`        `{ 

`            `"SportId": 2, 

`            `"SportName": "Basketball",             "OrderNumber": 2, 

`            `"EventGroupTypes": [ 

`                `{ 

`                    `"EventGroupTypeId": 1,                     "Count": 22, 

`                    `"EarlyFECount": 16, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 3, 

`                    `"ORCount": 3, 

`                    `"IsHasLive": true 

`                `}, 

`                `{ 

`                    `"EventGroupTypeId": 4,                     "Count": 9, 

`                    `"EarlyFECount": 9, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"EventGroupTypeId": 5,                     "Count": 9, 

`                    `"EarlyFECount": 9, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"EventGroupTypeId": 6,                     "Count": 9, 

`                    `"EarlyFECount": 9, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"EventGroupTypeId": 7,                     "Count": 9, 

`                    `"EarlyFECount": 9, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `} 

`            `], 

`            `"ProgrammeList": [ 

`                `{ 

`                    `"ProgrammeId": 314, 

`                    `"ProgrammeName": "Olympics",                     "Count": 2, 

`                    `"EarlyFECount": 0, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 2, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": true 

`                `} 

`            `], 

`            `"CompetitionList": [ 

`                `{ 

`                    `"CompetitionID": 199, 

`                    `"CompetitionName": "\*NBA", 

`                    `"Count": 5, 

`                    `"EarlyFECount": 5, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `}, 

`                `{ 

`                    `"CompetitionID": 5580, 

`                    `"CompetitionName": "CBA - China Basketball Association",                     "Count": 4, 

`                    `"EarlyFECount": 4, 

`                    `"TodayFECount": 0, 

`                    `"RBFECount": 0, 

`                    `"ORCount": 0, 

`                    `"IsHasLive": false 

`                `} 

`            `], 

`            `"IsCombo": false, 

`            `"IsHasLive": true, 

`            `"EarlyFECount": 52, 

`            `"TodayFECount": 0, 

`            `"ORCount": 3, 

`            `"RBFECount": 3, 

`            `"Count": 58 

`        `} 

`    `], 

`    `"ServerTime": "2021-12-06T06:40:11.0516596-04:00", 

`    `"StatusCode": 100, 

`    `"StatusDesc": "Success" 

} 

响应** 

2. **GETALLCOMPETITIONCOUNT** 索取所有竞赛计数

描述** 

此 API 常用于检索目前为每场竞赛提供的赛事计数. 访问频率限制:  

请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟.|
|LanguageCode |String |Yes |为本地名称返回的语言.|
|SportId |Int |Yes |指出体育项目. 参考附录3.3.|
|IsCombo |Boolean |Yes |指出请求是连串过关赛事或者非连串过关赛事|
|Market |Int |Yes |<p>指出“早盘”、“今日”或者“滚球”的盘口 <p>1 = 早盘 <p>2 = 今日 <p>3 = 滚球 |
|EventDate |Date |No |指出只返回属于特定赛事日期的赛事. 仅适用于 早盘盘口.|
|EventGroupTypeIds |List of Int |No |可选参数用于指出只返回特定赛事组别类型的 赛果. 参考附录3.4。|
|IncludeCloseEvent |Boolean |Yes |指出计数是否包括关闭赛事.|

响应** 

|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|SportId |Int |No |指出体育项目ID. 参考附录.|
|SportName |String |No |体育项目名称在特定请求中返回相应语言.|
|OrderNumber |Short |No |体育项目序号.|
|CompetitionId |Int |No |每场竞赛的特定ID.|
|CompetitionName |String |No |竞赛名称在指定请求中返回相应语言.|
|PMOrderNumber |Int |No |竞赛赛前序号. |
|RBOrderNumber |Int |No |竞赛滚球序号.|
|ProgrammeId |Int |No |竞赛组别的特定ID. |
|ProgrammeName |String |No |竞赛组别名称在指定请求中返回相应语言.|
|ProgrammeOrder Number |Int |No |竞赛组别序号|
|Count |Int |No |竞赛赛事计数.|
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|

范例** 

*Table 3: GetAllCompetitionCount Request* 

{ 

`  `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",      "LanguageCode":"eng", 

`  `"IsCombo":"false", 

`  `"SportId":1,        

`  `"Market":3,  

`  `"IncludeCloseEvent":"false",             

`  `"EventDate":"",                     

`  `"EventGroupTypeIds":[0,1,2,3,4,5,6,7],              

`  `"ProgrammeId":""                                         

} 

请求** 

*Table 4: GetAllCompetitionCount Response* 

{ 

`  `"CompetitionCount": [ 

`    `{ 

`      `"SportId": 1, 

`      `"SportName": "Soccer", 

`      `"OrderNumber": 1, 

`      `"CompetitionId": 782, 

`      `"CompetitionName": "Club Friendly", 

`      `"PMOrderNumber": 0, 

`      `"RBOrderNumber": 0, 

`      `"Market": 3, 

`      `"ProgrammeId": 1, 

`      `"ProgrammeName": "Others", 

`      `"ProgrammeOrderNumber": 2, 

`      `"Count": 1 

`    `}, 

`    `{ 

`      `"SportId": 1, 

`      `"SportName": "Soccer", 

`      `"OrderNumber": 1, 

`      `"CompetitionId": 15306, 

`      `"CompetitionName": "PleaseDontUserMyEvent", 

"PMOrderNumber": 0, 

`      `"RBOrderNumber": 0, 

`      `"Market": 3, 

`      `"ProgrammeId": 1, 

`      `"ProgrammeName": "Others", 

`      `"ProgrammeOrderNumber": 2, 

`      `"Count": 1 

`    `}, 

`    `{ 

`      `"SportId": 1, 

`      `"SportName": "Soccer", 

`      `"OrderNumber": 1, 

`      `"CompetitionId": 15748, 

`      `"CompetitionName": "Premier Cup (in Austria)",       "PMOrderNumber": 0, 

`      `"RBOrderNumber": 0, 

`      `"Market": 3, 

`      `"ProgrammeId": 1, 

`      `"ProgrammeName": "Others", 

`      `"ProgrammeOrderNumber": 2, 

`      `"Count": 1 

`    `}, 

`    `{ 

`      `"SportId": 1, 

`      `"SportName": "Soccer", 

`      `"OrderNumber": 1, 

`      `"CompetitionId": 12801, 

`      `"CompetitionName": "United Soccer League Championship",       "PMOrderNumber": 0, 

`      `"RBOrderNumber": 0, 

`      `"Market": 3, 

`      `"ProgrammeId": 1, 

`      `"ProgrammeName": "Others", 

`      `"ProgrammeOrderNumber": 2, 

`      `"Count": 4 

`    `}, 

`    `{ 

`      `"SportId": 1, 

`      `"SportName": "Soccer", 

`      `"OrderNumber": 1, 

`      `"CompetitionId": 133, 

`      `"CompetitionName": "USA Major League Soccer", 

`      `"PMOrderNumber": 0, 

`      `"RBOrderNumber": 0, 

`      `"Market": 3, 

`      `"ProgrammeId": 873, 

`      `"ProgrammeName": "United States", 

`      `"ProgrammeOrderNumber": 4, 

`      `"Count": 1 

`    `}, 

`    `{ 

`      `"SportId": 1, 

`      `"SportName": "Soccer", 

`      `"OrderNumber": 1, 

`      `"CompetitionId": 453, 

`      `"CompetitionName": "USA Major League Soccer - Specials",       "PMOrderNumber": 0, 

`      `"RBOrderNumber": 0, 

`      `"Market": 3, 

`      `"ProgrammeId": 873, 

`      `"ProgrammeName": "United States", 

`      `"ProgrammeOrderNumber": 4, 

`      `"Count": 2 

`    `}, 

`    `{ 

`      `"SportId": 1, 

`      `"SportName": "Soccer", 

`      `"OrderNumber": 1, 

`      `"CompetitionId": 329, 

`      `"CompetitionName": "Ecuador Serie A",       "PMOrderNumber": 2, 

`      `"RBOrderNumber": 2, 

`      `"Market": 3, 

`      `"ProgrammeId": 823, 

`      `"ProgrammeName": "Ecuador", 

`      `"ProgrammeOrderNumber": 5, 

`      `"Count": 1 

`    `} 

`  `], 

`  `"ServerTime": "2019-07-05T06:26:33.1825368-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

3. **GETEVENTINFOMBT**索取赛事和主要玩法资料** 

描述** 

此 API 根据请求参数中指定的特定准则, 常用于检索为特定体育所提供的所有赛事相关 的赛事及主要玩法赔率信息. GetDeltaEventInfoMBT API 用于检索更新的 delta 更改。 

访问频率限制(相同的参数): 1 分钟一次 请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | - | - | - |
|SportId |Int |Yes |指出体育项目. 参考附录3.3.SportId 39, 43, 44, 46, 47, 49, 52, 53, 请参考 GetVSEventInfo/GetDeltaVSEventInfo。 |
|Market |Int |Yes | <p>指出“早盘”、“今日”或者“滚球”的盘口 <p>1 = 早盘 <p>2 = 今日 <p>3 = 滚球 <p> 在早上(上午 9 点至下午 12 点)，今日盘口将 包括早盘(直至上午 12 点)的赛事。|
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟.|

响应** 

|范围** |数据类型**  |空值**  |描述 |
| - | :- | - | - |
|Sports |List |No |体育项目清单|
|- SportId |Int |No |指出体育项目. 参考附录3.3.|
|- SportName |String |No |运营商体育项目名称的默认语言|
|- OrderNumber |Int |No |体育项目序号|
|- Events |List |No |赛事清单 |
|-- OpenParlay |Bool |No |指出赛事是否支持连串过关|
|-- IsLive |Bool |No |指出赛事是否提供滚球|
|-- Market |Int |No | <p>指出“早盘”、“今日”或者“滚球”的盘口 <p>1 = 早盘 <p>2 = 今日 <p>3 = 滚球|
|-- EventId |Long |No |赛事的特定 ID|
|-- EventStatusId |Int |No | <p>指赛事状态 1 = 开盘 <p>2 = 关盘 |
|-- OrderNumber |Int |No |IMSB 中使用的序号用于排序竞赛中赛事的先后显示|
|-- EventDate |Date |No |赛事日期 |
|-- GroundTypeId |Int |No | <p>指出赛事是否举办于其中一队的主场或中立场. <p> 0 = 中立场 <p>1 = 主场 |
|-- EventGroupID |Long |No | <p>如果赛事是属于赛事组别，将显示赛事组别 ID。 <p>实际赛事可以分为不同事件组类型的多个赛事。 <p>范例： <p>Arsenal vs Everton (EPL) (Event ID: 00001) <p>Arsenal vs Everton (EPL Corners) (Event ID: 00002) <p>Arsenal vs Everton (EPL Specials) (Event ID: 00003) |
|-- EventGroupTypeId |Int |No |指出赛事的组别类型. 参考附录3.4.|
|-- TotalMarketlineC ount |Int |Yes | 指出赛事盘口总数. |
|-- IsPopular |Bool |No |指出是否热门赛事|
|-- IsFavourite |Bool |No |指出是否是会员的收藏赛事 (如果会员令牌以提交)|
|-- BREventId |Long |Yes | 可视化投注预测赛事ID. |
|-- SourceId |String |Yes | 赛事的外部参考ID. |
|-- HasVisualization  |Bool |No | 指出赛事是否是可视化. |
|-- HasStatistic |Bool |No | 指出赛事是否有的BetRadar的统计。不适用于IPIS商家。 |
|-- Season |String |Yes |赛季指标. 仅适用于虚拟足球, 虚拟篮球和虚拟世界杯各 项体育. |
|-- MatchDay |String |Yes |赛日指标. 仅适用于虚拟足球和虚拟篮球|
|-- LiveStreaming |Int |Yes |<p>指出赛事是否有现场直播Url <p> 0 = 没有 <p> 1 = 有 |
|-- LiveStreamingUrl |List |Yes |现场直播 URL清单. |
|--- URL |String |Yes |现场直播Url |
|--- Priority |Int |Yes |现场直播 URL优先级. |
|--- Type |Int |Yes |<p>播放类型. <p>0 = Unknown <p>1 = iFrame <p>2 = FLV <p>3 = M3U8 |
|-- HomeTeamId |Int |No | 主队或参赛者的特定 ID. |
|-- HomeTeam |String |Yes | 运营商主队名称的默认语言.  |
|-- AwayTeamId |Int |No | 客队或参赛者的特定 ID|
|-- AwayTeam |String |Yes | 运营商客队名称的默认语言. |
|-- RBTime |String |Yes | <p>如果赛事是在滚球中，这是赛事的滚球时间.  <p>请参考附录 3.5。|
|-- RBTimeStatus |Int |Yes |<p>如果赛事是在滚球中，这是赛事的滚球时间的状态. <p>0 =不适用 <p>1 = 开始 <p>2 = 进行中 <p>3 = 暂停 </p>|
|-- HomeScore |Int |Yes |主队的当前比分|
|-- AwayScore |Int |Yes |客队的当前比分|
|-- HomeRedCard |Int |Yes |主队当前红牌|
|-- AwayRedCard |Int |Yes |客队当前红牌|
|-- RelatedScores |List |Yes |相关比分清单 |
|--- EventGroupTypeId |Int |No |指出比分的组别类型. 参考附录3.4|
|--- HomeScore |Int |Yes |主队的当前组别类型比分|
|--- AwayScore |Int |Yes |客队的当前组别类型比分|
|-- ExtraInfo |String |Yes |赛事的更多信息。每个体育的额外信息将有所不同。|
|--- HasCorner |Bool |No |指出赛事是否具有角球投注类型。 适用于足球。|
|--- Server |String |Yes |指出当前的开球球员/球队。 适用于乒乓球和网球。 |
|--- BestOfN |Intege r |Yes |指出赛事的最大局数。 适用于乒乓球和网球。 |
|--- HPoints |String |Yes |指出当局的主队的分数。 适用于网球。 |
|--- APoints |String  |Yes |指出当局的客队的分数。 <p>适用于网球。 |
|--- PreviousClose |Decim al |Yes |表示前一天的收盘指数。 仅适用于金融投注。|
|--- TodayOpen |Decim al |Yes |表示今天的开盘指数。 仅适用于金融投注。|
|--- TodayHighest |Decim al |Yes |表示今天的最高指数。 仅适用于金融投注。|
|--- TodayLowest |Decim al |Yes |表示今天的最低指数。 仅适用于金融投注。|
|--- CurrentIndex |Decim al |Yes |表示当前的指标。 仅适用于金融投注。|
|-- Competition |List |No |竞赛 |
|--- CompetitionId |Int |No |每场竞赛的特定 ID|
|--- CompetitionName |String |No |运营商竞赛名称的默认语言|
|--- PMOrderNumber |Int |No |IMSB 中使用的序号用于排序赛前的比赛先后显示|
|--- RBOrderNumber |Int |No |IMSB 中使用的序号用于排序滚球中的比赛先后显示|
|-- Programme |List |Yes |竞赛程序 清单 |
|--- ProgrammeId |Int |Yes |指出特定的竞赛程序|
|--- ProgrammeName |String |Yes |程序名称. |
|-- MarketLines |List |Yes |盘口清单 |
|--- MarketLineId |Long |No |盘口的特定 ID|
|--- BetTypeId |Int |No |投注类型 ID |
|--- BetTypeName |String |No |运营商投注类型的默认语言|
|--- BetTypeNameList |List |No |投注类型的支持语言 |
|---- LanguageCode |String |No |语言 |
|---- BetTypeName |String |No |投注类型的名称 |
|--- PeriodId |Int |No |<p>比赛时段 ID  <p>1 = 全场 <p>2 = 上半场 <p>3 = 下半场 |
|--- PeriodName |String |No |运营商比赛时段的默认语言|
|--- MarketLineLevel |Int |No |盘口级别 |
|--- MarketlineStatusId |Int |No |<p>指出盘口状态. <p>1 = 开盘 <p>2 = 关盘 |
|--- IsLocked |Boolea n |No |指出盘口是否封盘|
|--- WagerSelections |List |No |投注选项清单|
|---- WagerSelectionId |Long |No |投注选项的特定 ID|
|---- SelectionId |Int |No |投注类型选项 ID|
|---- SelectionName |String |Yes |运营商投注类型选项的默认语言|
|---- Handicap |Float |Yes |<p>该项目仅适用于让球盘和大小盘.  <p>对于让球，主/客队的让球值是一样的。 <p>让球值是正值是指着主队正在让球。 <p>让分值为负值是指 着客队正在让球。 <p>对于大小盘，就是大于或小于的得分比较。 <p>如果是空值等于该让分不适用于该盘口或投注类型。|
|---- Specifiers |String |Yes |其他下注资料. |
|---- Odds |Float |No |选择赔率值|
|---- OddsList |List |No |赔率清单 |
|----- OddsType |Int |No |<p>赔率类型 <p>1 = 马来盘 <p>2 = 香港盘 <p>3 = 欧洲盘 <p>4 = 印尼盘 |
|----- OddsValues |Float |No |选择赔率值|
|Delta |Doubl e |Yes |<p>Delta 版本。 <p>Delta 值在 5 分钟后过期。 <p>对应于各自的 SportId 和 Market。 <p>格式：yyMMddHHmmssfff <p>范例: 171219001225452 |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID |
|**332** |盘口无效 |
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 5: GetEventInfoMBT Request* 

{ 

`  `"SportId":1,    

`  `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",   "Market": 3     

} ![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.005.png)

请求** *Table 6: GetEventInfoMBT Response* 

{ 

`  `"Sports": [ 

`    `{ 

`      `"SportId": 1, 

`      `"SportName": "Soccer", 

`      `"OrderNumber": 1, 

`      `"Events": [ 

`        `{ 

`          `"OpenParlay": false, 

`          `"IsLive": true, 

`          `"Market": 3, 

`          `"HasVisualization": false, 

`          `"HasStatistic": false, 

`          `"BREventId": 0, 

`          `"TotalMarketLineCount": 1, 

`          `"IsPopular": false, 

`          `"Season": 0, 

`          `"MatchDay": 0, 

`          `"EventId": 6011787, 

`          `"EventStatusId": 1, 

`          `"OrderNumber": 9999, 

`          `"EventDate": "2019-07-03T22:30:00.0000000-04:00", 

"GroundTypeId": 1, "EventGroupId": 319288, "EventGroupTypeId": 1, "HomeTeamId": 2540, "HomeTeam": "Club Tijuana", "AwayTeamId": 4172, "AwayTeam": "CS Herediano ", "RBTime": "2H 1214:14", "RBTimeStatus": 0, "HomeScore": 0, "AwayScore": 0, "HomeRedCard": 0, "AwayRedCard": 0, "IsBetTradeOpen": false, "LiveStreamingUrl": [], "RelatedScores": null, "Competition": { 

`            `"CompetitionId": 782, 

`            `"CompetitionName": "Club Friendly",             "PMOrderNumber": 0, 

`            `"RBOrderNumber": 0 

`          `}, 

`          `"MarketLines": [ 

`            `{ 

`              `"MarketlineId": 88807044, 

`              `"BetTypeId": 1, 

`              `"BetTypeName": "Handicap", 

`              `"PeriodId": 1, 

`              `"PeriodName": "Full Time", 

`              `"MarketLineLevel": 1, 

`              `"MarketlineStatusId": 1, 

`              `"IsLocked": true, 

`              `"WagerSelections": [ 

`                `{ 

`                  `"WagerSelectionId": 2397629650,                   "SelectionId": 1, 

`                  `"SelectionName": "Home", 

`                  `"Handicap": 0.0, 

`                  `"Specifiers": null, 

`                  `"OddsType": 1, 

`                  `"Odds": 0.77, 

`                  `"OddsList": [ 

`                    `{ 

`                      `"OddsType": 1, 

`                      `"OddsValues": { 

`                        `"A": "0.77", 

`                        `"B": "0.76", 

`                        `"C": "0.75", 

`                        `"D": "0.74", 

`                        `"E": "0.73", 

`                        `"F": "0.72", 

`                        `"G": "0.69" 

`                      `} 

`                    `}, 

`                    `{ 

`                      `"OddsType": 2,                       "OddsValues": {                         "A": "0.77", 

`                        `"B": "0.76", 

`                        `"C": "0.75", 

`                        `"D": "0.74", 

`                        `"E": "0.73", 

`                        `"F": "0.72", 

`                        `"G": "0.69" 

`                      `} 

`                    `}, 

`                    `{ 

`                      `"OddsType": 3,                       "OddsValues": {                         "A": "1.77", 

`                        `"B": "1.76", 

`                        `"C": "1.75", 

`                        `"D": "1.74", 

`                        `"E": "1.73", 

`                        `"F": "1.72", 

`                        `"G": "1.69" 

`                      `} 

`                    `}, 

`                    `{ 

`                      `"OddsType": 4,                       "OddsValues": {                         "A": "-1.3", 

`                        `"B": "-1.32", 

`                        `"C": "-1.34", 

`                        `"D": "-1.36", 

`                        `"E": "-1.37", 

`                        `"F": "-1.39", 

`                        `"G": "-1.45" 

`                      `} 

`                    `} 

`                  `] 

`                `}, 

`                `{ 

`                  `"WagerSelectionId": 2397629651,                   "SelectionId": 2, 

`                  `"SelectionName": "Away", 

`                  `"Handicap": 0.0, 

`                  `"Specifiers": null, 

`                  `"OddsType": 1, 

`                  `"Odds": -0.83, 

`                  `"OddsList": [ 

`                    `{ 

`                      `"OddsType": 1, 

`                      `"OddsValues": { 

`                        `"A": "-0.83", 

`                        `"B": "-0.84", 

`                        `"C": "-0.85", 

`                        `"D": "-0.86", 

`                        `"E": "-0.87", 

`                        `"F": "-0.88", 

`                        `"G": "-0.91" 

`                      `} 

`                    `}, 

`                    `{ 

`                      `"OddsType": 2, 

`                      `"OddsValues": { 

`                        `"A": "1.2", 

`                        `"B": "1.19", 

`                        `"C": "1.17", 

`                        `"D": "1.16", 

`                        `"E": "1.14", 

`                        `"F": "1.13", 

`                        `"G": "1.09" 

`                      `} 

`                    `}, 

`                    `{ 

`                      `"OddsType": 3, 

`                      `"OddsValues": { 

`                        `"A": "2.2", 

`                        `"B": "2.19", 

`                        `"C": "2.17", 

`                        `"D": "2.16", 

`                        `"E": "2.14", 

`                        `"F": "2.13", 

`                        `"G": "2.09" 

`                      `} 

`                    `}, 

`                    `{ 

`                      `"OddsType": 4, 

`                      `"OddsValues": { 

`                        `"A": "1.2",                         "B": "1.19",                         "C": "1.17",                         "D": "1.16",                         "E": "1.14",                         "F": "1.13",                         "G": "1.09"                       } 

`                    `} 

`                  `] 

`                `} 

`              `] 

`            `} 

`          `] 

`        `}, 

`        `{ 

`          `"OpenParlay": true, 

`          `"IsLive": true, 

`          `"Market": 3, 

`          `"HasVisualization": false, 

`          `"HasStatistic": false, 

`          `"BREventId": null, 

`          `"TotalMarketLineCount": 0, 

`          `"IsPopular": false, 

`          `"Season": 0, 

`          `"MatchDay": 0, 

`          `"EventId": 6013108, 

`          `"EventStatusId": 1, 

`          `"OrderNumber": 9999, 

`          `"EventDate": "2019-07-04T21:00:00.0000000-04:00",           "GroundTypeId": 1, 

`          `"EventGroupId": 318862, 

`          `"EventGroupTypeId": 2, 

`          `"HomeTeamId": 13839, 

`          `"HomeTeam": "FC Dallas - No. of Corners", 

`          `"AwayTeamId": 19077, 

`          `"AwayTeam": "Washington D.C. United - No. of Corners", 

`          `"RBTime": "2H 492:15", 

`          `"RBTimeStatus": 0, 

`          `"HomeScore": 5, 

`          `"AwayScore": 3, 

`          `"HomeRedCard": 0, 

`          `"AwayRedCard": 0, 

`          `"IsBetTradeOpen": false, 

`          `"LiveStreamingUrl": [], 

`          `"RelatedScores": [ 

`            `{ 

`              `"EventGroupTypeId": 1, 

`              `"HomeScore": 2, 

`              `"AwayScore": 0 

`            `} 

`          `], 

`          `"Competition": { 

`            `"CompetitionId": 453, 

`            `"CompetitionName": "USA Major League Soccer - Specials",             "PMOrderNumber": 0, 

`            `"RBOrderNumber": 0 

`          `}, 

`          `"MarketLines": [] 

`        `}, 

`        `{ 

`          `"OpenParlay": true, 

`          `"IsLive": true, 

`          `"Market": 3, 

`          `"HasVisualization": false, 

`          `"HasStatistic": false, 

`          `"BREventId": null, 

`          `"TotalMarketLineCount": 0, 

`          `"IsPopular": false, 

`          `"Season": 0, 

`          `"MatchDay": 0, 

`          `"EventId": 6013414, 

`          `"EventStatusId": 1, 

`          `"OrderNumber": 9999, 

`          `"EventDate": "2019-07-04T20:15:00.0000000-04:00",           "GroundTypeId": 1, 

`          `"EventGroupId": 319503, 

`          `"EventGroupTypeId": 1, 

`          `"HomeTeamId": 209229, 

`          `"HomeTeam": "Independiente del Valle.", 

`          `"AwayTeamId": 1448, 

`          `"AwayTeam": "Deportivo Cuenca", 

`          `"RBTime": "2H 547:37", 

`          `"RBTimeStatus": 0, 

`          `"HomeScore": 2, 

`          `"AwayScore": 0, 

`          `"HomeRedCard": 0, 

`          `"AwayRedCard": 0, 

`          `"IsBetTradeOpen": false, 

`          `"LiveStreamingUrl": [], 

`          `"RelatedScores": null, 

`          `"Competition": { 

`            `"CompetitionId": 329, 

`            `"CompetitionName": "Ecuador Serie A", 

`            `"PMOrderNumber": 2, 

`            `"RBOrderNumber": 2 

`          `}, 

`          `"MarketLines": [] 

`        `} 

`      `] 

`    `} 

`  `], 

`  `"TempDelta": null, 

`  `"Delta": 190705062603461.0, 

`  `"ServerTime": "2019-07-05T06:26:03.4663591-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

4. **GETDELTAEVENTINFOMBT**索取 DELTA 赛事和主要玩法详情** 

描述** 

此 API 根据请求参数中指定的特定准则, 常用于检索为特定体育所提供的所有赛事相关 的赛事及主要玩法赔率信息的 Delta 

访问频率限制: 早盘 (5 分钟一次), 今日 (1 分钟一次), 滚球 (10 秒一次) 

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|SportId |Int |Yes |<p>. 参考附录3.3. </p><p>指出体育项目</p>|
|Market |Int |Yes |<p>指出“早盘”、“今日”或者“滚球”的盘口 1 = 早盘 </p><p>2 = 今日 </p><p>3 = 滚球 </p><p>在早上（上午 9 点至下午 12 点），今日 包括早盘（直至上午 12 点）的赛事。 </p><p>盘口将</p>|
|Delta |Double |Yes |<p>Delta 版本 </p><p>格式：yyMMddHHmmssfff 范例: 171219001225452 </p>|
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟|
响应** 



|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|DeltaChanges |List |No |赛事清单 |
|- EventId |Int |No |赛事特定ID. |
|- Action |Int |No |<p>Delta 操作. </p><p>0 = 当根据已提交的 操作将被返回. </p><p>Delta版本插入每场新或更改赛事时 Delta版本移除每场现有赛事时操作</p><p>1 = 当根据已提交的 将被返回. </p>|
|- SportId |Int |No |<p>ID. 参考附录. </p><p>指出体育项目</p>|
|- EventTypeId |Int |No |<p>指出赛事属于定时赛事（普通）或优胜冠军赛事 1 = 定时赛事 </p><p>2 = 优胜冠军 </p>|
|- Values ||Yes |Delta 变化值 |
|Delta |Doubl e |Yes |<p>Delta 版本。 </p><p>Delta 值在 5 分钟后过期。 对应于各自的 SportId 和 Market。 格式：yyMMddHHmmssfff </p><p>范例: 171219001225452 </p>|
|StatusCode |Int |No |指出请求状态编码|
StatusDesc  String  No  状态编码的描述含义 状态编码![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.006.png)![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.007.png)** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID |
|**332** |盘口无效 |
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 7: GetDeltaEventInfoMBT Request* 

{ 

`  `"SportId": 7, 

`  `"Market": 1, 

`  `"TimeStamp": "{{timestamp}}",   "Delta": 191107030834631.0 

} 

请求** 

*Table 8: GetDeltaEventInfoMBT Response* 

{ 

`  `"DeltaChanges": [ 

`    `{ 

`      `"EventId": 6943367, 

`      `"Action": 0, 

`      `"SportId": 7, 

`      `"EventTypeId": 1, 

`      `"Value": "[{\"SportId\":7,\"SportName\":\"Badminton\",\"OrderNumber\":7,\"Events\":[{\"OpenParlay\":false,\"IsLi ve\":true,\"Market\":1,\"HasVisualization\":false,\"HasStatistic\":false,\"BREventId\":0,\"TotalMarketLineC ount\":3,\"IsPopular\":false,\"Season\":0,\"MatchDay\":0,\"IsFavourite\":false,\"EventId\":6943367,\"Even tStatusId\":1,\"OrderNumber\":9999,\"EventDate\":\"2019-12-01T00:02:00.0000000- 04:00\",\"GroundTypeId\":1,\"EventGroupId\":0,\"EventGroupTypeId\":0,\"HomeTeamId\":257220,\"Hom eTeam\":\"Badminton 6046530\",\"AwayTeamId\":239637,\"AwayTeam\":\"A\",\"RBTime\":null,\"RBTimeStatus\":0,\"HomeScor e\":null,\"AwayScore\":null,\"HomeRedCard\":null,\"AwayRedCard\":null,\"IsBetTradeOpen\":false,\"LiveSt reamingUrl\":[],\"RelatedScores\":null,\"Competition\":{\"CompetitionId\":17527,\"CompetitionName\":\" MockCompetition yepeng\",\"PMOrderNumber\":9999,\"RBOrderNumber\":9999,\"MarketLines\":[{\"MarketlineId\":105850 244,\"BetTypeId\":1,\"BetTypeName\":\"Handicap\",\"PeriodId\":1,\"PeriodName\":\"Full Time\",\"MarketLineLevel\":1,\"MarketlineStatusId\":1,\"IsLocked\":false,\"WagerSelections\":[{\"WagerSe lectionId\":2460051295,\"SelectionId\":1,\"SelectionName\":\"Home\",\"Handicap\":0.0,\"Specifiers\":null, \"OddsType\":1,\"Odds\":0.43,\"OddsList\":[{\"OddsType\":1,\"OddsValues\":{\"A\":\"0.43\",\"B\":\"0.42\" ,\"C\":\"0.41\",\"D\":\"0.4\",\"E\":\"0.39\",\"F\":\"0.38\",\"G\":\"0.35\"}},{\"OddsType\":2,\"OddsValues\": {\"A\":\"0.43\",\"B\":\"0.42\",\"C\":\"0.41\",\"D\":\"0.4\",\"E\":\"0.39\",\"F\":\"0.38\",\"G\":\"0.35\"}},{\" OddsType\":3,\"OddsValues\":{\"A\":\"1.43\",\"B\":\"1.42\",\"C\":\"1.41\",\"D\":\"1.4\",\"E\":\"1.39\",\"F\ ":\"1.38\",\"G\":\"1.35\"}},{\"OddsType\":4,\"OddsValues\":{\"A\":\"-2.33\",\"B\":\"-2.39\",\"C\":\"- 2.44\",\"D\":\"-2.5\",\"E\":\"-2.57\",\"F\":\"-2.64\",\"G\":\"- 2.86\"}}]},{\"WagerSelectionId\":2460051296,\"SelectionId\":2,\"SelectionName\":\"Away\",\"Handicap\": 0.0,\"Specifiers\":null,\"OddsType\":1,\"Odds\":- 0.53,\"OddsList\":[{\"OddsType\":1,\"OddsValues\":{\"A\":\"-0.53\",\"B\":\"-0.54\",\"C\":\"- 0.55\",\"D\":\"-0.56\",\"E\":\"-0.57\",\"F\":\"-0.58\",\"G\":\"- 0.61\"}},{\"OddsType\":2,\"OddsValues\":{\"A\":\"1.88\",\"B\":\"1.85\",\"C\":\"1.81\",\"D\":\"1.78\",\"E\": \"1.75\",\"F\":\"1.72\",\"G\":\"1.63\"}},{\"OddsType\":3,\"OddsValues\":{\"A\":\"2.88\",\"B\":\"2.85\",\"C\ ":\"2.81\",\"D\":\"2.78\",\"E\":\"2.75\",\"F\":\"2.72\",\"G\":\"2.63\"}},{\"OddsType\":4,\"OddsValues\":{\" A\":\"1.88\",\"B\":\"1.85\",\"C\":\"1.81\",\"D\":\"1.78\",\"E\":\"1.75\",\"F\":\"1.72\",\"G\":\"1.63\"}}]}]},{\ "MarketlineId\":105850247,\"BetTypeId\":2,\"BetTypeName\":\"Over/Under\",\"PeriodId\":1,\"PeriodNam e\":\"Full 

Time\",\"MarketLineLevel\":1,\"MarketlineStatusId\":1,\"IsLocked\":false,\"WagerSelections\":[{\"WagerSe lectionId\":2462220095,\"SelectionId\":3,\"SelectionName\":\"Over\",\"Handicap\":1.5,\"Specifiers\":null,\ "OddsType\":1,\"Odds\":0.4,\"OddsList\":[{\"OddsType\":1,\"OddsValues\":{\"A\":\"0.4\",\"B\":\"0.39\",\" C\":\"0.38\",\"D\":\"0.37\",\"E\":\"0.36\",\"F\":\"0.35\",\"G\":\"0.32\"}},{\"OddsType\":2,\"OddsValues\":{ \"A\":\"0.4\",\"B\":\"0.39\",\"C\":\"0.38\",\"D\":\"0.37\",\"E\":\"0.36\",\"F\":\"0.35\",\"G\":\"0.32\"}},{\"O ddsType\":3,\"OddsValues\":{\"A\":\"1.4\",\"B\":\"1.39\",\"C\":\"1.38\",\"D\":\"1.37\",\"E\":\"1.36\",\"F\": \"1.35\",\"G\":\"1.32\"}},{\"OddsType\":4,\"OddsValues\":{\"A\":\"-2.5\",\"B\":\"-2.57\",\"C\":\"- 2.64\",\"D\":\"-2.71\",\"E\":\"-2.78\",\"F\":\"-2.86\",\"G\":\"- 3.13\"}}]},{\"WagerSelectionId\":2462220096,\"SelectionId\":4,\"SelectionName\":\"Under\",\"Handicap\": 1.5,\"Specifiers\":null,\"OddsType\":1,\"Odds\":- 0.5,\"OddsList\":[{\"OddsType\":1,\"OddsValues\":{\"A\":\"-0.5\",\"B\":\"-0.51\",\"C\":\"-0.52\",\"D\":\"- 0.53\",\"E\":\"-0.54\",\"F\":\"-0.55\",\"G\":\"- 0.58\"}},{\"OddsType\":2,\"OddsValues\":{\"A\":\"2\",\"B\":\"1.96\",\"C\":\"1.92\",\"D\":\"1.88\",\"E\":\"1 .85\",\"F\":\"1.81\",\"G\":\"1.72\"}},{\"OddsType\":3,\"OddsValues\":{\"A\":\"3\",\"B\":\"2.96\",\"C\":\"2.9 2\",\"D\":\"2.88\",\"E\":\"2.85\",\"F\":\"2.81\",\"G\":\"2.72\"}},{\"OddsType\":4,\"OddsValues\":{\"A\":\"2 \",\"B\":\"1.96\",\"C\":\"1.92\",\"D\":\"1.88\",\"E\":\"1.85\",\"F\":\"1.81\",\"G\":\"1.72\"}}]}]},{\"Marketlin eId\":105850251,\"BetTypeId\":5,\"BetTypeName\":\"Odd / Even\",\"PeriodId\":1,\"PeriodName\":\"Full Time\",\"MarketLineLevel\":1,\"MarketlineStatusId\":1,\"IsLocked\":false,\"WagerSelections\":[{\"WagerSe lectionId\":2460051301,\"SelectionId\":10,\"SelectionName\":\"Odd\",\"Handicap\":null,\"Specifiers\":null, \"OddsType\":1,\"Odds\":0.6,\"OddsList\":[{\"OddsType\":1,\"OddsValues\":{\"A\":\"0.6\",\"B\":\"0.59\",\" C\":\"0.58\",\"D\":\"0.57\",\"E\":\"0.56\",\"F\":\"0.55\",\"G\":\"0.52\"}},{\"OddsType\":2,\"OddsValues\":{ \"A\":\"0.6\",\"B\":\"0.59\",\"C\":\"0.58\",\"D\":\"0.57\",\"E\":\"0.56\",\"F\":\"0.55\",\"G\":\"0.52\"}},{\"O ddsType\":3,\"OddsValues\":{\"A\":\"1.6\",\"B\":\"1.59\",\"C\":\"1.58\",\"D\":\"1.57\",\"E\":\"1.56\",\"F\": \"1.55\",\"G\":\"1.52\"}},{\"OddsType\":4,\"OddsValues\":{\"A\":\"-1.67\",\"B\":\"-1.7\",\"C\":\"-

1.73\",\"D\":\"-1.76\",\"E\":\"-1.79\",\"F\":\"-1.82\",\"G\":\"- 1.93\"}}]},{\"WagerSelectionId\":2460051302,\"SelectionId\":11,\"SelectionName\":\"Even\",\"Handicap\": null,\"Specifiers\":null,\"OddsType\":1,\"Odds\":- 0.7,\"OddsList\":[{\"OddsType\":1,\"OddsValues\":{\"A\":\"-0.7\",\"B\":\"-0.71\",\"C\":\"-0.72\",\"D\":\"- 0.73\",\"E\":\"-0.74\",\"F\":\"-0.75\",\"G\":\"- 0.78\"}},{\"OddsType\":2,\"OddsValues\":{\"A\":\"1.42\",\"B\":\"1.4\",\"C\":\"1.38\",\"D\":\"1.36\",\"E\":\ "1.35\",\"F\":\"1.33\",\"G\":\"1.28\"}},{\"OddsType\":3,\"OddsValues\":{\"A\":\"2.42\",\"B\":\"2.4\",\"C\":\ "2.38\",\"D\":\"2.36\",\"E\":\"2.35\",\"F\":\"2.33\",\"G\":\"2.28\"}},{\"OddsType\":4,\"OddsValues\":{\"A\" :\"1.42\",\"B\":\"1.4\",\"C\":\"1.38\",\"D\":\"1.36\",\"E\":\"1.35\",\"F\":\"1.33\",\"G\":\"1.28\"}}]}]}]}]}]" 

`    `} 

`  `], 

`  `"Delta": 191107034556661.0, 

`  `"ServerTime": "2019-11-07T03:46:07.9207717-04:00", 

`  `"StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.008.png)

5. **GETMLINFOOBT**索取其他玩法资料** 

描述** 

此 API 根据请求参数中指定的特定准则, 常用于检索为特定体育所提供的所有其他玩法 赔率信息. GetDeltaMLInfoOBT API 用于检索更新的 delta 更改。 

访问频率限制(相同的参数): 1 分钟一次 请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|SportId |Int |Yes |<p>. 参考附录3.3. </p><p>指出体育项目</p>|
|Market |Int |Yes |<p>指出“早盘”、“今日”或者“滚球”的盘口 1 = 早盘 </p><p>2 = 今日 </p><p>3 = 滚球 </p>|
|LanguageCode |String |No |<p>. </p><p>为本地名称返回的语言</p>|
|TimeStamp |String |Yes |<p>5分钟. </p><p>新生成的时间戳将持续</p>|
响应** 



|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|Sports |List |No |体育项目清单|
|- SportId |Int |No |<p>. 参考附录3.3. </p><p>指出体育项目</p>|
|- Events |List |No |赛事清单 |
|-- EventId |Long |No |<p>` `ID </p><p>赛事的特定</p>|
|-- Market |Int |No |<p>指出“早盘”、“今日”或者“滚球”的盘口 1 = 早盘 </p><p>2 = 今日 </p><p>3 = 滚球 </p>|
|-- MarketLines |List |Yes |盘口清单 |
|--- MarketLineId |Long |No |<p>` `ID </p><p>盘口的特定</p>|
|--- BetTypeId |Int |No |投注类型 ID |
|--- BetTypeName |String |No |运营商投注类型的默认语言|
|--- PeriodId |Int |No |<p>比赛时段 ID  1 = 全场 </p><p>2 = 上半场 3 = 下半场 </p>|

|--- PeriodName |String |No |运营商比赛时段的默认语言|
| - | - | - | - |
|--- MarketLineLevel |Int |No |盘口级别 |
|--- MarketlineStatusI d |Int |No |<p>. </p><p>指出盘口状态 1 = 开盘 </p><p>2 = 关盘 </p>|
|--- IsLocked |Boolea n |No |指出盘口是否封盘|
|--- WagerSelections |List |No |投注选项清单|
|---- WagerSelectionId |Long |No |<p>` `ID </p><p>投注选项的特定</p>|
|---- SelectionId |Int |No |<p>` `ID </p><p>投注类型选项</p>|
|---- SelectionName |String |Yes |运营商投注类型选项的默认语言|
|---- Handicap |Float |Yes |<p>该项目仅适用于让球盘和大小盘.  对于让球盘，负值等于选项在让分，正值相反。 对于大小盘，就是大于或小于的得分比较 如果是空值等于该让分不适用于该盘口或投注类型。</p><p>。 </p>|
|---- OddsList |List |No |赔率清单 |
|----- OddsType |Int |No |赔率类型 1 = 马来盘 2 = 香港盘 3 = 欧洲盘 4 = 印尼盘 |
|----- OddsValues |Float |No |选择赔率值|
|Delta |Doubl e |Yes |<p>Delta 版本 </p><p>格式：yyMMddHHmmssfff 范例: 171219001225452 </p>|
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID |
|**332** |盘口无效 |
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 9: GetMLInfoOBT Request* 

{ 

`  `"SportId": 1, 

`  `"Market": 1, 

`  `"TimeStamp": "dgFqE4m/R6hgyLu1T+AeY5IUfE3Vo6+GM05i2Lo636o=" } 

请求** 

*Table 10: GetMLInfoOBT Response* 

{ 

`    `"Sports": [ 

`        `{ 

`            `"SportId": 1, 

`            `"Events": [ 

`                `{ 

`                    `"EventId": 6971470, 

`                    `"MarketLines": [ 

`                        `{ 

`                            `"MarketlineId": 106459400, 

`                            `"BetTypeId": 13, 

`                            `"BetTypeName": "Winning Margin", 

`                            `"PeriodId": 1, 

`                            `"PeriodName": "Full Time", 

`                            `"MarketLineLevel": 1, 

`                            `"MarketlineStatusId": 1, 

`                            `"IsLocked": false, 

`                            `"WagerSelections": [ 

`                                `{ 

`                                    `"WagerSelectionId": 2462220609, 

`                                    `"SelectionId": 63, 

`                                    `"SelectionName": "Away Win by 1 Goal", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "variant=sr:winning\_margin:3+",                                     "OddsType": 3, 

`                                    `"Odds": 7.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "7.0000", 

`                                                `"B": "7.0000", 

`                                                `"C": "7.0000", 

`                                                `"D": "7.0000", 

`                                                `"E": "7.0000", 

`                                                `"F": "7.0000", 

`                                                `"G": "7.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220618, 

`                                    `"SelectionId": 60, 

`                                    `"SelectionName": "Home Win by 1 Goal", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "variant=sr:winning\_margin:3+",                                     "OddsType": 3, 

`                                    `"Odds": 3.5500, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "3.5500", 

`                                                `"B": "3.5500", 

`                                                `"C": "3.5500", 

`                                                `"D": "3.5500", 

`                                                `"E": "3.5500", 

`                                                `"F": "3.5500", 

`                                                `"G": "3.5500" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220458, 

`                                    `"SelectionId": 66, 

`                                    `"SelectionName": "Draw", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "variant=sr:winning\_margin:3+",                                     "OddsType": 3, 

`                                    `"Odds": 3.7000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "3.7000", 

`                                                `"B": "3.7000", 

`                                                `"C": "3.7000", 

`                                                `"D": "3.7000", 

`                                                `"E": "3.7000", 

`                                                `"F": "3.7000", 

`                                                `"G": "3.7000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220468, 

`                                    `"SelectionId": 61, 

`                                    `"SelectionName": "Home Win by 2 Goals", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "variant=sr:winning\_margin:3+",                                     "OddsType": 3, 

`                                    `"Odds": 4.6000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "4.6000", 

`                                                `"B": "4.6000", 

`                                                `"C": "4.6000", 

`                                                `"D": "4.6000", 

`                                                `"E": "4.6000", 

`                                                `"F": "4.6000", 

`                                                `"G": "4.6000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220481, 

`                                    `"SelectionId": 65, 

`                                    `"SelectionName": "Away Win by 3 or More Goals",                                     "Handicap": null, 

`                                    `"Specifiers": "variant=sr:winning\_margin:3+", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 50.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "50.0000", 

`                                                `"B": "50.0000", 

`                                                `"C": "50.0000", 

`                                                `"D": "50.0000", 

`                                                `"E": "50.0000", 

`                                                `"F": "50.0000", 

`                                                `"G": "50.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220517, 

`                                    `"SelectionId": 62, 

`                                    `"SelectionName": "Home Win by 3 or More Goals",                                     "Handicap": null, 

`                                    `"Specifiers": "variant=sr:winning\_margin:3+", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 4.8000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "4.8000", 

`                                                `"B": "4.8000", 

`                                                `"C": "4.8000", 

`                                                `"D": "4.8000", 

`                                                `"E": "4.8000", 

`                                                `"F": "4.8000", 

`                                                `"G": "4.8000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220562, 

`                                    `"SelectionId": 64, 

`                                    `"SelectionName": "Away Win by 2 Goals", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "variant=sr:winning\_margin:3+",                                     "OddsType": 3, 

`                                    `"Odds": 18.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "18.0000", 

`                                                `"B": "18.0000", 

`                                                `"C": "18.0000", 

`                                                `"D": "18.0000", 

`                                                `"E": "18.0000", 

`                                                `"F": "18.0000", 

`                                                `"G": "18.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `} 

`                            `] 

`                        `}, 

`                        `{ 

`                            `"MarketlineId": 106459502, 

`                            `"BetTypeId": 14, 

`                            `"BetTypeName": "1X2 and Over/Under", 

`                            `"PeriodId": 1, 

`                            `"PeriodName": "Full Time", 

`                            `"MarketLineLevel": 2, 

`                            `"MarketlineStatusId": 1, 

`                            `"IsLocked": false, 

`                            `"WagerSelections": [ 

`                                `{ 

`                                    `"WagerSelectionId": 2462220589, 

`                                    `"SelectionId": 70, 

`                                    `"SelectionName": "Draw & Over {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=2.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 13.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "13.0000", 

`                                                `"B": "13.0000", 

`                                                `"C": "13.0000", 

`                                                `"D": "13.0000", 

`                                                `"E": "13.0000", 

`                                                `"F": "13.0000", 

`                                                `"G": "13.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220599, 

`                                    `"SelectionId": 67, 

`                                    `"SelectionName": "Home & Under {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=2.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 4.1000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "4.1000", 

`                                                `"B": "4.1000", 

`                                                `"C": "4.1000", 

`                                                `"D": "4.1000", 

`                                                `"E": "4.1000", 

`                                                `"F": "4.1000", 

`                                                `"G": "4.1000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220434, 

`                                    `"SelectionId": 69, 

`                                    `"SelectionName": "Draw & Under {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=2.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 5.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "5.0000", 

`                                                `"B": "5.0000", 

`                                                `"C": "5.0000", 

`                                                `"D": "5.0000", 

`                                                `"E": "5.0000", 

`                                                `"F": "5.0000", 

`                                                `"G": "5.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220445, 

`                                    `"SelectionId": 68, 

`                                    `"SelectionName": "Home & Over {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=2.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 2.2700, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3,                                             "OddsValues": {                                                 "A": "2.2700",                                                 "B": "2.2700",                                                 "C": "2.2700",                                                 "D": "2.2700",                                                 "E": "2.2700",                                                 "F": "2.2700",                                                 "G": "2.2700"                                             } 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220525, 

`                                    `"SelectionId": 72, 

`                                    `"SelectionName": "Away & Over {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=2.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 8.2000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "8.2000", 

`                                                `"B": "8.2000", 

`                                                `"C": "8.2000", 

`                                                `"D": "8.2000", 

`                                                `"E": "8.2000", 

`                                                `"F": "8.2000", 

`                                                `"G": "8.2000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220551, 

`                                    `"SelectionId": 71, 

`                                    `"SelectionName": "Away & Under {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=2.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 11.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "11.0000", 

`                                                `"B": "11.0000", 

`                                                `"C": "11.0000", 

`                                                `"D": "11.0000", 

`                                                `"E": "11.0000", 

`                                                `"F": "11.0000", 

`                                                `"G": "11.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `} 

`                            `] 

`                        `}, 

`                        `{ 

`                            `"MarketlineId": 106459403, 

`                            `"BetTypeId": 14, 

`                            `"BetTypeName": "1X2 and Over/Under", 

`                            `"PeriodId": 3, 

`                            `"PeriodName": "2nd Half", 

`                            `"MarketLineLevel": 1, 

`                            `"MarketlineStatusId": 1, 

`                            `"IsLocked": false, 

`                            `"WagerSelections": [ 

`                                `{ 

`                                    `"WagerSelectionId": 2462220607, 

`                                    `"SelectionId": 68, 

`                                    `"SelectionName": "Home & Over {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=1.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 3.1500, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "3.1500", 

`                                                `"B": "3.1500", 

`                                                `"C": "3.1500", 

`                                                `"D": "3.1500", 

`                                                `"E": "3.1500", 

`                                                `"F": "3.1500", 

`                                                `"G": "3.1500" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220614, 

`                                    `"SelectionId": 72, 

`                                    `"SelectionName": "Away & Over {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=1.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 11.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "11.0000", 

`                                                `"B": "11.0000", 

`                                                `"C": "11.0000", 

`                                                `"D": "11.0000", 

`                                                `"E": "11.0000", 

`                                                `"F": "11.0000", 

`                                                `"G": "11.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220459, 

`                                    `"SelectionId": 71, 

`                                    `"SelectionName": "Away & Under {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=1.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 7.6000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "7.6000", 

`                                                `"B": "7.6000", 

`                                                `"C": "7.6000", 

`                                                `"D": "7.6000", 

`                                                `"E": "7.6000", 

`                                                `"F": "7.6000", 

`                                                `"G": "7.6000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220467, 

`                                    `"SelectionId": 67, 

`                                    `"SelectionName": "Home & Under {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=1.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 3.9000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "3.9000", 

`                                                `"B": "3.9000", 

`                                                `"C": "3.9000", 

`                                                `"D": "3.9000", 

`                                                `"E": "3.9000", 

`                                                `"F": "3.9000", 

`                                                `"G": "3.9000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220513, 

`                                    `"SelectionId": 70, 

`                                    `"SelectionName": "Draw & Over {total}", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "total=1.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 6.0000, 

IPIS Mobile

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3,                                             "OddsValues": {                                                 "A": "6.0000",                                                 "B": "6.0000",                                                 "C": "6.0000",                                                 "D": "6.0000",                                                 "E": "6.0000",                                                 "F": "6.0000",                                                 "G": "6.0000"                                             } 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220554, 

`                                    `"SelectionId": 69, 

`                                    `"SelectionName": "Draw & Under {total}",                                     "Handicap": null, 

`                                    `"Specifiers": "total=1.5", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 4.3000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "4.3000", 

`                                                `"B": "4.3000", 

`                                                `"C": "4.3000", 

`                                                `"D": "4.3000", 

`                                                `"E": "4.3000", 

`                                                `"F": "4.3000", 

`                                                `"G": "4.3000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `} 

`                            `] 

`                        `}, 

`                        `{ 

`                            `"MarketlineId": 106459483, 

`                            `"BetTypeId": 62, 

`                            `"BetTypeName": "Multiscores", 

`                            `"PeriodId": 1, 

`                            `"PeriodName": "Full Time", 

`                            `"MarketLineLevel": 1, 

`                            `"MarketlineStatusId": 1, 

`                            `"IsLocked": false, 

`                            `"WagerSelections": [ 

`                                `{ 

`                                    `"WagerSelectionId": 2462220602, 

`                                    `"SelectionId": 231, 

`                                    `"SelectionName": "2-1 / 3-1 / 4-1", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 4.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "4.0000", 

`                                                `"B": "4.0000", 

`                                                `"C": "4.0000", 

`                                                `"D": "4.0000", 

`                                                `"E": "4.0000", 

`                                                `"F": "4.0000", 

`                                                `"G": "4.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220624, 

`                                    `"SelectionId": 235, 

`                                    `"SelectionName": "Any Other Home Win Score",                                     "Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 40.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "40.0000", 

`                                                `"B": "40.0000", 

`                                                `"C": "40.0000", 

`                                                `"D": "40.0000", 

`                                                `"E": "40.0000", 

`                                                `"F": "40.0000", 

`                                                `"G": "40.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220627, 

`                                    `"SelectionId": 232, 

`                                    `"SelectionName": " 1-2 / 1-3 / 1-4",                                     "Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 11.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "11.0000", 

`                                                `"B": "11.0000", 

`                                                `"C": "11.0000", 

`                                                `"D": "11.0000", 

`                                                `"E": "11.0000", 

`                                                `"F": "11.0000", 

`                                                `"G": "11.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220446, 

`                                    `"SelectionId": 230, 

`                                    `"SelectionName": "0-4 / 0-5 / 0-6", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 101.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "101.0000", 

`                                                `"B": "101.0000", 

`                                                `"C": "101.0000", 

`                                                `"D": "101.0000", 

`                                                `"E": "101.0000", 

`                                                `"F": "101.0000", 

`                                                `"G": "101.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220460, 

`                                    `"SelectionId": 233, 

`                                    `"SelectionName": "3-2 / 4-2 / 4-3 / 5-1",                                     "Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 12.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "12.0000", 

`                                                `"B": "12.0000", 

`                                                `"C": "12.0000", 

`                                                `"D": "12.0000", 

`                                                `"E": "12.0000", 

`                                                `"F": "12.0000", 

`                                                `"G": "12.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220473, 

`                                    `"SelectionId": 234, 

`                                    `"SelectionName": "2-3 / 2-4 / 3-4 / 1-5",                                     "Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 35.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "35.0000", 

`                                                `"B": "35.0000", 

`                                                `"C": "35.0000", 

`                                                `"D": "35.0000", 

`                                                `"E": "35.0000", 

`                                                `"F": "35.0000", 

`                                                `"G": "35.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220494,                                     "SelectionId": 228, 

`                                    `"SelectionName": "0-1 / 0-2 / 0-3",                                     "Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 8.8000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "8.8000", 

`                                                `"B": "8.8000", 

`                                                `"C": "8.8000", 

`                                                `"D": "8.8000", 

`                                                `"E": "8.8000", 

`                                                `"F": "8.8000", 

`                                                `"G": "8.8000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220496,                                     "SelectionId": 229, 

`                                    `"SelectionName": "4-0 / 5-0 / 6-0",                                     "Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 15.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "15.0000", 

`                                                `"B": "15.0000", 

`                                                `"C": "15.0000", 

`                                                `"D": "15.0000", 

`                                                `"E": "15.0000", 

`                                                `"F": "15.0000", 

`                                                `"G": "15.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220533, 

`                                    `"SelectionId": 237, 

`                                    `"SelectionName": "Any Draw Score", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 3.4000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "3.4000", 

`                                                `"B": "3.4000", 

`                                                `"C": "3.4000", 

`                                                `"D": "3.4000", 

`                                                `"E": "3.4000", 

`                                                `"F": "3.4000", 

`                                                `"G": "3.4000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220545, 

`                                    `"SelectionId": 227, 

`                                    `"SelectionName": "1-0 / 2-0 / 3-0", 

`                                    `"Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 2.9000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "2.9000", 

`                                                `"B": "2.9000", 

`                                                `"C": "2.9000", 

`                                                `"D": "2.9000", 

`                                                `"E": "2.9000", 

`                                                `"F": "2.9000", 

`                                                `"G": "2.9000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `}, 

`                                `{ 

`                                    `"WagerSelectionId": 2462220573, 

`                                    `"SelectionId": 236, 

`                                    `"SelectionName": "Any Other Away Win Score",                                     "Handicap": null, 

`                                    `"Specifiers": "", 

`                                    `"OddsType": 3, 

`                                    `"Odds": 101.0000, 

`                                    `"OddsList": [ 

`                                        `{ 

`                                            `"OddsType": 3, 

`                                            `"OddsValues": { 

`                                                `"A": "101.0000",                                                 "B": "101.0000",                                                 "C": "101.0000",                                                 "D": "101.0000",                                                 "E": "101.0000",                                                 "F": "101.0000",                                                 "G": "101.0000" 

`                                            `} 

`                                        `} 

`                                    `] 

`                                `} 

`                            `] 

`                        `} 

`                    `] 

`                `} 

`            `] 

`        `} 

`    `], 

`    `"Delta": 191107030348096.0, 

`    `"ServerTime": "2019-11-07T03:03:48.0964840-04:00",     "StatusCode": 100, 

`    `"StatusDesc": "Success" 

} 

6. **GETDELTAMLINFOOBT**索取 DELTA 其他玩法详情** 

描述** 

此 API 根据请求参数中指定的特定准则, 常用于检索为特定体育所提供的所有其他玩法 赔率信息的 Delta 

访问频率限制: 早盘 (5 分钟一次), 今日 (1 分钟一次), 滚球 (10 秒一次) 

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|SportId |Int |Yes |<p>. 参考附录3.3. </p><p>指出体育项目</p>|
|Market |Int |Yes |指出“早盘”、“今日”或者“滚球”的盘口 1 = 早盘 |

IPIS Mobile



||||2 = 今日 3 = 滚球 |
| :- | :- | :- | - |
|LanguageCode |String |No |<p>. </p><p>为本地名称返回的语言</p>|
|Delta |Double |Yes |<p>Delta 版本 </p><p>格式：yyMMddHHmmssfff 范例: 171219001225452 </p>|
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟|
响应** 



|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|DeltaChanges |List |No |赛事清单 |
|- EventId |Int |No |赛事特定ID. |
|- Action |Int |No |<p>Delta 操作. </p><p>3 = 当根据已提交的Delta版本插入/更新新盘口或更改 现有的盘口时操作将被返回. </p><p>4 = 当根据已提交的Delta版本移除每项现有盘口时操作 将被返回. </p><p>13 =当根据已提交的Delta版本移除赛事所有盘口时操作 将被返回. </p>|
|- SportId |Int |No |<p>ID. 参考附录. </p><p>指出体育项目</p>|
|- EventTypeId |Int |No |<p>指出赛事属于定时赛事（普通）或优胜冠军赛事 1 = 定时赛事 </p><p>2 = 优胜冠军 </p>|
|- Values ||Yes |Delta 变化值 |
|Delta |Doubl e |Yes |<p>Delta 版本 </p><p>格式：yyMMddHHmmssfff 范例: 171219001225452 </p>|
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID |
|**332** |盘口无效 |
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|

范例** 
IPIS Mobile

*Table 11: GetDeltaMLInfoOBT Request* 

{ 

`    `"SportId": 1, 

`    `"Market": 1, 

`    `"Delta": 191107034131791, 

`    `"TimeStamp": "{{timestamp}}" } 

请求** 

*Table 12: GetDeltaMLInfoOBT Response* 

{ 

`  `"DeltaChanges": [ 

`    `{ 

`      `"EventId": 6971470, 

`      `"Action": 3, 

`      `"SportId": 1, 

`      `"EventTypeId": 1, 

`      `"Value": "[{\"MarketlineId\":106459502,\"BetTypeId\":14,\"BetTypeName\":\"1X2 and Over/Under\",\"PeriodId\":1,\"PeriodName\":\"Full Time\",\"MarketLineLevel\":2,\"MarketlineStatusId\":1,\"IsLocked\":false,\"WagerSelections\":[{\"WagerSe lectionId\":2462220589,\"SelectionId\":70,\"SelectionName\":\"Draw & Over {total}\",\"Handicap\":null,\"Specifiers\":\"total=2.5\",\"OddsType\":3,\"Odds\":13.0000,\"OddsList\":[{\"O ddsType\":3,\"OddsValues\":{\"A\":\"13.0000\",\"B\":\"13.0000\",\"C\":\"13.0000\",\"D\":\"13.0000\",\"E\ ":\"13.0000\",\"F\":\"13.0000\",\"G\":\"13.0000\"}}]},{\"WagerSelectionId\":2462220599,\"SelectionId\":6 7,\"SelectionName\":\"Home & Under {total}\",\"Handicap\":null,\"Specifiers\":\"total=2.5\",\"OddsType\":3,\"Odds\":4.1000,\"OddsList\":[{\"Od dsType\":3,\"OddsValues\":{\"A\":\"4.1000\",\"B\":\"4.1000\",\"C\":\"4.1000\",\"D\":\"4.1000\",\"E\":\"4. 1000\",\"F\":\"4.1000\",\"G\":\"4.1000\"}}]},{\"WagerSelectionId\":2462220434,\"SelectionId\":69,\"Select ionName\":\"Draw & Under {total}\",\"Handicap\":null,\"Specifiers\":\"total=2.5\",\"OddsType\":3,\"Odds\":5.0000,\"OddsList\":[{\"Od dsType\":3,\"OddsValues\":{\"A\":\"5.0000\",\"B\":\"5.0000\",\"C\":\"5.0000\",\"D\":\"5.0000\",\"E\":\"5. 0000\",\"F\":\"5.0000\",\"G\":\"5.0000\"}}]},{\"WagerSelectionId\":2462220445,\"SelectionId\":68,\"Select

ionName\":\"Home & Over {total}\",\"Handicap\":null,\"Specifiers\":\"total=2.5\",\"OddsType\":3,\"Odds\":2.2700,\"OddsList\":[{\"Od dsType\":3,\"OddsValues\":{\"A\":\"2.2700\",\"B\":\"2.2700\",\"C\":\"2.2700\",\"D\":\"2.2700\",\"E\":\"2. 2700\",\"F\":\"2.2700\",\"G\":\"2.2700\"}}]},{\"WagerSelectionId\":2462220525,\"SelectionId\":72,\"Select ionName\":\"Away & Over {total}\",\"Handicap\":null,\"Specifiers\":\"total=2.5\",\"OddsType\":3,\"Odds\":8.2000,\"OddsList\":[{\"Od dsType\":3,\"OddsValues\":{\"A\":\"8.2000\",\"B\":\"8.2000\",\"C\":\"8.2000\",\"D\":\"8.2000\",\"E\":\"8. 2000\",\"F\":\"8.2000\",\"G\":\"8.2000\"}}]},{\"WagerSelectionId\":2462220551,\"SelectionId\":71,\"Select ionName\":\"Away & Under {total}\",\"Handicap\":null,\"Specifiers\":\"total=2.5\",\"OddsType\":3,\"Odds\":11.0000,\"OddsList\":[{\"O ddsType\":3,\"OddsValues\":{\"A\":\"11.0000\",\"B\":\"11.0000\",\"C\":\"11.0000\",\"D\":\"11.0000\",\"E\ ":\"11.0000\",\"F\":\"11.0000\",\"G\":\"11.0000\"}}]}]}]" 

`    `}, 

`  `], 

`  `"Delta": 191107034131791.0, 

`  `"ServerTime": "2019-11-07T03:43:09.6018035-04:00", 

`  `"StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 
IPIS Mobile

![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.008.png)

7. **GETSELECTEDEVENTINFO** 索取赛事选项资料

描述** 

此 API根据所提交的赛事 ID 清单用于检索已选赛事及赔率信息. 有关赛事并属于同一组赛 事 ID 也将同时被返回. 

访问频率限制: 早盘 (20 秒一次), 今日 (20 秒一次), 滚球 (10 秒一次) 

请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|SportId |Int |Yes |指出体育项目. 参考附录3.3|
|EventIds |List |Yes |检索赛事 ID |
|BetTypeIds |List of Int |No |指出返回的投注类型|
|PeriodIds |List of Int |No |<p>筛选时段的ID清单.  <p>1 = FT 全场 <p>2 = 1H 上半场 <p>3 = 2H 下半场 |
|OddsType |Int |Yes |赔率类型 <p>1 = 马来盘 <p>2 = 香港盘 <p>3 = 欧洲盘 <p>4 = 印尼盘 |
|IsCombo |Boolean |Yes |指出请求是连串过关赛事或者非连串过关赛事 |
|IncludeGroup Events |Boolean |Yes |指出属于相同赛事组别ID的其他赛事是否同 时被返回. |
|Token |String |No |会员令牌. |
|MemberCode |String |No |用户名. |
|LanguageCode |String |No |为本地名称返回的语言.|
|TimeStamp |String |Yes  |新生成的时间戳将持续 5 分钟|

响应** 

该响应与 GetEventInfoMBT 响应一致. 


IPIS Mobile

状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID |
|**330** |<p>` `ID </p><p>无效赛事类型</p>|
|**334** |无效赛事 ID |
|**380** |无可选盘口|
|**400** |系统错误 |
|**501** |用户无访问权限|
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 13: GetSelectedEventInfo Request* 

{ 

` `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",    "SportId":1,                         

` `"EventIds":[6014772],     

` `"IncludeGroupEvents": "True"  , 

` `"OddsType":1, 

` `"Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee",               

`  `"MemberCode":"spkoormb01"       

} 

8. **GETVSEVENTINFO** 索取虚拟赛事列表** 

描述** 

此 API 用于检索相关虚拟赛事及赔率信息. 访问频率限制:  

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|SportId |Int |Yes |<p>ID. 参考附录. </p><p>指出体育项目</p>|
|Season |Int |Yes |赛季指标. (Betradar视频小部件) 仅适用于Sport ID = 39, 43, 44  和 46 |
|MatchDay |Int |Yes |赛日指标. (Betradar视频小部件) 仅适用于Sport ID = 39, 43, 44  和 46 |
|BREventIds |List of Int |No |Bet Radar 赛事ID。仅适用于Sport ID = 44和46 |
|OddsType |Int |Yes |赔率类型 1 = 马来盘 2 = 香港盘 3 = 欧洲盘 4 = 印尼盘 |
|BetTypeIds |List of Int |No |<p>ID清单. </p><p>筛选赛事投注类型</p>|
|PeriodIds |List of Int |No |<p>筛选时段的ID清单.  1 = FT 全场 </p><p>2 = 1H 上半场 </p><p>3 = 2H 下半场 </p>|
|MarketlineLevels |List of Int |No |可选参数用于指出只返回特定的盘口级别。只 是针对主要玩法。|
|LanguageCode |String |Yes |<p>. </p><p>为本地名称返回的语言</p>|
|MemberCode |String |No |用户名. |
|Token |String |No |会员令牌. |
|TimeStamp |String |Yes |<p>5分钟.  </p><p>新生成的时间戳将持续</p>|
响应** 

该响应与 GetEventInfoMBT 响应一致  

状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**405** |无效赛季 |
|**406** |无效赛日 |
|**407** |无效 Bet Radar 赛事 ID |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 14: GetVSEventInfo Request* 

{ ![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.009.png)

"SportId":43, "Season":22586, "MatchDay":29, "BREventIds":[], "OddsType":1, "BetTypeIds":[],  "PeriodIds":[], "MarketlineLevel":[], "LanguageCode":"eng", "MemberCode":"", "Token":"",  

"TimeStamp":"hWUsgKICyZmmr3/WQIwMnvtZiUnkfuyvRNhbEd0m0sg="  } 

请求** 

9. **GETDELTAVSEVENTINFO** 索取 **DELTA**虚拟赛事列表** 

描述** 

此 API 用于检索相关 Delta 虚拟赛事及赔率信息. 

访问频率限制:  

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|SportId |Int |Yes |<p>ID. 参考附录. </p><p>指出体育项目</p>|
|Season |Int |Yes |赛季指标. (Betradar视频小部件)|
|MatchDay |Int |Yes |赛日指标. (Betradar视频小部件)|
|BREventIds |List of Int |No |Bet Radar 赛事ID。仅适用于Sport ID = 44 and 46 |
|OddsType |Int |Yes |赔率类型 1 = 马来盘 2 = 香港盘 3 = 欧洲盘 4 = 印尼盘 |
|BetTypeIds |List of Int |No |<p>ID清单. </p><p>筛选赛事投注类型</p>|
|PeriodIds |List of Int |No |<p>筛选时段的ID清单.  1 = FT 全场 </p><p>2 = 1H 上半场 </p><p>3 = 2H 下半场 </p>|
|MarketlineLevels |List of Int |No |可选参数用于指出只返回特定的盘口级别。只 是针对主要玩法。|
|LanguageCode |String |Yes |<p>. </p><p>为本地名称返回的语言</p>|
|MemberCode |String |No |用户名. |
|Token |String |No |会员令牌. |
|TimeStamp |String |Yes |<p>5分钟.  </p><p>新生成的时间戳将持续</p>|
|Delta |Double |Yes |<p>Delta 版本 </p><p>格式：yyMMddHHmmssfff 范例: 171219001225452 </p>|
响应** 

该响应与 GetEventInfoMBT 响应一致  

状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**405** |无效赛季 |
|**406** |无效赛日 |
|**407** |无效 Bet Radar 赛事 ID |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 15: GetDeltaVSEventInfo Request* 

{ 

"SportId":43, 

"Season":22586, 

"MatchDay":29, 

"BREventIds":[], 

"OddsType":1, 

"BetTypeIds":[],  

"PeriodIds":[], 

"MarketlineLevel":[], 

"LanguageCode":"eng", 

"MemberCode":"", 

`                `"Delta":190705062052253.0, 

"Token":"",  "TimeStamp":"hWUsgKICyZmmr3/WQIwMnvtZiUnkfuyvRNhbEd0m0sg="  

} 

请求** 

10. **GETVSEVENTDETAILS**索取虚拟赛事资料** 

描述** 

此 API 用于检索相关虚拟赛事资料. 用于虚拟体育统计显示（只支持 PC 版）。 访问频率限制:  

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|SportId |Int |Yes |指出体育项目ID. 参考附录. |
|EventId |Int |Yes |赛事ID |
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟.  |
响应** 



|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|StatusCode** |Int** |No** |指出请求状态编码|
|StatusDesc** |String** |No** |状态编码的描述含义|
|VSHomeTeamId |Int |No |<p>` `ID. </p><p>虚拟主队或参赛者的特定</p>|
|VSAwayTeamId |Int |No |<p>` `ID. </p><p>虚拟主队或参赛者的特定</p>|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID |
|**380** |无可选盘口|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 16: GetVSEventDetails Request* 

{ ![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.010.png)

"SportId":43, 

"EventId":6877075, "TimeStamp":"BkMnB26AhAN/ZQ5xTleYBd8ie1jzrrXiLTeQwB7V4a0=" 

} 

请求** 

*Table 17: GetVSEventDetails Response* 

{ 

`    `"VSHomeTeamId": 7640508, 

`    `"VSAwayTeamId": 7640510, 

`    `"ServerTime": "2019-10-21T09:14:30.3570808-04:00",     "StatusCode": 100, 

`    `"StatusDesc": "Success" 

} 

响应** 

11. **GETOUTRIGHTEVENTS** 索取优胜冠军赛事

描述** 

此 API 常用于优胜冠军赛事. 

访问频率限制: 30 秒 

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|TimeStamp |String |Yes |<p>` `5 分钟  </p><p>新生成的时间戳将持续</p>|
|SportId |String |Yes |<p>. 参考附录3.3 </p><p>指出体育项目</p>|
|EventIds |List of Int |No |检索赛事 ID清单 |
|CompetitionIds |List of Int |No |<p>ID清单. 若没有提供竞赛ID, 所有竞</p><p>筛选特定竞赛 赛将被检索. </p>|
|LanguageCode |String |Yes |为本地名称返回的语言|
|ProgrammeId |Int |No |自选参数指出只返回特定程序的竞赛|
响应** 

|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|CompetitionId |Int |No |<p>` `ID. </p><p>每场竞赛的特定</p>|
|CompetitionName |String |No |运营商竞赛名称的默认语言|
|PMOrderNumber |Int |No |竞赛的赛前序号|
|Programme |List |Yes |竞赛程序 清单  |
|- ProgrammeId |Int |Yes |指出特定的竞赛程序|
|- ProgrammeName |String |Yes |程序名称 |
|EventId |Long |No |<p>ID </p><p>每场赛事的特定</p>|
|EventName |String |No |优胜冠军赛事名称在指定请求中返回相应语言|
|EventStatusId |Int |No |指赛事状态 1 = 开盘 2 = 关盘 |
|OrderNumber |Int |No |赛事序号 |
|EventDate |Date |No |赛事日期 |
|MarketLineId |Long |No |<p>` `ID </p><p>盘口的特定</p>|
|BetTypeId |Int |No |投注类型 ID |
|BetTypeName |String |No |运营商投注类型的默认语言|
|PeriodId |Int |No |比赛时段 ID.  1 = FT 全场 2 = 1H 上半场 3 = 2H 下半场 |
|PeriodName |String |No |运营商比赛时段的默认语言|
|MarketLineLevel |Int |No |盘口级别 |
|MarketlineStatusI d |Int |No |指出盘口状态|
|WagerSelectionId |Long |No |投注选项的特定 ID |
|SelectionId |Int |No |<p>` `ID </p><p>投注类型选项</p>|
|SelectionName |String |No |<p>名称 </p><p>投注类型选项</p>|
|Handicap |Float |Yes |<p>该项目仅适用于让球盘和大小盘.  对于让球盘，负值等于选项在让分，正值相反。 对于大小盘，就是大于或小于的得分比较 如果是空值等于该让分不适用于该盘口或投注类型。</p><p>。 </p>|
|OddsType |Int |No |赔率类型 1 = 马来盘 2 = 香港盘 3 = 欧洲盘 4 = 印尼盘 |
|Odds |Float |No |选择赔率值|
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
状态编码** 

状态编码**  描述 **![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.011.png)**

|**100** |成功 |
| - | - |
|**101** |无效时间戳|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 18: GetOutrightEvents Request* 

{ 

` `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",  "LanguageCode":"eng", 

` `"IsCombo":"False",                 

` `"SportId":1, 

` `"Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee",             

` `"MemberCode":"spkoormb01",   

` `"ProgrammeId":""                            

} 

请求** 

*Table 19: GetOutrightEvents Response* 

{ 

`  `"Events": [ 

`    `{ 

`      `"OutrightEventName": "\*GERMANY SUPER CUP - Winner",       "EventId": 5717367, 

`      `"EventStatusId": 1, 

`      `"OrderNumber": 9999, 

`      `"EventDate": "2019-12-30T03:28:00.0000000-04:00", 

`      `"Competition": { 

`        `"CompetitionId": 8237, 

`        `"CompetitionName": "\*GERMANY SUPER CUP", 

`        `"PMOrderNumber": 0, 

`        `"RBOrderNumber": 0 

`      `}, 

`      `"MarketLines": [ 

`        `{ 

`          `"MarketlineId": 82873442, 

`          `"BetTypeId": 11, 

`          `"BetTypeName": "Outright", 

`          `"PeriodId": 1, 

`          `"PeriodName": "Full Time", 

`          `"MarketLineLevel": 1, 

`          `"MarketlineStatusId": 1, 

`          `"IsLocked": false, 

`          `"WagerSelections": [ 

`            `{ 

`              `"WagerSelectionId": 2379259983, 

`              `"SelectionId": 336, 

`              `"SelectionName": "Bayern Munchen", 

`              `"Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 0.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "0.0", 

`                    `"B": "0.0", 

`                    `"C": "0.0", 

`                    `"D": "0.0", 

`                    `"E": "0.0", 

`                    `"F": "0.0", 

`                    `"G": "0.0" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 2379259982, 

`              `"SelectionId": 723, 

`              `"SelectionName": "Eintracht Frankfurt", 

`              `"Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 0.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "0.0", 

`                    `"B": "0.0", 

`                    `"C": "0.0", 

`                    `"D": "0.0", 

`                    `"E": "0.0", 

`                    `"F": "0.0", 

`                    `"G": "0.0" 

`                  `} 

`                `} 

`              `] 

`            `} 

`          `] 

`        `} 

`      `] 

`    `}, 

`    `{ 

`      `"OutrightEventName": "Russia Football National League Playoff - Winner",       "EventId": 5717369, 

`      `"EventStatusId": 1, 

`      `"OrderNumber": 9999, 

`      `"EventDate": "2019-12-31T03:32:00.0000000-04:00", 

`      `"Competition": { 

`        `"CompetitionId": 7958, 

`        `"CompetitionName": "Russia Football National League Playoff", 

`        `"PMOrderNumber": 0, 

`        `"RBOrderNumber": 0 

`      `}, 

`      `"MarketLines": [ 

`        `{ 

`          `"MarketlineId": 82873489, 

`          `"BetTypeId": 11, 

`          `"BetTypeName": "Outright", 

`          `"PeriodId": 1, 

`          `"PeriodName": "Full Time", 

`          `"MarketLineLevel": 1, 

`          `"MarketlineStatusId": 1, 

`          `"IsLocked": false, 

`          `"WagerSelections": [ 

`            `{ 

`              `"WagerSelectionId": 2379260175,               "SelectionId": 377, 

`              `"SelectionName": "Amkar Perm",               "Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 0.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "0.0", 

`                    `"B": "0.0", 

`                    `"C": "0.0", 

`                    `"D": "0.0", 

`                    `"E": "0.0", 

`                    `"F": "0.0", 

`                    `"G": "0.0" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 2379260178, 

`              `"SelectionId": 618, 

`              `"SelectionName": "FC Anzhi Makhachkala",               "Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 0.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "0.0", 

`                    `"B": "0.0", 

`                    `"C": "0.0", 

`                    `"D": "0.0", 

`                    `"E": "0.0", 

`                    `"F": "0.0", 

`                    `"G": "0.0" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 2379260180, 

`              `"SelectionId": 619, 

`              `"SelectionName": "Tom Tomsk", 

`              `"Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 0.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "0.0", 

`                    `"B": "0.0", 

`                    `"C": "0.0", 

`                    `"D": "0.0", 

`                    `"E": "0.0", 

`                    `"F": "0.0", 

`                    `"G": "0.0" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 2379260179, 

`              `"SelectionId": 1384, 

`              `"SelectionName": "FC Ufa", 

`              `"Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 1.01, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "1.01", 

`                    `"B": "1.01", 

`                    `"C": "1.01", 

`                    `"D": "1.01", 

`                    `"E": "1.01", 

`                    `"F": "1.01", 

`                    `"G": "1.01" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 2379260182, 

`              `"SelectionId": 1388, 

`              `"SelectionName": "Krylia Sovetov ",               "Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 0.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3,                   "OddsValues": {                     "A": "0.0", 

`                    `"B": "0.0", 

`                    `"C": "0.0", 

`                    `"D": "0.0", 

`                    `"E": "0.0", 

`                    `"F": "0.0", 

`                    `"G": "0.0" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 2379260176, 

`              `"SelectionId": 4011, 

`              `"SelectionName": "FC Tambov", 

`              `"Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 2.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "2.0", 

`                    `"B": "2.0", 

`                    `"C": "2.0", 

`                    `"D": "2.0", 

`                    `"E": "2.0", 

`                    `"F": "2.0", 

`                    `"G": "2.0" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 2379260177, 

`              `"SelectionId": 4018, 

`              `"SelectionName": "FC Yenisey Krasnoyarsk",               "Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 0.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "0.0", 

`                    `"B": "0.0", 

`                    `"C": "0.0", 

`                    `"D": "0.0", 

`                    `"E": "0.0", 

`                    `"F": "0.0", 

`                    `"G": "0.0" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 2379260181, 

`              `"SelectionId": 101881, 

`              `"SelectionName": "FC Olimpiets Nizhny Novgorod",               "Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 151.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "151.0", 

`                    `"B": "151.0", 

`                    `"C": "151.0", 

`                    `"D": "151.0", 

`                    `"E": "151.0", 

`                    `"F": "151.0", 

`                    `"G": "151.0" 

`                  `} 

`                `} 

`              `] 

`            `} 

`          `] 

`        `} 

`      `] 

`    `} 

`  `], 

`  `"Delta": 190705062604956.0, 

`  `"ServerTime": "2019-07-05T06:26:04.9727828-04:00", 

`  `"StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

12. **GETDELTAOUTRIGHTEVENTINFO** 索取 DELTA 优胜冠军赛事

描述** 

此 API 用于检索优胜冠军赛事里的 Delta 变化. 

访问频率限制: 20 秒 

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|SportId |String |Yes |<p>` `ID. 参考附录 </p><p>指出体育项目</p>|
|LanguageCode |String |No |为本地名称返回的语言|
|ProgrammeId |Int |No |<p>. </p><p>自选参数指出只返回特定程序的竞赛</p>|
|Delta |Double |Yes |<p>Delta 版本 </p><p>格式：yyMMddHHmmssfff 范例: 171219001225452 </p>|
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟|
响应** 



|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|InsertUpdateEven ts |List |No |<p>. </p><p>优胜冠军赛事清单</p>|
|RemoveEvent |List |No |选择删除的赛事 ID 名单. |
|Delta |Doubl e |Yes |<p>Delta 版本 </p><p>格式：yyMMddHHmmssfff 范例: 171219001225452 </p>|
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 20: GetDeltaOutrightEventInfo Request* 

{ 

` `"TimeStamp":"ruSHsDyYXBoLDYvbHDCx0m1zDGJg6Btx974bMn5l+n8=",    "SportId":1,                         

` `"Delta":190705062052253.0  

} 

请求** 

*Table 21: GetDeltaOutrightEventInfo Response* 

{ 

`  `"InsertUpdateEvent": [ 

`    `{ 

`      `"OutrightEventName": "\*欧洲冠军联赛 - C 组哪一队可晋级淘汰赛阶段",       "EventId": 7743793, 

`      `"EventStatusId": 1, 

`      `"OrderNumber": 9999, 

`      `"EventDate": "2019-12-12T12:00:00+08:00", 

`      `"Competition": { 

`        `"CompetitionId": 271, 

`        `"CompetitionName": "\*欧洲冠军联赛", 

`        `"PMOrderNumber": 180, 

`        `"RBOrderNumber": 0 

`      `}, 

`      `"MarketLines": [ 

`        `{ 

`          `"MarketlineId": 144567772, 

`          `"BetTypeId": 11, 

`          `"BetTypeName": "冠军", 

`          `"PeriodId": 1, 

`          `"PeriodName": "全场", 

`          `"MarketLineLevel": 1, 

`          `"MarketlineStatusId": 1, 

`          `"IsLocked": false, 

`          `"WagerSelections": [ 

`            `{ 

`              `"WagerSelectionId": 614308223, 

`              `"SelectionId": 405, 

`              `"SelectionName": "萨格勒布迪纳摩",               "Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 6.0, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "6.0", 

`                    `"B": "6.0", 

`                    `"C": "6.0", 

`                    `"D": "6.0", 

`                    `"E": "6.0", 

`                    `"F": "6.0", 

`                    `"G": "6.0" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 614308222, 

`              `"SelectionId": 685, 

`              `"SelectionName": "亚特兰大", 

`              `"Handicap": null,               "Specifiers": null,               "OddsType": 3, 

`              `"Odds": 3.3, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3,                   "OddsValues": {                     "A": "3.3", 

`                    `"B": "3.3", 

`                    `"C": "3.3", 

`                    `"D": "3.3", 

`                    `"E": "3.3", 

`                    `"F": "3.3", 

`                    `"G": "3.3" 

`                  `} 

`                `} 

`              `] 

`            `}, 

`            `{ 

`              `"WagerSelectionId": 614308224,               "SelectionId": 6332, 

`              `"SelectionName": "顿涅茨克矿工",               "Handicap": null, 

`              `"Specifiers": null, 

`              `"OddsType": 3, 

`              `"Odds": 1.55, 

`              `"OddsList": [ 

`                `{ 

`                  `"OddsType": 3, 

`                  `"OddsValues": { 

`                    `"A": "1.55", 

`                    `"B": "1.55", 

`                    `"C": "1.55", 

`                    `"D": "1.55", 

`                    `"E": "1.55", 

`                    `"F": "1.55", 

`                    `"G": "1.55" 

`                  `} 

`                `} 

`              `] 

`            `} 

`          `] 

`        `} 

`      `] 

`    `} 

`  `], 

`  `"RemoveEvent": [], 

`  `"Delta": 191205033601745.0, 

`  `"ServerTime": "2019-12-05T15:36:02.6780313+08:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

{ 

"InsertUpdateEvent" : [], "RemoveEvent" : [ 

5152067 

], 

"Delta" : 191205043111396, 

"ServerTime" : "2019-12-05T04:31:14.6136471-04:00", 

"StatusCode" : 100, 

"StatusDesc" : "Success" 

}** 

响应** 

13. **GETLIVERESULTS** 索取现场赛果

描述** 

此 API 用于检索当前现场赛果. 

访问频率限制:  请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|TimeStamp |String |Yes |<p>5分钟.  </p><p>新生成的时间戳将持续</p>|
|SportId |Int |Yes |<p>ID. 参考附录. </p><p>指出体育项目</p>|
|EventGroupTy peIds |List of Int |No |筛选特定赛事组别类型ID清单. 参考附录3.4。|
|ViewingCompe titionIds |List of Int |No |<p>ID清单. 若没有提供竞赛ID, 所有竞</p><p>筛选特定竞赛 赛将被检索. </p>|
|LanguageCode |String |Yes |会员选用的语言|
响应** 



|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|CompetitionId |Int |No |<p>ID. </p><p>每场竞赛的特定</p>|
|CompetitionName |String |No |竞赛名称. 这将在指定请求中返回相应语言. |
|RBOrderNumber |Int |No |<p>. </p><p>竞赛滚球序号</p>|
|EventId |Long |No |赛事特定ID. |
|EventGroupID |Long |No |<p>, 这将是赛事组别ID.  </p><p>如果赛事是属于赛事组别</p>|
|EventGroupTypeI d |Int |No |<p>类型. 参考附录3.4.  </p><p>指出赛事的组别</p>|
|EventDate |Date |No |赛事日期 |
|OrderNumber |Int |No |<p>IMSB中使用的序号 的先后显示. </p><p>用于排序竞赛中赛事</p>|
|HomeTeamId |Int |Int |<p>ID </p><p>主队或参赛者的特定</p>|
|HomeTeam |String |String |主队名称. 这将在指定请求中返回相应语言. |
|AwayTeamId |Int |int |<p>ID </p><p>客队或参赛者的特定</p>|
|AwayTeam |String |String |客队名称. 这将在指定请求中返回相应语言. |
|HomeScore |Int |Yes |主队比分 |
|AwayScore |Int |Yes |客队比分 |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 22: GetLiveResults Request* 

{ 

` `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",  "LanguageCode":"eng", 

` `"SportId":1, 

` `"ViewingCompetitionIds":[],      

` `"IncludeEventGroupTypeIds":[0,1,2,3,4,5,6,7]   

} 

请求** 

*Table 23: GetLiveResults Response* 

{ 

`  `"LiveResults": [ 

`    `{ 

`      `"EventId": 6014772, 

`      `"CompetitionId": 15306, 

`      `"CompetitionName": "PleaseDontUserMyEvent",       "RBOrderNumber": 0, 

"OrderNumber": 9999, 

"EventDate": "2019-07-05T06:11:00.0000000-04:00", "HomeTeamId": 229479, 

"HomeTeam": "Mock Team A96346546", "AwayTeamId": 229254, 

"AwayTeam": "Mock Team A96346548", "EventGroupId": 319608, 

"EventGroupTypeId": 1, 

"GroundTypeId": 1, 

"RBTime": "2H 09:38", 

"RBTimeStatus": 0, 

"HomeScore": 0, 

"AwayScore": 0, 

"HomeRedCard": 0, 

"AwayRedCard": 0, 

"RelatedScores": null 

`    `} 

`  `], 

`  `"Delta": 190705062632502.0, 

`  `"ServerTime": "2019-07-05T06:26:32.5025873-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

14. **GETLOCALIZATIONS** 索取定位

描述** 

此 API 常用于检索在赛事里所有被使用的定位名称. 它将被分成不同的类型并且将受到单 独性或一次性的检索. 

访问频率限制:  请求** 



|范围**  |数据类型||强制性**  |描述 |
| - | - | :- | - | - |
|LocalizationTy pe |Int ||Yes |<p>指出定位类型. </p><p>50 = 所有定位类型</p>|
|||||51 = 竞赛名称 |
|||||52 = 优胜冠军名称|
|||||53 = 队名包含优胜冠军队名|
|||||54 = 投注类型名称|
|||||55 = 投注选项类型名称|

||||<p>56= 取消提前兑现原因</p><p>57 =程序 </p><p>60 =投注类型全名（仅在提供BTNameCodeList时 可用） </p>|
| :- | :- | :- | - |
|IdList |String |No |指示用于搜索要返回的特定本地化类型的特定ID |
|BTNameCodeL ist |String |No |指示要针对本地化类型= 60返回的特定投注类型 名称代码 |
|LanguageCode List |String |No |表示要返回的特定语言|
|TimeStamp |String |Yes |<p>` `5 分钟. </p><p>新生成的时间戳将持续</p>|
响应** 



|范围** |数据类型||空值**  |描述 |
| - | - | :- | - | - |
|Localizations |List ||No |定位清单 |
|- LocalizationType |Int ||No |指出定位类型|
|- Details |List ||No |详情清单 |
|-- Id |String ||No |<p>` `ID. </p><p>各自的定位类型</p>|
|||||51 竞赛名称 = CompetitionId |
|||||52 优胜冠军名称 = EventId |
|||||53 队名/优胜冠军队名 =  HomeTeamId/AwayTeamId/OutrightTeamId 54 投注类型名称 = BetTypeId |
|||||55 投注选项类型名称 =  BetTypeSelectionId |
|||||56 提前兑现取消原因 = BetTradeCancelReasonId |
|||||57 程序名称 = ProgrammeId |
|-- Image |Boolean ||No |指出图片是否可用|
|-- Names |List ||No |名称信息清单|
|--- LanguageCode |String ||No |语言编码. 参考附录 |
|--- Name |String ||Yes |特定语言的名称|
|Delta |Double ||Yes |Delta 版本 |
|||||格式：yyMMddHHmmssfff |
|||||范例: 171219001225452 |
|StatusCode |Int ||No |指出请求状态编码|
|StatusDesc |String ||No |状态编码的描述含义|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**339** |无效定位类型|
|**400** |系统错误 |
|**417** |无效投注类型名称代 码 |
|**700** |维护 |
**710**  访问地区限制![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.012.png)

范例** 

*Table 24: GetLocalizations Request* 

{ 

`  `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",      "LocalizationType":"52"   

} 

请求** 

*Table 25: GetLocalizations Response* 

{ 

`  `"Localizations": [ 

`    `{ 

`      `"LocalizationType": 52, 

`      `"Details": [] 

`    `} 

`  `], 

`  `"Delta": 190705062701151.0, 

`  `"ServerTime": "2019-07-05T06:27:01.1514662-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

IPIS Mobile

15. **GETDELTALOCALIZATIONS** 索取

描述** 

` `此 API 常用于检索定位的 Delta 变化. 访问频率限制:  

DELTA 定位

IPIS Mobile

请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|LocalizationTy pe |Int |Yes |<p>指出定位类型. </p><p>50 = 所有定位类型</p>|

||||<p>51 = 竞赛名称 </p><p>52 = 优胜冠军名称</p><p>53 = 队名包含优胜冠军队名</p><p>54 = 投注类型名称</p><p>55 = 投注选项类型名称</p><p>56= 取消提前兑现原因</p><p>57 =程序 </p><p>60 =投注类型全名（仅在提供BTNameCodeList时 可用） </p>|
| :- | :- | :- | - |
|IdList |Int |No |指示用于搜索要返回的特定本地化类型的特定ID |
|BTNameCodeL ist |String |No |指示要针对本地化类型= 60返回的特定投注类型 名称代码 |
|LanguageCode List |String |No |表示要返回的特定语言|
|Delta |Double |Yes |<p>Delta 版本 </p><p>格式：yyMMddHHmmssfff 范例: 171219001225452 </p>|
|TimeStamp |String |Yes |<p>` `5 分钟. </p><p>新生成的时间戳将持续</p>|
响应** 



|范围** |数据类型||空值**  |描述 |
| - | - | :- | - | - |
|Localizations |List ||No |定位清单 |
|- LocalizationType |Int ||No |指出定位类型|
|- Details |List ||No |详情清单 |
|-- Id |String ||No |<p>` `ID. </p><p>各自的定位类型</p>|
|||||51 竞赛名称 = CompetitionId |
|||||52 优胜冠军名称 = EventId |
|||||53 队名/优胜冠军队名 =  HomeTeamId/AwayTeamId/OutrightTeamId 54 投注类型名称 = BetTypeId |
|||||55 投注选项类型名称 =  BetTypeSelectionId |
|||||56 提前兑现取消原因 = BetTradeCancelReasonId |
|||||57 程序名称 = ProgrammeId |
|-- Image |Boolean ||No |指出图片是否可用|
|-- Names |List ||No |名称信息清单|
|--- LanguageCode |String ||No |语言编码. 参考附录 |
|--- Name |String ||Yes |特定语言的名称|
|Delta |Double ||Yes |Delta 版本 |
|||||格式：yyMMddHHmmssfff |
|||||范例: 171219001225452 |
|StatusCode |Int ||No |指出请求状态编码|
|StatusDesc |String ||No |状态编码的描述含义|
状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**339** |无效定位类型|
|**400** |系统错误 |
|**417** |无效投注类型名称代 码 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 26: GetDeltaLocalizations Request* 

{ 

`  `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",      "LocalizationType":"52",   

`  `"Delta": 190705062701510.0 

} 

请求** 

*Table 27: GetDeltaLocalizations Response* 

{ 

`  `"Delta": 190705062701510.0, 

`  `"Localizations": [], 

`  `"ServerTime": "2019-07-05T06:27:01.5577269-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

16. **GETCOMPLETEDRESULTS** 索取完整赛果

描述** 

此 API 常用于检索所有在特定日期范围内完成的赛果. 

访问频率限制:  

请求** 



|范围**  |数据类型||强制性**  |描述 |
| - | - | :- | - | - |
|SportId |Int ||Yes |指出体育项目 ID. 参考附录 |
|EventTypeId |Int ||Yes |指出赛事属于定时赛事（普通）或优胜冠军赛事|
|||||1 = 定时赛事 |
|||||2 = 优胜冠军 |
|StartDate |Date ||Yes |<p>` `GMT-4 (定时赛事的最早日期是</p><p>开始时间时区为</p>|
|||||今日 -31 日. 优胜冠军的最早日期是 今日 -365 |
|||||日) |
|EndDate |Date ||Yes |<p>` `GMT-4 </p><p>结束时间时区为</p>|
|CompetitionId |Int ||No |用于过滤特定竞赛|
|LanguageCode |String ||Yes |使用会员语言|
|TimeStamp |String ||Yes |<p>` `5 分钟  </p><p>新生成的时间戳将持续</p>|
响应** 



|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|Competitions |List |No |竞赛清单 |
|- CompetitionId |Int |No |<p>` `ID </p><p>每项竞赛的特定</p>|
|- SportId |Int |No |<p>` `ID，参考附录</p><p>指出体育项目</p>|
|- CompetitionName |String |No |<p>竞赛的名称. 这将会在请求中还原特定的语言</p><p>. </p>|
|- CompetitionSeq |Int |No |IMSB 中使用的序号用于排序竞赛|
|- Programme |List |Yes |竞赛程序 清单（不适用于优胜冠军） |
|-- ProgrammeId |Int |Yes |<p>（不适用于优胜冠军） </p><p>指出特定的竞赛程序</p>|
|-- ProgrammeName |String |Yes |程序名称（不适用于优胜冠军） |
|- Events |List |No |赛事清单 |
|-- EventId |Long |No |<p>` `ID </p><p>赛事的特定</p>|
|-- BREventId |Long |Yes |<p>ID. </p><p>可视化投注预测赛事</p>|
|-- HasVisualization  |Bool |No |<p>. </p><p>指出赛事是否是可视化</p>|
|-- SourceId |String |Yes |<p>ID. </p><p>赛事的外部参考</p>|
|-- Season |String |Yes |赛季指标. 仅适用于虚拟足球, 虚拟篮球和虚拟世界杯 各项体育. |
|-- MatchDay |String |Yes |赛日指标. 仅适用于虚拟足球和虚拟篮球|
|-- EventTypeId |Int |No |<p>指出赛事属于定时赛事（普通）或优胜冠军赛事 1 = 定时赛事 </p><p>2 = 优胜冠军 </p>|
|-- EventOutrightNa me |String |Yes |<p>优胜冠军的名称.  这将会在请求中还原特定的语言 这将会被清空如果赛事不是优胜冠军赛事</p><p>. </p><p>. </p>|
|-- EventSeq |Int |No |IMSB 中使用的序号用于排序竞赛中赛事的先后显示. |
|-- EventGroupID |Long |No |<p>` `ID</p><p>如果赛事是属于赛事组别，将显示赛事组别</p>|
|-- EventGroupTypeI d |Int |No |<p>. 参考附录3.4.  </p><p>指出赛事的组别类型</p>|
|-- HomeTeamId |Int |Int |<p>` `ID. </p><p>主队或参赛者的特定</p>|
|-- HomeTeam |String |String |<p>主队名称. 这将会在请求中还原特定的语言</p><p>. </p>|
|-- AwayTeamId |Int |int |<p>` `ID. </p><p>客队或参赛者的特定</p>|
|-- AwayTeam |String |String |<p>客队名称. 这将会在请求中还原特定的语言</p><p>. </p>|
|-- GroundTypeId |Int |No |<p>指出赛事是否在主队场地或中立场地进行（只适用于 定时赛事，如果优胜冠军会是0） </p><p>0 = 中立场地 </p><p>1 = 主队场地 </p>|
|-- EventDate |Date |No |赛事日期 |
|-- ResultList |List |No |赛事详情清单|
|--- PeriodId |Int |No |<p>比赛时段 ID  1 = 全场 </p><p>2 = 上半场 3 = 下半场 </p>|
|--- PeriodName |String |No |比赛时间名称|
|--- HomeScore |Int |Yes |主队得分 |
|--- AwayScore |Int |Yes |客队得分 |
|--- OutrightWinnerT eamID |Long |Yes |<p>` `ID. 这会被清空如果不是优胜冠军</p><p>优胜冠军队伍</p>|
|--- OutrightWinnerT eamName |String |Yes |<p>队名.  这将会在请求中还原特定的语言 这会被清空如果不是优胜冠军</p><p>. </p>|
|--- IsCancelled |Bool |No |<p>. </p><p>指某时间段的结果被取消</p>|
|--- CancelReason |Int |No |<p>0 = No Reason 无原因 </p><p>1 = Abandoned 賽事終止 </p>|
|-- RelatedScores |List |Yes |相关比分清单 |
|--- EventGroupTypeI d |Int |No |<p>. 参考附录 </p><p>指出比分的组别类型 参考附录3.4. </p>|
|--- HomeScore |Int |Yes |主队的当前组别类型比分|
|--- AwayScore |Int |Yes |客队的当前组别类型比分|
|-- OverallScore |Int |Yes |指出赛事的总体得分。 如果没有分数，将返回Null。 |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
状态编码** 

状态编码**  描述 **![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.013.png)**

**100**  成功 

**101**  无效时间戳

|**107** |无效开始日期|
| - | - |
|**108** |无效结束日期|
|**311** |无效日期范围|
|**313** |无效体育 ID |
|**330** |<p>` `ID </p><p>无效赛事类型</p>|
|**331** |无效竞赛 ID |
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 28: GetCompletedResults Request* 

{ 

`    `"SportId": 2, 

`    `"EventTypeId": 1, 

`    `"StartDate": "2019-12-16T00:00:00",     "EndDate": "2019-12-17T00:00:00",     "CompetitionId": 0, 

`   `"TimeStamp": "{{timestamp}}", 

`    `"LanguageCode": 2, 

`    `"IsCombo": false 

} 

请求** 

*Table 29: GetCompletedResults Response* 

{ 

`  `"Competitions": [ 

`    `{ 

`      `"CompetitionId": 9407, 

`      `"SportId": 2, 

`      `"CompetitionName": "天神之战", 

`      `"CompetitionSeq": 9999, 

`      `"Events": [ 

`        `{ 

`          `"EventId": 7313878, 

`          `"EventTypeId": 1, 

`          `"EventOutrightName": "", 

`          `"EventSeq": 9999, 

`          `"HomeTeamId": 280152, 

`          `"HomeTeam": "BBallHome121600 Q3 -华语",           "AwayTeamId": 280153, 

`          `"AwayTeam": "BBallAway121600 Q3 -华语",           "GroundTypeId": 1, 

`          `"EventDate": "2019-12-16T02:40:15-04:00", 

`          `"HasVisualization": false, 

`          `"BREventId": 0, 

`          `"MatchDay": 0, 

`          `"SeasonId": 0, 

`          `"EventGroupId": 379371, 

`          `"EventGroupTypeId": 6, 

`          `"ResultList": [ 

`            `{ 

`              `"PeriodId": 1, 

`              `"PeriodName": "全场", 

`              `"HomeScore": 125, 

`              `"AwayScore": 111, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "",               "IsCancelled": false 

`            `}, 

`            `{ 

`              `"PeriodId": 2, 

`              `"PeriodName": "上半场", 

`              `"HomeScore": 70, 

`              `"AwayScore": 65, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "", 

`              `"IsCancelled": false 

`            `}, 

`            `{ 

`              `"PeriodId": 3, 

`              `"PeriodName": "下半场", 

`              `"HomeScore": 55, 

`              `"AwayScore": 46, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "", 

`              `"IsCancelled": false 

`            `} 

`          `] 

`        `}, 

`        `{ 

`          `"EventId": 7313879, 

`          `"EventTypeId": 1, 

`          `"EventOutrightName": "", 

`          `"EventSeq": 9999, 

`          `"HomeTeamId": 280154, 

`          `"HomeTeam": "BBallHome121600 Q4", 

`          `"AwayTeamId": 280155, 

`          `"AwayTeam": "BBallAway121600 Q4 -华语", 

`          `"GroundTypeId": 1, 

`          `"EventDate": "2019-12-16T02:40:15-04:00",           "HasVisualization": false, 

`          `"BREventId": 0, 

`          `"MatchDay": 0, 

`          `"SeasonId": 0, 

`          `"EventGroupId": 379371, 

`          `"EventGroupTypeId": 7, 

`          `"ResultList": [ 

`            `{ 

`              `"PeriodId": 1, 

`              `"PeriodName": "全场", 

`              `"HomeScore": 125, 

`              `"AwayScore": 111, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "",               "IsCancelled": false 

`            `}, 

`            `{ 

`              `"PeriodId": 2, 

`              `"PeriodName": "上半场", 

`              `"HomeScore": 70, 

`              `"AwayScore": 65, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "", 

`              `"IsCancelled": false 

`            `}, 

`            `{ 

`              `"PeriodId": 3, 

`              `"PeriodName": "下半场", 

`              `"HomeScore": 55, 

`              `"AwayScore": 46, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "",               "IsCancelled": false 

`            `} 

`          `] 

`        `} 

`      `] 

`    `}, 

`    `{ 

`      `"CompetitionId": 15958, 

`      `"SportId": 2, 

`      `"CompetitionName": "SF Mock other Sport octopus CHS",       "CompetitionSeq": 9999, 

`      `"Events": [ 

`        `{ 

`          `"EventId": 7313926, 

`          `"EventTypeId": 1, 

`          `"EventOutrightName": "", 

`          `"EventSeq": 9999, 

`          `"HomeTeamId": 280204, 

`          `"HomeTeam": "HomeTeamCodeA567146 CHS", 

`          `"AwayTeamId": 280205, 

`          `"AwayTeam": "AwayTeamCodeA567147 CHS", 

`          `"GroundTypeId": 1, 

`          `"EventDate": "2019-12-16T04:01:16-04:00",           "HasVisualization": false, 

`          `"BREventId": 0, 

`          `"MatchDay": 0, 

`          `"SeasonId": 0, 

`          `"EventGroupId": 379388, 

`          `"EventGroupTypeId": 1, 

`          `"ResultList": [ 

`            `{ 

`              `"PeriodId": 1, 

`              `"PeriodName": "全场", 

`              `"HomeScore": 125, 

`              `"AwayScore": 111, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "",               "IsCancelled": false 

`            `}, 

`            `{ 

`              `"PeriodId": 2, 

`              `"PeriodName": "上半场", 

`              `"HomeScore": 70, 

`              `"AwayScore": 65, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "", 

`              `"IsCancelled": false 

`            `}, 

`            `{ 

`              `"PeriodId": 3, 

`              `"PeriodName": "下半场", 

`              `"HomeScore": 55, 

`              `"AwayScore": 46, 

`              `"OutrightWinnerTeamID": 0, 

`              `"OutrightWinnerTeamName": "", 

`              `"IsCancelled": false 

`            `} 

`          `] 

`        `} 

`      `] 

`    `} 

`  `], 

`  `"ServerTime": "2019-12-18T03:09:42.8321543-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

}** 

响应** 

17. **LOGOUT**  退出

描述** 

此 API 常用于结束会员的操作会. 访问频率限制:  

请求** 

|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|Token |String |Yes |会员令牌. |
|MemberCode |String |Yes |用户名. |
|TimeStamp |String |Yes |新生成的时间戳将持续 5 分钟.|
响应** 



|范围** |数据类型**  |空值**  |描述 |
| - | - | - | - |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 30: Logout Request* 

{ 

`  `"Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee", 

`  `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",   "MemberCode":"spkoormb01"  

} 

请求** 

*Table 31: Logout Response* 

{ 

`  `"ServerTime": "2019-07-05T06:27:02.3324633-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

18. **GETBETINFO** 索取投注信息

描述** 

此 API 常用于实际投注前索取最后的投注信息, 调用在会员投注时点击一个特定选项..  访问频率限制: 5 秒。。对于滚球篮球，每个请求 3 秒将带来更好的下注率。 

请求** 



|范围**  |数据类型|强制性** | 描述     |
| :- | :- | :- | :- |
|WagerType |Int |Yes |指出投注性质. 1 = Single单注 2 = Combo连串过关 |
|WagerSelectio nInfos |List ||Yes |<p>. </p><p>投注选项详情清单</p>|
|- RefId |Long |No |参考ID. 仅对多个单注是强制性的. |
|- BetTypeId |Int |Yes |投注类型 ID. |
|- EventId |Long |Yes |赛事 ID. |
|- SportId |Int |Yes |<p>` `ID. 参考附录 </p><p>指出体育项目</p>|
|- OddsType |Int |Yes |赔率类型 1 = 马来盘 2 = 香港盘 3 = 欧洲盘 <p>4 = 印尼盘 </p><p>只有让球, 大/小和单/双注类型可以作为返回</p> OddsType 的参考。 对于其他投注类型，将返回 OddsType = 3（欧洲盘）。 串关只支持OddsType =3（欧洲盘）。 |
|- Odds |Float |Yes |赔率选择 |
|- WagerSelectio nId | Long |Yes |<p>` `ID. </p><p>投注选择的特定</p>|
|- MarketlineId |Long |Yes |<p>` `ID </p><p>盘口的特定</p>|
|- PeriodId |Int |Yes |比赛时段 ID  1 = 全场 2 = 上半场 3 = 下半场 |
|- Handicap |Float |Yes |该项目仅适用于让球盘和大小盘.  对于让球盘，负值等于选项在让分，正值相反。对于大小盘，就是大于或小于的得分比较。 如果是空值等于该让分不适用于该盘口或投注类 型。 |
|- Specifiers |String |Yes |其他下注资料. |
|- BetTypeSelecti onId |Int |Yes |<p>` `ID. （只适用于定时赛事，如果优</p><p>投注选项类型 胜冠军会是0） </p>|
|- OutrightTeamI d |Int |Yes |<p>` `ID. （只适用于优胜冠军，如果定</p><p>优胜冠军类型 时赛事会是0） </p>|
|ReturnNearest Handicap |Boolean |No |<p>若设置为 true而当前的让球盘选项不再开出, API 将返回投注选项资料最接近的让球盘.  这仅应用在让球投注类型. 若返回的让球盘与提 交的让球盘有差别, 投注选项的状态编码将返回 381. 对于篮球滚球赛事，请为让球和大小投注类型设 置“ReturnNearestHandicap”= true 以增加成功</p><p>投注的几率。</p>|
|Token |String |Yes |会员令牌. |
|MemberCode |String |Yes |用户名. |
|TimeStamp |String |Yes |<p>` `5 分钟 </p><p>新生成的时间戳将持续</p>|

响应** 



|范围** |数据类型|空值**  |描述 |
| :- | :- | :- | :- |
|WagerSelectionInf os |List |No |<p>. </p><p>投注选项详情清单</p>|
|- Status |Int |No |<p>.  </p><p>显示投注选项状态的编码</p>|
|- RefId |Long |No |参考ID. |
|- EventId |Long |No |赛事的特定 ID. |
|- MarketlineId |Long |No |盘口清单 |
|- MarketlineStatusI d |Int |No |<p>. </p><p>指出盘口状态 1 = 开盘 </p><p>2 = 关盘 </p>|
|- BetTypeId |Int |Yes |投注类型 ID. |
|- WagerSelectionId |Long |No |<p>` `ID. </p><p>投注选项的特定</p>|
|- Handicap |Float |Yes |<p>.该项目仅适用于让球盘和大小盘  <p>.对于让球盘，负值等于选项在让分，正值相反。 <p>.对于大小盘，就是大于或小于的得分比较。 <p>.如果是空值等于该让分不适用于该盘口或投注类型。 |
|- Specifiers |String |Yes |其他下注资料. |
|- BetTypeSelectionI d |Int |No |<p>ID. （只适用于定时赛事，如果优胜冠军会投注选项类型 是0） |
|- OutrightTeamId |Long |No |<p>` `ID. （只适用于优胜冠军，如果定时赛事会</p><p>优胜冠军类型</p>|
|||||是0） |
|- HomeScore |Int |Yes |<p>. (只适用定时滚球赛事) </p><p>主队当前得分</p>|
|- AwayScore |Int |Yes |<p>. (只适用定时滚球赛事) </p><p>客队当前得分</p>|
|- OddsType |Int |No |<p>赔率类型 </p><p>1 = 马来盘 </p><p>2 = 香港盘 </p><p>3 = 欧洲盘 </p><p>4 = 印尼盘 </p><p>只有让球, 大/小和单/双注类型可以作为返回 OddsType 的 参考。 </p><p>对于其他投注类型，将返回 OddsType = 3（欧洲盘）。 串关只支持OddsType =3（欧洲盘）。 </p>|
|- Odds |Float |No |<p>.  </p><p>选择赔率值</p>|
|- SportId |Int |No |<p>` `ID. 参考附录. </p><p>指出体育项目</p>|
|- Market |Int |No |<p>指出“早盘”、“今日”或者“滚球”的盘口 1 = 早盘 </p><p>2 = 今日 </p><p>3 = 滚球 </p>|
|BetSetting |List |No |投注设置清单. |
|- RefId |Long |No |参考ID. |
|- MaxStakeAmount |Decimal |No |最高投注限额|
|- MinStakeAmount |Decimal |No |<p>. </p><p>最低投注限额</p>|
|- NoOfCombination |Int |No |<p>/连串过关类型注单. </p><p>指出排列数量</p>|
|- ComboSelection |Int |No |<p>. 单项投注即使不是混</p><p>指出连串过关类型</p>|
|- EstimatedPayout Amount |Decimal |No |<p>` `$1投注金额. </p><p>预测派彩金额根据</p>|
|ReturnNearestHa ndicap |Boolean |No |<p>若设置为 true而当前的让球盘选项不再开出, API 将返回投 注选项资料最接近的让球盘. </p><p>这仅应用在让球投注类型. 若返回的让球盘与提交的让球盘 有差别, 投注选项的状态编码将返回 381. </p>|
|StatusCode |Int |No |指出请求状态编码.|
|StatusDesc |String |No |状态编码的描述含义.|



状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功（所有投注选项状态为 100） |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|
|**313** |无效体育 ID |
|**334** |无效赛事 ID |
|**335** |无效投注类型 |
|**336** |<p>` `ID </p><p>无效投注类型</p>|
|**337** |无效投注类型 ID |
|**338** |无效 Marketline ID |
|**344** |无效赔率类型|

|**346** |无效赔率 |
| - | - |
|**350** |检索投注信息错误（一个或以上的投注 选项状态是 350 或 380） |
|**355** |超出投注上限 |
|**400** |系统错误 |
|**415** |无效参考编号 |
|**416** |重复参考编号|
|**501** |用户无访问权限|
|**700** |维护 |
|**710** |访问地区限制|
**Wager Selection** 状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**350** |检索投注信息错误|
|**380** |<p>如果 marketlinestatusid =1，用同样的请 求值再次调用 api。 </p><p>如果 marketlinestatusid =2，显示消息以 指示盘口已关闭。 </p>|
|**381** |赔率/让球盘/大小盘与提交的值不同。|
范例** 

*Table 32: GetBetInfo Request* 

{ 

`  `"WagerType": 1, 

`  `"WagerSelectionInfos": [ 

`    `{ 

`      `"BetTypeId": 1, 

`      `"EventId": 23298442, 

`      `"SportId": 1, 

`      `"OddsType": 4, 

`      `"Odds": -1.2, 

`      `"WagerSelectionId": 1169860759,       "MarketlineId": 338374498, 

`      `"PeriodId": 1, 

`      `"Handicap": 0, 

`      `"BetTypeSelectionId": 2, 

`      `"RefId": 1169860759, 

`      `"OutrightTeamId": 0, 

`      `"ReturnNearestHandicap": true, 

`      `"Specifiers": "0" 

`    `} 

`  `], 

`  `"Token": "6bc59747-b170-4f35-a723-2391ac18d902", 

`  `"MemberCode": "testtw2", 

`  `"TimeStamp": "7SWPtRSb+u0G9/EX9q4Yuu32Gn7edLlbXoDfquziT5U=",   "LanguageCode": 1, 

`  `"IsCombo": false 

} 

请求** 

*Table 33: GetBetInfo Response* 

{ 

`    `"WagerSelectionInfos": [ 

`        `{ 

`            `"Status": 100, 

`            `"EventId": 23298442, 

`            `"MarketlineId": 338374498, 

`            `"BetTypeId": 1, 

`            `"MarketlineStatusId": 1, 

`            `"WagerSelectionId": 1169860759,             "Handicap": 0.0000, 

`            `"BetTypeSelectionId": 2, 

`            `"OutrightTeamId": 0, 

`            `"HomeScore": null, 

`            `"AwayScore": null, 

`            `"OddsType": 4, 

`            `"Odds": -1.2, 

`            `"RefId": 1169860759, 

`            `"SportId": 1, 

`            `"Market": 1, 

`            `"Specifiers": null 

`        `} 

`    `], 

`    `"BetSetting": [ 

`        `{ 

`            `"MaxStakeAmount": 83.33, 

`            `"MinStakeAmount": 3.0000, 

`            `"NoOfCombination": 0, 

`            `"ComboSelection": 0, 

`            `"EstimatedPayoutAmount": 1.0,             "RefId": 1169860759 

`        `} 

`    `], 

"ServerTime": "2022-01-11T05:09:45.6706525-04:00", 

`    `"StatusCode": 100, 

`    `"StatusDesc": "Success" } 

响应** 

19. **PLACEBET** 投注

描述** 

此 API 常用于展示各投注项目. 当会员在确认投注时将被调用. 访问频率限制:  

请求** 



|范围**  |数据类型|强制性**  |描述 |
| - | - | - | - |
|WagerType |Int |Yes |指投注性质. <p>1 = Single 单注 <p>2 = Combo 连串过关 |
|CustomerIP |String |Yes |客户 IP 地址 |
|ServerIP |String |Yes |伺服器 IP 地址 |
|CustomerMAC Address |String |No |客户 MAC 地址 |
|UserAgent |String |No |用户代理字符|
|AppDeviceNam e |String |No |设备名. 只强制客户端渠道|
|AppModel |String |No |设备型号. 只强制客户端渠道|
|AppOSVersion |String |No |OS 版设备. 只强制客户端渠道|
|AppPlatform |String |No |设备平台. 只强制客户端渠道|
|AppVersion |String |No |<p>. 只强制客户端渠道</p><p>客户端版本</p>|
|IsComboAccep tAnyOdds |Boolean |No |指出会员投注时出现赔率变更并是否接受任何赔 率。 <p>默认是只接受跟高的赔率。 |
|WagerSelectio nInfos |List |Yes |投注选项详情清单|
|- WagerSelectio nId |Long |Yes |投注选项特定 ID |
|- MarketlineId |Long |Yes |盘口特定 ID |
|- BetTypeId |Int |Yes |投注类型 ID |
|- BetTypeSelecti onId |Int |Yes |<p>` `ID （只适用于定时赛事，如果</p><p>指投注类型选项 优胜冠军会是0） </p>|
|- OutrightTeamI d |Long |Yes |<p>` `ID. （只适用于优胜冠军，如果定</p><p>队伍或参赛者 时赛事会是0） </p>|
|- OddsType |Int |Yes |赔率类型 1 = 马来盘 2 = 香港盘 3 = 欧洲盘 4 = 印尼盘 |
|- Handicap |Float |Yes |该项目仅适用于让球盘和大小盘.  对于让球盘，负值等于选项在让分，正值相反。 对于大小盘，就是大于或小于的得分比较。 如果是空值等于该让分不适用于该盘口或投注类 型。 |
|- Odds |Float |Yes | 选择赔率值|
|- HomeScore |Int |No |主队当前得分. (只适用定时滚球赛事和支持比分 的体育项目) |
|- AwayScore |Int |No |(只适用定时滚球赛事和支持比分客队当前得分的体育项目) </p>|
|- EventId |Long |Yes |<p>` `ID. </p><p>赛事的特定</p>|
|- SportId |Int |Yes |<p>` `ID. 参考附录. </p><p>指出体育项目</p>|
|- Market |Int |Yes |<p>指出“早盘”、“今日”或者“滚球”的盘口 1 = 早盘 </p><p>2 = 今日 </p><p>3 = 滚球 </p>|
|Specifiers |String |No |<p>其他下注资料。如果不适用，则提交Specifier </p><p>= null。 </p>|
|ComboSelectio ns |List |No |连串过关选项清单|
|- ComboSelectio n |Int |Yes |指出连串过关类型. 单项投注即使不是混|
|- StakeAmount |Decimal |Yes |投注金额(2 decimal places) |
|Token |String |Yes |会员令牌 |
|MemberCode |String |Yes |用户名 |
|TimeStamp |String |Yes |<p> 5 分钟 <p>新生成的时间戳将持续 |
|LanguageCode |String |Yes |使用会员语言投注|


响应** 



|范围** |数据类型|空值**  |描述 |
| - | - | - | - |
|WagerSelectionInf os |List |No |投注选项详情清单|
|- WagerId |String |No |下注成功的注单号|
|- BetStatusMessage |String |No |对于相应组合选择的注单状态|
|- ComboSelectionId |Int ||No |<p>. 单项投注即使不是混合过关也会被显</p><p>指出连串过关类型 示. 参考附录3.6 </p>|
|- BetConfirmationS tatus |Int |No |<p>投注状态确认</p><p>1 = Pending 待处理 </p><p>2 = Confirmed 已确认 </p><p>3 = Rejected (refers to Danger Cancel) 已拒绝（危险球取 消） </p>|
|AcceptedWagerSe lectionList |List |Yes |<p>投注资料清单 </p><p>下注成功的</p>|
|- StakeOdds |Float |Yes |接收赔率选项|
|- BetTypeSelectionI d |Int |Yes |<p>投注选项类型ID (仅适用于定时赛事</p><p>, 如果优胜冠军会是 0) </p>|
|- OutrightTeamId |Long |Yes |<p>团队或参赛者ID </p><p>(仅适用于优胜冠军赛事</p><p>, 如果是定时赛事会是 0) </p>|
|- EventId |Long |Yes |赛事ID. |
|如果Bet Status Message = 1107，将返回以下内容|
|UpdatedWagerSel ectionInfos |List |No |<p>. </p><p>投注选项详情清单</p>|
|- Status |Int |No |<p>.  </p><p>显示投注选项状态的编码</p>|
|- RefId |Long |No |参考ID. |
|- EventId |Long |No |<p>` `ID. </p><p>赛事的特定</p>|
|- MarketlineId |Long |No |盘口清单 |
|- MarketlineStatusI d |Int |No |<p>. </p><p>指出盘口状态 1 = 开盘 </p><p>2 = 关盘 </p>|
|- BetTypeId |Int |Yes |投注类型 ID. |
|- WagerSelectionId |Long |No |<p>` `ID. </p><p>投注选项的特定</p>|
|- Handicap |Float |Yes |该项目仅适用于让球盘和大小盘.  对于让球盘，负值等于选项在让分，正值相反。 对于大小盘，就是大于或小于的得分比较。 如果是空值等于该让分不适用于该盘口或投注类型。|
|- Specifiers |String |Yes |其他下注资料|
|- BetTypeSelectionI d |Int |No |<p>` `ID. （只适用于定时赛事，如果优胜冠军会</p><p>投注选项类型 是0） </p>|
|- OutrightTeamId |Long |No |<p>` `ID. （只适用于优胜冠军，如果定时赛事会</p><p>优胜冠军类型 是0） </p>|
|- HomeScore |Int |Yes |<p>. (只适用定时滚球赛事) </p><p>主队当前得分</p>|
|- AwayScore |Int |Yes |<p>. (只适用定时滚球赛事) </p><p>客队当前得分</p>|
|- OddsType |Int |No |<p>赔率类型 </p><p>1 = 马来盘 </p><p>2 = 香港盘 </p><p>3 = 欧洲盘 </p><p>4 = 印尼盘 </p><p>只有让球, 大/小和单/双注类型可以作为返回 OddsType 的 参考。 </p><p>对于其他投注类型，将返回 OddsType = 3（欧洲盘）。 串关只支持OddsType =3（欧洲盘）。 </p>|
|- Odds |Float |No |<p>.  </p><p>选择赔率值</p>|
|- SportId |Int |No |<p>` `ID. 参考附录. </p><p>指出体育项目</p>|
|- Market |Int |No |<p>指出“早盘”、“今日”或者“滚球”的盘口 1 = 早盘 </p><p>2 = 今日 </p><p>3 = 滚球 </p>|
|UpdatedBetSettin g |List |No |<p>. </p><p>投注设置清单</p>|
|- RefId |Long |No |参考ID. |
|- MaxStakeAmount |Decimal |No |最高投注限额|
|- MinStakeAmount |Decimal |No |<p>. </p><p>最低投注限额</p>|
|- NoOfCombination |Int |No |<p>/连串过关类型注单. </p><p>指出排列数量</p>|
|- ComboSelection |Int |No |<p>. 单项投注即使不是混</p><p>指出连串过关类型</p>|
|- EstimatedPayout Amount |Decimal |No |预测派彩金额根据 $1投注金额. |
|AvailableBalance |Float |Yes |可用余额. |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功（一个或以上的成功投注） |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|
|**305** |无效语言编码|
|**335** |无效投注类型 |
|**336** |无效投注类型 ID |
|**337** |无效投注类型 ID |
|**338** |无效 盘口 ID |
|**340** |无效连串过关选项|
|**342** |无效投注类型选项 ID |
|**343** |无效优胜冠军队伍 ID |
|**344** |无效赔率类型|
|**345** |无效让球盘|
|**346** |无效赔率 |
|**347** |无效主队得分|
|**348** |无效客队得分|
|**351** |无效伺服器 IP 地址 |
|**352** |无效客户 MAC 地址 |
|**353** |无效用户代理|
|**355** |超出投注上限 |
|**395** |在地区限制投注|
|**1000** |投注错误（没有成功投注）|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
|**1554** |无效注单 |
|**1556** |虚拟足球未启用|
|**1557** |虚拟篮球未启用|
|**100** |成功 |
|**380** |无可选盘口|
|**411** |无效货币 |
|**1000** |投注错误 |
|**1001** |赔率更新中|
|**1102** |会员用户不活跃|
|**1103** |余额不足 |
|**1105** |投注金额超于限额|
|**1106** |投注金额低于最小投注额|
|**1107** |赔率已变更|
|**1108** |这赛事总投注金额超于限额|
|**1126** |所选赛事不支持连串过关，请选其他赛事|
|**1132** |无效投注金额|
|**1135** |比赛日期验证失效|
|**1136** |赛季 ID 验证失效 |
|**1141** |此项体育不存在|
|**1200** |投注被拒 |
范例** 

*Table 34: PlaceBet Request* 

{ 

`    `"WagerType": 1, 

`    `"CustomerIP": "192.168.10.11", 

`    `"ServerIP": "192.168.14.128", 

`    `"CustomerMACAddress": null, 

`    `"UserAgent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/98.0.4758.82 Safari/537.36", 

`    `"AppDeviceName": null, 

`    `"AppModel": null, 

`    `"AppOSVersion": null, 

`    `"AppPlatform": null, 

`    `"AppVersion": null, 

`    `"IsComboAcceptAnyOdds": false, 

`    `"WagerSelectionInfos": [ 

`        `{ 

`            `"WagerSelectionId": 3089666124, 

`            `"MarketlineId": 317418254, 

`            `"BetTypeId": 1, 

`            `"BetTypeSelectionId": 1, 

`            `"OutrightTeamId": 0, 

`            `"OddsType": 1, 

`            `"Handicap": 6.75, 

`            `"Odds": 0.91, 

`            `"HomeScore": null, 

`            `"AwayScore": null, 

`            `"EventId": 22220715, 

`            `"SportId": 1, 

`            `"Market": 2, 

`            `"Season": 0, 

`            `"MatchDay": 0, 

`            `"Specifiers": null 

`        `} 

`    `], 

`    `"ComboSelections": [ 

`        `{ 

`            `"ComboSelection": 0, 

`            `"StakeAmount": 100.0 

`        `} 

`    `], 

`    `"Token": "5ec597f2-1c1d-4662-9dec-4e0dca8ab21a", 

`    `"MemberCode": "adminmelcny", 

`    `"TimeStamp": "h2ylCbA6ZXhvljvlm6dl6Atywsr1bu9zDbVVOj3loDw=",     "LanguageCode": 1, 

`    `"IsCombo": false 

}  

请求** 

*Table 35: PlaceBet Response* 

{ 

`    `"WagerSelectionInfos": [ 

`        `{ 

`            `"WagerId": "2202110412082572", 

`            `"BetStatusMessage": "100", 

`            `"ComboSelectionId": 0, 

`            `"BetConfirmationStatus": 2, 

`            `"EstimatedPayoutFullAmount": 91.0         } 

`    `], 

`    `"AcceptedWagerSelectionList": [ 

`        `{ 

`            `"StakeOdds": 0.91, 

`            `"BetTypeSelectionId": 1, 

`            `"EventId": 22220715 

`        `} 

`    `], 

`    `"UpdatedWagerSelectionInfos": [], 

`    `"UpdatedBetSetting": [], 

`    `"AvailableBalance": 700.0, 

`    `"ServerTime": "2022-02-11T04:10:06.8767114-04:00",     "StatusCode": 100, 

`    `"StatusDesc": "Success" 

}**  

响应** 

20. **GETBETLIS**T索取投注明细

描述** 

此 API 常用于检索会员在各场赛事中未结算的投注. 在一般情况下, 投注未得到结算出于 赛事还没完毕, 但依然存在一些场合投注先得到结算 (投注处于作废或取消状态被视为已 结算无论赛事是否完毕)。将不提供兑现投注。 

访问频率限制: 5 秒 请求** 



|范围**  |数据类型|强制性**  |描述 |
| - | - | - | - |
|BetConfirmatio nStatus |List |Yes |<p>确认投注状态清单. </p><p>1 = Pending 待处理 </p>2 = Confirmed 已确认 </p>3 = Rejected (refers to Danger Cancel) 已拒绝 (危险球取消) </p>4 = Cancelled 已取消 |
|StartDate |Date Time |No |<p>` `GMT-4. 这是针对赛事日期和时</p><p>开始时间时区为 间。 </p>|
|EndDate |Date Time |No |<p>` `GMT -4. 这是针对赛事日期和时</p><p>结束时间时区为 间。 </p>|
|LanguageCode |String |Yes |使用会员语言|
|Token |String |Yes |会员令牌 |
|MemberCode |String |Yes |用户名 |
|TimeStamp |String |Yes |新生成的时间戳将持续 5 分钟 |

响应** 

|范围** |数据类型|空值**  |描述 |
| - | - | - | - |
|WagerList |List |No |投注清单 |
|- WagerId |String |No |下注成功的注单号|
|- WagerCreationDa teTime |Date Time ||No |投注创建的日期和时间|
|- MemberCode |String |No |用户名 |
|- InputtedStakeAm ount |Decimal |No |会员提交的投注金额|
|- MemberWinLoss Amount |Decimal |No |输赢金额 |
|- Outcome |Integer |Yes |结算后投注的结果。<p>（1=赢，2=输，3=平，4=赢一半，5=输一半） <p>对于取消、未结算或兑现的投注，价值将为空。|
|- OddsType |Int |No |赔率类型 <p>1 = 马来盘 <p>2 = 香港盘 <p>3 = 欧洲盘 <p>4 = 印尼盘 |
|- WagerType |Int |No |指投注性质<p>1 = Single 单注 <p>2 = Combo 连串过关 |
|- BettingPlatform |String |Yes |投注的设备|
|- BetConfirmationS tatus |Int |No |<p>确认投注状态清单. <p>1 = Pending 待处理 <p>2 = Confirmed 已确认 <p>3 = Rejected (refers to Danger Cancel) 已拒绝 (危险球取消) <p>4 = Cancelled 已取消 |
|- BetSettlementStat us |Int |No |0 = Not Settled 未结算 1 = Settled 已结算 |
|- BetResettled |Int |No |0 = Not Resettled 没重新结算 <p>1 = Resettled 有重新结算 |
|- BetTradeStatus |Int |No |0 = Not Sold 未售出 <p>1 = Sold 已售出 <p>2 = In Progress 进行中 <p>3 = Cancelled 已取消 <p>对于已售出的投注，无论是否赛事已经结算， BetSettlementStatus=1 |
|- BetTradeSuccess DateTime |Date Time |Yes |指出兑现成功时间 |
|- PricingId |String |Yes |提前兑现 的价格 ID |
|- BuyBackPricing |Dec |Yes |提前兑现提供的回购价格|
|- BetTradeBuyBack Amount |Dec |Yes |<p>. 只有已售给提前兑现的投注产生<p>提前兑现已买投注的金额 数值 |
|- NoOfCombination |Int |No |<p>/投注数字 </p><p>指出连串过关类型的排列</p>|
|- ComboSelection |Int |No |<p>. 单项投注即使不是混合过关也会被显</p><p>指出连串过关类型 示. 参考附录3.6 </p>|
|- PotentialPayout |Decimal |No |投注潜在的派彩金额|
|- CanSell |Boolean |No |指出投注可售给提前兑现|
|- WagerItemList |List |No |<p>. 对于单项投注, 主要投注</p><p>一个主要投注至少包含一项投注 将包含一项投注. 对于混合过关</p><p>, 主要投注将包含多项投注</p><p>(因为它是于不同的赛事进行多项选择</p><p>) </p>|
|-- WagerItemConfir mationStatus |Int |No |<p>指出每项投注的确认状态</p><p>1 = Pending 待处理 </p><p>2 = Confirmed 已确认 </p><p>3 = Rejected (refers to Danger Cancel) 已拒绝（参考危险球 取消） </p><p>4 = Cancelled 已取消 </p>|
|-- WagerItemConfir mationType |Int |No |<p>指出每项投注的确认类型 </p><p>0 = Not Confirmed 未确认 </p><p>1 = Normal Confirmed 普通确认 2 = Danger Confirmed 危险求确认</p>|
|-- WagerItemCancel Type |Int |No |<p>. </p><p>指出每项投注是否被取消和取消类型 1 = Not Cancelled 不取消 </p><p>2 = Wager Cancelled 投注被取消 3 = Event Cancelled 赛事被取消</p>|
|-- WagerItemCancel Reason |Int |No |<p>投注被取消原因. </p><p>0 = No Reason 无原因 </p><p>1 = Danger Red Card 危险红牌 </p><p>2 = Danger Goal 危险进球 </p><p>4 = Others: Danger 其他：危险</p><p>5 = Others: System Timeout 其他：系统超 101 = Abandoned 賽事終止 </p><p>时 </p>|
|-- Market |Int |No |<p>指出“早盘”、“今日”或者“滚球”的盘口 1 = 早盘 </p><p>2 = 今日 </p><p>3 = 滚球 </p>|
|-- EventId |Long |No |赛事特定 ID |
|-- EventTypeId |Int |No |<p>指出赛事属于定时赛事（普通）或优胜冠 1 = Fixture 定时赛事 </p><p>2 = Outright 优胜冠军 </p>|
|-- EventDateTime |Date |No |赛事日期和时间|
|-- SportId |Int |No |<p>` `ID. 参考附录. </p><p>指出体育项目</p>|
|-- CompetitionId |Int |No |竞赛 ID |
|-- CompetitionName |String |No |竞赛的名称. 这将会在请求中还原特定的语言. |
|-- SourceId |String |Yes |<p>ID. </p><p>赛事的外部参考</p>|
|-- Season |String |Yes |赛季指标. 仅适用于虚拟足球, 虚拟篮球和虚拟世界杯各项 体育. |
|-- MatchDay |String |Yes |赛日指标. 仅适用于虚拟足球和虚拟篮球|
|-- EventGroupTypeI d |Int |No |<p>. 参考附录 3.4(只适用于定时赛事) </p><p>指出赛事的组别类型</p>|
|-- HomeTeamId |Int |No |<p>` `ID (只适用于定时赛事. 如果优胜冠军</p><p>主队或参赛者的特定 会是 0) </p>|
|-- HomeTeamName |String |Yes |主队名称. (只适用于定时赛事. 如果优胜冠军会是 0) 这将会在请求中还原特定的语言|
|-- AwayTeamId |Int |No |<p>` `ID (只适用于定时赛事. 如果优胜冠军</p><p>客队或参赛者的特定 会是 0) </p>|
|-- AwayTeamName |String |Yes |客队名称. (只适用于定时赛事. 如果优胜冠军会是 0) 这将会在请求中还原特定的语言|
|-- FavTeam |String |Yes |<p>. (只适用于定时赛事. 如果优胜冠军会是 0) </p><p>指出最爱队伍 H = 主队 </p><p>A = 客队 </p>|
|-- BetTypeId |Int |No |投注类型 ID |
|-- BetTypeName |String |No |<p>投注名称. 这将会在请求中还原特定的语言</p><p>. </p>|
|-- PeriodId |Int |No |<p>比赛时段 ID  1 = 全场 </p><p>2 = 上半场 3 = 下半场 </p>|
|-- BetTypeSelectionI d |Int |Yes |<p>` `ID (只适用于定时赛事，如果优胜冠军会是</p><p>投注选项类型 0) </p>|
|-- SelectionName |String |Yes |<p>名称. </p><p>投注类型选项</p>|
|-- EventOutrightNa me |String |Yes |<p>优胜冠军名称 (只适用于优胜冠军赛事，如果定时赛事会 是 0) </p><p>这将会在请求中还原特定的语</p>|
|-- OutrightTeamId |Long |No |<p>` `ID (只适用于优胜冠军，如果定时赛事会是0) </p><p>优胜冠军类</p>|
|-- OutrightTeamNa me |String |No |<p>. </p><p>优胜冠军队伍名称</p>|
|-- Odds |Float |No |投注选择的赔率值|
|-- Handicap |Float |Yes |该项目仅适用于让球盘和大小盘.  对于让球盘，只针对主队。正值等于主队在让分，负值相 反。范例： 如果handicap是0.25，就是在这盘口主队在 让0.25分。当投注是在主队，投注选项就是主队-0.25。 当投注是在客队，投注选项就是客队+0.25。 对于大小盘，就是大于或小于的得分比较。 如果是空值等于该让分不适用于该盘口或投注类型|
|-- HomeTeamHTSco re |Int |Yes |<p>上半场得分. 若不存在得分, 将还原为空值. </p><p>主队于赛事</p>|
|-- AwayTeamHTSco re |Int |Yes |<p>上半场得分. 若不存在得分, 将还原为空值. </p><p>客队于赛事</p>|
|-- HomeTeamFTSco re |Int |Yes |主队于赛事全场得分. 若不存在得分, 将还原为空值|
|-- AwayTeamFTScor e |Int |Yes |<p>. 若不存在得分, 将还原为空值<p>客队于赛事全场得分|
|-- WagerHomeTeam Score |Int |Yes |主队于投注成功后得分. 只适用于滚球定时的足球（1）， 棒球（8）， 草地曲棍球（18）， 美式足球（19）， 冰 上曲棍球（25）， 橄榄球（31）赛事. 若不存在得分, 将还 原为空值. |
|-- WagerAwayTeam Score |Int |Yes |客队于投注成功后得分. 只适用于滚球定时的足球（1）， 棒球（8）， 草地曲棍球（18）， 美式足球（19）， 冰 上曲棍球（25）， 橄榄球（31）赛事. 若不存在得分, 将还 原为空值. |
|-- OverallScore |Int |Yes |指出赛事的总体得分。 如果没有分数，将返回Null。 |
|-- WinningTeamList |List |Yes |<p>(只适用于优胜冠军赛事) </p><p>优胜冠军队伍清单</p>|
|--- WinningTeamId |Int |Yes |<p>` `ID (只适用于优胜冠军赛事) </p><p>优胜冠军队伍</p>|
|--- WinningTeamNa me |String |Yes |<p>(只适用于优胜冠军赛事) </p><p>优胜冠军队伍名称</p>|
|-- GroundTypeId |Int |No |<p>` `(只适用于定</p><p>指赛事是否举办于其中一队的主场或中立场 时赛事，如果优胜冠军会是 0) </p><p>0 = Neutral Ground 中立场 </p><p>1 = Home Ground 主场 </p>|
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|
|**349** |无效投注状态|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|

范例** 

*Table 36: GetBetList Request* 

{ 

` `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",     "Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee", 

` `"MemberCode":"spkoormb01", 

` `"LanguageCode":"eng", 

` `"BetConfirmationStatus":[1,2,3,4],   "StartDate":"2019-05-27", 

` `"EndDate":"" 

} 

请求** 

*Table 37: GetBetList Response* 

{ 

`  `"WagerList": [ 

`    `{ 

`      `"WagerId": "1907050626072763", 

`      `"WagerCreationDateTime": "2019-07-05T06:26:08.6845846-04:00",       "MemberCode": "spkoormb01", 

`      `"InputtedStakeAmount": 2.0, 

`      `"MemberWinLossAmount": 0.0, 

`      `"OddsType": 3, 

`      `"WagerType": 1, 

`      `"BettingPlatform": "Mobile", 

`      `"BetConfirmationStatus": 1, 

`      `"BetSettlementStatus": 0, 

`      `"BetTradeStatus": 0, 

`      `"PricingId": null, 

`      `"BuyBackPricing": null, 

`      `"BetTradeBuyBackAmount": 0.0, 

`      `"NoOfCombination": 0, 

`      `"ComboSelection": 0, 

`      `"PotentialPayout": 1.8, 

`      `"CanSell": false, 

`      `"WagerItemList": [ 

`        `{ 

`          `"WagerItemConfirmationStatus": 1, 

`          `"WagerItemConfirmationType": 0, 

`          `"WagerItemCancelType": 1, 

`          `"WagerItemCancelReason": 0, 

`          `"Market": 3, 

`          `"EventId": 6014772, 

`          `"EventTypeId": 1, 

`          `"EventDateTime": "2019-07-05T06:11:00-04:00",           "SportId": 1, 

`          `"CompetitionId": 15306, 

`          `"CompetitionName": "PleaseDontUserMyEvent",           "EventGroupTypeId": 1, 

`          `"HomeTeamId": 229479, 

`          `"HomeTeamName": "Mock Team A96346546", 

`          `"AwayTeamId": 229254, 

`          `"AwayTeamName": "Mock Team A96346548", 

`          `"FavTeam": "H", 

`          `"BetTypeId": 1, 

`          `"BetTypeName": "Handicap", 

`          `"PeriodId": 1, 

`          `"BetTypeSelectionId": 1, "SelectionName": "Home", "EventOutrightName": null, "OutrightTeamId": 0, "OutrightTeamName": null, "Odds": 1.9, 

"Handicap": -2.2500, "HomeTeamHTScore": null, "AwayTeamHTScore": null, "HomeTeamFTScore": null, "AwayTeamFTScore": null, "WagerHomeTeamScore": 0, "WagerAwayTeamScore": 0, "GroundTypeId": 1, "Season": 0, 

"MatchDay": 0, 

"Specifiers": null 

`        `} 

`      `] 

`    `}, 

`    `{ 

`      `"WagerId": "1907050622062762", 

`      `"WagerCreationDateTime": "2019-07-05T06:22:06.1077841-04:00",       "MemberCode": "spkoormb01", 

`      `"InputtedStakeAmount": 2.0, 

`      `"MemberWinLossAmount": 0.0, 

`      `"OddsType": 3, 

`      `"WagerType": 1, 

`      `"BettingPlatform": "Mobile", 

`      `"BetConfirmationStatus": 2, 

`      `"BetSettlementStatus": 0, 

`      `"BetTradeStatus": 0, 

`      `"PricingId": null, 

`      `"BuyBackPricing": null, 

`      `"BetTradeBuyBackAmount": 0.0, 

`      `"NoOfCombination": 0, 

`      `"ComboSelection": 0, 

`      `"PotentialPayout": 0.02, 

`      `"CanSell": false, 

`      `"WagerItemList": [ 

`        `{ 

"WagerItemConfirmationStatus": 2, "WagerItemConfirmationType": 1, 

"WagerItemCancelType": 1, 

"WagerItemCancelReason": 0, 

"Market": 1, 

"EventId": 5717369, 

"EventTypeId": 2, 

"EventDateTime": "2019-12-31T03:32:00-04:00", 

"SportId": 1, 

"CompetitionId": 7958, 

"CompetitionName": "Russia Football National League Playoff", "EventGroupTypeId": 0, 

"HomeTeamId": 0, 

"HomeTeamName": null, 

"AwayTeamId": 0, 

"AwayTeamName": null, 

"FavTeam": "H", 

`          `"BetTypeId": 11, 

`          `"BetTypeName": "Outright", 

`          `"PeriodId": 1, 

`          `"BetTypeSelectionId": 0, 

`          `"SelectionName": "", 

`          `"EventOutrightName": "Russia Football National League Playoff - Winner",           "OutrightTeamId": 1384, 

`          `"OutrightTeamName": "FC Ufa", 

`          `"Odds": 1.01, 

`          `"Handicap": 0.0, 

`          `"HomeTeamHTScore": null, 

`          `"AwayTeamHTScore": null, 

`          `"HomeTeamFTScore": null, 

`          `"AwayTeamFTScore": null, 

`          `"WagerHomeTeamScore": null, 

`          `"WagerAwayTeamScore": null, 

`          `"GroundTypeId": 0, 

`          `"Season": 0, 

`          `"MatchDay": 0, 

`          `"Specifiers": null 

`        `} 

`      `] 

`    `}, 

`    `{ 

`      `"WagerId": "1907050620562761", 

`      `"WagerCreationDateTime": "2019-07-05T06:20:57.4419244-04:00", 

"MemberCode": "spkoormb01", "InputtedStakeAmount": 2.0, "MemberWinLossAmount": 0.0, "OddsType": 3, 

"WagerType": 1, "BettingPlatform": "Mobile", "BetConfirmationStatus": 1, "BetSettlementStatus": 0, "BetTradeStatus": 0, 

"PricingId": null, "BuyBackPricing": null, "BetTradeBuyBackAmount": 0.0, "NoOfCombination": 0, "ComboSelection": 0, "PotentialPayout": 1.76, "CanSell": false, "WagerItemList": [ 

`        `{ 

`          `"WagerItemConfirmationStatus": 1, 

`          `"WagerItemConfirmationType": 0, 

`          `"WagerItemCancelType": 1, 

`          `"WagerItemCancelReason": 0, 

`          `"Market": 3, 

`          `"EventId": 6014772, 

`          `"EventTypeId": 1, 

`          `"EventDateTime": "2019-07-05T06:11:00-04:00",           "SportId": 1, 

`          `"CompetitionId": 15306, 

`          `"CompetitionName": "PleaseDontUserMyEvent",           "EventGroupTypeId": 1, 

`          `"HomeTeamId": 229479, 

"HomeTeamName": "Mock Team A96346546", "AwayTeamId": 229254, 

"AwayTeamName": "Mock Team A96346548", "FavTeam": "H", 

"BetTypeId": 1, 

"BetTypeName": "Handicap", 

"PeriodId": 1, 

"BetTypeSelectionId": 1, 

"SelectionName": "Home", "EventOutrightName": null, "OutrightTeamId": 0, 

`          `"OutrightTeamName": null,           "Odds": 1.88, 

`          `"Handicap": -2.2500, 

`          `"HomeTeamHTScore": null,           "AwayTeamHTScore": null, 

`          `"HomeTeamFTScore": null, 

`          `"AwayTeamFTScore": null, 

`          `"WagerHomeTeamScore": 0,           "WagerAwayTeamScore": 0,           "GroundTypeId": 1, 

`          `"Season": 0, 

`          `"MatchDay": 0, 

`          `"Specifiers": null 

`        `} 

`      `] 

`    `}]} 

响应** 

21. **GETSTATEMENT** 索取投注账目

描述** 

此 API 常用于索取会员所有已结算/进行交易的投注明细, 无论投注中的赛事是否完毕.  访问频率限制: 每 2 秒 1 次（一样的请求参数）

请求** 



|范围**  |数据类型|强制性**  |描述 |
| - | - | - | - |
|Token |String |Yes |会员令牌 |
|MemberCode |String |Yes |用户名 |
|DateType |Int |No |日期类型 <p>1 = 赛事时间 <p>2 = 下注时间 <p>3 = 结算时间 <p>默认 = 1 |
|StartDate |Date |Yes |开始时间时区为 GMT-4. 最初日期不可早于31天 前.|
|EndDate |Date |Yes |结束时间时区为 GMT -4.|
|StartTime |Time |No |开始时间. 默认为 00:00:00 |
|EndTime |Time |No |结束时间. 默认为 23:59:59 |
|LanguageCode |String |Yes |使用会员语言|
|TimeStamp |String |Yes |新生成的时间戳将持续 5 分钟|

响应** 

与 GetBetList 一致. 

状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**202** |无效用户名|
|**107** |无效开始时间|
|**108** |无效结束时间|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 38: GetStatement Request* 

{ 

` `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",     "Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee", 

` `"MemberCode":"spkoormb01", 

` `"LanguageCode":"eng", 

` `"DateType":1,        

` `"StartDate":"2019-07-04", 

` `"EndDate":"2019-07-05"  

} 

请求** 

22. **GETBALANCE** 索取余额

描述** 

此 API 常用在检索会员的余额. 访问频率限制: 30 秒 

请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|Token |String |Yes |会员令牌 |
|MemberCode |String |Yes |用户名 |
|TimeStamp |String |Yes |新生成的时间戳将持续 5 分钟|

响应** 

|范围** |数据类型**  |空值**  |描述 |
| - | - | - | - |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
|AvailableBalance |Float |No |可用余额 |
|OutstandingBalan ce |Float |No |待结算余额|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 39: GetBalance Request* 

{ ![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.014.png)

`  `"Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee", 

`  `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",   "MemberCode":"spkoormb01"  

} 

请求** 

*Table 40: GetBalance Response* 

{ 

`  `"AvailableBalance": 99779626.25, 

`  `"OutstandingBalance": 117322.0, 

`  `"ServerTime": "2019-07-05T06:26:32.7114298-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

IPIS Mobile

23. **GETPENDINGWAGERSTATUS** 索取待处理 描述** 

此 API 用于检索待处理投注状态. 

访问频率限制: 5 秒 

请求** 

投注状态

IPIS Mobile
|范围**  |数据类型|强制性**  |描述 |
| - | - | - | - |
|Token |String |Yes |会员令牌. |
|WagerIds |List of String |Yes |投注ID清单. |
|MemberCode |String |Yes |用户名 |
|LanguageCode |String |Yes |会员选用的语言.|
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟.|

响应** 

|范围** |数据类型**  |空值**  |描述 |
| - | - | - | - |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
|PendingWagerStatusList |List |No |确认状态的投注清单|
|- WagerId |String |No |投注ID. |
|- BetConfirmationStatus |Int |No |<p>投注确认状态. <p>1 = 待处理 <p>2 = 确认 <p>3 = 已拒绝 (参考危险球取消) <p>4 = 已取消 |
|- WagerItemStatus |List |No |投注中的投注项目清单 |
|-- WagerItemConfirmationStatus |Int |No |<p>已取消投注的取消原因. <p>0 = 无原因 <p>1 = 危险情况 红牌 <p>2 = 危险情况 进球|
|-- WagerItemCancelReason |Int |No |<p>已取消投注的取消原因. <p>0 = No Reason 无原因 <p>1 = Danger Red Card 危险红牌 <p>2 = Danger Goal 危险进球 <p>4 = Others: Danger 其他:危险 <p>5 = Others: System Timeout <p>其他:系统超时|
|-- EventId |Long |No |赛事ID |

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|
|**370** |找不到主单或注单已 结算|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|

范例** 

*Table 41: GetPendingWagerStatus Request* 

{ 

` `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",     "Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee", 

` `"MemberCode":"spkoormb01", 

` `"LanguageCode":"eng", 

` `"WagerIds":[1901140306398137] 

} 

请求** 

*Table 42: GetPendingWagerStatus Response* 

{ 

`  `"ServerTime": "2019-07-05T06:26:45.1062187-04:00", 

`  `"StatusCode": 370, 

`  `"StatusDesc": "Wager cannot be found or wager already settled" } 

响应** 

24. **GETANNOUNCEMENT** 索取通告

描述** 

此 API 常用于检索通告. 所有在前 31 天内上传过的通告将被检索. 这将不包括任何被屏蔽的 通告. 

访问频率限制:  请求** 



|范围**  |数据类型 |强制性**  |描述 |
| - | - |  - | - |
|OrderBy |Int |No |<p>指定使用的排序 <p>1 = 通告日期时间升序 <p>2 = 通告日期时间降序 <p>默认 = 1 |
|TimeStamp |String |Yes |新生成的时间戳将持续 5 分钟|


响应** 

|范围** |数据类型|空值**  |描述 |
| - | - |  - | - |
|Announcement |List |No |通告清单 |
|- AnnouncementId |Long |No |通告 ID |
|- PostingDate |Date |No |通告日期和时间|
|- ExpiryDate |Date |No |通告过期日期和时间|
|- DateUpdated |Date |No |通告更新日期|
|- AnnouncementDe tail |List |No |通告详情清单|
|-- LanguageCode |String |No |通告语言 |
|-- Content |String |Yes |内容 |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|


状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 43: GetAnnouncement Request* 

{ 

` `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=" } 

请求** 

*Table 44: GetAnnouncement Response* 

{ 

`  `"Announcement": [ 

`    `{ 

`      `"AnnouncementId": 985, 

`      `"PostingDate": "2019-06-25T04:11:03.0000000-04:00", 

`      `"ExpiryDate": "2019-07-15T04:11:00.0000000-04:00", 

`      `"DateUpdated": "2019-06-25T04:12:27.5333431-04:00", 

`      `"AnnouncementDetail": [ 

`        `{ 

`          `"LanguageCode": "ENG", 

`          `"Content": "????GodWar?????All The Sunflower Your Bali Trip is Coming! 12 July - 15 July ????"         }, 

`        `{ 

`          `"LanguageCode": "CHS", 

`          `"Content": "????GodWar?????All The Sunflower Your Bali Trip is Coming! 12 July - 15 July ????"         } 

`      `] 

`    `}, 

`    `{ 

`      `"AnnouncementId": 984, 

`      `"PostingDate": "2019-06-25T04:11:12.0000000-04:00", 

`      `"ExpiryDate": "2019-10-31T04:11:00.0000000-04:00", 

`      `"DateUpdated": "2019-06-25T04:12:04.7674377-04:00", 

`      `"AnnouncementDetail": [ 

`        `{ 

`          `"LanguageCode": "ENG", 

`          `"Content": "????GodWar?????Autumn is Coming Soon! Please Prepare Your Leaves To Let It DRY! ??????????????????" 

`        `}, 

`        `{ 

`          `"LanguageCode": "CHS", 

`          `"Content": "????GodWar?????Autumn is Coming Soon! Please Prepare Your Leaves To Let It DRY! ??????????????????" 

`        `} 

`      `] 

`    `} 

`  `], 

`  `"ServerTime": "2019-07-05T06:26:45.3249580-04:00", 

`  `"StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

25. **GETMEMBERBYTOKEN** 索取会员信息 描述** 

此 API 常用于检索会员信息. 

访问频率限制:  

请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|Token |String |Yes |会员令牌 |
|MemberCode |String |Yes |用户名 |
|TimeStamp |String |Yes |<p>` `5 分钟 </p><p>新生成的时间戳将持续</p>|
响应** 



|范围** |数据类型||空值**  |描述 |
| - | - | :- | - | - |
|MemberCode |String ||No |用户名 |
|CurrencyCode |String ||No |货币编码 |
|SpreadGroup |String ||No |水位分组 |
|CompanyId |Int ||No |公司ID |
|StatusCode |Int ||No |指出请求状态编码|
|StatusDesc |String ||No |状态编码的描述含义|
状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 45: GetMemberByToken Request* 

{ 

`  `"Token": "0ead5efd-301a-4a2b-befe-da1596d091fd", 

`  `"TimeStamp": "UQmCC9dTA5gwnFZe1ge+w6rO1cFUOPGd7SYuuL4Ma2A=" } 

请求** 

*Table 46: GetMemberByToken Response* 

{ 

`    `"MemberCode": "testmember", 

`    `"CurrencyCode": "RMB", 

`    `"SpreadGroup": “A”, 

`    `"CompanyId": 7, 

`    `"ServerTime": "2020-02-06T03:40:06.9315784-04:00",     "StatusCode": 100, 

`    `"StatusDesc": "Success" 

} 

响应** 

26. **GETUSERPREFERENCES** 索取用户自定义 描述** 

此 API 常用于检索用户自定义. 

访问频率限制:  请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|Token |String |Yes |会员令牌 |
|MemberCode |String |Yes |用户名 |
|TimeStamp |String |Yes |<p>` `5 分钟 </p><p>新生成的时间戳将持续</p>|
响应** 



|范围** |数据类型||空值**  |描述 |
| - | - | :- | - | - |
|AvailableOddsTyp e |List ||No |赔率类型 1 = 马来盘 |
|||||2 = 香港盘 |
|||||3 = 欧洲盘 |
|||||4 = 印尼盘 |
|SelectedOddsTyp e |Int ||No |赔率类型 1 = 马来盘 |
|||||2 = 香港盘 |
|||||3 = 欧洲盘 |
|||||4 = 印尼盘 |
|SelectedTimeZone |Int ||No |会员时区 |
|FastBetSingle |List ||No |单项投注中三项快速投注金额清单|
|FastBetCombo |List ||No |连串过关投注中三项快速投注金额清单|
|SelectedSport |Int ||No |会员首选的体育|
|SelectedEventSort ing |Int ||No |<p>指定使用的排序.  </p><p>1 = 赛事日期时间顺序</p>|
|||||2 = IM 体育顺序 |
|BettingStyle |Int ||No |投注方式 |
|||||1 = 专业 |
|||||2 = 简单 |
|ComboAutoAccep t |Int ||No |连串过关自动接受模式 1 =自动接受更高的赔率|
|||||2 =自动接受任何赔率|
|LanguageCode |String ||Yes |使用会员语言|
|StatusCode |Int ||No |指出请求状态编码|
|StatusDesc |String ||No |状态编码的描述含义|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|

|**400** |系统错误 |
| - | - |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 47: GetUserPreferences Request* 

{ 

`  `"Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee", 

`  `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",   "MemberCode":"spkoormb01"  

} 

请求** 

*Table 48: GetUserPreferences Response* 

{ 

"AvailableOddsType": [ 

1, 

2, 

3, 

4 

], 

"SelectedOddsType": 1, 

"SelectedTimeZone": 11, 

"FastBetSingle": [ 

10, 

100, 

1000 

], 

"FastBetCombo": [ 

20, 

200, 

2000 

], 

"SelectedSport": 2, 

"SelectedEventSorting": 1, "SelectedViewTypeBySport": [ 

{ 

"SportId": 1, 

"SelectedViewType": 1 

}, 

{ 

"SportId": 2, 

"SelectedViewType": 2 

} 

], 

"ServerTime": "2019-07-19T04:22:46.0816743-04:00", 

"StatusCode": 100, "StatusDesc": "Success" 

} 

响应** 

27. **UPDATEUSERPREFERENCES** 更新用户自定义 描述** 

此 API 常用于更新用户自定义. 

访问频率限制:  

请求** 



|范围**  |数据类型||强制性**  |描述 |
| - | - | :- | - | - |
|Token |String ||Yes |会员令牌 |
|MemberCode |String ||Yes |用户名 |
|SelectedOddsT ype |Int ||Yes |赔率类型 1 = 马来盘 |
|||||2 = 香港盘 |
|||||3 = 欧洲盘 |
|||||4 = 印尼盘 |
|SelectedTimeZ one |Int ||Yes |时区。参考附录|
|FastBetSingle |List ||Yes |单项投注中三项快速投注金额清单|
|||||每项金额范围为 0 – 999999 |
|FastBetCombo |List ||Yes |连串过关投注中三项快速投注金额清单|
|||||每项金额范围为 0 - 999999 |
|SelectedSport |Int ||No |会员首选的体育|
|SelectedEventS orting |Int ||No |<p>指定使用的排序.  </p><p>1 = 赛事日期时间顺序</p>|
|||||2 = IM 体育顺序 |
|BettingStyle |Int ||No |投注方式 |
|||||1 = 专业 |
|||||2 = 简单 |
|ComboAutoAcc ept |Int ||No |连串过关自动接受模式 1 =自动接受更高的赔率|
|||||2 =自动接受任何赔率|
|LanguageCode |String ||No |使用会员语言|
|TimeStamp |String ||Yes |<p>` `5 分钟 </p><p>新生成的时间戳将持续</p>|
响应** 

|范围** |数据类型**  |空值**  |描述 |
| - | - | - | - |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|
状态编码** 



|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**102** |无效令牌 |
|**202** |无效用户名|
|**313** |无效体育 ID |
|**344** |无效赔率类型|
|**356** |无效时区 |
|**357** |无效单项快速投注|
|**358** |无效连串过关快速投 注 |
|**397** |无效排序|
|**414** |无效投注方式|
|**418** |无效连串过关自动接 受模式 |
|**2102** |快速投注值不能低于 最少投注设置|
|**2103** |连串过关投注值不能 低于最少投注设置|
|**400** |系统错误 |
|**403** |无效查看类型 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 49: UpdateUserPreferences Request* 

{ 

"SelectedOddsType": 1, "SelectedTimeZone": 11, "FastBetSingle": [ 10,100,1000 

], 

"FastBetCombo": [ 20,200,2000 

], 

"SelectedSport": 1, 

"SelectedEventSorting": 1, 

"SelectedViewTypeBySport":[ 

{ 

"SportId": 1, 

"SelectedViewType":1 

}, 

{ 

"SportId": 2, 

"SelectedViewType":2 

} 

], 

"Token": "bd588ceb-12f6-4f61-ba3e-858e62c591ed", "MemberCode": "imtest02", 

"TimeStamp": "z24HakpPBCKIthA9UJT4EmtfA4pgl+8+kfV5ZcajPRo=", "LanguageCode": 1, 

"IsCombo": true 

} 

请求** 

*Table 50: UpdateUserPreferences Response* 

{ 

`  `"ServerTime": "2019-07-05T06:26:45.2780818-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

28. **GETFAVOURITEEVENT** 索取所有收藏赛事** 描述** 

此 API 用于检索所有收藏赛事的赛事及赔率信息. 访问频率限制:  

请求** 

|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|SportIds |List of Int |Yes |指出体育项目. 参考附录3.3.|
|Market |Int |No |<p>指出“早盘”、“今日”或者“滚球”的盘口 <p>1 = 早盘 <p>2 = 今日 <p>3 = 滚球 |
|ProgrammeIds |List of Int |No |每场竞赛程序的特定ID. 没提供竞赛程序就不会有竞赛程序的过滤。 |
|EventGroupTypeI ds |List of Int |No |可选参数用于指出只返回特定赛事组别类型的 赛果. 参考附录3.4。|
|BetTypeIds |List of Int |No |指出返回的投注类型|
|PeriodIds |List of Int |No |<p>筛选时段的ID清单.  <p>1 = FT 全场 <p>2 = 1H 上半场 <p>3 = 2H 下半场 </p>|
|MarketlineLevels |List of Int |No |可选参数用于指出只返回特定的盘口级别。只是针对主要玩法。|
|IncludeGroupEvents |Boolean |Yes |指出属于相同赛事组别ID的其他赛事是否同时 被返回|
|OddsType |Int |Yes |<p>赔率类型 <p>1 = 马来盘 <p>2 = 香港盘 <p>3 = 欧洲盘 <p>4 = 印尼盘 |
|OrderBy |Int |No |<p>指定使用的排序. <p>1 = 赛事日期时间顺序 <p>2 = IM 体育顺序 <p>默认 = 1 |
|MemberCode |String |Yes |用户名 |
|Token |String |No |会员令牌. |
|LanguageCode |String |No |为本地名称返回的语言.|
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟.|

响应** 

该响应与 GetEventInfoMBT 响应一致. 唯一的区别是 Delta 响应参数（String）的数据类型。 


状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID|
|**332** |无效盘口 |
|**336** |无效投注类型 ID|
|**400** |系统错误 |
|**397** |无效排序 |
|**700** |维护 |
|**710** |访问地区限制|
范例** 

*Table 51: GetFavouriteEvent Request* 

{ 

` `"TimeStamp":"fMN5hS5qXUHMeYCE7r0R+JwkK495N/2e1Y/ES3kTji0=",  "Token":"b5e6ff21-1141-4b98-b48c-3cd5c06391fd", 

` `"SportIds":[],    

` `"BetTypeIds":[],    

` `"PeriodIds":[],     

` `"OddsType":1, 

` `"OrderBy":1,        

` `"LanguageCode":"eng", 

` `"MemberCode":"spkoormb02"  

}** 

请求** 

响应** 

该响应与 GetEventInfoMBT 响应一致. 

29. **ADDFAVOURITEEVENT** 加收藏赛事** 

描述** 

此 API 用于加收藏赛事. 访问频率限制:  

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟.|
|Token |String |No |会员令牌. |
|MemberCode |String |No |用户名. |
|SportId |Int |Yes |指出体育项目. 参考附录3.3.|
|EventIds |List of Int |Yes |检索赛事 ID清单 |
|LanguageCode |String |Yes |为本地名称返回的语言.|

响应** 

|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|StatusCode |String |Yes |指出请求状态编码.|
|StatusDesc |String |Yes |状态编码的描述含义.|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|

范例** 

*Table 52: AddFavouriteEvent Request* 

{ 

` `"TimeStamp":"ZCwqRHgZze0epmcjwjsrJL0wmpDLgoZ+0OIlIl64Um8=",  "Token":"28764819-934a-4d9a-a044-9d3705407278", 

` `"SportId":1, 

` `"EventIds":[5417419],   /\*Mandatory; List\*/ 

` `"MemberCode":"ksp123456"  

} 

请求** 

*Table 53: AddFavouriteEvent Response* 

{ 

`  `"ServerTime": "2019-09-24T04:48:05.8671409-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

30. **REMOVEFAVOURITEEVENT** 删除收藏赛事** 

描述** 

此 API 用于删除收藏赛事. 访问频率限制:  

请求** 



|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|TimeStamp |String |Yes |新生成的时间戳将持续5分钟.|
|Token |String |No |会员令牌. |
|MemberCode |String |No |用户名. |
|SportId |Int |Yes |指出体育项目. 参考附录3.3.|
|EventIds |List of Int |Yes |检索赛事 ID清单 |
|LanguageCode |String |Yes |为本地名称返回的语言.|

响应** 

|范围**  |数据类 型**  |强制性**  |描述 |
| - | :- | - | - |
|StatusCode |String |Yes |指出请求状态编码.|
|StatusDesc |String |Yes |状态编码的描述含义.|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|


范例** 

*Table 54: RemoveFavouriteEvent Request* 

{ 

` `"TimeStamp":"ZCwqRHgZze0epmcjwjsrJPsTOJH0qkY6ZVqzH1V4eUI=",  "Token":"b10b8f1e-7cf0-4a2a-a314-3292af9559c3", 

` `"SportId":1, 

` `"EventIds":[5417419],   /\*Mandatory; List\*/  "MemberCode":"ksp123456"  

} 

请求** 

*Table 55: RemoveFavouriteEvent Response* 

{ 

`  `"ServerTime": "2019-09-24T04:48:11.4955995-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

31. **GETDELTABETTRADE** 提前兑现 **DELTA**

描述** 

此 API 用于检索提前兑现的 Delta 变化. 访问频率限制: 5 秒 


请求** 

|范围**  |数据类型|强制性**  |描述 |
| - | - | - | - |
|TimeStamp |String |Yes |<p>5分钟.  </p><p>新生成的时间戳将持续</p>|
|Token |String |Yes |会员令牌. |
|MemberCode |String |Yes |用户名. |
|WagerIds |List of String |Yes |投注ID清单. |
|Delta |Double |No | <p>Delta 版本 <p>格式：yyMMddHHmmssfff <p>范例：171219001225452 <p>提交0进行初始请求。|

响应** 

|范围** |数据类 型**  |空值**  |描述 |
| - | :- | - | - |
|Value |List |No |提前兑现版本改变清单 |
|WagerId |String |No |下注成功的注单号.|
|BetTradeStatus |Int |No |<p>0 = 未售出 <p>1 = 已售出 <p>2 = 进行中 <p>3 = 已取消 |
|BetTradeBuyBackAmount |Dec |Yes |提前兑现已买投注的金额. 只有已售给提前兑现的投注 产生数值.|
|BuyBackPricing |Dec |Yes |提前兑现提供的回购价格.|
|PricingId |String |Yes |提前兑现提供的价格ID. |
|CanSell |Boolean |No |指出投注是否可售给提前兑现.|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|


范例** 

*Table 56: GetDeltaBrtTrade Request* 

{ 

`  `"TimeStamp":"ruSHsDyYXBoLDYvbHDCx0m1zDGJg6Btx974bMn5l+n8=",    "MemberCode":"spkoormb01", 

`  `"Token":"b54111d0-cccb-4e28-a398-ebc88a2fc5b3", 

`  `"Delta":0  ![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.017.png)} 

请求** 

32. **SUBMITBUYBACK**  提交回购

描述** 

此 API 常用于为提前兑现提交的回购请求. 当一个代码成功响应, 等于回购请求已成功地提 交处理. 

访问频率限制:  请求** 



|范围**  |数据类型|强制性**  |描述 |
| - | - | - | - |
|WagerId |String |Yes |成功下注的投注单号|
|BuyBackPricin g |Decimal |Yes |提前兑现提供的回购价格|
|PricingId |String |Yes |提前兑现 的价格 ID |
|Token |String |Yes |会员令牌 |
|MemberCode |String |Yes |用户名 |
|TimeStamp |String |Yes |新生成的时间戳将持续 5 分钟|


响应** 

|范围** |数据类型**  |空值**  |描述 |
| - | - | - | - |
|BuyBackPricing |Dec |Yes |提前兑现提供的回购价格|
|PricingId |String |Yes |提前兑现 的价格 ID |
|StatusCode |Int |No |指出请求状态编码|
|StatusDesc |String |No |状态编码的描述含义|


状态编码** 
|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**364** |无效价格. |
|**365** |无效投注单号|
|**366** |无效回购价格 |
|**367** |价格 ID 过期 |
|**368** |投注不可出售，前一个请求正在处理中|
|**369** |投注单号已售给提前兑现 |
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|


范例** 

*Table 57: SubmitBuyBack Request* 

{     

` `"TimeStamp":"On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=",     "Token":"fd1f066e-7116-4e97-93e8-d5db34e5b8ee", 

` `"MemberCode":"spkoormb01", 

` `"WagerId":"1906070334385215", 

` `"PricingId":"075140621\_1", 

` `"BuyBackPricing":"12.5" 

} 

请求** 

*Table 58: SubmitBuyBack Response* 

{ 

`  `"BuyBackPricing": 0.0, 

`  `"PricingId": null, 

`  `"ServerTime": "2019-07-05T06:26:44.8912307-04:00",   "StatusCode": 365, 

`  `"StatusDesc": "Invalid Wager Number" 

} 

响应** 

IPIS Mobile

33. **GETLIVESTREAMINGINFO**  索取赛事直播资料

描述** 

此 API 用于检索滚球赛事的直播视频资料. 访问频率限制:  

请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|EventId |Int |Yes |赛事的特定 ID.|
|SportId |Int |Yes |指出体育项目. 参考附录3.3.|
|TimeStamp |String |Yes |新生成的时间戳将持续 5 分钟|

响应** 

|范围** |数据类型|空值**  |描述 |
| - | - | - | - |
|LiveStreamingURLs |List |Yes |现场直播 URL清单. <p>如果没有直播视频，列表将为空。|
|- Priority |Int |Yes |现场直播 URL优先级. |
|- URL |String |Yes |现场直播Url. |
|- Type |Int |Yes |<p>播放类型. <p>0 = Unknown <p>1 = iFrame <p>2 = FLV <p>3 = M3U8 |
|- Referer |String |Yes |视频来源的Referer |
|StatusCode |Int |No |指出请求状态编码<p>当赛事不活跃或不可用或找不到时，返回380 |
|StatusDesc |String |No |状态编码的描述含义|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**313** |无效体育 ID |
|**334** |无效赛事 ID |
|**380** |无可选盘口|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|


范例** 

*Table 59: GetLiveStreamingInfo Request* 

{ 

`  `"SportId": 1, 

`  `"EventId": 7205157, 

`  `"TimeStamp": " On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=" } 

请求** 

*Table 60: GetLiveStreamingInfo Response* 

{ 

`  `"LiveStreamingURLs": [ 

`    `{ 

`      `"Url": "https://192.168.11.245/livestreaming/framewoplayer?url=https%3a%2f%2ffront.nanostreaming.tech%2fif rame%2fplayerplain.html%3fclient\_id%3d22%26stream\_id%3d82684%26referrer\_url%3dhttps%3a%2f%2fs ports-web-stg-ls.inplaymatrix.com%2f+", 

`      `"Priority": 1, 

`      `"Type": 1, 

`      `"Referrer": null 

`    `}, 

`    `{ 

`      `"Url": "https://www.youtube.com/watch?v=zK7ztTKzTnQ", 

`      `"Priority": 2, 

`      `"Type": 1, 

`      `"Referrer": null 

`    `} 

`  `], 

`  `"ServerTime": "2019-12-03T23:55:57.8291542-04:00", 

`  `"StatusCode": 100, 

`  `"StatusDesc": "Success" 

}** 

响应** 

34. **GETCOMPANYBYID** 以 **COMPANYID** 索取公司设定

描述** 

此 API 常用在从 CompanyID索取公司设定。

请求** 



|范围**  |数据类型**  |强制性**  |描述 |
| - | - | - | - |
|TimeStamp |String |Yes |新生成的时间戳将持续 5 分钟.|
|ReferralUrl |String |Yes |ReferralUrl。 |
响应** 



|范围** |数据类型**  |空值**  |描述 |
| - | - | - | - |
|CompanyId |Int |No |公司ID |
|ShowBetTrade |Boolean |No |指出公司是否有兑现功能。|
|AvailableOddsTyp e |List |No |指出支持的赔率类型。 |
|BRClientId |String |Yes |Bet Radar客户编号。如果不适用, 值将为null。 |
|ShowMemberCod e |Boolean |No |指出是否显示用户名。|
|ServerTime |DateTime |No |服务器时间|
|StatusCode |Int |No |指出请求状态编码.|
|StatusDesc |String |No |状态编码的描述含义.|

状态编码** 

|状态编码** |描述** |
| - | - |
|**100** |成功 |
|**101** |无效时间戳|
|**400** |系统错误 |
|**700** |维护 |
|**710** |访问地区限制|


范例** 

*Table 61: GetCompanyById Request* 

{ 

`  `"CompanyId": 7, 

`  `"TimeStamp": ""On+2WvKF79wqqOt23dI37oDSaiLMb8mw1pCPawlWUyY=" } 

请求** 

*Table 62: GetCompanyById Response* 

{ ![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.018.png)

`  `"CompanyId": 7, 

`  `"ShowBetTrade": true, 

"AvailableOddsType": [ 

1, 

2, 

3, 

4 

], 

`  `"ShowMemberCode": true, 

`  `"BRClientId": "199", 

`  `"ServerTime": "2019-10-18T02:53:21.4803120-04:00",   "StatusCode": 100, 

`  `"StatusDesc": "Success" 

} 

响应** 

3**  附录![](Aspose.Words.a0645f36-2d97-479a-89cf-6c3969ef4a5e.019.png)

1. 语言编码 



|**Language Code** |**Languages** 描述** |
| - | - |
|ENG |English |
|CHS |简体中文 |
|TH |Thai |
|VN |Vietnamese |
|ID |Indonesian |
|ES |西班牙文 |

2. 货币 编码** 

|货币编码** |货币** 名称** |加密货币** |
| - | - | - |
|ALG** |阿拉贡** |是** |
|ARS |阿根廷比索||
|BCH |比特币现金|是 |
|BDT |孟加拉塔卡||
|BND |汶来元 ||
|BRL |巴西雷亚尔||
|BTG |比特币黄金|是 |
|CLP |智利比索 ||
|CNY |中国元 ||
|DSH |达世币 |是 |
|EOS |柚子币 |是 |
|ETH |以太坊 |是 |
|EUR |欧元 ||
|GBP |英镑 ||
|GHS |加纳塞地 ||
|HBA |哈希图币 |是 |
|HKD |港币 ||
|IDR |印尼盾 ||
|JPY |日圆 ||
|KES |肯尼亚先令||
|KHR |柬埔寨瑞尔||
|KIP |寮幣 ||
|KRW |韩币 ||
|LKR |斯里兰卡卢比||
|LTC |莱特币 |是 |
|MBT |毫比特 |是 |
|MMK |缅甸元 ||
|MXN |墨西哥比索|||
|NIO |尼加拉瓜科多巴||
|PEN |秘鲁索尔 ||
|PKR |巴基斯坦卢比||
|PLN |波兰兹罗提||
|RMB |人民币 ||
|RUB |俄罗斯卢布||
|THB |泰铢 ||
|TRX |波场币 |是 |
|USD |美元 ||
|UST |USDT 加密货币 |是 |
|VND |越南盾 ||
|XLM |恒星币 |是 |
|XRP |瑞波币 |是 |
|ZEC |大零币 |是 |
|ZWD |津巴布韦元||


IPIS Mobile

\*加密货币将为以下参数支持

- AvailableBalance 
- BetTradeBuyBackAmount 
- MemberWinlossAmount 
- PotentialPayout 
- BuyBackPricing 

4 个小数位 

IPIS Mobile

3. 体育 ID 



|**SportId** |**Sports Name** |**Remarks** |
| - | - | - |
|1 |足球 ||
|2 |篮球 ||
|3 |网球 ||
|6 |田径 ||
|7 |羽毛球 ||
|8 |棒球 ||
|11 |拳击 ||
|15 |飞镖 ||

|18 |草地曲棍球|||
| - | - | :- | :- |
|19 |美式足球 |||
|21 |高尔夫球 |||
|23 |手球 |||
|25 |冰上曲棍球|||
|29 |赛车运动 ||包括赛车 |
|31 |橄榄球 |||
|32 |帆船 |||
|34 |斯诺克 / 英式台球 ||包括亚洲 9 球和台球 |
|36 |乒乓球 |||
|39 |虚拟足球 |||
|40 |排球 |||
|41 |水球 |||
|43 |虚拟篮球 |||
|44 |虚拟世界杯|||
|45 |娱乐投注 |||
|46 |虚拟国家杯|||
|47 |虚拟足球英国联赛|||
|49 |虚拟足球西班牙友谊赛|||
|51 |金融投注 |||
|52 |虚拟足球西班牙联赛|||
|53 |虚拟足球意大利联赛 |||
4. 赛事组别类型 ID 



|**EventGroupType  ID** |描述** |
| :-: | - |
|1 |主要 |
|2 |角球 |
|3 |普通 |
|4 |第一节 |
|5 |第二节 |
|6 |第三节 |
|7 |第四节 |
|8 |让分局 |
|9 |第一盘 |
|10 |第二盘 |
|11 |第三盘 |
|12 |第四盘 |
|13 |第五盘 |
|14 |让分盘 |
|15 |第 1 局 |
|16 |第 2 局 |
|17 |第 3 局 |
|18 |第 4 局 |
|19 |第 5 局 |
|20 |第 6 局 |
|21 |第 7 局 |
|22 |上半场 |
|23 |下半场 |
|24 |加时赛 |
5. 滚球时间段



|体育** |滚球时间段|
| - | - |
|所有体育 |!Live: 没有滚球时间或赛事还没开始 HT: 休息 |
|足球 |<p>1H: 上半场 </p><p>2H: 下半场 所有比赛名的前缀是 不支持秒数。</p><p>` `VS - IM 独家 FIFA20 开头, RBTime</p>|
|篮球 |Q1: 第一节 Q2: 第二节 Q3: 第三节 Q4: 第四节 1H: 上半场 2H: 下半场 OT: 加时 |
|网球 |S1: 第一盘 S2: 第二盘 S3: 第三盘 S4: 第四盘 S5: 第五盘 |
|乒乓球 |G1：第 1 局 G2：第 2 局 G3：第 3 局 G4：第 4 局 G5：第 5 局 G6：第 6 局 G7：第 7 局 |
6. 赛事顺序** 

早盘和今日 

日期顺序：

赛事日期 -》 早盘顺序 -》 竞赛名称 -》 赛事顺序 -》 主队名称 受欢迎顺序：

早盘顺序 -》 竞赛名称 -》 赛事日期 -》 赛事顺序 -》 主队名称 

滚球 

赛事日期 -》 滚球顺序 -》 竞赛名称 -》 赛事顺序 -》 主队名称 受欢迎顺序：

滚球顺序 -》 竞赛名称 -》 赛事日期 -》 赛事顺序 -》 主队名称 

7. 连串过关选项



|**ID** |描述** |
| - | - |
|0 |单注 - 选择一个事件中获胜方的投注|
|1 |三串四 - 三串四为多重投注,包括四个有三种选择的注.此投注有三个孖宝和一个三 宝 |
|2 |四串十一式 - 四串十一式 - 选择 4 个项目投注, 共十一注, 包括 1 个四串一,  4 个三串一及 6 个二串一 |
|3 |五串二十六式 - 五串二十六式 - 投注二十六个不同的过关，其中包括十个二串 一，十个三串一，五个四串一及一个五串一的过关|
|4 |六串五十七式 - 六串五十七式 - 投注 6 项选择, 共 57 注 , 包括 1 个六串一 , 6 个五串一 ,  15 个四串一 , 20 个三串一 , 15 个二串一 |
|5 |七串一百二十式 - 七串一百二十式 - 从不同事件中选出 7 个来组合为： 21 个孖 宝、 35 个三宝、35 个四关、 21 个五关、 7 个六关和 1 个过七关的注单|
|6 |八串二百四十七式 - 八串二百四十七式 - 从不同事件中选出 8 个来组合为：28 个 双宝、 56 三宝、 70 个四关、 56 个五关、 28 个六关、8 个七关、 和 1 个过八关 的注单 |
|7 |九串五百零二式|
|8 |十串一千零十三式|
|9 |两串一 |
|10 |三串一 |
|11 |四串一 |
|12 |五串一 |

|13 |六串一 |
| - | - |
|14 |七串一 |
|15 |八串一 |
|16 |九串一 |
|17 |十串一 |
|18 |所有连串过关|
8. 时区** 



|TimeZoneId |TimeZone |
| - | - |
|1 |-12:00 |
|2 |-11:00 |
|3 |-10:00 |
|5 |-09:00 |
|6 |-08:00 |
|7 |-07:00 |
|8 |-06:00 |
|9 |-05:00 |
|11 |-04:00 |
|13 |-03:00 |
|14 |-02:00 |
|15 |-01:00 |
|17 |+01:00 |
|18 |+02:00 |
|19 |+03:00 |
|21 |+04:00 |
|23 |+05:00 |
|26 |+06:00 |
|28 |+07:00 |
|29 |+08:00 |
|32 |+09:00 |
|34 |+10:00 |
|36 |+11:00 |
|37 |+12:00 |
9. 团队图标** 

在初始集成期间将提供和发送所有可用的团队图标。 任何后续的添加或更新将通过 FTP 提 供。 

如果 FTP 服务器实施 IP 限制，请将 IM Sportsbook 服务器 IP 列入白名单，以便接收图标更新。 体育博彩服务器 IP 可在集成文档中找到。

10. 状态编码** 



|状态编码** |描述** |**Remarks** |
| - | - | - |
|**100** |成功 ||
|**101** |无效时间戳|时间戳在超过五分钟将过期|
|**102** |无效令牌 ||
|**107** |无效开始时间||
|**108** |无效结束时间||
|**202** |无效用户名|商户令牌验证 API 没返回任何 用户名 |
|**210** |无效商户 ||
|**305** |无效语言编码||
|**311** |无效时间范围||
|**313** |无效体育 ID ||
|**330** |无效赛事类型 ID ||
|**331** |无效比赛 ID ||
|**332** |无效盘口 ||
|**333** |无效操作会话||
|**334** |无效赛事 ID ||
|**335** |无效投注类型 ||
|**336** |<p>` `ID </p><p>无效投注类型</p>||
|**337** |无效投注选项 ID ||
|**338** |无效盘口 ID ||
|**339** |无效定位类型||
|**340** |无效连串过关选项||
|**341** |无效投注金额||
|**342** |无效投注类型选项 ID ||
|**343** |无效优胜冠军队伍 ID ||
|**344** |无效赔率类型||
|**345** |无效让球盘||
|**346** |无效赔率 ||
|**347** |无效主队得分||
|**348** |无效客队得分||
|**349** |无效投注状态||

|**350** |检索投注信息错误|||
| - | - | :- | :- |
|**351** |无效伺服器 IP 地址 |||
|**352** |无效客户 MAC 地址 |||
|**353** |无效用户代理|||
|**355** |超出投注上限 |||
|**356** |无效时区 |||
|**357** |无效单项快速投注|||
|**358** |无效连串过关快速投注|||
|**359** |无效新闻 ID |||
|**360** |无效投注限额组别|||
|**361** |无效时段 ID |||
|**364** |无效价格 ID |||
|**365** |无效投注金额 |||
|**366** |无效派彩 |||
|**367** |价格 ID 过期 |||
|**368** |投注无法出售. 上一个请求正在进行中|||
|**369** |注单已售给提前兑现|||
|**370** |<p>注单已结算 </p><p>找不到主单或</p>|||
|**380** |无可选盘口|||
|**381** |赔率不相同||GetBetInfo 成功但赔率与提交赔率不相同|
|**390** |无效 App 版本 |||
|**391** |无效 App 设备名称 |||
|**392** |无效 App 型号 |||
|**393** |无效 App 平台 |||
|**394** |无效 App OS 版本 |||
|**395** |投注单来自受限制国家|||
|**397** |无效排序 |||
|**398** |无效页面大小|||
|**399** |无效运营商|||
|**400** |系统错误 ||任何不在上述提及到的错误|
|**401** |无效筛选 |||
|**405** |无效赛季|||
|**406** |无效赛日|||
|**407** |无效 Bet Radar 赛事 ID|||
|**408** |无效每页记录数|||
|**411** |无效货币 |||
|**412** |无效个人公告号|||
|**413** |无效个人公告状态|||
|**414** |无效投注方式 |||
|**415** |无效参考编号 |||
|**416** |重复参考编号|||
|**417** |无效投注类型名称代码|||
|**418** |无效连串过关自动接受模式|||
|**419** |无效操作 |||
|**420** |无效搜索类型 |||
|**421** |无效搜索 ID |||
|**500** |不授权访问|||
|**501** |用户无访问权限|||
|**600** |Delta 过期 |||
|**700** |维护 |||
|**710** |访问地区限制|||
|**1000** |投注错误 |||
|**1001** |赔率更新中|||
|**1102** |会员账户不活跃|||
|**1103** |账户余额不足|||
|**1105** |投注金额超出投注上限|||
|**1106** |投注未达到最少投注金额要求|||
|**1107** |赔率已更改|||
||该赛事的总投注金额超出赛事投注|||
|**1108** |限额 |||
||所选赛事不支持连串过关投注|. 请||
|**1126** |选择其他赛事|||
|**1132** |无效投注金额|||
|**1135** |赛日验证失败|||
|**1141** |非公司支持的体育项目|||
|**1200** |投注被拒|||
|**1554** |无效投注 |||
|**1556** |未开启虚拟体育 |||
|**2102** |快速投注金额不能低于最低投注限额|||
|**2103** |快速连串过关投注金额不能低于最低投 注限额 |||
11. **IPIS**版本** 

IPIS API 的版本可以在 HTTP custom header“ipis-version” (例: “ipis-version = 2.0”) 中指定。 仅 针对 IPIS API 的重要合同更改而引入新版本。 版本控制提供了 API 以前版本和新版本的共存， 并允许更好地管理合同更改。 如果未指定版本，则默认版本将是尚未过期的最早版本。



|**Version** |**Changes** |**Expiry** |
| - | - | - |
|1.0 |Initial version |2021-03-09 |
|2.0 |All Bet Type Names has been changed. BetTypeName response parameter affected. |||

