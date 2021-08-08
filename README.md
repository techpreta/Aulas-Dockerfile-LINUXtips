# Aulas-Docker-Dockerfiles
<html>
  <b>ADD</b> => Copia novos arquivos, diretórios, arquivos TAR ou arquivos remotos e os adicionam ao filesystem do container;

<b>CMD</b> => Executa um comando, diferente do RUN que executa o comando no momento em que está "buildando" a imagem, o CMD executa no início da execução do container;

<b>LABEL</b> => Adiciona metadados a imagem como versão, descrição e fabricante;

<b>COPY</b> => Copia novos arquivos e diretórios e os adicionam ao filesystem do container;

<b>ENTRYPOINT</b> => Permite você configurar um container para rodar um executável, e quando esse executável for finalizado, o container também será;

<b>ENV</b> => Informa variáveis de ambiente ao container;

<b>EXPOSE</b> => Informa qual porta o container estará ouvindo;

<b>FROM</b> => Indica qual imagem será utilizada como base, ela precisa ser a primeira linha do Dockerfile;

<b>MAINTAINER</b> => Autor da imagem; 

<b>RUN</b> => Executa qualquer comando em uma nova camada no topo da imagem e "commita" as alterações. Essas alterações você poderá utilizar nas próximas instruções de seu Dockerfile;

<b>USER</b> => Determina qual o usuário será utilizado na imagem. Por default é o root;

<b>VOLUME</b> => Permite a criação de um ponto de montagem no container;

<b>WORKDIR</b> => Responsável por mudar do diretório / (raiz) para o especificado nele;
</html>
