# CloudComputingPractice
## Sample yaml files

---                                                                                                                                                                                                                
 
apiVersion: v1
 
kind: Pod 
 
metadata:
 
  name: mybroker
 
  labels:
 
    app: web 
 
spec:
 
  containers:
 
    - name: front-end
 
      image: ubuntu-python
 
      ports:
 
        - containerPort: 80
 
    - name: helper
 
      image: ubuntu
 
      ports:
 
        - containerPort: 88
