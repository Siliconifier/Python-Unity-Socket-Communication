Created by Youssef Elashry to solve the common problem for TWO-WAY communication Unity/C# applications with Python 3.

The files attached will allow you to both send and receive data between Unity (C#) and Python 3.

Feel free to use this in your individual or commercial projects BUT make sure to reference me as: Two-way communication between Python 3 and Unity (C#) - Y. T. Elashry
It would be appreciated if you send me how you have used this in your projects (e.g. Machine Learning) at youssef.elashry@gmail.com

Use at your own risk
Use under the Apache License 2.0

To run demo:
- Ensure IP, send and receive ports are the same between server.py and UdpSocket.cs [edited via inspector] scripts. They are the same in the demo.
- Run server.py on the python side to send and receive data from Unity
- Add UdpSocket.cs to a game object in a scene
- RECOMMENDED: Run server.py THEN Unity Scene

- To be able to use the UdpSocket.cs script for your own script, REMOVE the lines and functions with a // DELETE THIS comment.
These lines and functions are for the purposes of the demo and do not affect the main functionality.

![alt text](https://github.com/Siliconifier/Python-Unity-Socket-Communication/blob/master/Images/Example.png)
