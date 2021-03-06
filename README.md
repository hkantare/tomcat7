# Tomcat 7 Template

This template allocates a virtual machine instance and provisions Apache Tomcat onto the instance.

## Using This Template

In Schematics create variables `softlayer_username`, `softlayer_api_key`, `ssh_key`.

The file `/root/tomcat` has the associated credentials & access information.

## Variables

|Variable Name|Description|Default Value|
|-------------|-----------|-------------|
|hostname     |           |hostname|
|domain       |           |domain.dev|
|datacenter   |           |wdc01|
|os_reference_code||CENTOS_7|
|cores|CPU cores|1|
|memory||1026|
|disk_size|in GB|25|
|private_network_only||false|
|network_speed||100|
|tags|||
|ssh_user|provisioning username|root|
|ssh_label||public ssh key - Schematics VM|
|ssh_notes|||
|ssh_key|your public SSH key to use for access to virtual machine||
