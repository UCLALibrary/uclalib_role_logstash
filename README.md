uclalib_role_logstash [![Build Status](https://travis-ci.com/UCLALibrary/uclalib_role_logstash.svg?branch=master)](https://travis-ci.com/UCLALibrary/uclalib_role_logstash)
=========

Usage of this role will configure logstash 7.x on CentOS and RedHat 7 systems.

Requirements
------------

No external requirements.

Role Variables
--------------

Please view the [defaults](defaults/main.yml) for available role variables and types.

Dependencies
------------

No Dependencies

Example Playbook
----------------

### logstash with defaults configured
    - hosts: servers
      roles:
         - { role: uclalib_role_logstash }

License
-------

[License](LICENSE)

Author Information
------------------

GitHub [issues](https://github.com/UCLALibrary/uclalib_role_logstash/issues) is open in case you'd like to file a ticket or make a suggestion. You can also contact Anthony Vuong at <a href="mailto:avuong@cachemeoutside.io">avuong@cachemeoutside.io</a> if you have a question about the project.
