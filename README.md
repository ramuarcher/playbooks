# My playbooks
This project about testing basic ansible modules with playbook examples

ansible execution 
 
````ansible-plabook -i hosts playbook.yml -s -K -k````

debug.yml playbook execution

   ````ansible-plabook -i hosts debug.yml -s -K -k````


	Debug mode: p result
                    p task.args
                    task.args['data'] = '{{ var1 }}'
                    p task.args
                    redo


