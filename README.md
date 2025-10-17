# TP CI/CD Terraform Pipeline Azure DevOps pour fmt, validate et plan (dev & prod).
L’automatisation de la CI dans ce TP va permettre de gerer deux workspace dev et prod avec des backend distants pour le state sous cette forme au niveau architecture en re utilisant le Container déjà existant :
tfstate/
--------- rg-demo/
------- terraform.tfstate
----- dev/ ← Workspace DEV
----- prod/ ← Workspace PROD
