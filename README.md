# Teste de Turin

## Como utilizar
1. Instalar o Python

2. Instalar o socket com `pip`
  ```bash
  pip install socket
  ```

---

## Sobre o projeto

* Esse teste de turing foi um projeto utilizado no doutorado do meu professor de filosofia, onde consisite na interação de três pessoas. A pessoa A tenta descobrir se a pessoa B ou C são humanos ou não.  

---

## Estrutura
- Cliente.py = código que irá fazer as perguntas
- Pessoa_B.py = interface da pessoa que irá responder as perguntas
- Server.py = servidor que fará a lógica de negócio, onde cuidará de receber as perguntas do Cliente, receber a primeira resposta da Pessoa_B, gerar a segunda resposta utilizando a API do chatGPT (ao qual para essa versão, optei por tirar esta função para futuras atualizações), e por fim enviar as duas respostas para o Cliente.
