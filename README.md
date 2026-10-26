# Pharos Doc-Grounded Builder Agent

Um agente inteligente desenvolvido em **Java** para a Pharos Agent Arena que responde a pedidos do tipo "como faço X no Pharos" consultando a documentação oficial (Docs MCP), planeando com fontes citadas, executando via Chain MCP e verificando o resultado on-chain.

## 📋 Requisitos Cumpridos

1. **Planeamento Baseado em Docs (Req. 01):** Consulta a Docs MCP para formular um plano com fontes citadas antes de agir.
2. **Execução e Assinatura (Req. 02):** Executa o plano e prepara transações que movimentam fundos para assinatura.
3. **Verificação On-Chain (Req. 03):** Verifica o resultado on-chain e reporta o sucesso em conformidade com o plano.
4. **Múltiplos Pedidos (Req. 04):** Funciona para pelo menos 3 solicitações distintas do tipo "como faço...".
5. **Tratamento de Lacunas (Req. 05):** Rejeita pedidos não cobertos pela documentação de forma transparente, recusando-se a improvisar.

## 🚀 Como Executar

1. Certifique-se de ter o **Java JDK** instalado.
2. Compile o ficheiro:
   ```bash
   javac DocGroundedBuilderAgent.java
