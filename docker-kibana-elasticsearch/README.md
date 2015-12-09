# Deployment of Kibana+Elasticsearch Containers with Docker Compose

These templates are taken from <a href="https://github.com/Azure/azure-quickstart-templates/tree/master/docker-kibana-elasticsearch">The github Azure account</a>, I have just added North Europe as a possible region

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faspenryd%2Fazure-quickstart-templates%2Fmaster%2Fdocker-kibana-elasticsearch%2Fazuredeploy.json" target="_blank">
	<img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template allows you to deploy an Ubuntu Server 15.04 VM with Docker (using the [Docker Extension][ext])
and starts a Kibana container listening on port 5601 which uses Elasticsearch database running
in a separate but linked Docker container, which are created using [Docker Compose][compose]
capabilities of the [Azure Docker Extension][ext].


[ext]: https://github.com/Azure/azure-docker-extension
[compose]: https://docs.docker.com/compose
