# How to Start the Project

This project is a social web application that allows users to create and share their thoughts, experiences, and ideas. The application is built using Node.js, Express.js, MongoDB, and React.js. Beside, it is also the project for the CS385[A] — Mobile Application Development (2024-25:Semester 1) course at National University of Ireland Maynooth. This project was finished by [Songyan Lai](https://github.com/SongyanLai) and [Li Men](https://github.com/TymeoL1).

This project consists of two parts: the backend and the frontend.<br>

To start the backend:<br>
Run the following command in the terminal:<br>

node server.js<br>

To start the frontend:<br>
Navigate to the frontend directory and run:<br>

npm start<br>

Test Credentials:<br>
Username: test1<br>
Password: root

# 19.Dec.2024 Update <br>

1，撰写了英文注释 2，增加了 blog 的删除功能 3，更改了主题颜色和样式 4，解决了评论内容和时间冲突的问题

Added English comments.

Implemented blog deletion functionality.

Changed theme colors and styles.

Resolved conflicts between comment content and timestamps.

# 18.Dec.2024 Update <br>

Add Post content recording function and save data by uploading it to the database through the backend<br>
添加 Post 内容记录功能，通过后端上传到数据库保存数据

# 12.Dec.2024 Update <br>

Reorganized the path structure <br>
更新了文件结构保证合理性<br>

合并了原'CS385Project/welcome' 到 'CS385Project/frontend/mian/src' 并更名为 SignPage <br>
Merged the original flie 'CS385Project/welcome' into 'CS385Project/frontend/mian/src' and renamed it to SignPage

Use React router function to make page jump <br>
添加 React Router 功能实现页面跳转

修改原 branch 中/App.js 为 /Welcome.js <br>
Modify /App.js in the original branch to /Welcome.js

Add a variable [ isLoggedIn ] in /Welcome to update the status to implement simple offline verification (only applicable to offline, no authentication methods such as Token are used to ensure the security of communication between the front-end and back-end servers) <br>
在/Welcome 中添加了一个变量 [ isLoggedIn ] 用于更新状态实现简单的离线验证（仅适用于离线，未使用 Token 等认证方法保证前后端服务器通信的安全性）

# 5.Dec.2024 Update

Created Homepage

# Created

Songyan Lai

1.Deleted Type.

2. Updated the function of using the API to get weather

3. Created a new search interface and completed the search function

4.blogPage.js and SearchPage.js correspond to blog pages and search pages respectively. There is also the BlogPage.css blog page style.

5. Add a simple interactive interface to simply verify the user data stored in MongoDB.
