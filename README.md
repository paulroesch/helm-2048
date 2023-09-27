# helm chart for 2048 game 
This is a helm chart of the 2048 game. It has been created for practicing helm. 
Used command: "helm create helm-2048" to create the chart.
Adjusted values of file values.yaml: 
- image.repository: pauroe/2048-game
- image.tag: "latest"
- replicaCount: 5

Dockerimage: pauroe/2048-game (built from https://github.com/andrisro/docker-2048)
