# CheckPoint TAdP

## Desenvolvido por Marchel Augusto e @hecasan

### API para monitoramento de ambientes domésticos.
## Tela do projeto
![image](https://github.com/user-attachments/assets/9493c16f-431d-407f-980b-b1a2d2319e8a)

## Técnologias utilizadas 
### O projeto foi desenvolvido em 2 seções, um backend em Node.JS (repositório 2emr-backend-IoT-dados-sensores, que está disponível na aba repositórios da conta Chel2815) e um FrontEnd desenvolvido com HTML, CSS e JavaScript (arquivo que está sendo lido agora =) ).
### No BackEnd do projeto, foram utilizadas as bibliotecas Express (que permite a criação de um server para a realização de requisições de envio e recebimento de dados), SQLite3 (um banco de dados local, para armazenamento dos dados de sensores, login e senha do usuário), BCrypt (biblioteca utilizada para criptografar os dados enviados, usuário, senha e dados dos sensores), JsonWebToken (cria um token para recebimento e autorização de usuários), Cors (biblioteca que autoriza o envio de dados através do protocolo HTTP, podendo enviar ou receber os dados) e Socket.IO (biblioteca que permite a comunicação bilateral).

## Como utilizar o projeto? 
### Copie o link do repositório:
![image](https://github.com/user-attachments/assets/159eeac6-e465-4e1b-ba4a-b30dad6456a2)

### Crie uma pasta no local de sua preferência do seu computador
![image](https://github.com/user-attachments/assets/ed85487e-2e72-4097-b027-f6d0d724d864)
### Nomeie a pasta do jeito desejado, com isto feito, clique com o botão direito do mouse dentro da pasta
![image](https://github.com/user-attachments/assets/32624df1-dd1b-4500-8a23-94e4446676f9)
### Caso no seu computador você tenha instalado a ferramenta Git Bash, clique na opção Open GitBash Here, caso não possua, vá no indicador de rota do exploradorde arquivos e digite este comando:
![image](https://github.com/user-attachments/assets/628857e9-e46b-4de9-be08-ce3f7480128a)
### Com o CMD ou terminal GitBash abertos, digite o comando "git clone" de um espaço e aperte as teclas Shift + Insert, o link do repositório será colado, basta apertar Enter e o repositório será clonado para a pasta.
### Feche o terminal ou GitBash e abra a pasta com os arquivos:
![image](https://github.com/user-attachments/assets/ec9cabee-0fe8-4ba0-a48b-0c2413e4ed37)
### Abra o terminal dentro da pasta com os arquivos, e digite o comando "code ."
### O projeto será aberto no VSCode 

### Com o arquivo Backend é necessário digitar os seguintes comandos no terminal (que pode ser acessado apertando as teclas Ctrl + ") e apertar a tecla enter:
![image](https://github.com/user-attachments/assets/a998e3b3-f168-4a90-815e-bf5c22780042)
![image](https://github.com/user-attachments/assets/52570143-b90b-48f2-a08a-c66380087ef6)

### Após a instalação das dependências, basta digitar o comando "node server.js" no terminal. 
![image](https://github.com/user-attachments/assets/98359533-3ace-480a-bc66-4e0667928c66)
### Para acessar a rota gerada basta apertar a tecla Ctrl + clique botão esquerdo do mouse no link que aparece no terminal.

### Para fazer a instalação do FrontEnd basta seguir os mesmos passos feitos anteriormente, porém copiando o link do repositório Ambiente-Monitorado-Chel2815
### Para rodar o projeto no FrontEnd, é necessário fazer a instalação da extensão Live Server do VSCode:
![image](https://github.com/user-attachments/assets/0128bece-ac7a-4ff4-9a17-024a1a3c61ce)
### Instale a primeira opção
![image](https://github.com/user-attachments/assets/f4af92d3-a05e-45bb-9a9f-d5e48ca6a4db)

### Volte ao arquivo Index.html do projeto, no canto inferior da guia do VSCode busque a opção Live Server e clique nela:
![image](https://github.com/user-attachments/assets/53851694-641e-4bc5-85a2-3462b88e1136)
### Já é possível visualizar a tela inicial do projeto.

## Como o projeto funciona?

### Apertando o botão de + ou esperando 30 segundos, o FrontEnd fará o envio e recebimento dos dados simulados a partir do BackEnd.

### Cada dado enviado será armazenado no banco de dados SQLite3, criando uma linha nova na tabela do banco para cada nova informação recebida pelo BackEnd.









