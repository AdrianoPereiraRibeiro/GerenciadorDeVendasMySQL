# Sistema de Vendas em Java

Este projeto implementa um sistema simples de vendas desktop em Java. Ele permite cadastrar produtos e realizar vendas.

![Captura de tela 2025-07-02 000051](https://github.com/user-attachments/assets/d16e6d80-9846-4198-b9bb-5f9aee4407b7)
![Captura de tela 2025-07-01 230048](https://github.com/user-attachments/assets/1f3cb45e-f53a-436b-93b0-88a5b3a43955)
![Captura de tela 2025-07-02 000112](https://github.com/user-attachments/assets/db8319b5-9db0-40c6-9a4e-eeb8364f0f20)
![Captura de tela 2025-07-02 000109](https://github.com/user-attachments/assets/35fd2589-399b-43dd-99e7-6a45004f45e2)
![Captura de tela 2025-07-02 000104](https://github.com/user-attachments/assets/365e6303-d744-439e-a9b5-e1d4eed0cf0a)
![Captura de tela 2025-07-02 000101](https://github.com/user-attachments/assets/0ca1c753-d304-4d08-9a9d-23de0ccbdda3)

## 🔧 Requisitos

- Java JDK 11 ou superior
- Um editor de código (recomendado: VSCode ou NetBeans)

## ▶️ Como Executar

1. Compile os arquivos Java e depois execute:
javac src/*.java
java -cp src Main

 
---

### 📄 relatorio.txt (Relatório Explicativo)


RELATÓRIO EXPLICATIVO – SISTEMA DE VENDAS

1. CENÁRIO ESCOLHIDO
O sistema desenvolvido representa uma loja fictícia onde é possível cadastrar produtos e realizar vendas.

2. DESCRIÇÃO FUNCIONAL
O sistema funciona via terminal (modo texto). Ao executar o programa, o usuário tem acesso a um menu com as seguintes opções:

- Cadastrar produto (nome, preço)
- Cadastrar venda ()
- Mostrar Itens (seleciona cliente e produtos)
- Sair

Todos os dados são armazenados em banco de dados (há persistência em MySQL).

3. JUSTIFICATIVA DAS ESCOLHAS

- **Armazenamento em memória** foi adotado para simplificar a lógica e manter o foco no fluxo de vendas.
- A separação de responsabilidades em classes (`Produto`, `Venda`, `GerenciadorVendas`) garante organização e facilita futuras melhorias.
- Esse programa foi escolhido por ser algo utíl e relativamente simples de visualizar em uma situação real.

Este sistema tem foco didático, ideal para introduzir conceitos de orientação a objetos,lógica de programação e programação desktop.

