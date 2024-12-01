```markdown
# Detalhes do IP Externo

Este projeto, desenvolvido durante uma aula da Digital Innovation One (DIO), utiliza uma API para buscar informações detalhadas sobre o IP externo do usuário, incluindo dados como localização geográfica, organização, e endereço IP.

## 📝 Descrição

O script faz uma requisição à API `ipinfo.io` para obter detalhes sobre o endereço IP externo do usuário e exibe informações organizadas, como:
- Endereço IP
- Região
- País
- Cidade
- Organização

## 🚀 Como executar

1. Certifique-se de que o Python esteja instalado no seu computador.
2. Clone este repositório ou copie o código para um arquivo local.
3. Execute o script Python:
   ```bash
   python detalhes_ip.py
   ```

## 📂 Estrutura do Código

O código segue a seguinte lógica:
1. Importa as bibliotecas necessárias (`re`, `json` e `urlopen` de `urllib.request`).
2. Faz uma requisição à API `https://ipinfo.io/json` para obter informações do IP.
3. Processa e organiza os dados retornados em variáveis específicas.
4. Exibe os detalhes formatados no terminal.

## 🛠 Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **API ipinfo.io**: Serviço utilizado para buscar informações sobre IP.

## 📚 Referências

- [Documentação da API ipinfo.io](https://ipinfo.io/)

## 🏫 Créditos

Este código foi desenvolvido durante uma aula prática da **Digital Innovation One (DIO)**.
```
