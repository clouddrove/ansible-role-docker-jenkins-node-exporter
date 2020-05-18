<!-- This file was automatically generated by the `geine`. Make all changes to `README.yaml` and run `make readme` to rebuild this file. -->


<p align="center"> <img src="https://user-images.githubusercontent.com/50652676/62451340-ba925480-b78b-11e9-99f0-13a8a9cc0afa.png" width="100" height="100"></p>

<h1 align="center">
    Ansible Role Docker Jenkins Node Exporter


</h1>

<p align="center" style="font-size: 1.2rem;"> 
    This ansible role is used to setup Jenkins node exporter with docker.
     </p>

<p align="center">

<a href="https://www.ansible.com">
  <img src="https://img.shields.io/badge/Ansible-2.8-green?style=flat&logo=ansible" alt="Ansible">
</a>
<a href="LICENSE.md">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="Licence">
</a>
<a href="https://ubuntu.com/">
  <img src="https://img.shields.io/badge/ubuntu-16.x-orange?style=flat&logo=ubuntu" alt="Distribution">
</a>
<a href="https://ubuntu.com/">
  <img src="https://img.shields.io/badge/ubuntu-18.x-orange?style=flat&logo=ubuntu" alt="Distribution">
</a>


</p>
<p align="center">

<a href='https://facebook.com/sharer/sharer.php?u=https://github.com/clouddrove/ansible-role-docker-jenkins-node-exporter'>
  <img title="Share on Facebook" src="https://user-images.githubusercontent.com/50652676/62817743-4f64cb80-bb59-11e9-90c7-b057252ded50.png" />
</a>
<a href='https://www.linkedin.com/shareArticle?mini=true&title=Ansible+Role+Docker+Jenkins+Node+Exporter&url=https://github.com/clouddrove/ansible-role-docker-jenkins-node-exporter'>
  <img title="Share on LinkedIn" src="https://user-images.githubusercontent.com/50652676/62817742-4e339e80-bb59-11e9-87b9-a1f68cae1049.png" />
</a>
<a href='https://twitter.com/intent/tweet/?text=Ansible+Role+Docker+Jenkins+Node+Exporter&url=https://github.com/clouddrove/ansible-role-docker-jenkins-node-exporter'>
  <img title="Share on Twitter" src="https://user-images.githubusercontent.com/50652676/62817740-4c69db00-bb59-11e9-8a79-3580fbbf6d5c.png" />
</a>

</p>
<hr>



We eat, drink, sleep and most importantly love **DevOps**. DevOps always promotes automation and standardisation. While setting up various environments like local, dev, testing, production, etc. it is critical to maintain the same environment across. This can easily be achieved using automating the environment setup & installation with the help of ansible-playbooks. 

Smaller roles are created for each environment elements; which also include tasks & tests. These roles can then be grouped together in [ansible-playbook](https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html) to achieve the desired yet consistent results.



## Prerequisites

This module has a few dependencies: 

- [Ansible2.8](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- [Python](https://www.python.org/downloads)
- [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu)
- [Jenkins](https://github.com/clouddrove/ansible-role-docker-jenkins)




## What Includes

Following things includes in this role:

- jenkins-node-exporter







## Example Playbook

**IMPORTANT:** Since the `master` branch used in `source` varies based on new modifications, we suggest that you use the release versions [here](https://github.com/clouddrove/ansible-role-docker-jenkins-node-exporter/releases).


```yaml
- hosts: localhost
  remote_user: ubuntu
  become: true
  roles:
    - clouddrove.ansible_role_docker_jenkins_node_exporter
```


## Variables

```yaml
  jenkins_exporter_server_port: 9103
  jenkins_exporter_server_bind: 0.0.0.0
  jenkins_exporter_server_password: false
  jenkins_exporter_version: latest
  jenkins_address: "{{ PrivateIp }}"
  jenkins_user: ""
  jenkins_pass: ""
```


## Installation

```console
  $ ansible-galaxy install clouddrove.ansible_role_docker_jenkins_node_exporter
```






## Feedback 
If you come accross a bug or have any feedback, please log it in our [issue tracker](https://github.com/clouddrove/ansible-role-docker-jenkins-node-exporter/issues), or feel free to drop us an email at [hello@clouddrove.com](mailto:hello@clouddrove.com).

If you have found it worth your time, go ahead and give us a ★ on [our GitHub](https://github.com/clouddrove/ansible-role-docker-jenkins-node-exporter)!

## About us

At [CloudDrove][website], we offer expert guidance, implementation support and services to help organisations accelerate their journey to the cloud. Our services include docker and container orchestration, cloud migration and adoption, infrastructure automation, application modernisation and remediation, and performance engineering.

<p align="center">We are <b> The Cloud Experts!</b></p>
<hr />
<p align="center">We ❤️  <a href="https://github.com/clouddrove">Open Source</a> and you can check out <a href="https://github.com/clouddrove">our other modules</a> to get help with your new Cloud ideas.</p>

  [website]: https://clouddrove.com
  [github]: https://github.com/clouddrove
  [linkedin]: https://cpco.io/linkedin
  [twitter]: https://twitter.com/clouddrove/
  [email]: https://clouddrove.com/contact-us.html
  [terraform_modules]: https://github.com/clouddrove?utf8=%E2%9C%93&q=terraform-&type=&language=
