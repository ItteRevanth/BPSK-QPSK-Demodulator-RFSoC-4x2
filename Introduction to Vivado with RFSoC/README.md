Once the board file is downloaded. Add its path on seetings>tools settings>> Vivado store>>Board repository.
![alt text](image.png)
Once the path is added , restart the Vivado.
![alt text](image-1.png)
Now when you reach the board adding stage after creating a new project, you could be able to see above interface with rfsoc4x2 board.
This ends the basic board setting.
One might face license issue while synthesising some design on this board. There exists a subtle loop hole to exploit
These is the error message that might pop up
![alt text](image-2.png)
To get around it one must follow the following steps
One has to go to Help>>Manage license
![alt text](image-3.png)
It will load the following interface
![alt text](image-4.png)
Click obtain license option>>Get my full purchased certificate based license>> process now
![alt text](image-5.png)
A portal will open up to sign in and fill some required fields.
After that go to manage license section and click modify license.
![alt text](image-6.png)
Tick all the fileds and click next
![alt text](image-7.png)
A .lic file will be sent to your mail id. Upload that .lic file in vivado
![alt text](image-8.png)
Thats it you are good to go again