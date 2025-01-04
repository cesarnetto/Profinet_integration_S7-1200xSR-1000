# Integração Profinet SR-1000 x S7-1200

## Introdução

Este projeto tem como objetivo a integração entre o dispositivo SR-1000 e o controlador S7-1200 utilizando o protocolo de comunicação Profinet. 
A solução permite a troca de dados entre o SR-1000 e o PLC S7-1200.

## Arquitetura do Sistema

A comunicação entre o S7-1200 e o SR-1000 é realizada através da rede Profinet, com o S7-1200 atuando como o controlador principal e o SR-1000 como um dispositivo de campo. O fluxo de dados entre ambos é realizado por meio de entradas e saídas mapeadas no TIA Portal.

## Dependências

  - PLC Siemens S7-1200;
  - Leitor de código SR-1000 da Keyence com interface Profinet; 
  - Software TIA Portal para programação e configuração do PLC V15.1;
  - AutoID Network Navigator Software para cofiguração do leitor.
    
