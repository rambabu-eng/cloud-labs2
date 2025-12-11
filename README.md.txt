az group create --name myRG --location eastus

az vm create \
  --resource-group myRG \
  --name myVM \
  --image UbuntuLTS \
  --admin-username azureuser \
  --generate-ssh-keys
az vnet create --venet name vnet1 --subnet name subnet1
