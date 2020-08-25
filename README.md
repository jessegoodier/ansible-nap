# ansible-nap

## Usage
install galaxy collections:
`ansible-galaxy install nginxinc.nginx`
`ansible-galaxy install nginxinc.nginx_app_protect`

install NGINX Plus first

`ansible-playbook nginx_plus.yaml -b -i inventory`

install app protect

`ansible-playbook nginx-app-protect-ansible-playbook.yml -b -i inventory`
