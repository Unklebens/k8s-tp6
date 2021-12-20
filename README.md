 # TP6





 kubectl run wepabb-red --image=kodekloud/webapp-color --port 8080 --env APP_COLOR=red 

 kubectl run nginx-tp6 --image=nginx --port 8080 --replicas=2