# externalsecret-demo
vault is running inside kuberntes.
examples uses : externalsecret operator for kuberntes
key value used: 
- vault kv put secret/devwebapp/config username='giraffe' password='salsa'

offical vault doc followed for authetication can be used any.

-- the same permisson is needed if svcaccounnt token used for review.[else follow your own auth module,there are many :)]