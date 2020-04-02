# ARM templates

- resource-group.json
`az deployment sub create --name testdeploy --location "local" --template-file resoure-group.json`

- vnest.json
`az deployment group create --name myvnet --resource-group myResourceGroup --template-file vnets.json`

- nsg.json
`az deployment group create --name new-nsg --resource-group myResourceGroup --template-file nsg.json`

- routetable.json
`az deployment group create --name new-routetable --resource-group myResourceGroup --template-file routetable.json`

- vm-nw.json
`az deployment group create --name vms --resource-group myResourceGroup3 --template-file  vm-nw.json`
