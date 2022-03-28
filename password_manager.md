# Passwords, We Don't Need no Stinking Passwords

![](img/passwords.jpg)

Use a password manager [they](https://www.ncsc.gov.uk/collection/top-tips-for-staying-secure-online/password-managers) say. Make sure you don't use the same password for every account, because that's pretty bad. 

A password manager means you can store all your passwords securely, so you don’t have to worry about remembering them and the Precursor is the *ideal* hardware device to do that, so I'm going to attempt to build one. 

## Fundamentals

Before I do this, I need to learn how the following works:

* 1: Unambiguous Thin Register Abstraction (UTRA) - a register abstraction for accessing hardware resources
* 2: How one stores credentials and accesses them in a secure way. 
* 3: What is the Xous microkernel operating system?
* 4: How to create an application in Rust 
* 5: Do I need to use the Graphical Abstraction Manager (GAM)?
* 6: What is the The Plausibly Deniable DataBase (PDDB) and how should I use it?
* 7: How does one securely open and close the password manager? 
* 8: How does one export all data? How does that work with Wi-Fi in a secure way?
* 9: How does one get this app onto the device and sign it to run properly?
* 10: Can the app detect when it has been tampered with? 

As you can see from the above, this journey intimidates me but at the same time excites me as it's about designing a secure application from the start and validating each phase/function. 

There's so much I don't know but as I've already said, I want to use this device to learn and grow so this will be a road with many potholes and failures, but at least you can come along with me on the journey. 