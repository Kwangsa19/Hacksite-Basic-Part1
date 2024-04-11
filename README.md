# Hacksite-basic
> Please visit ["Hack This Site"](https://www.hackthissite.org/) for further information.

> The "Hack This Site" helps improve your penetration testing. 

## Basic - Level 1

### Scenario 1: 

`This level is what we call "The Idiot Test", if you can't complete it, don't give up on learning all you can, but, don't go begging to someone else for the answer, thats one way to get you hated/made fun of. Enter the password and you can continue.`

![chrome_rVCjpERrUA](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/ba4fc1f0-eda5-4c40-a75b-9fbde7fa02a7)

### Solutions: 
* Right-click anywhere on the web page, choose `view page source`.
* Scroll down until we find the word `password` or `Ctrl + f` and type the word `password`.

![chrome_OCZgLEIPTv](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/72ff819b-6fa2-40af-b524-04368c5b9054)

* Copy the `password` and paste it back on the password button and click `submit`. 

![chrome_XgUY02EKjn](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/7a7e2591-4bb8-49c8-8799-df32510b6c3f)


### Recommendation:
* Passwords should never be stored in plaintext in the source code. We can store it as a hashed value in a separate file or kept in an encrypted file. Hashing is more secure. 

## Basic - Level 2

### Scenario 2: 

`Network Security Sam set up a password protection script. He made it load the real password from an unencrypted text file and compare it to the password the user enters. However, he neglected to upload the password file...`

![chrome_XBE2FTZFwF](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/408863b9-eabb-42d6-ab7c-f99db67824a8)

### Solutions: 
* Leave the `password` button blank and click `submit`.

![chrome_I9itVCrHtI](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/e7ff2632-5fbe-4872-bc62-3ea7418a98f1)

### Recommendation: 
* Always test the application by submitting an empty blank password field.

## Basic - Level 3

### Scenario 3
`This time Network Security Sam remembered to upload the password file, but there were deeper problems than that.`

![chrome_b6zGCkWCqd](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/b76045ee-41a5-4d91-8bdc-9cb72e08206f)

### Solutions:
* Right-click anywhere on the web page, choose `view page source`.
* On the `hidden` form, the value is `password.php`. So, please visit `https://www.hackthissite.org/missions/basic/3/password.php`.

![chrome_Y0s1pgEMD9](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/1ed8b55e-654b-4c61-a180-c334ecaf3303)

* The password will appear. Copy and paste it on the `password` button and click `submit`.

![chrome_7QtJaTMoGy](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/c2dcf966-6ea5-40d3-b31e-f767ea141e91)

![chrome_1bmo6kwLQP](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/e968b190-7353-420d-86f1-173bc3e69aaa)

### Recommendations: 
* Map out the directory structure of a web application before deploying it.

## Basic - Level 4
