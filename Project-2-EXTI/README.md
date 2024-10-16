# Controle da cadência de piscar de um LED utilizando EXTI e botão de usuário

## Introdução
Nesta prática, vamos explorar a implementação de um sistema utilizando a placa STM NUCLEO-H753ZI, focando no uso do periférico EXTI (External Interrupt)
para controlar um LED. Através deste exemplo prático, o LED será programado para piscar com uma frequência variável, onde a velocidade será controlada pelo botão
de usuário (botão azul) da placa. O periférico EXTI permite que interrupções externas disparem eventos, tornando-o ideal para interações com dispositivos como botões. Ao pressionar o
botão de usuário, a interrupção será ativada, alterando dinamicamente a frequência de piscar do LED.

## Disciplina

- DCExt Sistemas Embarcados Poli/UPE 2024.2

## Requisitos Necessários

Para a realização da prática proposta, são necessários os seguintes requisitos:

- **Placa de Desenvolvimento**: NUCLEO-H753ZI
- **Software**: 
  - STMCubeIDE (Versão utilizada: 1.16.1)
  - STM32CubeMX (Versão utilizada: 6.12.1)
- **Hardware**: 
  - Cabo USB-microUSB (Com suporte a carregamento e transferência de dados)

## Instalação e Configuração

1. Instale o STMCubeIDE e o STM32CubeMX nas versões mencionadas acima.
2. Conecte a placa NUCLEO-H753ZI ao seu computador usando um cabo USB-microUSB.
3. Clone este repositório em sua máquina local:
    ```bash
    git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
    ```
4. Abra o STMCubeIDE e importe o projeto a partir do diretório clonado.
5. Certifique-se de que o STMCubeMX esteja devidamente configurado para o modelo STM32H7.
6. Compile e carregue o código na placa NUCLEO-H753ZI.

## Estrutura do Projeto

- **/code**: Contém os arquivos de código-fonte.
- **/tutorial**: Documento com o tutorial passo a passo da execução e elaboração do projeto
- **/video**: Contém um video com o resultado obtido no projeto.

## Autores

- Denilson José do Bom Jesus Silva de Lima
- Rennan de Abreu e Lima Januario Silva
- Rodrigo Luiz da Silva
- Thales Mateus Lima Evaristo


