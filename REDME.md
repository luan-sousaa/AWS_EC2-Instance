AWS EC2 Instance with Basic HTML Webpage
Este projeto demonstra a criação de uma instância EC2 na AWS e a configuração de um servidor HTTPD para hospedar uma página web simples usando HTML básico.

Objetivo
O objetivo deste projeto é mostrar o conhecimento básico em AWS, incluindo a criação e configuração de uma instância EC2 e a implantação de uma página web estática.

Pré-requisitos
Antes de começar, você precisará:

Uma conta na AWS
Conhecimento básico de linha de
Familiaridade com conceitos de rede e servidores web 

Passos para Configuração

1. Criação da Instância EC2
Acesse o console da AWS e vá para o serviço EC2.
Clique em "Launch Instance".
Escolha uma Amazon Machine Image (AMI). Neste exemplo, utilizamos a Amazon Linux 2 AMI.
Selecione o tipo de instância. O tipo "t2.micro" é suficiente para este projeto.
Configure as opções da instância conforme necessário e clique em "Next: Add Storage".
Adicione armazenamento conforme necessário e clique em "Next: Add Tags".
Adicione tags para identificar sua instância (opcional) e clique em "Next: Configure Security Group".
Configure o Security Group para permitir tráfego HTTP (porta 80).
Revise as configurações e clique em "Launch".
Escolha ou crie um par de chaves para acessar a instância e clique em "Launch Instances".

Este projeto mostra como criar uma instância EC2 na AWS, configurar um servidor HTTPD e hospedar uma página web básica.
É um ótimo ponto de partida para entender os conceitos fundamentais de computação em nuvem e servidores web.