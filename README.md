# Minimalist Ansible Example

Make it simple, we tested ansible on docker container

collection used in this example
- [file_module ansible](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/file_module.html)

run
- `docker run --rm -it -v {absolute_path_to_project}/example:/data/example cytopia/ansible ansible-playbook -i example/hosts example/playbook.yml`

result
- new `touch.txt` in example folder
