# Ansible role to install and configure NRPE under xinetd on CentOS 7

This installs Nagios, NRPE, and xinetd and configures NRPE to run under xinetd. That's pretty much it at this point.

I created this to demonstrate that I could reliably reproduce an error with a minimal install, but in the process have found that I cannot reproduce the error.

Default username/password for http://localhost/nagios/ is nagiosadmin/nagiosadmin.