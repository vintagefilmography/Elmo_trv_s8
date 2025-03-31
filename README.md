# Elmo_trv_s8  
![image](https://github.com/user-attachments/assets/94041915-6e14-4a32-9b15-12efb355ffb1)
This is a  rare S8 film projector with sound. The old low resolution camera has been taken out  
and replaced with the Raspberry Pi HQ camera for real time high resolution capture of video and sound.  
The Raspberry Pi is  small format computer running Linux.  
Once the keyboard and the mouse are attached  and the unit is connected to an HDMI monitor  
 (HDMI cable provided) you are ready to capture your S8 films (sound and no sound)  
 onto internal memory or externally using an HDMI recorder (not provided).  
The recording or previewing process is very simple and does not require any Linux knowledge.  
Just run a few commands    

Sound film:  
record 14285 35 1  
14285 - shutter time in micro seconds  
35 - frame rate  
1 - recorded file sequence number  

Silent film:  
record 16666 30 1  

Run preview:  
Sound film   
preview 14285 35 0  
14285 - shutter  
35 - frame rate  
0 - gain  

Silent film   
preview 16666 30 0  

Sample videos:  
Sound  
https://youtu.be/0zzYeLvgRic   
The original film quality is not very good but ok for sound check.   

Silent
https://youtu.be/xLMJtXiw3q4



![image](https://github.com/user-attachments/assets/dc2bf727-a3d0-4c10-b90f-540af402d108)
![image](https://github.com/user-attachments/assets/2de3fbb8-1ad0-4867-aea2-df91c94948a6)
