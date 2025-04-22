# Use fleet.yaml to deploy

```
Name                 test
Repository URL       https://github.com/cooloo9871/Rancher_CD
Branch Name          main
Paths -> Add Path    test
Deploy To            [Downstream Cluster Name]
```
![image](https://github.com/user-attachments/assets/199d0360-433b-4c05-9d51-1e97d006fbee)

![image](https://github.com/user-attachments/assets/7fe4e95c-9e34-4d3d-96d3-b2180acf4c51)

![image](https://github.com/user-attachments/assets/2a98d1ee-f2e3-4ac7-b811-fcb9b5f7aece)

![image](https://github.com/user-attachments/assets/9e9bc6b2-ac2e-4795-87aa-ec640c816cfa)


```
$ kubectl -n cert-manager get pod
NAME                                       READY   STATUS    RESTARTS   AGE
cert-manager-8576d99cc8-bxrcp              1/1     Running   0          83s
cert-manager-cainjector-664b5878d6-h6pwk   1/1     Running   0          83s
cert-manager-webhook-6ddb7bd6c5-zmjzc      1/1     Running   0          83s
```
