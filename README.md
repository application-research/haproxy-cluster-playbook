# haproxy-cluster-playbook
A highly available set (usually a triplet) of haproxies

## Usage
* Fill out vars
* Fill out inventory
* `ansible-playbook site.yml --become --ask-become-pass`

## TODO
* Add support for multiple floating IPs, as it currently won't configure all of them for you.