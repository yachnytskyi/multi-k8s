The project uses React on the frontend side and Express on the backend side. It also uses Docker/Kubernetes/Travis/Scaffold for CI/CD with Google Cloud. 
You can deploy and launch this project in your own Google Cloud account. In this case you must replace all credentials on yours in deploy.sh, travis.yml,
Dockerrrun.aws.json (if you need it), client-deployment.yaml, server-deployment.yaml, worker-deployment.yaml. You alse need to create credentials for your own 
login/password accounts with Travis and Google Cloud.

The project also uses scaffold for local launching. You can launch it locally by using this command: 

scaffold dev

Using this command you also can deploy some local changes to your kubernetes cluster directly without the full CI/CD proccess.
