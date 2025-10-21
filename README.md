Formulário de Cadastro de Clientes em Java Swing
📝 Descrição do Projeto
Este projeto consiste na implementação de um formulário de cadastro de clientes utilizando Java Swing, atendendo aos requisitos de interface gráfica e lógica de validação. A interface replica o layout de "Cadastrar Clientes" fornecido na especificação.

🛠️ Instruções de Execução
O código está estruturado para rodar em qualquer ambiente Java Desktop com suporte a GUI (como NetBeans, Eclipse ou IDEs com JDK).

Ambiente (Codespaces / Terminal)
Para compilar e executar no terminal (incluindo o GitHub Codespaces):

Compilação: O comando a seguir compila o código e gera o arquivo .class na estrutura de pacotes correta (dentro do diretório src).

Bash

javac src/FormularioCadastro.java -d .
Execução:

Bash

java src.FormularioCadastro
⚠️ NOTA IMPORTANTE: HeadlessException no Codespaces
O ambiente do GitHub Codespaces não possui um servidor de exibição gráfica (X11 DISPLAY) configurado por padrão.

A execução do comando java src.FormularioCadastro resultará no erro java.awt.HeadlessException. Este erro é esperado e não indica um problema no código-fonte. O código está funcional, conforme testado em ambiente local (NetBeans), e cumpre todos os requisitos do projeto.
