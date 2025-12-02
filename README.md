## 吳彥東 (東東) 

我目前在 [CMIS 中程資訊顧問有限公司](https://cmis.tw/) 工作，主要負責將現有用 Delphi 2009 製作的 營建工程管理資訊系統(ERP)，

改寫成 Golang(後端) + Vue(前端) 的網頁版ERP，
Delphi 2009 的部分 負責 "CMIS 整合桌面資訊系統" 和 "CMIS 銷售前置分析系統" 的維護開發。

## 🛠️ 使用語言/工具

### 後端

- ![Go](https://img.shields.io/badge/Go-1.25.4-blue?logo=go)  ![Echo](https://img.shields.io/badge/Echo-v4.13.4-blue?logo=data:image/vnd.microsoft.icon;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAADS0lEQVQ4jU3MXWiVZQDA8f/zPO/7nvecfbXNrbn5mZsrkTLIebN2YV0E+VEhk9zNTPNiaTVEtuyDQ1HgXW5elItAhaSREbmVBQkRlSIMaZxpGzQ2HG7uQ7d5zvv9PF1EsP/97y96jh1LLdTV7XehI0mSC9PT01/09vYG2WxWZrNZDdDf369aW1uTXC7nRFF0BHgr1Ppi5HlnxHufnNpTo5Ke2C1aH8TxZOz772QymZHOzs6brCiXyzX5vr/Gcd2PXcd5HK8wOePHJwU/jf++4+7oQNud665GegXbOSwxawWc6+rq6jDG6OHh4T6tdTtC3i1KdK9jK++0WyP/Kl71iuDncYNhnsyqfa+NXN6+bXbs1YLlrAu0+bbEdZeampqidElJqS3E/lQc3h56ZPXFD5zaiXqHr5UkI/HyY+iozFqaeu7L+mePvP/E7qu+r3eWx0E+nU4fr66u6q6E/PiDws7uyq1/9JXWvrElTYvtkNEBtwSDox9hqSIMEyKV+tQsP5hCpfoaCguVb0/9aZ56pik8v3mbdTtIz2QM3aliyuKEE0qxIQ6YVRzouIox80TRJZSsQBtXhgU9X7vx0A/lW7+a3NZovDL7pJPX/whFHVL8EkdcErBXGNotjAHb2oVQv6LJo/VpLexalER68zsqTFVJDPhS/q1hSAmethxaVJoXogVQHDhairIkIhnHcd4kDB+F+HviKG+kM9ZYV7oY+uJ2EnNNCI4LyW4M1zCU6YQLFpb9PEn0HUbdIArvgdkAaje228zy8mWdSFdl+FD7hCah0VjMGvhNGwJls8dCySdJ9CakOEJiPkeqNIlfQXXNY3j+LsuiVGaoDxcZkA7nMcwhWK0M7wKOxPNugrTRySakOEqSuCj5DdN3hkCCwHiL3NCGQZ2AVBwGGoTESWKGLObut7B+7UECX2Hb5QTePrAfYhgmDvsDH1eneElpmo2hzTiUCsMCkhPkOWtxqHkZ6GFgopwk3oKythP6a6lY00Y4M+lkKKKE9kKez1DMYuifW+Ls9QaxBGABYIxEiPvA6wze2oxlvUzgGUyyDk1JEmCwGNGGMz9WidwKo/8bCKEByBrJi2IUOMWV8XsoeyOCYv8hB6/UiHMr4f/mX9vWh8qiuQgvAAAAAElFTkSuQmCC)  ![Xorm](https://img.shields.io/badge/Xorm-1.3.11-blue?logo=data:image/png;base64,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)  

### 前端

- ![Vue.js](https://img.shields.io/badge/Vue.js-v3.5.25-brightgreen?logo=vue.js)  ![Vite](https://img.shields.io/badge/Vite-v7.2.6-brightgreen?logo=vite)  ![Axios](https://img.shields.io/badge/Axios-v1.13.2-brightgreen?logo=axios)  ![PrimeVue](https://img.shields.io/badge/PrimeVue-v4.3.4-brightgreen?logo=primevue)  ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v4.1.17-brightgreen?logo=tailwindcss)  ![MasterCSS](https://img.shields.io/badge/MasterCSS-v1.37.8-brightgreen?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAPUSURBVFhH7ZJPaFxVFMa/c9//l4aUpihIiRZFsQZKY1JqRPxHRFQkXWgXEhsRjEFdNNFgNVqTMTERorUL6camFZUaCgYxIMZSApYEHMUGDVTQKKRIY9OYtjNv3rz37nERJt65ycSudDM/+BbvOx/nnnfPBcqUKfM/Q7qhcy59wN/kVz0F0B1gGSeM4xtqO7/UcwCQ+2noIQYeBwlTymTSu0RHRGNnoOdU1h3gYnqgyvXMCQJtV31mfsOvfbFH9YIfh94E4VXVY+bvPbh3U+3zV1RfReiGim2LHjBvZ5ZQJVkeyEwP1hdymenBesnJK3oO4LqAs73FXYspOUDmzMAWcNImkwS6ICVJKfsKWcmyj6UkPSeTBFIm7ZkzA1uKu/9DyRUspXsPCyHadF+FkdxDJAhMp/SaioQ8XFX3ervuo9QAi1OprSTis0Rk6TUVZj4NIiKgUa+pSObItXCzt6PnN71WYgXhvSxldxJHUzKJUEos4zs5iRp1X1USR5OQsjsXRvfpp6DUDcwcu786m/sruP2ZR3ILp4MxAj+oZ64GZoxVf+0/+t11X7i+u9Hbtvfkgp5ZNcDMsaYOML9NRAFD7K2u2TYNljMksO46VsHIM8Rti3MzdSzlB8zskaCOW58cP6TGigY4+2nzTkg5SbS8Gma+7NjmLXbltfsF0Qtq9l8hHFqcPzdoCPwMoAIAwJwIk3bd9Njn6UKs6A1YpttvOr4wbB+G7cN0KioTtrsQh6k4H15KohBXozgKlxIjSTmu95Jh+xWFfoZTYQjhD6hnrtzA72OtTWD6Si0CAIOzcRhvtUz5NMD9en1NGPttr+pIGOVmCeTrZRA/cP3DR8dRuAFmkGH6fYbtQZdp+75bWbWPcvmDcRjMJfkc1lMcBnMURu8lQnSYtu/r/Qzbg2H6fczLPy8AYH6ic7fpeg2m42EtGbbTWLPnRBBHuVQcBlhPMh/21uw5ERim16j3WZHrNfwx0bkbAASPjBhke6mVPWkSlich7C4AuHzlz+Eol/01CrNYW5lfljLzRwGATKdLWJ7U+628L9tL8ciIQYvpt1qZeFhd0QoMSCn3bd7ZfbBg/fB+fQsxf1gcXEaCWnY8l/6o8L3wbaqDhDFUnFIgtArDcZ41bQ+rZLkLwnKeUA8HgM/Opz+O85mRKMygSPns8dH59CdqtrrhtXcMy2kxLO/iqv7LZ7TT7OywuzkImolwFwjXALgAiam8Y4xuurFtSW2oQFP9NzQxcRMIbEKMN7w8O66HCizOvrvRyrnNIN4FoBpE5zmJv7ngbRjVs2XKlPnP+RteaDvhzI7VnAAAAABJRU5ErkJggg==)


### 全端

- ![Delphi 2009](https://img.shields.io/badge/Delphi%202009-Object%20Pascal-orange?logo=delphi)

## 關於我

- 🌱 目前正在將舊有的 Delphi 2009 應用程式逐步重寫為網頁版的 Web 應用，後端用 Golang 的 Echo 和 XORM，前端用 Vue.js、Vite、PrimeVue、MasterCSS。

- 📫 您可以透過 [wuc656@gmail.com] 與我聯繫。
  
![Top Langs](https://github-readme-stats-dong.vercel.app/api/top-langs/?username=wuc656&langs_count=10&layout=compact&size_weight=0.5&count_weight=0.5&locale=zh-tw)
<img src="https://github-readme-stats.vercel.app/api?username=wuc656&show_icons=true&locale=zh-tw">

# **事蹟**
- 2024年 3月18日 入職 [中程資訊顧問有限公司](https://cmis.tw/ "中程資訊顧問有限公司")
- 2023年 9月19日 入伍 (4個月軍事訓練役) 於當年12月31日結訓
- 2023年 於 [國立高雄科技大學](https://www.nkust.edu.tw/ "國立高雄科技大學") 畢業
- 2019年 考上了[國立高雄科技大學](https://www.nkust.edu.tw/ "國立高雄科技大學")(建工校區)資訊工程系
- 2016年 考上了[臺中市私立僑泰高級中學](https://www.ctas.tc.edu.tw/ "臺中市私立僑泰高級中學") 畢業於資訊科三年甲班
- 2016年 得到 國中教育會考 **3A2B** 的成績 (A++,A+,A,B++,B+)
- 2015年 與 2016年 與 學校國文老師([鄭麗美](https://www.facebook.com/dadulucy))
  
   為大道國中當屆畢業生製作畢業微電影 [2015畢業微電影](https://www.youtube.com/watch?v=df7rQDfLSqU&feature=youtu.be) [2016畢業微電影](https://www.youtube.com/watch?v=cpNNkTnlw68&feature=youtu.be)
- 2016年 畢業於[大道國中](http://www.ddjhs.tc.edu.tw/)
- 2013年 畢業於[山陽國小](https://syps.tc.edu.tw/)
- 創立並營運著 [東東的創世神伺服【1.12.2】](https://www.facebook.com/wud656) 

# **興趣**

[星球：重啟](https://www.2112earthrevival.com/ "星球：重啟")

[崩壞：星穹鐵道](https://hsr.hoyoverse.com/zh-tw/home "崩壞：星穹鐵道")

# **個人特質**

當他開始玩電腦後，就因為遊戲的關係開始研究電腦知識。

雖然有時候會做一些很邪惡的事情.....

但是他的電腦知識比同齡的人高了許多，電腦優化、系統重灌、電腦組裝....。

# **相關網站**

[**Facebook**](https://www.facebook.com/wut656)

[**Facebook(粉絲專頁)**](https://www.facebook.com/wut656)

[**Youtube**](https://www.youtube.com/user/wuc656)

**[Youtube(播放清單)](https://www.youtube.com/user/wuc656/playlists)**

**[Twitch](https://www.twitch.tv/wuc656)**

**[Twitch(個人檔案)](https://www.twitch.tv/wuc656/profile)**

**[Twitter(X)](https://twitter.com/wuc656)**

**[Instagram](https://www.instagram.com/wuc656/)**

**[Dailymotion](http://www.dailymotion.com/wuc656)**
