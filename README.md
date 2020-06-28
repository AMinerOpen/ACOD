# AMiner COVID-19 Open Dataset

## Introduction

This dataset is designed for providing COVID-19 related data. Two types of data are contained: the epidemic data and events data.

This data is applied in [**AMiner COVID-19 Dashboard**](https://covid-dashboard.aminer.cn) where several applications are integrated based on this dataset, including *Epidemic Map*, *Trend Prediction*, *COVID-19 Risk Index*, *Events Relation Analysis*, *Events Influence Estimation* and *Entity Influence Estimation*.

The epidemic data and events data are integrated from several data sources. A full list of data sources is listed below.

Download Links: [Epimemic Data](https://covid-dashboard.aminer.cn/api/dist/epidemic/epidemic.zip), [Events Data](https://covid-dashboard.aminer.cn/api/dist/events/events.zip). To view previously published data, refer to [*changelog*](./changelog) for more data links.

## Data Description

For epidemic data, we provide historical data for over 1,000 regions. The first date can be traced back to January 22rd, 2020 when the COVID-19 pandemic is officially reported by the China government for the first time.

For events data, two major types of data are included. The **Social News** is automatically collected from several authoritative sources such as XINHUANET or WHO. The **Academic Progress** part can be further divided into three categories: **Research Paper**, **Expert Opinion** and **Academic Activity**. Some of these data are manually annotated while others are similarly automatically retrieved. To see detailed statistics of each data type, refer to [*changelog*](./changelog).

The epidemic data is organized into CSV data format and the events data is saved in JSON format since it has more complex structure. The epidemic data is updated daily and the events data is updated weekly.

## Data Sources

#### Epidemic data
[WHO Covid situation reports](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports)
[ncov2019.live](https://ncov2019.live/data)
[ncov.dxy.cn](https://ncov.dxy.cn/ncovh5/view/pneumonia)
[163.com](https://wp.m.163.com/163/page/news/virus_world/index.html?spssid=e205fe771eb79b6e597833b5e13e7516&spsw=1&spss=native)
[Bing](https://cn.bing.com/covidans/locations)

#### Scholar
[The Lancet](https://www.thelancet.com/coronavirus/correspondence)
[Science](https://www.sciencedirect.com/search/advanced?tak=Coronavirus%20OR%20%22Corona%20virus%22%20OR%20%222019-nCoV%22%20OR%20%22SADS-CoV%22%20OR%20%22SARS-CoV%22%20OR%20%22MERS-CoV%22%20OR%20%E2%80%9CSevere%20Acute%20Respiratory%20Syndrome%E2%80%9D%20OR%20%E2%80%9CMiddle%20East%20Respiratory%20Syndrome%E2%80%9D&articleTypes=REV%2CFLA&show=100&ent=true&years=2020&lastSelectedFacet=years")
[Nature](https://www.springernature.com/gp/researchers/campaigns/coronavirus)
[JAMA Network](https://jamanetwork.com/journals/jama/pages/coronavirus-alert)
[bioRxiv](https://www.biorxiv.org/search/COVID-19)
[medRxiv](https://www.medrxiv.org/search/Coronavirus)
[ChemRxiv](https://chemrxiv.org/search?q=covid-19&searchMode=1)
[scienceDirect](https://www.sciencedirect.com/search/advanced?tak=Coronavirus%20OR%20%22Corona%20virus%22%20OR%20%222019-nCoV%22%20OR%20%22SADS-CoV%22%20OR%20%22SARS-CoV%22%20OR%20%22MERS-CoV%22%20OR%20%E2%80%9CSevere%20Acute%20Respiratory%20Syndrome%E2%80%9D%20OR%20%E2%80%9CMiddle%20East%20Respiratory%20Syndrome%E2%80%9D&articleTypes=REV%2CFLA&show=100&ent=true)
[中科院COVID-19科研动态监测](http://stm.las.ac.cn/STMonitor/qbwnew/openhome.htm?serverId=172)
[arXiv](https://arxiv.org/search/?query=Coronavirus+&searchtype=all&source=header)
[SCI666](http://www.sci666.com.cn/)
[科学网](http://www.sciencenet.cn)

#### News
[WHO Rolling updates on coronavirus disease](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/events-as-they-happen)
[xinhuanet.com](http://www.xinhuanet.com/english/)
[Worldometers](https://www.worldometers.info/coronavirus/)
[记疫-南都传媒](https://m.mp.oeeee.com/h5/pages/v20/nCovTimeline/)

## Terms of Use
1. The data provided in this repository, mostly comes from sources listed above, with some processing techniques applied to align names and detech abnormal changes. Some part of the data are collected and annotated by the AMiner team.
2. This data can be only used for non-profit public health, educational, and academic research purposes. The commercial use is strictly prohibited.