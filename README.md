# Bilhetinho — WEBGUI

> MVP desenvolvido para a disciplina de **Engenharia de Software**  
> Pós-Graduação em Engenharia de Software — PUC-Rio

---

## Autor

Marcelo M. Caetano  
[https://www.linkedin.com/in/marcelomcaetano/](https://www.linkedin.com/in/marcelomcaetano/)  

---

## Sobre o Projeto

O **Bilhetinho WEBGUI** é o projeto centralizador e integrador da solução **Bilhetinho**. Ele representa a visão unificada do produto, cujo propósito é modernizar e digitalizar a tradicional interação entre o público e os músicos em apresentações ao vivo em bares, restaurantes e eventos.

Em vez de escrever pedidos de música em guardanapos de papel ou depender da entrega pelo garçom, a solução permite que as pessoas façam pedidos diretamente de seus celulares e que os músicos tenham controle ágil sobre o repertório e as solicitações recebidas no palco.

---

## O que cada pasta representa neste ecossistema

Este projeto central organiza a solução em duas frentes complementares e independentes:

* **📁 `bilhetinho-ui` (Interface com o Usuário):**  
  Representa a camada de apresentação visual do produto. É onde acontecem todas as interações humanas do sistema: a tela que o público utiliza para escolher músicas e enviar seus bilhetinhos, e o painel de controle que o músico consulta para visualizar e responder aos pedidos em tempo real.

* **📁 `bilhetinho-api` (Serviço de Negócios e Dados):**  
  Representa o cérebro funcional do produto. É responsável por receber, organizar, validar e guardar todas as informações dos eventos e pedidos de música, garantindo que os dados fiquem seguros e disponíveis para alimentar a interface.
