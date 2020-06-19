﻿# cat & wc

#### 一、cat

a. cat 2.txt = cat <2.txt => 觀看2.txt的檔案的內容

<img src ="https://github.com/syuan0327/Linux-note/blob/master/cat%20%26%20wc/1.JPG" width=50% height=50%>

b. cat >2.txt => 修改2.txt的檔案的內容

<img src ="https://github.com/syuan0327/Linux-note/blob/master/cat%20%26%20wc/2.JPG" width=50% height=50%>

c. cat 2.txt | tee 4.txt => 同時顯示和把內容放到4.txt

<img src ="https://github.com/syuan0327/Linux-note/blob/master/cat%20%26%20wc/3.JPG" width=50% height=50%>

#### 二、wc(word count統計字數)
a. wc 2.txt

 顯示：xyz 2.txt

 x:行數

 y:字數

 z:字母(包含空白格)
 
 <img src ="https://github.com/syuan0327/Linux-note/blob/master/cat%20%26%20wc/4.JPG" width=50% height=50%>

b. wc <2.txt

 不顯示檔名只有數量
 
 <img src ="https://github.com/syuan0327/Linux-note/blob/master/cat%20%26%20wc/5.JPG" width=50% height=50%>

