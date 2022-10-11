# Single_Li_Battery_UPS

## 12V 输入输出不间断电源

秋季作息晚上会断电，为了让台灯在断电后还能亮着，设计一个使用单节锂电池的小型UPS

### 实现功能

1. 12V input&output
2. input掉电后不影响output输出
3. 自动充放电

### 实现方式

buck降压 + 充电管理 + boost升压 + pmos切换
<br>
![成品](/img/1.jpg "成品")
