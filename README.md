# 01_shell_signup_page
#!/bin/bash

echo "************************"
echo "                        "
echo "welcome to signup page, "
echo "                        "
echo "************************"

echo "please enter your name: "
read name

echo "please enter your email address:"
read email

echo "please enter your password:"
read password

echo "please confirm your password:"
read conform

if [[ $password == $conform ]]
then
        echo   "your signup is successfull!"
        echo "name: $name "
        echo "email: $email"
else
        echo " sorry'  do not match! please try again."
fi
