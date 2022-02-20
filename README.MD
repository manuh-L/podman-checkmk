The playbook downloads the check-mk image, upload it and runs the check-mk container on podman

Change the IP/hostname in the inventory file to your target node

* Run: 
        #### ansible-playbook podman-cmk.yml

# URL to access the Check-MK: 
http://nodeIP:8080/cmk/check_mk/