## 🤖 Engenharia de Prompts e "Cicatrizes"

Para extrair o melhor das fontes densas (livros de Malware e Kali), utilizei uma abordagem de refinamento de prompts:

### 🔬 Testes Realizados:

1.  **Prompt de Contexto Amplo (Genérico):** * *Pergunta:* "Faça um resumo sobre cibersegurança com base nas fontes."
    * **Cicatriz:** O resultado foi muito básico. A IA ignorou os detalhes técnicos dos livros e focou em dicas comuns de internet.

2.  **Prompt de Especialista (Persona & Tabela):**
    * *Pergunta:* "Atue como um Analista de Segurança Sênior. Crie uma tabela relacionando uma vulnerabilidade OWASP, uma ferramenta do Kali e o conceito de rede envolvido."
    * **Cicatriz:** Excelente melhora. A IA conseguiu cruzar dados de três documentos diferentes (Livro de Kali, OWASP e Cartilha de Redes) para gerar uma resposta estruturada.

3.  **Prompt de Profundidade Técnica (Troubleshooting):**
    * *Pergunta:* "Com base no livro 'Practical Malware Analysis', como um malware compromete a INTEGRIDADE usando Code Injection?"
    * **Cicatriz:** A IA provou sua utilidade ao buscar um termo específico (Injeção de Código) dentro de um livro de 800 páginas, algo que um humano levaria horas para localizar manualmente.

---

## 📝 Miniguia de Estudo (Entrega Final)

### 🚀 Resumo Estruturado: Defesa em Camadas
A segurança não é um produto, mas um processo. Com base nos estudos:
* **Camada Humana:** Conscientização contra Phishing (conforme OWASP).
* **Camada de Rede:** Entender o tráfego TCP/IP para detectar anomalias (Fascículo de Redes).
* **Camada de Aplicação:** Sanetização de inputs para evitar Injeções (SQLi).

### 📖 Glossário de Conceitos Aprendidos
* **Tríade CIA:** Confidencialidade, Integridade e Disponibilidade.
* **Exploit:** Pedaço de software que aproveita uma vulnerabilidade.
* **Payload:** A parte do malware que executa a ação maliciosa (ex: criptografar arquivos).
