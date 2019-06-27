all:
	make pre-test
	make test
	make post-test

pre-test:
	which vagrant >/dev/null 2>&1
	which ansible-playbook >/dev/null 2>&1

test:
	vagrant up

post-test:
	vagrant destroy -f
