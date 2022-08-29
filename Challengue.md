DevSecOps Challengue


Usando el free tier (gratis) de AWS

Crear un repositorio de CodeCommit y clonar el contenido de https://github.com/4auvar/VulnNodeApp
Crear un pipeline con CodePipeline que permita:

1 - Compilar la app
2 - Scanear dependencias de Nodejs, informar sus vulnerabilidades y visualizarlas
3 - Crear un container de docker con la app
4 - Scanear el container de docker implementando trivy
5 - Chequear secrets en el codigo (gitleaks)
6 - Deployar el container en una instancia de EC2 t2.nano (free tier)
7 - Ejecutar un webscan utilizando ZAP Proxy

Notas

Crear la infraestructra de codigo de la instancia de EC2 respetando framework PCI.
