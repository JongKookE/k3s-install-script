# K3S Install Script

``` bash
sudo apt install ansible -y

ansible-playbook -i inventory.ini playbook.yml

# 특정 태그만 실행
# ansible-playbook -i inventory.ini playbook.yml --tags [tag1, tag2]

# 또 다른 role 만들기
# ansible-galaxy init another-role
```