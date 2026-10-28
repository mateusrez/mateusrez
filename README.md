# `root@mateusrez:~# ./status.sh`

> **"A medicina ensina a lidar com sistemas biológicos complexos, mal documentados e que não aceitam *rollback*. A programação e o *self-hosting* são a minha recusa em aceitar que o mundo digital funcione da mesma forma."**

Estudante de **Medicina** com um pé na clínica e o outro no terminal. 

Fora da rotina acadêmica, dedico meu tempo a projetar **infraestrutura *self-hosted*** e desenvolver **automações** para eliminar gargalos operacionais. Acredito que dados sensíveis devem morar em servidores que você controla, e que qualquer tarefa repetitiva feita mais de duas vezes na mão é um *bug* de processo esperando por um script.

---

### 🩻 Anatomia Técnica

| Camada | Foco & Ferramentas | Diagnóstico |
| :--- | :--- | :--- |
| **🫀 Infraestrutura & Virtualização** | `Linux` · `Proxmox` · `Docker` · `LXC` · `ZFS` | Porque "a nuvem" é só o computador de outra pessoa cobrando assinatura mensal. |
| **🧠 Automação & Engenharia** | `Python` · `Bash` · `Git` · `APIs` · `Local LLMs` | Código voltado para auditoria de dados, conciliação de fluxos e extermínio de retrabalho. |
| **🛡️ Rede & Privacidade** | `Reverse Proxy` · `DNS Sinkhole` · `Zero-Trust` · `Self-Hosted Auth` | Se tem telemetria oculta ou dependência externa desnecessária, o firewall barra na porta. |
| **📊 Observabilidade** | `Grafana` · `Prometheus` · `Logs` · `Healthchecks` | Monitoramento contínuo — porque descobrir que o sistema caiu pelo usuário final é falência múltipla. |

---

### 🔥 Manifesto Crítico (Opiniões Não Solicitadas)

* **Sobre Softwares na Área da Saúde:** 90% dos sistemas clínicos parecem ter sido desenhados em 2004 por alguém que odiava tanto médicos quanto pacientes. Se um fluxo de trabalho exige copiar dados entre três telas diferentes por duas horas, isso não é "rotina administrativa" — é a falta de 60 linhas de Python.
* **Sobre o Paradoxo do Self-Hosting:** Comecei a hospedar meus próprios serviços para ter soberania digital, privacidade e controle. Resultado: hoje sou SysAdmin não remunerado de mim mesmo de madrugada. *(10/10, não voltaria para o SaaS).*
* **Sobre IA e Hype:** Inteligência artificial é brilhante quando roda localmente ou automatiza triagens de dados reais em *background*; quando vira apenas um botão brilhante embutido em um serviço pago na nuvem, é só barulho de marketing.
* **Sobre Código:** O melhor código não é o mais complexo nem o que usa o *framework* da moda — é aquele que roda silenciosamente via *cronjob* há meses sem precisar de intervenção humana.

---

### 📈 Telemetria Atual

```text
INFRAESTRUTURA (SELF-HOSTED)                 OPERADOR (MED STUDENT)
----------------------------                 ----------------------
[███████████████████░] 99.9% Uptime          [███████░░░░░░░░░░░░░] 38.0% Ritmo Circadiano
[████░░░░░░░░░░░░░░░░] 19.0% System Load     [██████████████████░░] 92.0% Cafeína Sérica
[████████████████████] Telemetria: 0%        [████████████████████] Tolerância a Bloatware: 0%
```

---

### 🔒 Por que tão poucos repositórios públicos?

Por uma questão simples de **OpSec e privacidade por design**:
1. Configurações de infraestrutura, *docker-compose* internos e rotas de rede ficam em instância privada.
2. Automações voltadas para fluxos de trabalho reais lidam com regras de negócio que não pertencem ao escopo público.

Quando construo uma ferramenta genérica o suficiente para ajudar outros a escaparem do trabalho braçal sem expor minha arquitetura interna, ela ganha um `git push` público por aqui.
<!--
**mateusrez/mateusrez** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
