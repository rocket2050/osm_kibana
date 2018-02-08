osm_kibana
----------
This repo is configuring kibana which is accessed by nginx for mutil version OS. This repo by default install kibana 5 but can be dynamic by passing extra-vars or changing the values in vars/main.yml

Supported OS
------------
redhat6/7
centos6/7
ubuntu14/16

Role Name
=========

A brief description of the role goes here.

Requirements
------------
None

Role Variables
--------------

Available variables are listed below, along with default values(see vars/mail.yml):

# vars file for kibana

elk_kibana_username: "admin"

elk_kibana_password: "admin@kibana"

Elasticsearch_ip: ""

Kibana_server_ip: ""


Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: "{{ host }}"
      roles:
         - { role: osm_kibana }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
