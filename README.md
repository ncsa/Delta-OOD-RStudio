# Open OnDemand RStudio App for Delta

Interactive RStudio app for Delta's Open OnDemand portal

## Requirements

On compute nodes (NOT the Open OnDemand node):

 - Apptainer

## Installation

 1. Clone this app to OOD's app directory (/var/www/ood/apps/sys by default).
 2. Adjust repo URLs in `container_files/matlab-proxy.def` to use correct local or external repos
 3. Build the Apptainer image and place it into a path that matches the command in `template/script.sh.erb`.
 4. Adjust cluster name and Lmod module names in form.yml to match the system.

## Acknowledgements

 - [OSC/bc_osc_jupyter](https://github.com/OSC/bc_osc_jupyter)
