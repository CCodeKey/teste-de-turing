
# Teste de Turing
Esse "teste de turing" foi um projeto utilizado no mestrado do meu ex professor de filosofia, onde consisite na interação de três pessoas, com o objetivo da pessoa A tentar descobrir se a pessoa B ou C são humanas, através de perguntas e respostas.


## Autores

- [@Gabriel Tertuliano](https://www.github.com/ccodekey)
- [@Hellen Lima](https://www.github.com/hellenilda)
- [@Victor Pereira](https://www.instagram.com/victorpereiragomes/)
- [@Juliana](https://www.instagram.com/jullis_august/)
## Estrutura do Projeto

```bash
├── Cliente.py       # cliente que irá fazer e receber as perguntas e respostas 
├── Pessoa_B.py      # interface da pessoa responsável por responder as perguntas recebidas 
├── Server.py        # servidor que fará a lógica de negócio, onde cuidará de receber as perguntas do Cliente, receber a primeira resposta da Pessoa_B, gerar a segunda resposta utilizando a API do chatGPT (ao qual para essa versão, optei por tirar esta função para futuras atualizações), e por fim enviar as duas respostas para o Cliente.
└── README.md        # Documentação do projeto  

```

## Como executar

- Ter o Python instalado na máquina
- Alterar os IPs nos códigos 

```bash
Cliente:
  - Host = ''                           # linha 3

Pessoa_B:
  - HOST = '# IP da maquína local'      # linha 2
  - HOST = '# IP servidor'              # linha 12

Server:
    - HOST = '# IP servidor'            # linha 3
    - HOSTb = '#IP - PC Ro'             # linha 44
    - HOSTa = '# IP servidor'           # linha 49    
```
- Instalar o socket com pip

```bash
  pip install socket
```


## Stack utilizada
- Python
- Socket
