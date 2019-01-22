# nginxconfigansible
ansible script for nginx config deploy

# cmd
ansible-playbook -i inventory nginx_deploy.yaml --extra-vars 'frontend_dns=optit.cccsuk.co.uk backend_dns=optit-test.cccsuk.co.uk keycloak_dns=optitkl.cccsuk.co.uk'

