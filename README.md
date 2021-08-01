# ScriptsCursosContainersExpert

### Tecnologias estudadas
![Docker](https://img.shields.io/badge/-Docker-0db7ed?style=flat-square&logo=docker&logoColor=384d54)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-blue?style=flat-square&logo=kubernetes&logoColor=white)

### Status dos cursos
![DescomplicandoDocker](https://img.shields.io/badge/Descomplicando%20Docker-Finalizado-green)
![DescomplicandoKubernetes](https://img.shields.io/badge/Descomplicando%20Kubernetes-Em%20andamento-orange)
![DescomplicandoIstio](https://img.shields.io/badge/Descomplicando%20Istio-Não%20iniciado-red)

## Sobre o repositório
Aqui se encontram alguns dos scripts ensinados durante a certificação [Containers Expert](https://www.linuxtips.io/certifica%C3%A7%C3%B5es), da escola [LinuxTips](https://www.linuxtips.io/). Fui contemplada com estes treinamentos de forma gratuita através do programa #ChamaAsMinas, visando aumentar a presença feminina em vagas relacionadas à DevOps. Gostaria de, desde já, deixar meu agradecimento ao grande [Jeferson Fernando](https://twitter.com/badtux_) pela iniciativa e pelos fantásticos aprendizados adquiridos (até agora!).

## Organização das pastas
### 🐳 Descomplicando Docker
Contém scripts YAMLs relacionados à parte de Docker Compose do treinamento.

### ⛴ Descomplicando Kubernetes
Contém scripts YAMLs que criam diversos componentes diferentes do K8S. Estão nomeados por ordem de "aparecimento" durante o treinamento, sendo que: o primeiro número representa o dia do treinamento onde apareceu e o segundo número, a ordem.

**Exemplo:** #2.1_ExemploService.yaml ➡ significa que este script apareceu no Dia 2, e foi o primeiro que eu executei e/ou salvei.

## Como usar?
### 🐳 Scripts Docker Compose
Baixe o script e execute-o através do comando `docker-compose`, estando com o Docker devidamente sendo executado na sua máquina.

**Exemplo:** 
```
docker-compose -f Exemplo1.yml up
```

### ⛴ Scripts Kubernetes
Baixe o script e execute-o através do comando `kubeclt create`, estando com o Kubernetes devidamente sendo executado na sua máquina e tendo um cluster funcionando.

**Exemplo:** 
```
kubectl create -f ExemploService.yaml
```

## Créditos
Olá! Meu nome é Olivia. Eu sou uma desenvolvedora web focada no backend e que, muito casualmente, se arrisca no front.

Fique à vontade para me contatar com qualquer pergunta, dicas ou feedbacks sobre esse projeto. Vou ficar muito feliz em ouvir e responder!

:envelope: Email: oli.pmatt@gmail.com

:globe_with_meridians: Blog: [oliviamattiazzo.dev](http://oliviamattiazzo.dev/)

:hatched_chick: Twitter: [@oliviamattiazzo](https://twitter.com/oliviamattiazzo)

:iphone: [Linkedin](https://www.linkedin.com/in/oliviamattiazzo/)