# Python Password Cracker

This is a basic brute - force password application that may be used to crack commonly used passwords. 

## Instructions for Use:

- Clone the repository or download the contents of the repository as a Zip file.
- Set up Python on your computer
- Run the following command in your terminal to install the python packages listed in the requirments.txt file:

    ```python3
    >>> pip install -r requirements.txt #for windows
    >>> pip3 install -r requirements.txt #for macos and linux
    ```
 
- Run the password_cracker.py file by running <i>python password_cracker.py</i> or <i>password_cracker.py</i> on it.
- Then select the type of hash you want to decode (type only the number corresponding to the action and not the word itself).
- Then enter the hash you want to crack and wait for the script to attempt to crack it; if successful, the text password is displayed; if not, a relevant remark is displayed.
- The script now stores approximately 10,000 popular passwords and will be updated in the future. 