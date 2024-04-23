# gh-to-azure-package

Github to Azure Artifact - Publish python package 
Used PAT as Authentication and ADo username 
Root level of repo add .pypirc file which includes from Project setup and Publish package from the connect feed option from Azure Devops Artifacts

ADO -> ORG -> Artifact -> Select feed -> Connect Feed -> twine -> Project setup and Publish package (Will get pypirc file contehnt and gh actions to include installation steps)
Create PAT from ADO and update that in GH repo secrets to authenticate 

Build the project from setup.py file location : python setup.py sdist bdist_wheel


