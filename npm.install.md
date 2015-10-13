# Install Nodejs & package

## Windows (OS)
สำหรับ  Windows  ให้โหลด Nodejs แล้วมันจะพ่วง npm มาให้ด้วย

[Download Here](https://nodejs.org/en/)

## Linux Ubuntu
ต้องเป็น Root ให้ใช้คำสั่งด้างล่าง
<pre>sudo -i</pre>

ลง Nodejs
<pre>
apt-get install nodejs
</pre>

เรามีการเพิ่ม package เสริมสำหรับเพิ่มความสามารถในการเขียนโค๊ด

ให้ใช้ **"sudo"** นำหน้าทุกคำสั่งสำหรับ Linux บางระบบ

แล้วใส่ Password แล้วจะสามารถใส่คำสั่งด้านล่างได้เลย
<pre>
npm install -g gulp-cli
npm install -g bower
npm install -g jscs
npm install -g coffeelint
npm install -g jshint
npm install -g node-inspector
</pre>
หรือ ฉบับย่อ

<pre>
npm install -g gulp-cli bower jscs coffeelint jshint node-inspector
</pre>


#### ความหมายของ Package ต่างๆ

**"JSCS, coffeelint, jshint"** สำหรับ Validate Code
**"node-inspector"** สำหรับ Debug โค๊ด
