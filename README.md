### 使用

- 将原始验证码图片存放在`source_code`目录下，并将文件名改为验证码的内容，用来当做训练数据;

- 运行`learn.py`，将图片去噪并阈值化处理，并将单个验证码按照训练文件的名称分好类，开始训练并生成`code.pkl`
- 执行`server.py`,启动服务，将验证码二进制数据发送服务端，返回识别后的验证码