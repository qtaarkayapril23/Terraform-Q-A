### 1.What do you mean by Terraform?

* Terraform is open-source communication as a system software tool created by HashiCorp. 
* It is an instrument for building, altering, and versioning transportation safely and professionally. 
* Terraform can direct existing and accepted service providers as well as convention in-house solutions.

### 2.What are the reasons for choosing Terraform for DevOps?

* Below are the reasons for choosing Terraform for DevOps
    * It can do complete orchestration and not just configuration management  (like Ansible and Puppet).
    * Has amazing support of almost all the popular cloud providers like AWS, Azure, GCP, DigitalOcean etc.
    * Easily manages the configuration of an immutable (dynamic) infrastructure.
    * Provide immutable infrastructure where configuration changes smoothly.
    * Works on HCL (HashiCorp configuration language), which is very easy to learn and understand.
    * Easily portable from one provider to another.
    * Easy Installation.


### 3.Define Terraform init?

* Terraform initialises the code with the command `terraform init`. 
* This command is used to set up the working directory for Terraform configuration files. 
* It is safe to run this command multiple times.
* You can use the init command for
    * Installing Plugins
    * Installation of a Child Module
    * Initialization of the backend


### 4.Name some major competitors of Terraform?

* Some of them are
    * Packer
    * Cloud Foundry
    * `Ansible`
    * Kubernetes


### 5.Define Terraform provider?

* Terraform is a tool for managing and informing infrastructure resources such as physical machines, virtual machines (VMs), network switches, containers, and more. 
* A provider is responsible for API interactions that are thoughtful and reveal resources. 
* Terraform is compatible with a wide range of cloud providers.


### 6.How does Terraform work?

* Terraform creates an implementation plan, defines what it will do to achieve the desired state, and then executes it to build the infrastructure described. 
* Terraform is capable of determining what changed and generating incremental execution plans that are practical as the configuration changes.


### 7.Name some major features of Terraform?

* Some of them are
    * Execution Plan
    * Change Automation
    * Resource Graph
    * Infrastructure as code


### 8.Define IAC?

* `IaC` is a short form to the term “Infrastructure as Code”. 
* IaC refers to a scheme whereby developers can run and provision the computer data center’s mechanically instead of getting into a physical process. 
* Terraform IAC, for example, is a case tool of IAC.


### 9.How to check the installed version of Terraform?

* We can use `terraform -version` of the command to identify the version which we are running.


### 10.Describe the working of Terraform core?

* The terraform core examines configuration monitoring and generates configuration-based analysis and evaluation. 
* It keeps track of and compares versions (current and previous) before displaying the results via the terminal.
* Terraform core mainly takes two inputs:
    * Terraform Configuration – It keeps track of the infrastructure detail
    * Terraform state – It keeps track of the infrastructure status.

### 11.What are the key features of Terraform?

* Following are the key features of Terraform:
    * Infrastructure as Code: Terraform’s high-level configuration language is used to define your infrastructure in human-readable declarative configuration files.
    * You may now create an editable, shareable, and reusable blueprint.
    
    * Terraform generates an execution plan that specifies what it will do and asks for your approval before making any infrastructure alterations. 
    * You can assess the modifications before Terraform creates, updates, or destroys infrastructure.
    
    * `Terraform` creates a `resource graph` while simultaneously developing or altering non-dependent resources. 
    * Terraform can now build resources as quickly as possible while also giving you more information about your infrastructure.
    
    * Terraform’s the automation of change allows you to apply complex changesets to your infrastructure with little to no human interaction.


### 12.What are the use cases of Terraform?

* Following are the use cases of Terraform:
    * Setting Up a Heroku App:
        * Heroku is a popular platform as a service for hosting web applications (PaaS). 
        * Developers first create an app, then add add-ons such as a database or an email service. 
        * One of the best features is the ability to scale the number of dynos or workers as needed. 
        * Most non-trivial applications, on the other hand, quickly necessitate a large number of add-ons and external services.
        
        * Terraform can be used to codify the configuration of a Heroku application, ensuring that all necessary add-ons are present, but it can also go beyond, such as configuring DNSimple to set a CNAME or Cloudflare as the app’s CDN. 
        * Best of all, Terraform can accomplish all of this in under 30 seconds without the use of a web interface.
    
    * Clusters of Self-Service: 
        * A centralised operations team overseeing a large and expanding infrastructure becomes extremely difficult at a certain organisational level. 
        * Implementing “self-service” infrastructure, which allows product teams to manage their own infrastructure using tooling provided by the central operations team, becomes more appealing.
        
        * Terraform configuration can be used to keep track of how a service is built and scaled. 
        * You can then share these settings with the rest of your company, allowing client teams to manage their services using Terraform.
    
    * Quick Creation of Environments: 
        * It is common to have both a production and a staging or quality assurance environment. 
        * These environments are miniature versions of their production counterparts, and they are used to test new programmes before they are released to the public. 
        * Maintaining an up-to-date staging environment becomes increasingly difficult as the production environment grows larger and more involved.
        
        * Terraform can be used to codify and share the production environment with staging, QA, and development. 
        * These parameters can be quickly used to create new testing environments that can be easily discarded. 
        * Terraform, which allows parallel environments to be created and destroyed on the fly, can help to alleviate the difficulty of maintaining them.
    
    * Schedulers of Resources:
        * Static application assignment to computers becomes increasingly difficult in large-scale infrastructures. 
        * Among the schedulers that can help with this challenge are Borg, Mesos, YARN, and Kubernetes. 
        * These can be used to schedule Docker containers, Hadoop, Spark, and a variety of other software applications dynamically.
        
        * Terraform isn’t just for Amazon Web Services and other physical service providers. 
        * Terraform can request resources from resource schedulers because they can be viewed as providers. 
        * Terraform can now work in layers, such as deploying the physical infrastructure that powers the schedulers and provisioning into the scheduled grid.
    
    * Demonstrations of software:
        * In today’s world, software is becoming increasingly networked and distributed. 
        * Although virtualized demo environments can be created with tools such as Vagrant, displaying software on real infrastructure that closely replicates production environments remains difficult.
        
        * A Terraform configuration can be used by software authors to design, provision, and bootstrap a demo on cloud providers such as AWS. 
        * End users can simply demo the application on their own infrastructure, and configuration options such as cluster size can be changed to evaluate tools at any scale.


![preview](Images/Thank%20you%20.png)