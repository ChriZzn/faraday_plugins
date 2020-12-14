1.4.0:
---
 * Add new plugin base class, for multi line json
 * New ncrack plugin 
 * New nuclei plugin
 * New sslyze json plugin
 * New WhatWeb plugin
 * Fix missing ip in some arachni reports
 * Fix change name vuln in Netsparker plugin
 * Fix whois plugin, command whois IP not parse data
 * Change the way we detect json reports when they are lists of dictionaries

1.3.0:
---
 * ADD plugin AppSpider
 * Add tests to faraday-plugins cli
 * add a default value to plugin_version
 * Add --output-file parameter to faraday-plugins process command
 * Add plugins prowler
 * Add plugins ssl labs
 * Add support for tenable io
 * delete old deprecated methods
 * Bug fix: Arachni Plugin 'NoneType' object has no attribute 'find'
 * Bug fix: Openvas Plugin - Import xml from OpenVas doesnt work
 * Bug fix: QualysWebApp Plugin, error in get info OPERATING_SYSTEM
 * Fix Hydra plugin to resolve ip address
 * Fix Nessus mod severity HIGH for Low 
 * Bug Fix: Detect plugins AWS Prowler
 * Fix broken xml on nmap plugin
 * Add new rdpscan plugin
 * UPDATE xml report to appscan
 * Update Readme
 * Fix how ZAP genereate vulns
