# vagrant-ansible-generic
A generic Vagrant recipe using the Ansible provisioner and initial configuration from Phansible.com

# Steps 1 - 4

Follow branches step1 - 4 to configure a generated template from Phansible.com to (commits on each step):

### (step1)

```
[Phansible] Added the generated template from Phansible.com
```

### (step2)

```
[Ansible] Added task to import database schema
[Application] Create basic DB schema script.
[Application] Create DB populate script.
[Ansible] Add mysql populate DB task.
```
### (step3)

```
[Composer] Add an empty composer.json file.
[Ansible] Created task for composer install.
```
### (step4)

```
[Application] A basic script using composer's autoloader with a namespace as a basic example.
[Composer] Added an autoloader for the sample 1-file app.
[Vagrantfile] Minor change so we are no longer asked the su pwd during the initial vagrant up.
```
