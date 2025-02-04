# Welcome to NewsNow Labs

NewsNow Labs is the R&D arm of global top-50 news website [NewsNow](https://www.newsnow.co.uk/about), _The Independent News Discovery Platform_.

NewsNow Labs performs cutting-edge research across natural language processing, machine learning, infrastructure management, and software development tooling. Where it can, it makes its research public.

## Our public projects

### Dockside

Dockside is an open-source highly-configurable self-hosted software development environment, that lets dev teams code from anywhere in clones of their production environment and share and stage their work online for stakeholders.

Dockside lets developers provision and access lightweight, fully containerised and access-controlled IDEs, staging environments and sandboxes - aka _devtainers_ - within only a few clicks, directly from their browser.

By provisioning a devtainer for each task or branch, collaborative software and product development teams can make their lean and iterative development practices much more productive and efficient.

Dockside is free and open-source and can be hosted by anyone, on-prem or in the cloud.

To learn more, see [dockside.io](https://dockside.io), view [Dockside on Github](https://github.com/newsnowlabs/dockside), and to see Dockside in action try the [Dockside Live Demo](https://www.demo.dockside.cloud/demo/).

## Docker Ingress Routing Daemon

The Docker Ingress Routing Daemon (DIRD) is a daemon that modifies the operation of Docker swarm ingress mesh routing to expose true client IPs (as opposed to load balancer node private IPs) to service containers.

DIRD implements its modifications purely through changes to routing and firewall rules, without the need for running any additional application layers (like traefik or other reverse proxies) or for reconfiguring your existing application.

DIRD is the most lightweight solution available for directly exposing client IPs within Docker service containers.

To learn more, view [DIRD on Github](https://github.com/newsnowlabs/docker-ingress-routing-daemon).

## RunCVM

RunCVM (Run Container Virtual Machine) is an experimental open-source Docker container runtime for Linux, that makes launching standard containerised workloads in virtual machines (VMs) as easy as launching them in containers, using `docker run`.

RunCVM:
   - provides stronger workload isolation than standard containers
   - allows running and testing applications like `systemd`, Docker, and Kubernetes that won't easily run in standard containers
   - supports tools and apps like `iptables`, `ipvsadm` or `openvpn` that requires a running kernel (or a kernel version or modules not available on the host)
   - can emulate specific hardware e.g. disks, network cards, and graphics displays
   - makes it easy to create arrays of networked VMs for testing complex multi-machine setups like Docker Swarms
   - makes an ideal playground for pre-bare-metal training and testing

RunCVM uses a lightweight 'wrapper-runtime' technology that piggybacks the standard container runtime `runc`, making its code footprint and external dependencies small. It is built by bolting together 'off-the-shelf' (i.e. pre-existing open-source) components using shell script for simplicity, portability and ease of development.

To learn more, view [RunCVM on Github](https://github.com/newsnowlabs/runcvm).

## log_do

log_do is a bash library to assist writing self-documenting self-logging bash scripts, by simply prefacing each command with log_do.

log_do makes bash scripts easy to develop, debug and use, through:

- logging every command, its stdout, stderr and exit code;
- providing an automagic dry-run mode;
- providing an automagic interactive execution mode.

Thanks to these features, log_do helps you build complex sysadmin bash scripts iteratively and keep them well maintained. Thanks to the built-in dry-run mode, that lists all commands without executing them, log_do reduces the cognitive load needed for running scripts with which you are (or have become over time) unfamiliar.

To learn more, view [log_do on Github](https://github.com/newsnowlabs/log_do).

## Contact

Please reach out to us with any suggestions or queries on the [NewsNow Labs Slack Workspace](https://join.slack.com/t/newsnowlabs/shared_invite/zt-wp54l05w-0DTxuc_n8uISJRtks3Xw3A). We are typically available Monday-Friday, 9am-5pm London time.

## More about NewsNow

[NewsNow](https://www.newsnow.co.uk/) is the UK’s largest independent news aggregation and discovery platform. A one-stop shop for news for 12m unique monthly visitors, NewsNow is a UK top 50 website, and a [global top 50 English-language news site](https://pressgazette.co.uk/most-popular-websites-news-world-monthly/), that also provides [US](https://www.newsnow.com/us/), [Nigerian](https://www.newsnow.com/ng/) and [Romanian](https://www.newsnow.com/ro/) editions.

NewsNow is proud of its 25-year heritage and its place within the media ecosystem, providing an editorially-driven platform that makes it easy for millions of people to discover news from thousands of publishers; and for publications - particularly those that are smaller and independent - to access audiences that can be otherwise hard to reach. The NewsNow platform helps support the growth of credible, independent and public interest journalism and news media plurality.

At NewsNow, we believe a healthy society needs a healthy news diet. Today, we are focussed on how we can improve our own services to facilitate this; and how, together with other news organisations, we can move towards a future where public interest news and journalism is funded sustainably by the people it serves.

[Read more about NewsNow’s social mission, ethos and history.](https://www.newsnow.co.uk/about/)

NewsNow is led by a gender-diverse and technically-minded board. Of our three directors, two are developers — and that includes the Founder & CEO, Struan Bartlett (who is also the founding developer of [Dockside](https://dockside.io)). This means that development is core to the business: developers are appreciated for their creative input and areas of excellence; and the importance of investing in solutions that stand the test of time, and in managing technical debt, is well understood.

If this sounds like a place you might like to work, please check out the [NewsNow Careers page](https://www.newsnow.co.uk/careers/) for current vacancies.
