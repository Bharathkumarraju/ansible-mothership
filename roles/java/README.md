The Role is used to install java with specific versions
Default java package to be installed is java-1.8.0-openjdk-1.8.0.181

In our playbook the role can be called as below with required java_package name and version

  roles:
     - { role: java, java_package: 'java-1.8.0-openjdk', version: '1.8.0.191.b12-0.el7_5' , test: '123'}
    
