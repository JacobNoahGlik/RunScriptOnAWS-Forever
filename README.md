# Run A Python Script On AWS Forever (For Free)
Run a Python script on an EC2 instance (on AWS) forever, for FREE!

<br> 

## Step 1: Have your code
* Have some Python code that can run all the time (in a `while true:` loop or otherwise)
  * Note: this can also work with code that needs to be re-run all the time, but will not work with code that should only be run once a day, or once every `x` hours. That code should be moved to a scheduler script, and that's the script that should be used here.
  * This project will use [The Math DiscordBot](https://github.com/JacobNoahGlik/MathDiscordBot) as an example.

<br>

## Step 2: Create a free AWS account
* Go to [sign up for AWS](https://portal.aws.amazon.com/billing/signup?nc2=h_ct&src=header_signup&redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation#/start/email) and create your free account
  * You must enter your email twice on the `aws create account website` and confirm it by typing in the verification number sent to your inbox. Create a strong password and attach a payment method.
  * Note: you may need to attach a credit card to this account, and a $1 hold may be placed on the account for 3 business days to make sure AWS can charge you in case you start using paid services. But as long as you use free services (as outlined in this readme), you will not be charged.
<details>
  <summary>Screenshots of every step (when creating your free AWS account) outlined above</summary>
  <p>Step-by-step instructions for creating a free AWS account.</p>
  <img src="SignUpForAWS.png" alt="Screenshot 1">
  ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/b21fee5e-9b2c-42a2-8f52-d5002d7a2acb) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/4067ddf8-d981-41e6-905b-ccfba660ce4c) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/bec37588-8693-4527-96a0-eccf145862e5) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/3b0c0063-e685-4a1a-98f0-2aa8ef0a1c9d) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/6e521d26-b6f6-47df-b72d-e14959850587) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/346ab0c8-78b6-4ed0-bd8f-1c391f68388a) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/1a64d598-c20b-4e15-b97a-cdfe2a60ad9f) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/56d3c136-1e08-4a70-8bf9-e097d37395f0) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/c5a0ba70-ca5e-48df-a1ae-7cdb311b53a7) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/4190eb9f-e61e-4115-a041-df8f16e6df62) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/8149052c-1614-4f82-8bf2-8d2789b91188) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/897de783-cc74-48f3-a051-3933c3db2eca) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/c60de612-910e-46f1-a430-12ea075a1ef1) ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/3aa1b20c-a26a-4c05-bc6a-edfd3cbded87)
</details>

<br>

## Step 3: Create a new EC2 instance.
Create EC2:
* Scroll to the `Build a Solution` box and click "Launch a virtual machine With EC2"
  * ![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/ed0a3052-e90e-4e31-82ed-5c23ac2fd5b9)

Launch EC2:
* Click on the orange drop-box labeled: `Launch instance`
* This will open two options (`Launch instance`, and `Launch instance from template`) chose `Launch instance`
![image](https://github.com/JacobNoahGlik/RunScriptOnAWS-Forever/assets/70964953/373417f0-a775-4a06-829e-d890bf653628)


Configure:
* Give your EC2 instance a name
* In Quick Start, choose `Amazon Linux` OS Image and a `64-bit (x86)` architecture
 * It will have the following subtext `"""Amazon Linux 2023 AMI | ami-0578f2b35d0328762 (64-bit (x86), uefi-preferred) / ami - ..."""`
 * But the important thing is that it's "Free tier eligible" so you won't be charged no matter how many you have or how long you run them
* << Image >> 
* Launch

<br>

## Step 4: Run your code

<br>

<br>

<br>

Credits to [Hitch's](https://www.youtube.com/watch?v=xXirbnUB3NU&ab_channel=TechwithHitch) incredibly quick guide for setting up a free ec2 instance on aws which gave me this idea.
