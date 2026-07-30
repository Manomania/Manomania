<img src="assets/banner.svg" alt="Maxime Martinez, devops and infrastructure, 42 Lyon" width="100%">

<img align="right" width="38%" src="assets/card-stack.svg" alt="Stack: Docker, Kubernetes, Argo CD, Nginx, Ansible, Vagrant, Bash, Make, GitHub Actions, Prometheus, Grafana, Google Cloud, PostgreSQL, MariaDB, Linux, C, C++, Python, TypeScript">

I spent five years repairing cash handling machines on customer sites before I
started at 42. Infrastructure turned out to be the same job with better tooling:
something is broken, people are waiting, go find out why.

Based in Lyon, open to DevOps and platform work.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-1F5E48?style=flat-square&logo=linkedin&logoColor=CBC135)](https://www.linkedin.com/in/maxime-martinez-643300254/)
[![Email](https://img.shields.io/badge/Email-1F5E48?style=flat-square&logo=maildotru&logoColor=CBC135)](mailto:maxime.martinez96@hotmail.fr)
[![CodinGame](https://img.shields.io/badge/CodinGame-1F5E48?style=flat-square&logo=codingame&logoColor=CBC135)](https://www.codingame.com/profile/85b780e0c973cc20cb7b3113734c81391256935)

## PROJECTS

### [ft_transcendence](https://github.com/Manomania/ft_transcendance)

Multiplayer arcade platform, five of us, with [@nahamida](https://github.com/Sunny-444/), [@faoriol](https://github.com/faoriol/),
[@dmazari](https://github.com/Mazakov-d/) and [@mniemaz](https://github.com/POLEC4T/). I took the infrastructure.
 
Thirteen services, four Docker networks, an Nginx reverse proxy in front, CI on
GitHub Actions, Prometheus and Grafana with a Blackbox Exporter for the probes,
one Postgres schema per service, secrets through Docker secrets. Most of my time
went into the network topology: the gateway has to reach everything, and nothing
else is allowed to.

### [Cloud-1](https://github.com/Manomania/Cloud-1)

With [@faoriol](https://github.com/faoriol/). Nginx, MariaDB, php8.2-fpm and phpMyAdmin, provisioned from
nothing on a Debian VM in Google Cloud by Ansible roles. Destroy the instance, run the playbook,
the site is back.
 
Getting there was less elegant than it sounds. WordPress stores its own URL in
the database, GCP hands out a new external IP on every rebuild, and the two facts
do not get along.

### [Inception of Things](https://github.com/Manomania/InceptionOfThings)

With [@cben-bar](https://github.com/cben-bar/) and [@efayolle](https://github.com/ElFlamingoBob/). Two node K3s cluster on Vagrant, Ingress
routing, and Argo CD reconciling the cluster against a Git repository. Push to main, the cluster follows.
 
The three days I lost on this had nothing to do with Kubernetes: a stray K3s
instance still running on the host was stealing routes from the VMs underneath.

<br clear="right">

<img src="assets/divider.svg" alt="" width="100%">

<img align="right" width="38%" src="assets/card-timeline.svg" alt="Timeline: 2019 field service technician at PayComplete, 2024 42 Lyon, 2026 post cursus infrastructure work">

## Before 42

Level 2 field maintenance technician at PayComplete for five years, on banking automation hardware across southeast France. On call, on site, a customer watching, and a machine that had to work again before the branch opened.

None of it was fashionable and it is still the best training I have had for this line of work: diagnose fast, on equipment that is not yours, with an audience.

<br clear="right">

<img src="assets/divider.svg" alt="" width="100%">

<details>
<summary><b>42 cursus, full project list</b></summary>

<br>


| Project | What it taught me | With |
|---|---|---|
| [minishell](https://github.com/Manomania/minishell) | Process control, forks, pipes, file descriptors | [@elagouch](https://github.com/airone01/) |
| [philosophers](https://github.com/Manomania/philosopher) | Threads, mutexes, deadlock and starvation | |
| [NetPractice](https://github.com/Manomania/NetPractice) | Subnetting, routing tables, network troubleshooting | |
| [Cub3D](https://github.com/Manomania/Cub3D) | Raycasting engine in C | [@elagouch](https://github.com/airone01/) |
| [CPP 00 to 04](https://github.com/Manomania/CPP) | OOP, orthodox canonical form, polymorphism | |
| [CPP 05 to 09](https://github.com/Manomania/CPP_05-09) | Exceptions, templates, STL containers | |
| [Inception](https://github.com/Manomania/inception) | First contact with Docker, one service per container | |
| [ft_irc](https://github.com/Manomania/ft_irc) | TCP server, RFC 1459, non blocking I/O | [@elagouch](https://github.com/airone01/), [@nahamida](https://github.com/Sunny-444/) |
| [ft_transcendence](https://github.com/Manomania/ft_transcendance) | Microservices, CI, monitoring, team lead | [@nahamida](https://github.com/Sunny-444/), [@faoriol](https://github.com/faoriol/), [@dmazari](https://github.com/Mazakov-d/), [@mniemaz](https://github.com/POLEC4T/) |
| [ft_ping](https://github.com/Manomania/ft_ping) | Raw ICMP sockets, signal handling, flood mode | |
| [ft_ls](https://github.com/Manomania/ft_ls) | WORKING ON |  |

Certified in C and in C++ on
[CodinGame](https://www.codingame.com/profile/85b780e0c973cc20cb7b3113734c81391256935).

</details>

<img src="assets/divider.svg" alt="" width="100%">

## Get in touch

[LinkedIn](https://www.linkedin.com/in/maxime-martinez-643300254/) or
`maxime.martinez96@hotmail.fr`. Happy to talk about infrastructure, homelabs, or why
your Docker network cannot resolve that hostname.
