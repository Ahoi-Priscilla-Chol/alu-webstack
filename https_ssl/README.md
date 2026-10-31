# HTTPS SSL

This directory contains the scripts for the HTTPS and SSL project.

## Tasks

- `0-world_wide_web`: Bash script that displays information about the
  subdomains `www`, `lb-01`, `web-01` and `web-02` of a given domain, or
  about one specific subdomain if it is passed as a second argument. It uses
  `dig` and `awk` and prints the record type and destination of each one.
