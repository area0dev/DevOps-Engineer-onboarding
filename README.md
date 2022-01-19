# DevOps-Engineer-onboarding
## Guiding thoughts
**Take time to learn.** Don't get sucked into the minutia of decision-making or project involvement too early - there will be plenty of time for that later. In your first 30 days, try to focus on getting comfortable and learning how things work. Try to learn Linux basic, bash scripts and etc.

**Invest in relationships.** By day 60, you'll be in execution mode. In your first two months, spend as much time as you can getting to know people and forming relationships. So, try to learn Git, docker and bash advanced, which are nessesary tools for DevOps engineers. 

## 90-day milestones
After that, you need to get some experience with sql db sush as postgresql and mysql, with web-server Nginx and Kubernetes basic and ,of course, CI/CD. I've put together this onboarding plan to help you get up to speed in your new role as a DevOps Engineer on DevOps team. 

**Don't be afraid to ask.** No one expects you to know how things at Area0 work right away. Take advantage of that and ask for help when you need it. Feel free to reach out if you have any questions. <br />
[@Andrey Gerasimov](https://github.com/geri4)<br />
[@Timur Nasridinov](https://github.com/timur-ND)
| Outcome | Steps | Tasks |
| :---: | --- | --- |
|I understand how to work with Linux|[1. Online Linux basics course](https://stepik.org/course/73/syllabus) <br /> [2. Read about cron](https://tproger.ru/translations/guide-to-cron-jobs/) <br /> [3. Yandex Kit video course](https://www.youtube.com/playlist?list=PLdJo1XilUTZPmME0miIBCClFzL5rptwkQ) <br /> [4. Read about Linux Directory Structure](https://eng.libretexts.org/Bookshelves/Computer_Science/Operating_Systems/Linux_-_The_Penguin_Marches_On_(McClanahan)/04%3A_Managing_Linux_Storage/5.12%3A_Linux_Directory_Structure/5.12.01%3A_Linux_Directory_Structure_-_Hierarchy) |[A. Install Ubuntu on your desktop](https://ubuntu.com/download/desktop) <br /> B. Investigate your system - install **htop** and find out your resources. <br /> C. Create your own folder for your files, install usefull programms (Web-browser, Visual Studio Code, some messengers, Guake Terminal and etc.) <br /> D. Configure you workplace (configure terminal, create new patition on disk (optional) and etc.)
|I can write on Bash|[1. Bash Guide for Begginers](https://tldp.org/LDP/Bash-Beginners-Guide/html/index.html) <br /> [2. Advanced Bash-Scripting](https://tldp.org/LDP/abs/html/index.html) <br /> [3. Bash guide](https://github.com/Idnan/bash-guide)| A. Try to create Bash script with basic commands (write file to disk, read file, calculate something and etc.) <br />
|I know how to deal with Git| [1. Read an article about Git](https://proglib.io/p/git-for-half-an-hour) <br />[2. Katacoda Git course](https://katacoda.com/courses/git)| A. Create your own repo in Github.com and try to push some files (for example, your Bash scripts from previous step) <br /> B. Clone some public repos and investigate it structure.
|I know what is Regex|[1. Bash Regex](https://habr.com/ru/company/ruvds/blog/327896/)| A. Try to use regex in your bash scripts, for example, find some lines in file.
|I know what is SSH|[1. SSH Guide](https://www.digitalocean.com/community/tutorials/how-to-use-ssh-to-connect-to-a-remote-server-ru)<br /> [2. Add ssh key to github](https://docs.github.com/en/enterprise-server@3.0/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)| A. Generate ssh keys, add it to your github/gitlab account. <br /> B. Try to login to some server with ssh (you can ask access from [@Andrey Gerasimov](https://github.com/geri4) or [@Timur Nasridinov](https://github.com/timur-ND)).
|I know what is Prometheus|[1. Prometheus Guide](https://habr.com/ru/company/southbridge/blog/455290/)<br /> [2. Prometheus querying](https://prometheus.io/docs/prometheus/latest/querying/operators/)| A. Investigate https://prometheus.area0.ru/graph and try to create some queries.
|I know what is SaltStack, yaml and jinja template|[1. Saltstack for 10 minutes](https://habr.com/ru/post/315012/)<br />[2. Yaml tutorial ](https://tproger.ru/translations/yaml-za-5-minut-sintaksis-i-osnovnye-vozmozhnosti/)<br /> [3. Understanding Jinja](https://docs.saltproject.io/en/latest/topics/jinja/index.html)| A. Clone https://github.com/area0dev/salt and investigate it.<br />
|I know how to configure CI/CD pipelines| [1. Read about Gitlab CI/CD](https://docs.gitlab.com/ee/ci/)<br /> [2. Read about Github Actions](https://docs.github.com/en/actions/learn-github-actions)<br /> [3. Read about Drone CI/CD](https://docs.drone.io/)| A. [Register in gitlab.com.](https://about.gitlab.com/free-trial/) and create repo. <br />B. Setup and register your [specific runner](https://docs.gitlab.com/runner/register/).<br /> C. Write your own gitlab-ci.yml and try build docker image. <br /> D. Try repeat this with Github Actions and Drone-CI.
|I know Network Basics|[1. Network Basic course](https://stepik.org/course/58678/)| A. Study the course, labs and practics can be skipped.
|I know how to configure iptables|[1. Iptables full guide](https://www.opennet.ru/docs/RUS/iptables/)<br />[2. Iptables beginner guide](https://losst.ru/nastrojka-iptables-dlya-chajnikov) | A. Try to open some ports to get access from remote to your app (need nginx and virtual machine)
|I know how to use **dig**| [1. Read how to use dig](https://jvns.ca/blog/2021/12/04/how-to-use-dig/) | A. Try to use this commands for find A and CNAME records for some domains.
|I know how to configure Nginx|[1. Install and Configure Nginx](https://serveradmin.ru/ustanovka-i-nastrojka-nginx/)<br />[2. Nginx beginners guide](http://nginx.org/ru/docs/beginners_guide.html)| A. Try to test your nginx config on some virtual machines.
|I know how to work with Postgresql|[1. Beginners guide](https://knowledgepill.it/posts/postgresql-basics-guide/)<br />[2. Postgres course DBA1](https://youtu.be/mXA861YV7Us?list=PLaFqU3KCWw6JhHBp07QSu9uE8zahhKnTn)<br />[3. Postgres course DBA2](https://www.youtube.com/playlist?list=PLaFqU3KCWw6KycrRthIC6mESoLLQen1k6)|A. Write instructions and commands from videos in a notebook  <br /> B. Install locally PostgreSQL or MySQL and try execute some commands from DBA course.
|I know about Docker|[1. Video about docker](https://youtu.be/I18TNwZ2Nqg)<br /> [2. Katacoda docker course](https://katacoda.com/courses/docker) <br /> [3. Online course about docker](https://stepik.org/course/74010/promo)| A. Create account in hub.docker.com <br /> B. Pull some images, like busybox or alpine, on your local machine and investigate it. <br /> C. Create Dockerfile and try to write your own image. Build image, run it on your desktop and push image to your repo in hub.docker.com.
|I'm familiar with Kubernetes|[1. Katacoda kubernetes course](https://katacoda.com/courses/kubernetes)<br /> [2. Helm](https://helm.sh/docs/chart_template_guide/getting_started/) <br /> [3. Kubernetes Admin course](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/) | A. Try to setup k8s to local machine with **minikube** or better with **Kubeadm**. <br /> B. [Deploy some pods](https://kubernetes.io/docs/concepts/workloads/pods/) to different namespaces. <br /> C. Write Helm chart and try deploy it.
|I'm familiar with Terraform|[1. Take terraform basics course](https://learn.hashicorp.com/terraform)| A. Try to write .tf files.