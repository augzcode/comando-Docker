# comando-Docker
### 10 comando Docker para ir se aocstumando com o sistema

<div align="center">

<img width="600" height="300" alt="docker_banner_2022" src="https://github.com/user-attachments/assets/ad6105c5-838d-48c7-89cd-5a166d29ab4e" />

  <p align="center">
    <strong>O Docker é uma plataforma que utiliza containers para executar aplicações de forma isolada e padronizada, facilitando o desenvolvimento, teste e implantação em diferentes ambientes.</strong>
    
  </p>
  </div>

  ## 1. Docker pull < imagem >
`Docker pull` Baixa uma imagem do Docker Hub para sua máquina.

## 2. Docker  run
`Docker run` Cria e inicia um novo contêiner a partir de uma imagem.
Exemplo: docker run -d -p 80:80 nginx executa o Nginx em segundo plano e libera o terminal.

## 3. Docker ps
`Docker ps` Lista apenas os contêineres que estão em execução no momento.
`docker ps -a` Lista todos os contêineres criados, incluindo os parados ou finalizados.

## 4. Docker stop < id ou nome >
`Docker stop` Interrompe um contêiner em execução de forma segura.

## 5. Docker start < id ou nome >
`Docker start` Inicia novamente um contêiner que já foi criado anteriormente.

## 6. Docker rm < id ou nome >
`Docker rm` Remove permanentemente um contêiner parado do sistema.

## 7. Docker images
`Docker images` Exibe todas as imagens Docker armazenadas na máquina.

## 8. Docker rmi < id da imagem >
`Docker rmi` Remove uma imagem específica do sistema.

## 9. Docker exec -it < id ou nome >
`Docker exec -it` Abre um terminal interativo dentro de um contêiner em execução.

## 10. Docker logs < id ou nome >
`Docker logs` Exibe os logs e mensagens geradas por um contêiner, útil para identificar erros ou acompanhar sua execução.
