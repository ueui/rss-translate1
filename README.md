#  Rss-Translation

## 这是一个外文RSS翻译转换订阅页面 

[![circle_translate](https://github.com/ueui/rss-translate/actions/workflows/circle_translate.yml/badge.svg)](https://github.com/ueui/rss-translate/actions/workflows/circle_translate.yml) [![Deploy](https://github.com/ueui/rss-translate/actions/workflows/jekyll-gh-pages.yml/badge.svg)](https://github.com/ueui/rss-translate/actions/workflows/jekyll-gh-pages.yml)

 💡重构翻译文件配置、更新Action环境依赖，添加不同翻译机制,已修复特殊字符转译

 📢查看 [项目修改完善、已添加源及使用说明](https://github.com/ueui/rss-translate/tree/main/illustrate)

 📢查看[ 本页 ](https://ueui.github.io/rss-translate) 参考自[ rss-translate ](https://github.com/talengu/rss-translate)

## 已转换翻译源
 - source001 [https://news.google.com/rss/search?q=when:24h+allinurl:bloomberg.com&hl=en-US&gl=US&ceid=US:en](https://news.google.com/rss/search?q=when:24h+allinurl:bloomberg.com&hl=en-US&gl=US&ceid=US:en) -> [bloomberg_news](rss/bloomberg_news.xml)
 - source002 [https://feeds.bloomberg.com/Crypto/news.rss](https://feeds.bloomberg.com/Crypto/news.rss) -> [Bloomberg_Crypto](rss/Bloomberg_Crypto.xml)
 - source003 [https://www.vice.com/en/rss?locale=en_us](https://www.vice.com/en/rss?locale=en_us) -> [English_VICE](rss/English_VICE.xml)
 - source004 [https://kill-the-newsletter.com/feeds/h541vjjth6mkic38ik3f.xml](https://kill-the-newsletter.com/feeds/h541vjjth6mkic38ik3f.xml) -> [Bloomberg](rss/Bloomberg.xml)
 - source005 [https://kill-the-newsletter.com/feeds/bhi9909b0d1dbhqq7o7h.xml](https://kill-the-newsletter.com/feeds/bhi9909b0d1dbhqq7o7h.xml) -> [Reuters_newsletters](rss/Reuters_newsletters.xml)
 - source006 [https://fetchrss.com/rss/620d11a970b7d1781324262266e2f73edf2f98627b0e7aa2.xml](https://fetchrss.com/rss/620d11a970b7d1781324262266e2f73edf2f98627b0e7aa2.xml) -> [Research_Commentary_Brookings](rss/Research_Commentary_Brookings.xml)
 - source007 [https://fetchrss.com/rss/620d11a970b7d1781324262266e2f4c31634514d1d0e1a32.xml](https://fetchrss.com/rss/620d11a970b7d1781324262266e2f4c31634514d1d0e1a32.xml) -> [Commentary_and_Articles_RAND](rss/Commentary_and_Articles_RAND.xml)
 - source008 [http://fetchrss.com/rss/6437f470034816381c2bcb926690a7ec65440a4de80b0252.xml](http://fetchrss.com/rss/6437f470034816381c2bcb926690a7ec65440a4de80b0252.xml) -> [Culture_|_The Economist](rss/Culture_%7C_The%20Economist.xml)
 - source009 [https://kill-the-newsletter.com/feeds/kxnraollt2n0gd03szin.xml](https://kill-the-newsletter.com/feeds/kxnraollt2n0gd03szin.xml) -> [Carnegieendowment](rss/Carnegieendowment.xml)
 - source010 [https://politepol.com/fd/LES08YuDyITn.xml](https://politepol.com/fd/LES08YuDyITn.xml) -> [Culture_GQ](rss/Culture_GQ.xml)
 - source011 [https://www.pewresearch.org/feed/](https://www.pewresearch.org/feed/) -> [Pew_Research_Center](rss/Pew_Research_Center.xml)
 - source012 [https://www.bloomberg.com/authors/ARbTQlRLRjE/matthew-s-levine.rss](https://www.bloomberg.com/authors/ARbTQlRLRjE/matthew-s-levine.rss) -> [Matt_Levine_Bloomberg_Opinion_Columnist](rss/Matt_Levine_Bloomberg_Opinion_Columnist.xml)
 - source013 [https://kill-the-newsletter.com/feeds/88lhiotcswouh2kqelf0.xml](https://kill-the-newsletter.com/feeds/88lhiotcswouh2kqelf0.xml) -> [bloomberg_Business_of_Space](rss/bloomberg_Business_of_Space.xml)
 - source014 [http://fetchrss.com/rss/6518f1be2d18ae56d5360f7265d35fc7c43c5356173e4013.xml](http://fetchrss.com/rss/6518f1be2d18ae56d5360f7265d35fc7c43c5356173e4013.xml) -> [Ideas_Morgan_Stanley](rss/Ideas_Morgan_Stanley.xml)
 - source015 [https://fetchrss.com/rss/620d11a970b7d1781324262266e5485ed46ec68d5f06da32.xml](https://fetchrss.com/rss/620d11a970b7d1781324262266e5485ed46ec68d5f06da32.xml) -> [Supreme_Court_Of_The_United_States_Reuters](rss/Supreme_Court_Of_The_United_States_Reuters.xml)
 - source016 [https://www.nytimes.com/svc/collections/v1/publish/https://www.nytimes.com/spotlight/on-politics/rss.xml](https://www.nytimes.com/svc/collections/v1/publish/https://www.nytimes.com/spotlight/on-politics/rss.xml) -> [NYT_U.S._Politics](rss/NYT_U.S._Politics.xml)
 - source017 [https://rsshub.app/reuters/investigates/](https://rsshub.app/reuters/investigates/) -> [Special_Reports_from_Reuters_journalists](rss/Special_Reports_from_Reuters_journalists.xml)
