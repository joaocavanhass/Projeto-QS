```markdown
# Relatório de Decisão de Qualidade

## 🚦 Decisão Final: LIBERAR

## 📋 Critérios Utilizados
1. **Cobertura de Testes:** Superior a 80% verificado via JaCoCo.
2. **Quality Gate:** Aprovado no SonarCloud com zero bugs críticos.
3. **Desempenho:** Teste de carga com 0% de falhas e tempo de resposta aceitável.
4. **Clone Limpo:** Execução automatizada sem pendências locais.

## ⚠️ Riscos Aceitos
* **Risco:** Ausência de cache em memória para requisições de pico extremo.
  * **Impacto:** Baixo.
  * **Justificativa:** O volume de usuários esperado na Release 1.0 está coberto pelas métricas de carga atuais.
  * **Responsável:** João Pedro Cavanhas Colombo

## 👥 Contribuição dos Integrantes
* **João Pedro Cavanhas Colombo:** Configuração da automação de testes, infraestrutura do pipeline e elaboração do pacote de evidências.
* **Nicolas Thomaz:** Implementação dos diagramas de arquitetura, documentação da API e suíte de testes de integração.