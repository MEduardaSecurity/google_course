# Curso 2 - Módulo 1  

## CISSP: Gerenciamento de Segurança e Risco  

### Definir Metas e Objetivos de Segurança  
- **Objetivo:** Reduzir riscos a ativos e dados críticos.  
- **Exemplo:** Criar políticas que limitem acesso a documentos financeiros apenas para gerentes, minimizando riscos de vazamento.  

### Mitigação de Riscos  
- **Exemplo:** Implementar autenticação multifator (MFA) para evitar acessos indevidos após uma violação.  

---

## Gerenciamento de Segurança e Risco  

### Segurança de Ativos  
- Proteção de ativos digitais e físicos, abrangendo armazenamento, manutenção, retenção e destruição de dados.  

### Arquitetura e Engenharia de Segurança  
- **Descrição:** Otimização da segurança de dados por meio de ferramentas, sistemas e processos eficazes.  

### Comunicação e Segurança de Rede  
- Gerenciamento e proteção de redes físicas e comunicações sem fio.  
- **Exemplo:** Implementar políticas contra conexões Bluetooth inseguras e Wi-Fi público.  

### Gerenciamento de Identidade e Acesso (IAM)  
- **Objetivo:** Garantir que apenas usuários autorizados acessem sistemas e dados.  
- **Exemplo:** Uso de senha e reconhecimento facial para acessar sistemas internos.  

### Avaliação e Teste de Segurança & Operações de Segurança  
- Testar e melhorar controles de segurança para mitigar riscos.  
- **Exemplo:** Simular ataques de ransomware para avaliar a eficiência do plano de resposta a incidentes.  

### Segurança de Desenvolvimento de Software  
- **Descrição:** Integração de práticas de codificação seguras no ciclo de desenvolvimento.  
- **Exemplo:** Revisar códigos para corrigir vulnerabilidades como injeções SQL antes do lançamento.  

---

# Módulo 2: Frameworks de Segurança  

### O Que São Frameworks de Segurança?  
- Diretrizes para reduzir riscos e garantir conformidade com regulamentos.  

### Exemplos de Frameworks  
- **Cyber Threat Framework (CTF):**  
  - Linguagem comum para descrever e compartilhar informações sobre ameaças.  
- **ISO/IEC 27001:**  
  - Padrão internacional para gerenciamento de segurança da informação.  

---

## Controles de Segurança  

### O Que São?  
- Medidas para prevenir, detectar ou corrigir problemas de segurança.  

### Classificação  
- **Físicos:** Portões, cercas, câmeras, cartões de acesso.  
- **Técnicos:** Firewalls, MFA, antivírus.  
- **Administrativos:** Separação de tarefas, autorizações.  

---

## Tríade da CIA  

1. **Confidencialidade:**  
   - Garantir que apenas pessoas autorizadas acessem informações.  
   - **Exemplo:** Uso de criptografia e permissões.  

2. **Integridade:**  
   - Assegurar que dados sejam precisos e não alterados sem autorização.  
   - **Exemplo:** Checagem automática para detectar alterações em relatórios financeiros.  

3. **Disponibilidade:**  
   - Manter sistemas acessíveis a usuários autorizados.  
   - **Exemplo:** Usar servidores redundantes para continuidade de serviços.  

---

## OWASP  

- **Descrição:**  
  Projeto aberto que fornece recursos para segurança de aplicações web.  

- **Princípios de Segurança:**  
  - Minimizar a superfície de ataque.  
  - Princípio do privilégio mínimo.  
  - Defesa em profundidade.  
  - Separação de funções.  
  - Simplicidade na segurança.  
  - Correção adequada de vulnerabilidades.  

---

# Módulo 3: SIEM  

## SIEM: Ferramenta Essencial  
- Coleta e análise de dados para monitoramento e detecção de ameaças.  
- Necessidade de personalização para atender às especificidades de cada organização.  

### Splunk  
- **Plataformas:** Splunk Enterprise e Splunk Nuvem.  
- **Painéis:**  
  - **Postura de Segurança:** Monitora ameaças em tempo real.  
  - **Resumo Executivo:** Visão geral da saúde organizacional.  
  - **Revisão de Incidentes:** Destaque de itens de maior risco.  
  - **Análise de Risco:** Prioriza vulnerabilidades com maior impacto.  

### Chronicle (Google)  
- **Descrição:** Plataforma nativa da nuvem que analisa registros para identificar ameaças.  
- **Painéis:**  
  - **Insights da Empresa:** Classifica alertas por gravidade.  
  - **IoC Matching:** Identifica tendências em indicadores de comprometimento.  
  - **Detecções de Regras:** Analisa alertas acionados por regras específicas.  

---

# Módulo 4: Manuais (Playbooks) em Segurança Cibernética  

## Visão Geral  
- Guia operacional para ações específicas em resposta a incidentes.  

### Características  
- **Documento Vivo:** Atualizado regularmente para refletir mudanças no setor.  
- **Razões para Atualizações:** Falhas detectadas, mudanças em regulamentos, evolução de ameaças.  

### Tipos de Manuais  
- **Resposta a Incidentes:** Foco em eventos inesperados, como violações de dados.  
- **Resposta a Vulnerabilidades:** Tratamento de fraquezas antes que se tornem incidentes.  

### Etapas Comuns  
1. Preparação.  
2. Detecção.  
3. Análise.  
4. Contenção.  
5. Erradicação.  
6. Recuperação.  
7. Pós-incidente: Relatórios e coordenação entre equipes.  

### Integração com Ferramentas SOAR  
- **Exemplo:** Bloquear automaticamente contas após tentativas de login falhas, reduzindo riscos de intrusão.  
