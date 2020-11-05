
<h1 aligin="center"> Monitoração Dynatrace </h1>

<p aligin="justify"> Arquivo necessário para monitorar infraestrutura das aplicações do cliente MC1</p>



### <p> Instalação</p>

<p>Para instalar o agent, será necessario copiar o script Dynatrace-OneAgent-Linux, e chave dt-root.cert para o host ou container que queria monitorar e executar o seguinte comando: </p>

```
/bin/sh Dynatrace-OneAgent-Linux-1.203.166.sh --set-host-name="Nome do Container" NON_ROOT_MODE=0
```

Obs: Mude o set-host-name com o nome do container da aplicação
