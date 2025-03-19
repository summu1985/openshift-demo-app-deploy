#Cleanup [ All Container Apps ]

```
oc delete Deployment/webapp, Deployment/todoapi , ConfigMap/todo-app-configmap , StatefulSet/mysqldb , Service/todoapi , Service/webapp , Service/mysqldb -n <your namespace name>
```
