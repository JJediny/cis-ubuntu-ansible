stage name: "Configure CIS Ubuntu Ansible"
node("master"){
	sh "mkdir -p ansible/roles-ubuntu/roles"
	dir("mkdir -p ansible/roles-ubuntu"){
		git 'https://github.com/GSA/cis-ubuntu-ansible.git'
		sh "touch playbook.yml"
	    echo "we are dealing with "+NISTAudit
		//sh "ansible-playbook -b -u ubuntu -i '10.0.0.114,' playbook.yml --tags "+NISTAudit
	}
}