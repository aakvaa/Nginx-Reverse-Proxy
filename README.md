# Nginx-Reverse-Proxy para esteira CICD kubernetes

Exemplo de configuração DNS

> Configurar DNS na máquina:
- abrir bloco de notas como admin e abrir o txt no seguinte caminho;
- C:\Windows\System32\drivers\etc\hosts
- adicionar a seguinte linha para apontar o ip:
  192.168.x.x jenkins.localhost.com gitea.localhost.com harbor.localhost.com sonarqube.localhost.com argocd.localhost.com
onde 192.168.x.x é o ip da vm do cluster.
