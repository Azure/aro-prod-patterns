### Post Provisioning Task


APPID=85d2f968-101b-4ac1-8bb1-cdc7580d4f45
SECRET=_xm.7~wqf4qBp_B1a2uc3A5O-qd18dU7Ym



az aro create \
  --resource-group $RESOURCEGROUP \
  --name $CLUSTER \
  --vnet aro-vnet \
  --master-subnet master-subnet \
  --worker-subnet worker-subnet \
  --client-id $APPID \
  --client-secret $SECRET \
  --pull-secret @pull-secret.txt

cluster: https://console-openshift-console.apps.vc7tjz4j.eastus.aroapp.io/dashboards

kubeadmin
aKoJa-WkewJ-gdgoP-iFgnu