1- Créer un fork à partir de https://github.com/app-generator/sample-flask-pandas-dataframe.git
2-git clone https://github.com/Kissamisa/sample-flask-pandas-dataframe.git
dans ma machine local 
3-Créer une connexion avec ma machine virtuelle 170.75.161.30
après sh jenkins.sh et activer l env 
4-Create database via Flask CLI
5-Loader les données via un fichier csv 
6-Créer Dockerfile build/run
docker build -t flask-pandas-app .
docker run -p 5000:31201 -d flask-pandas-app