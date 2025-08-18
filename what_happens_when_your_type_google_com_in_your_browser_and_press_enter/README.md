# What happens when you type google.com in your browser and press Enter

- **Level**: Master
- **Author**: Sylvain Kalache
- **Weight**: 1
- **Note**: Manual QA review must be done (request it when you are done with the project)

## Description

For this project, we expect you to look at this concept:
- [Technical Writing Tips and Tricks for students](https://intranet.hbtn.io/concepts/816)

### Background Context

Being a Full-Stack Software Engineer means you’re comfortable interacting with any layer of the stack. A way to easily assess this is to simply ask an engineer to explain how a software system works. They can have a general overview of the flow or can choose to dig deep in a certain area. Let’s practice by exploring the infrastructure side (network, servers, security…) of the question.

![Infrastructure Overview](https://s3.eu-west-3.amazonaws.com/hbtn.intranet.project.files/holbertonschool-sysadmin_devops/298/aJPw3mw.jpg)

## Requirements

### General
- You can post your blog post on the platform of your choice, LinkedIn or Medium are good ones
- A README.md file, at the root of the folder of the project, is required

## Tasks

### 0. What happens when...
Write a blog post explaining what happens when you type `https://www.google.com` in your browser and press `Enter`.

**Requirements**, your post must cover:
- DNS request
- TCP/IP
- Firewall
- HTTPS/SSL
- Load-balancer
- Web server
- Application server
- Database

Publish your blog post on Medium or LinkedIn; share the URL of your blog post in your answer file and in the field below.

**Repo**:
- GitHub repository: `holbertonschool-network`
- Directory: `what_happens_when_your_type_google_com_in_your_browser_and_press_enter`
- File: `0-blog_post`

### 1. Everything's better with a pretty diagram
Add a schema to your blog post illustrating the flow of the request created when you type `https://www.google.com` in your browser and press `Enter`.

**The diagram should show**:
- DNS resolution
- That the request hits the server IP on the appropriate port
- That the traffic is encrypted
- That the traffic goes through a firewall
- That the request is distributed via a load balancer
- That the web server answers the request by serving a web page
- That the application server generates the web page
- That the application server requests data from the database

[Gliffy](https://intranet.hbtn.io/rltoken/psFvxy-j0nALTn_sapK5tg) is free and recommended, but feel free to use what fits you best.

Some unrelated examples:

![Pic 2](http://i.imgur.com/i9ivkdo.png)

![Pic 3](http://i.imgur.com/R8R3sqC.png)

Share the URL of your diagram image in your answer file and in the field below.

**Repo**:
- GitHub repository: `holbertonschool-network`
- Directory: `what_happens_when_your_type_google_com_in_your_browser_and_press_enter`
- File: `1-what_happen_when_diagram`