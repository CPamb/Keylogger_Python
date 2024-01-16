# Introduction 

The purpose of this repository is to create a simple Python keylogger using the pynput library. This keylogger will log the keys pressed by the user and save them to a file.

# How to Run 

To run this script, clone the repository and run the pynput_keylogger.py file using Python. Make sure to install the pynput library if you haven't already.

# Implementation 

The pynput library is used to listen for keyboard events. When a key is pressed, the on_press function is called, which appends the key to a list and increments a counter. Once the counter reaches 10, the write_file function is called to write the keys to a file and reset the counter and list. The on_release function is called when a key is released. If the released key is the escape key, the script will stop running.

# Potential Concerns 

Please note that this script is for educational purposes only and should not be used to invade the privacy of others. It is the responsibility of the user to ensure that they have the necessary permissions to monitor keyboard inputs on a given device.

# Conclusion 

This project demonstrates the basic functionality of a keylogger in Python. It serves as a starting point for anyone interested in exploring this topic further. Keep in mind that the code provided here is for educational purposes only, and using it for any malicious purposes is strictly prohibited.
