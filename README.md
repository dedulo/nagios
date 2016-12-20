# Nagios

This repository contains plugins and scripts related to monitoring (but not to each other).

* **check_directory.pl**: checks the age of oldest / newest file and file count in a
directory, even recursively.

* **check_nrpe_prtg.pl**: translates the output of NRPE plugins \>= 2.0 to the PRTG xml
format. It includes any counters, descriptions, status and messages. It enables
to use Nagios plugins with PRTG.

* **NagiosStatus.pl** and **t/nagios.pl**: Perl module for sending status to Nagios.

* **nagios_to_prtg.txt**: Migration notes.

* **prtg_push.pl**: Perl module for sending status to PRTG.

