# Dev-opps
dev-opp gits and all

1. what is DevOps? 
- The word 'DevOps' is a combination of two words 'development' and 'operations.'
- DevOps is a set of practices that automates the processes between software development and IT teams, in order that they can build, test, and release software faster and more reliably. 

  ![devops](https://www.guru99.com/images/2-2017/092917_0812_DevOpsTrain1.png)


2. why do we need DevOps? 
- DevOps helps to increases an organization's speed to deliver applications and services. It allows organizations to serve their customers better and compete more strongly in the market.


3. Mention the key aspects or principle behind DevOps?
- Continuous Integration
- Continuous deployment
- Automation
- Monitoring
- Security
- Infrastructure as code


4. List out some of the popular tools for DevOps? 
 - Jenkins
 - Docker
 - Ansible
 - Git
 - Nagios
 - Monit
 - ELK (Elasticsearch, Logstash, Kibana)
 - Collectd/Collectl


5. what is a version control system?
 - Version control systems are a category of software tools that help a software team manage changes to source code over time. Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.


6. What is Git and explain the difference between Git and SVN? 
 - Git (/ɡɪt/)[7] is a distributed version-control system for tracking changes in source code during software development.[8] It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.
 - Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development.[12] Its current maintainer since 2005 is Junio Hamano.
 
 -
 - Git is a distributed VCS; 
 - SVN is a non-distributed VCS.
 - Git has a centralized server and repository; 
 - SVN does not have a centralized server or repository.
 - The content in Git is stored as metadata; 
 - SVN stores files of content.


7. what language is used in Git? 


8. what is Docker? 
- Docker is a set of coupled (SaaS + PaaS) software-as-a-service and platform-as-a-service products that use OS-level virtualization to develop and deliver software in packages called containers. The software that hosts the containers is called Docker Engine. 


9. what is Docker Image ?
  - contains the application and environment required by the application to run, and a container is a running instance of the image.
  - 
  - A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

10. what is Docker Container?
  - Container is a running instance of the image.
  - Container images become containers at runtime and in the case of Docker containers - images become containers when they run on Docker Engine.
  - Containers isolate software from its environment and ensure that it works uniformly despite differences for instance between development and staging.

11. Can we consider DevOps as Agile methodology? 
 - (https://www.guru99.com/agile-vs-devops.html)
 - Fundamentally, DevOps brings together two large siloed teams together to allow for quicker software releases while Agile is focused on getting smaller teams to collaborate with each other so it can react quickly to the ever-changing consumer needs.
 - Agile focuses on making developers and development cycles more efficient, while DevOps brings the operations team into play to enable continuous integration and continuous delivery.

12. what are the advantages of using Git? 
(https://rogerdudler.github.io/git-guide/)
- Centralized cloud storage of your code.
- Version Control
- Working in teams
- Get involved / Open Source
- Bettering your code
- Show off
- You’re gonna need it anyway
-
- Documentation
- Showcase your work
- Markdown
- GitHub is a repository
- Track changes in your code across versions
- Integration options


13. what is difference between grep -i and grep -v? 
- To display the lines that do not match a pattern, use the -v ( or --invert-match) option.
  For example to display the lines from the /etc/passwd file ,
  that do not contain the string nologin you can use the following command:
  grep -v nologin /etc/passwd

- if you perform a case insensitive search using the -i option, it will match both upper and lower case letters:
    grep -i Zebra /usr/share/words

14. what is kernel? 15. what is concept of sudo in linux? 
  - A kernel is the lowest level of easily replaceable software that interfaces with the hardware in your computer. It is responsible for interfacing all of your applications that are running in “user mode” down to the physical hardware, and allowing processes, known as servers, to get information from each other using inter-process communication (IPC).
  - 
  - If you prefix “sudo” with any linux command, it will run that command with elevated privileges.  Elevated privileges are required to perform certain administrative tasks.
  - Using the sudoers file, system administrators can give certain users or groups access to some or all commands without those users having to know the root password. It also logs all commands and arguments so there is a record of who used it for what, and when.
  - The sudo command also makes it easier to practice the principle of least privilege (PoLP), which is a computer security concept that helps control system access and potential system exploits and compromises. 

16. what is a Jenkins Pipeline? 
- Jenkins Pipeline (or simply "Pipeline" with a capital "P") is a suite of plugins which supports implementing and integrating continuous delivery pipelines into Jenkins.
- 
17. How to stop and restart the Docker container? 
- docker stop {ContainerID}
- docker restart {containerID}

18. What is Scrum? 
- Scrum is a framework within which people can address complex adaptive problems, while productively and creatively delivering products of the highest possible value
-- Scrum is simple.  It is the opposite of a big collection of interwoven mandatory components. Scrum is not a methodology. Scrum implements the scientific method of empiricism. Scrum replaces a programmed algorithmic approach with a heuristic one, with respect for people and self-organization to deal with unpredictability and solving complex problems.

19. Explain the difference between git pull and git fetch? 
-- $ git fetch origin
git fetch really only downloads new data from a remote repository - but it doesn't integrate any of this new data into your working files. Fetch is great for getting a fresh view on all the things that happened in a remote repository.
Due to it's "harmless" nature, you can rest assured: fetch will never manipulate, destroy, or screw up anything. This means you can never fetch often enough.
-
- $ git pull origin master
git pull, in contrast, is used with a different goal in mind: to update your current HEAD branch with the latest changes from the remote server. This means that pull not only downloads new data; it also directly integrates it into your current working copy files.
- 
- This has a couple of consequences:

Since "git pull" tries to merge remote changes with your local ones, a so-called "merge conflict" can occur.
- 
Like for many other actions, it's highly recommended to start a "git pull" only with a clean working copy. This means that you should not have any uncommitted local changes before you pull. Use Git's Stash feature to save your local changes temporarily.



20. What is the difference between Maven, Ant and Jenkins?
- Jenkins is a continuous integration tool which is much more than build tool. 
- Main difference between ANT and Maven is that In ANT you need to define every thing i.e. source directory, build directory, target directory etc while Maven adopts principle of Convention over configuration. Which means Maven has predefined project structure i.e. standard directory for source files, test files and resources
- Maven is a build tool which knows how to build project and Jenkins or Hudson provides trigger to build. You can control when to trigger build automatically using Jenkins or Hudson or any CI tool.
= Hudson is similar to Jenkins.

21. Explain what is continuous integration? 
-Continuous Integration (CI) is a development practice that requires developers to integrate code into a shared repository several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early. 
-
- Developers practicing continuous integration merge their changes back to the main branch as often as possible. The developer's changes are validated by creating a build and running automated tests against the build. By doing so, you avoid the integration hell that usually happens when people wait for release day to merge their changes into the release branch.

By integrating regularly, you can detect errors quickly, and locate them more easily.

22. What is the relation between Hudson and Jenkins? 
- Hudson is a continuous integration server for Java development. The development of this platform started with Hudson while Jenkins was forked from Hudson when Sun was acquired by Oracle who aimed to develop a commercial version of the software. Since the fork, Jenkins has grown to be much more than a continuous integration solution
- Jenkin has more plugins compared to Hudson.
- Jenkins provide more updates with more active community support.

23. What are the advantages of Jenkins? 
-  Generate test reports
- Integrate with many different Version Control Systems
- Push to various artifact repositories
- Deploys directly to production or test environments
- Notify stakeholders of build status 

(https://www.cs.colorado.edu/~kena/classes/5828/s12/presentation-materials/bowesjesse.pdf)


24. Which SCM tools does Jenkins supports? 
- it supports version control tools, including AccuRev, CVS, Subversion, Git, Mercurial, Perforce, TD/OMS, ClearCase and RTC, and can execute Apache Ant, Apache Maven and sbt based projects as well as arbitrary shell scripts and Windows batch commands.

25. What is your daily activities in your current role?

26. What are the challenges you faced in recent times? 

27. What are the build and deployment failures you got and how you resolved those? 
28.How you will do the releases? 
29. How you automate the whole build and release process? 

30. What is Continuous Monitoring and why checking is basic in DevOps?
- Continuous monitoring is an essential step for organizations to identify and measure the security implications for planned and unexpected changes to hardware, software, firmware and to assess vulnerabilities in a dynamic threat space.


31. Explain about from Continuous Delivery. 
- Continuous delivery is an extension of continuous integration to make sure that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button.

32. Success factor for the Continuous Integration
(https://www.dilatoit.com/2018/06/07/continuous-integration-success-factors-integration-readiness.html)
  - AUTOMATIC BUILD/DEPLOYMENT SCRIPT
  - LABELING OF ANY STABLE BUILD
  - STABILITY CRITERIA

33. What is Configuration Management? 
- configuration management is about installing and updating system packages, setting network configurations – in short, making machine/server ready for deployment once it comes live, or even later.
- “Configuration management is the process of standardizing resource configurations and enforcing their state across IT infrastructure in an automated yet agile manner.” [Puppet]

34. Explain a few prerequisites that are useful for DevOps implementation. 

35. What are the top 10 devops tools that are used in the industry today? 
Gradle. Your DevOps tool stack will need a reliable build tool. ...
Git. Git is one of the most popular DevOps tools, widely used across the software industry. ...
Jenkins. Jenkins is the go-to DevOps automation tool for many software development teams. ...
Bamboo. ...
Docker. ...
Kubernetes. ...
Puppet Enterprise. ...
Ansible.
Nagios
RayGun
---------------------------
Git and GitHub – Source code management (Version Control System)
Jenkins – Automation server, with plugins built for developing CI/ CD pipelines
Selenium – Automation testing
Docker – Software Containerization Platform
Kubernetes – Container Orchestration tool
Puppet – Configuration Management and Deployment
Chef – Configuration Management and Deployment
Ansible – Configuration Management and Deployment
Nagios – Continuous Monitoring
(https://raygun.com/blog/best-devops-tools/)

36. Have you been involved in DevOps implementation in the cloud? If yes which cloud computing platform? 

37. How is DevOps different from Agile? DevOps Vs Agile 

38. Can you brief Roles, Responsibilities, and Skills of a DevOps Engineer 
- DevOps Engineer is somebody who understands the Software Development Lifecycle and has the outright understanding of various automation tools for developing digital pipelines (CI/ CD pipelines).

39. what are Devops Principles?
- DevOps value is derived in the core principles that started the movement:
Iterative
Incremental
Continuous
Automated
Self-service
Collaborative
Holistic
Teams should analyze existing processes against the principles, and see where DevOps practices can add value.


40. What is Git? 
Git is a free and open source distributed version control system designed to 
handle everything from small to very large projects with speed and efficiency.

Git is easy to learn and has a tiny footprint with lightning fast performance. 
It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features 
like cheap local branching, convenient staging areas, and multiple workflows.
By far, the most widely used modern version control system in the world today is Git. 
Git is a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds,
 the famous creator of the Linux operating system kernel. 
A staggering number of software projects rely on Git for version control,
 including commercial projects as well as open source. 
Developers who have worked with Git are well represented in the pool of 
available software development talent and it works well on a wide range of 
operating systems and IDEs (Integrated Development Environments).

Having a distributed architecture, Git is an example of a DVCS (hence Distributed Version Control System). 
Rather than have only one single place for the full version history of the software as is common 
in once-popular version control systems like CVS or Subversion (also known as SVN), 
in Git, every developer's working copy of the code is also a repository that can contain the full history of all changes.
In addition to being distributed, Git has been designed with performance, security and flexibility in mind.

41. What is the command to write a commit message in Git? 
git commit -m "Message"

42. What language is used in Git? 
Mar 22, 2011 - The Git architecture allows different subcommands (add, commit, pull, ... Alternatively, 
the tools that make up the core Git distribution are written in C and (Bourne) shell, ... Python, 
the well-known 'gitk' tool is in Tcl, and the list of language ... Perl is used for a few tools 
still these days like git-send-mail, git-svn, .

43. What is the difference between git pull and git fetch?
- In the simplest terms, git pull does a git fetch followed by a git merge.

You can do a git fetch at any time to update your remote-tracking branches under refs/remotes/<remote>/.

This operation never changes any of your own local branches under refs/heads, and is safe to do without changing your working copy.

I have even heard of people running git fetch periodically in a cron job in the background (although I wouldn’t recommend doing this).

A git pull is what you would do to bring a local branch up-to-date with its remote version, while also updating your other remote-tracking branches.

git pull = git fetch + git merge.

-

44. What is ‘staging area’ or ‘index’ in Git? 
- One practical use of the staging area is that it allows you to fine-tune your commits. You can add and remove changes from staging area until you are satisfied with how your next commit will look like, at which point you can do git commit
- As we mentioned earlier index is not a directory but a file, so git is not actually storing objects (blobs) into it. Instead, git is storing information about each file in our repository:
(https://hackernoon.com/understanding-git-index-4821a0765cf)

45. What is the function of ‘git config’? 
- The git config command is a convenience function that is used to set Git configuration values on a global or local project level. These configuration levels correspond to .gitconfig text files.
- local/global/system level

46. How can you create a repository in Git? 
- git init
- creates an empty Git repository - basically a .git directory with subdirectories for objects, refs/heads, refs/tags, and template files.
- The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.

47. Can you explain about Branching and Merging in GIT? 
- Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.
- git merge takes two commit pointers, usually the branch tips, and will find a common base commit between them. Once Git finds a common base commit it will create a new "merge commit" that combines the changes of each queued merge commit sequence.
- A branch represents an independent line of development. Branches serve as an abstraction for the edit/stage/commit process. You can think of them as a way to request a brand new working directory, staging area, and project history.

48. what is git stash?
- git stash temporarily shelves (or stashes) changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on. Stashing is handy if you need to quickly switch context and work on something else, but you're mid-way through a code change and aren't quite ready to commit.
- (https://www.atlassian.com/git/tutorials/saving-changes/git-stash)

49. what are the different ways to add/stage files/change to the git repository? 
- git add .
- git commit -m ""
- git push -u origin

50. How to get current status of local repository?
- git status

51. What is a Docker? 

52. What are the components of Docker Architecture and explain? 
- The Docker architecture uses a client-server model and comprises of the Docker Client, Docker Host, Network and Storage components, and the Docker Registry/Hub. Let’s look at each of these in some detail.
- (https://www.aquasec.com/wiki/display/containers/Docker+Architecture)

53. What is Docker Container? 

54. What are Docker Image and Docker Hub? 
- Docker Hub is the world’s largest repository of container images |. with an array of content sources including container community developers, open source projects and independent software vendors (ISV) building and distributing their code in containers.
= Docker Hub is a registry service on the cloud that allows you to download Docker images that are built by other communities. You can also upload your own Docker built images to Docker hub

55. What are the different functionalities and applications of using Docker? 


56. What is a Docker Registry?
- A Docker registry is organized into Docker repositories , where a repository holds all the versions of a specific image. The registry allows Docker users to pull images locally, as well as push new images to the registry 

57. What is the lifecycle of Docker Container? 
(https://medium.com/@nagarwal/lifecycle-of-docker-container-d2da9f85959)
  ![devops](https://miro.medium.com/max/1411/1*vca4e-SjpzSL5H401p4LCg.png)

58. What are Docker Objects? 
= Objects: Docker objects are various entities used to assemble an application in Docker. The main classes of Docker objects are images, containers, and services.[34]
- A Docker container is a standardized, encapsulated environment that runs applications.[37] A container is managed using the Docker API or CLI.[34]
- A Docker image is a read-only template used to build containers. Images are used to store and ship applications.[34]
- A Docker service allows containers to be scaled across multiple Docker daemons. The result is known as a swarm, a set of cooperating daemons that communicate through the Docker API.[34]


59. What are the important Docker commands?
docker run – Runs a command in a new container.
docker start – Starts one or more stopped containers
docker stop – Stops one or more running containers
docker build – Builds an image form a Docker file
docker pull – Pulls an image or a repository from a registry
docker push – Pushes an image or a repository to a registry
docker export – Exports a container’s filesystem as a tar archive
docker exec – Runs a command in a run-time container
docker search – Searches the Docker Hub for images
docker attach – Attaches to a running container
docker commit – Creates a new image from a container’s changes


60. What’s the benefit of “Dockerizing?”
Few advantages of dockerizing your environment.

- Continuous Integration: Any changes in the code will be automatically deployed immediately and would be available for testing anytime. Thus, Docker helps in Continuous Integration by significantly reducing the time.
- Continuous Delivery: The transition time from development to production can be greatly reduced as one container can be used across multiple environments. This way applications can be delivered much faster and in a more reliable way than ever before.
- Portability: Docker can be moved from one server to another with ease. Docker images come very handy while moving the container from one server to another without much efforts thereby saving a lot of time. The images can be either private or public.
- Scalability: A Docker container is very lightweight in size like tens of megabytes when compared to gigabytes in the case of virtual machines. Thus, multiple docker containers can be launched on a single machine and are highly scalable as per the demand.
- Micro Services Integration: Integrating microservices with the applications running on containers is easy. Each tier of a multi-tier application running on Docker behaves as an independent container and can be used to integrate microservices with the application.
- Reduced Cost: Due to its various advantages such as continuous integration and continuous delivery, Docker significantly reduces the cost of running an application .



Important Sites:
https://dzone.com/articles/what-is-devops-the-beginners-guide-from-logzio

https://docs.docker.com/get-started/

https://aws.amazon.com/what-is-cloud-computing/

https://www.ibm.com/cloud/learn/cloud-computing

https://www.ibm.com/cloud/garage/practices/code/tool_jenkins/

https://guides.github.com/introduction/git-handbook/
