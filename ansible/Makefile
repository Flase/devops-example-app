deploy:
	ansible-playbook release.yml -i inventory.ini --extra-vars="version=v${V}" -vv

setup:
	ansible-playbook setup.yml -i inventory.ini --extra-vars="version=v${V}" -vv

setup-pvc:
	ansible-playbook setup-pvc.yml -i inventory.ini --extra-vars="version=v${V}" -vv