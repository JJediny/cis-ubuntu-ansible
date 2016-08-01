stage name: "Configure CIS Ubuntu Ansible"
node("master"){
	sh "mkdir -p ansible/roles-ubuntu/roles"
	dir("mkdir -p ansible/roles-ubuntu"){
		checkout scm
		sh "touch playbook.yml"
	}
}