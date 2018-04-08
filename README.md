# Hotel.NG Intership 4

Please invite others who are interested in learning to code. Use this link: [https://join.slack.com/t/hnginternship4/shared_invite/enQtMzQwOTU4NzAwNjExLWQ0NWFlZDBmNjRkMTRkNGZmYjQ5MzA0YmUzZDBiZDEzOTBkZGE1ZWUxZTI1YjkxMTQ5N2MyZTMyMzBmMTEyOWM](URL)

Please do invite all others who may be interested in the internship

Notice: 
*Setting up your profile information such as, names, display names, what you can do, (off-course that will change as soon as you learn on), profile image, phone number and status is very important.*


**Everyone else, please set your profile picture - we always disable all those without profile pictures**



---
## Stage 0
*If you know you have no knowledge of programming at all, join [#stage0](https://hnginternship4.slack.com/archives/CA2BESFFA)*

As soon as you complete stage 1 task, please exit stage0 channel

---
## Stage 1 (Setting up of environment for Coding)

### Pre-resquite
1. Set your profile picture.
2. Setup a Git account and learn how to use Git. 
    * Free GitHub private account for the next 1 year. Use this link to redeem: [https://github.com/redeem/hng_ingressive_github](URL), or use the coupon code HNG_INGRESSIVE_GITHUB on your existing github account. Once done, give a shout-out to @GitHubCommunity @GitHubEducation and @_Ingressive_ on Twitter
3. Setup a Figma account. 
    * Figma is the first interface design tool with real-time collaboration. It keeps everyone on the same page. Focus on the work instead of fighting your tools.

    1. Go to [figma.com](URL)
    2. Click Sign Up at the top right side of your screen
    3. Enter your details and Sign Up
    4. Go to your MailBox for a confirmation link which returns you back to your figma profile
    5. Click the + sign at the top left side of your screen to get started
    
4. Download and install Docker. 
    * #### Guide for installing docker on windows Method 1

        Step 1 - Make sure you have Microsoft 64bit Windows 10 Pro, Enterprise and Education (1607 Anniversary Update, Build 14393 or later).

        Step 2 - Make sure your system supports virtualization and *make sure it is enabled*

        Step 3 - Go to https://docs.docker.com/docker-for-windows/install/

        Step 4 - Download the stable version community edition

        Step 5 - Double click on your *Docker for windows installer.exe* file and follow all the prompt the install wizard gives

        Step 6 After docker has been installed locate the docker icon and start up docker

        Step 7 After docker has started, open your terminal and type the command `docker -version` if everything went smoothly it should output the version of docker installed

        Step 8 Run the command `docker run hello-world` then it should build your very first docker container. Once this is successful, you're all set and ready to go

    * #### Guide for installing docker on windows Method 2
        If your system doesn't meet the specifications for installing docker, you can install docker toolbox instead

        *Note* For people whose windows operating system is maybe Windows 10 home or windows 7, or not 1607 Anniversary Update, Build 14393 or later

        Also for people whose system does not support virtualization
        Step 1 - Go to https://docs.docker.com/toolbox/toolbox_install_windows/

        Step 2 - Download docker toolbox from that link

        Step 3 - Double click on the docker toolbox installer 

        Step 4 - Follow all the prompts in the setup wizard

        Step 5 - After installation is complete, look for the Docker quick start icon and lunch, a bash window should open

        Step 6 - When the bash window is open, once docker starts you should see the docker symbol drawn command line style and most importantly you would see a $ symbol with your keyboard cursor blinking

        Step 7 - To verify your installation, type the command `docker run hello-world` then if that runs successfully, you are set to go
        

    * #### Guide for installing docker on Ubuntu 16.04 and 17.10
    * 
        Make sure you're using a user that has *sudo* privileges

        *NOTE!!!*
        Do not run these commands as a root user i.e. your terminal would use the # symbol, always make sure you're seeing this symbol $
        I take no responsibility for what ever damage you incur on your system is you do the wrong thing :walking:

        Step 1 - Update the apt package index
            `$ sudo apt-get update`

        Step 2 - Install packages to allow `apt` to use a repository over HTTPS
           ` $ sudo apt-get install \`
            `$apt-transport-https \`
            `ca-certificates \`
            `curl \`
           ` software-properties-common```

        Step 3 - Add docker's official GPG key
            `$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -`
        Verify that you now have the key with the fingerprint `9DC8 5822 9FC7 DD38 854A E2D8 8D81 803C 0EBF CD88`, by searching for the last 8 characters of the fingerprint.
            `$ sudo apt-key fingerprint 0EBFCD88`

       ``pub   4096R/0EBFCD88 2017-02-22``
      Key fingerprint = 9DC8 5822 9FC7 DD38 854A  E2D8 8D81 803C 0EBF CD88
        uid                  Docker Release (CE deb) <docker@docker.com>
        sub   4096R/F273FCD8 2017-02-22```

        Step 4 - Add the Docker repository to APT sources
            `$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"`

        Step 5 - Update the `apt` package index
            `$ sudo apt-get update`

        Step 6 - Finally, install docker-ce
            `$ sudo apt-get install docker-ce`

        Step 7 - Verify docker has been installed
            $ sudo docker `run hello-world`
        If this runs successfully, then you're almost golden.

5. Get a basic PHP environment working on your system (Hello World).

### Task
To pass stage 1, 
Go to #stage1
You will need the following:

1. Design a very simple page in Figma
2. Implement it in html/css (this design should include showing the current time using php)
3. Setup docker
4. Get php to run in docker
4. Make your app work on your local browser
5. Your app must show properly
6. You will need to submit a screenshot to pass to Stage 2


---
## Stage 2 (Learning Collaborative Coding.)
