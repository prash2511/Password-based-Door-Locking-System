# Password-based-Door-Locking-System


1. Introduction -

There is a rapid spread of the use of internet today making the world to become a global village. Other forms of advancements in science and technology have also contributed more in this development. It should also be noted that due to this advancements, there is an increasing rate in crime, attacks by thieves, vandals and intruders. 

Despite all the necessary forms of security that has been put in place for the security of information over the internet and properties at homes, more still needs to be done especially in the security of properties and lives at homes, shops and offices.

In most countries that are involved with the use of mechanical locks, the crime rate has increased because these locks are easily broken. It is difficult to always identify who actually had access in to a home or apartment illegally with the mechanical locks. Therefore, there is the need for the use of other types of locks especially the use of electronic locks. 

So, we have made the Password Based Door Locking System Using Arduino & Keypad. So a digital code lock can secure your home or locker easily. It will open your door only when the right password is entered.


2. Components Required -

- Arduino Uno Board (Arduino Uno R3 V1.0)
- Keypad (4X3 Keypad)
- LCD Display (LM044L 20x4 Alphanumeric LCD)
- PCF8574A (8-Bit I/O Expander for I2C-Bus)
- Buzzer (5V Active Buzzer)
- LED (Animated LED model (Red, Green))
- Transistor (BC547BP NPN Transistor)
- Resistor (220R 3W Resistor)
- Button (SPST Push Button)
- Connection Wires


3. Circuit Diagram -

![image](https://user-images.githubusercontent.com/76968308/120674308-97cd4600-c4b1-11eb-800d-2ec05d173fd6.png)


4. Working -

In this project, we have defined the default password “7296” in the Arduino. We can change it through coding.

When we enter a password, it will match entered password with the password stored in the Arduino. If it is correct, then it will show ‘Welcome, Access Granted’ and then Green LED will glow as the door is opened.

It will then give 5 seconds time for entering via the door. Once 5 seconds completed, the door will get locked automatically.

If the password is wrong, then it will show ‘Code Incorrect’. And Red LED will glow as door is locked.

When incorrect password is entered for 3 times, it will show “Warning , Access denied”. And the buzzer will start beeping.


5. Future Scope -
The security level can be increased by adding a biometric fingerprint scanner.
 
We can interface sensors like Fire, LPG, PIR motion detector to Arduino in case of any accident so that door will open automatically. 

We can interface camera to the Arduino so that it could capture the picture of the thief who is trying to breach the security. 

This simple circuit can be used at home to ensure better safety. 

It can also be used at organizations to ensure authorized access to highly secured places.


6. Conclusion -

This project is productive in providing enough security as long as the password is not shared. In future this “Password based Door Lock System” can be provided maximum security by the above enhancements in order to completely satisfy user’s needs. Hence, a common man can afford to buy such locking system in minimal cost to keep his valuables safely without any worries.






  
 





  
  
  
  
  
  
  
 

