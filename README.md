# SISTEMA WEB - FLASK & PYTHON
> _Caio Pietro Fernandes - N° 03_  
> 
> _Daniel Fonseca Monteiro - N° 05_  
> 
> _Daniel Amaral Santos - N° 07_  
> 
> _Matheus Vinicius Gatto - N°25_  
> 
> _Murillo Henrique de Oliveira Rodrigues - N°26_  
>

> *RASCUNHO NOTION: https://lizard-tangerine-a45.notion.site/SISTEMA-WEB-1ee6cd955f7a80f6bf8ff024739c9c27?pvs=4*    
> *INTERFACE FIGMA: https://www.figma.com/design/UVNVsQCscNTI7k1Csrbe3D/Untitled?node-id=0-1&t=nj8AfGZnQ008U5vX-1*  
___
### DAILY
_Nosso projeto consiste no desenvolvimento de um sistema web com o objetivo de monitorar um broker, facilitando o acompanhamento e a visualização das informações em tempo real. A aplicação está sendo construída utilizando Python como linguagem principal, com o framework Flask para o desenvolvimento da interface web e da lógica de backend. A proposta é garantir uma solução leve, funcional e acessível via navegador, permitindo uma melhor gestão e análise dos dados fornecidos pelo broker._  
_Iremos reutilizar os equipamentos utilizados no projeto anterior, visando otimizar tempo e agilizar o processo de desenvolvimento, iremos ultilizar a biblioteca PAHO MQTT, porque conseguimos conectar o nosso Servidor Web com o nosso broker MQTT, assim lendo as mensagens. A raspberry vai ser mais uma vez o servidor que irá fazer a conexão entre as máquinas, pórem, dessa vez nao iremos trabalhar com mais um grupo._ 

_Iremos fazer o monitoramento de um LDR, botão e um Led, porque pensamos em sair um pouco da curva_
<p align="center">
  <img src="https://github.com/user-attachments/assets/7c48af9d-ef10-4fef-b25f-adedc99b359f" width="500"/>
  <img src="https://github.com/user-attachments/assets/127da00f-8608-4e67-8434-7f57798098c4" width="400"/>
</p>
_Fizemos uma interface boa, porém com um unico objetivo, que era monitorar as mensagens enviadas e recebidas de um dispositivo para o outro, a ideia do design do nosso interface é deixar uma fácil interpretação para quem precisar ler.             
___

O unico comando que nós usamos para "ativar" o MQTT foi ver se ele estava ativado, com isso o comando foi:

```
sudo systemctl status mosquitto   
```
_SAÍDA: "active (running)"_ = ✅   
_Com isso tivemos a certeza que nosso equipamento está pronto para começar a operação._
___
## EQUIPAMENTOS 
- LDR
- ESP-32
- BOTÃO
- LED
- JUMPERS
- RESISTOR
- RASP BERRY

## REGISTROS
<p align="left">
  <img src="https://github.com/user-attachments/assets/a61f744a-90a6-4d7f-b104-80e9eef0f54e" width="300"/>
</p>

___
## CÓDIGOS PARA O PROJETO

```

```

