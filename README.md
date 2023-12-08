# Mems-Lidar-GraphicFrame
Two channels  high-speed realtime  weak signal plot  
Amplitude: ±187.5mV  
Resolution: 22nV  
Sample rate: 16kHz  
Offset: 0V  

### 08.12.23
- Document: device_socket.py  
Func: def connect_socket(self, samplerate)  
**samplerate** changeable  

Document: data_reader.py  
Parser(2,500)  
changeable  

queue full 报错  

调整data_timer 15->1  ???  


何种情况下，串口异常关闭会被一直占用    

error:  High Pass-> RuntimeWarning: overflow encountered in cast  

通道二没信号  