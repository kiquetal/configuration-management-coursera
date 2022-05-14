#### Configuration Management

##### Scale
	
	Being able to scale means that we can keep archiving larger impacts with
	the same amount of effort.

##### Configuration Management

	A set of configuration ready to be replicated in all nodes, using automation easily
	
#### IaC

	When all the configuration are stored in version control.

#### Puppet

	Resources: basic unit for modeling a conf.
	
	class sysctl {
	file { '/etc/sysctl.d':
	     ensure => directory,
        }
     }

