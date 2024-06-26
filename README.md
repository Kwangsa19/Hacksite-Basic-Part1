# HackThisSite-PenTesting-Basic-Part1
> Please visit ["Hack This Site"](https://www.hackthissite.org/) for further information.

> The "Hack This Site" helps improve your penetration testing. The requirements include: HTML, common sense, email address, and JavaScript. 

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

### Scenario 3:
`This time Network Security Sam remembered to upload the password file, but there were deeper problems than that.`

![chrome_b6zGCkWCqd](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/b76045ee-41a5-4d91-8bdc-9cb72e08206f)

### Solutions:
* Right-click anywhere on the web page, choose `view page source`.
* On the `hidden` form, the value is `password.php`. So, please visit `https://www.hackthissite.org/missions/basic/3/password.php`.

![chrome_Y0s1pgEMD9](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/1ed8b55e-654b-4c61-a180-c334ecaf3303)

* The password will appear. 

![chrome_7QtJaTMoGy](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/c2dcf966-6ea5-40d3-b31e-f767ea141e91)

* Copy and paste it on the `password` button and click `submit`.

![chrome_1bmo6kwLQP](https://github.com/Kwangsa19/Hacksite-basic/assets/135963482/e968b190-7353-420d-86f1-173bc3e69aaa)

### Recommendations: 
* Map out the directory structure of a web application before deploying it.

## Basic - Level 4

### Scenario 4:
`This time Sam hardcoded the password into the script. However, the password is long and complex, and Sam is often forgetful. So he wrote a script that would email his password to him automatically in case he forgot. Here is the script:`

![chrome_DjJeR74TT8](https://github.com/Kwangsa19/Hacksite-Basic-Part1/assets/135963482/7f870dd3-021c-4ce4-a213-af1e75b4e2ad)

### Solutions: 
* Right-click anywhere on the web page, choose `view page source`.
* On the `type: hidden` input, the value should be changed from `sam@hackthissite.org` to whatever email address corresponds to your account.
   
![chrome_aSNXB3Bl6L](https://github.com/Kwangsa19/Hacksite-Basic-Part1/assets/135963482/55690513-69b3-4570-8e5f-7febcb3b402a)

* Click `send password to Sam`. Please check the email address you put it down before.

![chrome_kroxA1liT9](https://github.com/Kwangsa19/Hacksite-Basic-Part1/assets/135963482/8802daea-675e-4415-ad19-3c9425e0bc94)

* Copy and paste the password on the `password` button. Submit the password.
  
![chrome_lT8DdPs88q](https://github.com/Kwangsa19/Hacksite-Basic-Part1/assets/135963482/0076e0ee-546d-4482-958d-af8fb6fe2bc6)

### Recommendations: 
* Sensitive information should not be included in the code if it is carried out on the client-side. 
* Protect the sensitive information from being accessed by unauthorized personnels. 


## Basic - Level 5

### Scenario 5:
`Sam has gotten wise to all the people who wrote their own forms to get the password. Rather than actually learn the password, he decided to make his email program a little more secure.`

![chrome_1LvuMIMR2g](https://github.com/Kwangsa19/Hacksite-Basic-Part1/assets/135963482/9c45fa34-268d-43bd-8dab-abe34c4c4baf)

### Solutions: 
* Right-click anywhere on the web page, choose `view page source`.
* On the `type: hidden` input, the value should be changed from `sam@hackthissite.org` to whatever email address corresponds to your account.
  
![chrome_evT0g8ZUjp](https://github.com/Kwangsa19/Hacksite-Basic-Part1/assets/135963482/d74440f9-b903-4a5e-9f8e-563eab86143c)

* Click `send password to Sam`. Please check the email address you put it down before.
  
![chrome_ShENo45hNY](https://github.com/Kwangsa19/Hacksite-Basic-Part1/assets/135963482/2af65c36-88e5-4592-b571-0fd0e8388554)

* Copy and paste the password on the `password` button. Submit the password.
  
![chrome_Bli8sfqgVF](https://github.com/Kwangsa19/Hacksite-Basic-Part1/assets/135963482/7e855be1-1fbd-475c-b94b-2e4ea676164a)

### Recommendations: 
* Sensitive information should not be included in the code if it is carried out on the client-side. 
* Protect the sensitive information from being accessed by unauthorized personnels.

## Conclusion
* Part 1 consists of HTML knowledge and common sense. 
