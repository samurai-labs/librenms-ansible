Ansible playbook that will automate the installation of LibreNMS based on installation instructions
located at: http://docs.librenms.org/Installation/Installation-(Debian-Ubuntu)

Next steps for Ansible config: add logic for installing on Debian/Ubuntu/Redhat variants

After running please visit the site below to finish the configuration (local admin, etc)
http://docs.librenms.org/Installation/Installation-(Debian-Ubuntu)/#initialise-the-database

CAUTION: This script is not idempotent - not safe to run more than once
More specifically, it's safe to run more than once as long as you have 
not intilized the database and added hosts to monitor.

TESTED ON: Debian 8.1
