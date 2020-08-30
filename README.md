# ansible-aws
<h1>Webserver configuration on AWS EC2 Instance using Ansible</h1>
<img src="https://miro.medium.com/max/1400/1*cuhl9GR6ZGnAt3al7z3xLg.jpeg" alt="Ansible" width="1080" height="1920">1920
<h2>Problem Statement</h2>
<li>
Provision EC2 instance through ansible.</li>
<li>Retrieve the IP Address of instance using a dynamic inventory concept.</li>
<li>Configure the webserver through ansible!</li>
<li>Create a role for the webserver to customize the Instance and deploy the webpage to the root directory.
  </l1>
<p>In this task we will learn how to deploy a webserver on the top AWS EC2 instance using Ansible roles.
We will be using RHEL8 as Controller Node and AWS Ec2 instance as Managed Node.</p>

<h1>About Ansible</h1>
<p>Ansible is an open-source software provisioning, configuration management, and application-deployment tool enabling infrastructure as code. It runs on many Unix-like systems and can configure both Unix-like systems as well as Microsoft Windows. It includes its own declarative language to describe system configuration. Ansible was written by Michael DeHaan and acquired by Red Hat in 2015. Ansible is agentless, temporarily connecting remotely via SSH or Windows Remote Management (allowing remote PowerShell execution) to do its tasks.</p>
<h1>Amazon Elastic Compute Cloud (EC2) </h1>
<p>Amazon Elastic Compute Cloud (EC2) is a part of Amazon.com's cloud-computing platform, Amazon Web Services (AWS), that allows users to rent virtual computers on which to run their own computer applications. EC2 encourages the scalable deployment of applications by providing a web service through which a user can boot an Amazon Machine Image (AMI) to configure a virtual machine, which Amazon calls an "instance", containing any software desired. A user can create, launch, and terminate server-instances as needed, paying by the second for active servers - hence the term "elastic". EC2 provides users with control over the geographical location of instances that allows for latency optimization and high levels of redundancy.</p>
