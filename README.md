# ARM templates

- resource-group.json
`az deployment sub create --name testdeploy --location "local" --template-file resoure-group.json`

- vnest.json
`az deployment group create --name myvnet --resource-group myResourceGroup --template-file vnets.json`

- nsg.json
`az deployment group create --name new-nsg --resource-group myResourceGroup --template-file nsg.json`
