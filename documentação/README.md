# Trabalho Prático Individual - Integração de Sistemas

## Unidade Curricular: Integração de Sistemas
**Docente:** Filipe Madeira  
**Discente:** David Berec - 220000909  

---

## Descrição do Projeto
Este projeto tem como objetivo desenvolver um **sistema cliente-servidor** demonstrando a implementação e integração de **múltiplas tecnologias de serviços web**. O sistema inclui funcionalidades para **exportação e importação de dados** nos formatos **XML e JSON**, garantindo a persistência e validação dos dados.


## Tecnologias Utilizadas

### **Servidor**
**SOAP** – Implementado com **Spyne**, utilizando validação XML via **XSD**  
**REST** – API desenvolvida em **Flask**, validando JSON com **JSON Schema**  
**GraphQL** – Implementação com **Ariadne**, suportando **queries e mutations**  
**gRPC** – Comunicação otimizada usando **gRPC e Protobuf**  
**Armazenamento** – Persistência dos dados em **arquivos JSON/XML**   

### **Cliente**
Desenvolvido em **Python**  
Interage com todos os serviços (**SOAP, REST, GraphQL e gRPC**)  
Demonstra a **exportação e importação de dados** entre **JSON e XML**  
Usa **requests, Zeep (SOAP), Apollo Client (GraphQL) e gRPC lib**  

