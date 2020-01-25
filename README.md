# Data visualization and analysis for short rent dataset

## 一、数据介绍

- 数据集链接：https://tianchi.aliyun.com/competition/entrance/231715/information

- 数据分为汇总版和明细版两类。
- listings 数据为短租房源基础信息，包括房源、房东、位置、类型、价格、评论数量和可租时间等等。明细版listings_detail 中包含更多房源相关细节。
- calendar 数据为短租房源时间表信息，包括房源、时间、是否可租、租金和可租天数等等。
- reviews 数据为短租房源的评论信息。汇总版中仅包括房源 listing_id和评论日期，用来时间序列和数据可视化分析。明细版reviews_detail 还包括评论相关的内容和作者信息。
- neighbourhoods 数据为北京的行政区划。
- 数据来源：本次活动数据来自 Airbnb 于 2019 年 4 月 17 日公开的北京地区数据。数据均来源于 Airbnb 网站的公开信息，不包含任何个人隐私数据。感谢相关机构做出的数据工作，更多信息可访问 http://insideairbnb.com/get-the-data.html。

- 分析所用数据集说明
    - 本次分析主要使用listings_detail 数据集，其中包含106个特征，28452条数据。
    - 数据集主要包含了短租房源的基础信息，如房源、房东、地理位置、价格、评论数量等等。通过对特征进行初步筛选，丢掉部分无用信息，最终提取46个特征，主要分为一下几类：房东特征（服务、可信度、房东类型等）、房源特征（起始时间、地理位置、硬件设施、价格等等）、房客特征（住房反馈等）。


## 二、主要内容

- Part one:数据集简明介绍
- Part two:数据预处理
- Part three:数据可视化分析