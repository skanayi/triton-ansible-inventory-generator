# triton-ansible-inventory-generator
A simple tool to generate ansible inventory files from triton cloud api.All the tags will be considered as ansible host variables
# Usage
- clone repo
- go build (tested with go1.16.4 )
- Make sure ansible.tmpl file is already available in the same directory
- Set the environment variables as seen under inventory.env and export them (Change values accordingly)
- execute ./triton-ansible-inventory-generator
- wait for ansible.inventory files to be ready
- you can use the same exported variables and golang templates to create various other formats (example: json |yml or anything)

