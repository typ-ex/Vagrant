# Vagrant

Set up Vagrant and Virtualbox, and run a basic ansible playbook that ensures that chrony is installed and running

Won't work on AWS.  Virtualbox won't work on AWS because Xen environment isn't supported.

Won't work on Azure.  Nested virtualization is supported on limited instance builds, and windows only.  The windows bit makes Ansible a pain to use.

It could work on GCP.  Instructions seem to be a bit much to bother executing this on GCP.

Used on digitalocean and should work on local assuming host OS is some distro of linux, virtualbox/vagrant is installed.
