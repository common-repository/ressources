# Ressources
Contributors: bastho, agencenous 
Donate link:  https://apps.avecnous.eu/produit/ressources/?mtm_campaign=wp-plugin&mtm_kwd=ressources&mtm_medium=wp-repo&mtm_source=donate
Tags: server, linux, resources, memory, monitoring, load average, performances 
Requires at least: 4.6  
Tested up to: 6.4  
Stable tag: 1.0.1  
License: GPLv2 

Monitoring the server resources with dashboard widgets

## Description

Not tested on non linux hosted sites !

WordPress monitoring, displays for the super admin, the server ressources on the (network) dashboard

* hostname and distro
* size of the wp-content directory
* available memory
* space used on linux partitions
* process running on the servers

## Installation

1. Upload `ressources` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress network admin

## Frequently asked questions

### Does this plugin works on a windows server ?

No, this plugin only runs on linux servers.

### Does this plugin works on all wordpress instances ?

Yes, both single and multisite. But only the superadmin can view the monitors.

## Screenshots

1. widgets

## Changelog

### 1.0.1
- Check for empty variables
- Declare class property, Fix warnings in PHP8.2

### 1.0
* Use WP translation system
* New icon

### 0.9
* More consistent Style
* Fix HTML Syntax
* Fix PHP Notices (Real instead of Float)

### 0.8
* Fix numeric calculation

### 0.7
* Add PHP memory

### 0.6
* Add number of CPU and CPU model
* Correctly manage RAM

### 0.5
* PHP 7 compliant

### 0.4.1
* WP 4.3 compliant

### 0.4.0
* Add server informations: PHP verion, SQL version
* Optimize performances by introducing different refresh delays

### 0.3.1
* Better calculation of page loading duration
* French localization

### 0.3
* Add: Admin bar info: host name (useful for fallback)
* Add: CPU load average
* Add: Ajax refresh
* Fix: code cleanup

### 0.2
* Add process view

### 0.1
* Plugin creation :
* use SSH commands via php exec() function to display the server ressources.

## Upgrade notice

No particular informations
