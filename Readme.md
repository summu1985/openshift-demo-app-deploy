# Cleanup [ All Container Apps ]

```
oc delete Deployment/webapp
oc delete Deployment/todoapi
oc delete ConfigMap/todo-app-configmap
oc delete StatefulSet/mysqldb
oc delete Service/todoapi
oc delete Service/webapp
oc delete Service/mysqldb 
oc delete Route/todo-webapp
```
