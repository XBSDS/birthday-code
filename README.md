1.**基本运行过程**
1. 双击”点击这里.html"，会打开本地的浏览器进行播放，页面如下所示。
<img width="1154" height="638" alt="image" src="https://github.com/user-attachments/assets/ed912428-a889-4ec1-acf1-f0108956334f" />

2. 点击页面黑色框后，会自动播放“小黄人”视频。
3. 初始密码我设置的为“0000”（后面会展示怎样修改此处密码部分）。
4. 后面在倒计时“3、2、1”结束，出现以下页面前可能会有一段时间的空置，小生本地的时间间隔是刚刚好，可能因电脑不同而有所区别。下图中只能点击“我真喜欢”，“我不喜欢”是点不了的 <img width="1110" height="659" alt="image" src="https://github.com/user-attachments/assets/de71f552-575c-4b8c-a9cd-a90f23d2a698" />

5. 在文字页面的最后，点击“彩蛋”那个框框，会继续播放后面的页面<img width="1106" height="760" alt="image" src="https://github.com/user-attachments/assets/cf406a26-03f0-44c2-a160-52959248e64a" />

6. 在下图中点击“礼物盒”，会出现“图片”从下到上，逐渐变大浮现的效果，持续大概10秒左右<img width="1107" height="871" alt="image" src="https://github.com/user-attachments/assets/ad0e40ad-73f1-4e77-9745-f4ad8045be1f" />

7. 最后，在倒计时结束后，出现最后“粒子交织”的画面，代码到此正式结束。<img width="1042" height="520" alt="image" src="https://github.com/user-attachments/assets/cbf00bc2-e590-4b78-8f20-53b859b6a976" />

2.**部分修改建议**
（1）密码修改（可能后面有时间我会将这一块给删除掉，感觉有点麻烦）
在html文件夹下的login.html文件中
<img width="1084" height="219" alt="image" src="https://github.com/user-attachments/assets/94590536-dbfd-4fe2-b78e-2aedf7fab5cb" />

在js文件夹下的jquery-1.8.4.min.js文件中
<img width="829" height="145" alt="image" src="https://github.com/user-attachments/assets/53686aad-895f-48d7-9ce7-6f6f2a82fe93" />

**两处一定要同步修改**

（2）内容修改（处于“html”文件夹或者“js”文件夹下进行修改）
<1>彩蛋.html<img width="1088" height="385" alt="image" src="https://github.com/user-attachments/assets/507c8fea-0c1a-4a16-bace-e7dfda101157" />

红框中是最后“粒子”显示的内容
<2>1.html
<img width="1086" height="587" alt="image" src="https://github.com/user-attachments/assets/d00e6c5c-78bd-45ad-ab6f-939962c175bb" />

红框中是倒数第二个页面显示的文字内容
<3>Memories.html
共有6屏的内容可供修改，也可以自行删去不需要的“屏”或者添加多余的“屏”，在“叉号”处修改内容即可。
<img width="1086" height="574" alt="image" src="https://github.com/user-attachments/assets/f05ea674-3aec-48be-9605-719baf26c33b" />

<4>indexl.js
文字内容自行修改
<img width="1088" height="162" alt="image" src="https://github.com/user-attachments/assets/3d0f0849-bc09-4a61-ba20-baa86d725b85" />

记得修改内容后注意播放时间的修改，更改数字即可
<img width="896" height="304" alt="image" src="https://github.com/user-attachments/assets/927fcd56-3a03-439a-a060-05a4ac549791" />

（3）音乐修改（修改代码的文件均位于html文件夹下）
*前提：记得在music文件夹中下载自己喜欢音乐才方便后面的调用，之后按照文件路径修改图中代码即可*
<1>index1.html（登录页面的播放音乐）
<img width="1049" height="197" alt="image" src="https://github.com/user-attachments/assets/7f00e223-fd3b-4501-ad0e-b94369f94740" />

<2>Memories.html（文字屏的音乐）
<img width="1051" height="227" alt="image" src="https://github.com/user-attachments/assets/5f2df83d-39fc-436a-a604-cdc4bb4a6559" />

<3>BirthdayCake.html（蛋糕界面的音乐）
<img width="1052" height="160" alt="image" src="https://github.com/user-attachments/assets/34edfcab-ffbb-4fdc-a307-4fd7c3ee226e" />

（4）图片修改（代码部分的修改均在html文件夹中）
*前提：记得在img文件夹中下载自己喜欢的图片，相应地可以在在html文件夹中进行修改*
倒数第二个页面“图片浮现”的效果处，想要更改图片可以在img文件夹中，将所要更换的图片命名为“流图1”、“流图2”······，这样比较简单，或者能看懂代码的话可以在对应的“1.html”中进行修改（“2.html”是我之前制作的网页，对整个代码运行没有影响，可以删除）
<img width="1085" height="687" alt="image" src="https://github.com/user-attachments/assets/cab3fbab-b5ee-41f4-a656-23159908a27c" />

**写的可能没有那么清楚，后续会持续改进，欢迎大家的批评指正，谢谢**
