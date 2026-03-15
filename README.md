# miniguia-estudos-notebooklm

# Tema: Tipos de Malwares e como evita-los.

# Objetivo: 
Conseguir compreender como funciona os Malwares, a forma como infecta os dispositivos eletrônicos e de como é possivel se proteger de tais ameaças.

# Links utilizados no NotebookLM:
- https://www.avast.com/pt-br/c-malware
- https://pt.wikipedia.org/wiki/Malware
- https://www.malwarebytes.com/pt/malware
- https://www.techtudo.com.br/listas/2021/03/o-que-e-malware-veja-significado-tipos-e-saiba-remover.ghtml
- https://nsfocusglobal.com/pt-br/o-que-e-malware/

# Primeira tentativa de prompt:

# Prompt utilizado:
"Explique o que é um malware."

# Resposta obtida: 
O NotebookLM trouxe uma explicação geral sobre o que é um malware, mecionando os tipos que se encontra, a forma de infecção e sinais de alerta junto a formas de se prevenir.

# Problema identificado:
- Respota extensa demais, apresentando os conceitos de forma generica.
- Sem aprofudamento no assunto.

# Cicatriz identificada:
O prompt aplicado foi muito simples, o que fez o resultado ser uma resposta superficial.

# Segunda tentativa de prompt:

# Prompt utilizado: 
"Organize a explicação sobre o que é malware em tópicos, separando a definição, formas de infecção e principais exemplos."

# Resposta obtida: 
O NotebookLM trouxe uma explicação bem mais organizada e coerente. Sendo assim, possuindo uma estrutura melhor para estudo e informações mais claras.

# Conclusão do processo:
Foi possível observar que a qualidade da resposta apresentada pelo NotebookLM depende diretamente da clarez e especificidade do prompt utilizado.

# Troubleshooting (Dificuldade Encontradas):
Durante a interação com o NotebookLM foram identificadas algumas dificuldades no processo, como:

Excesso de Infomação: Algumas respostas eram muito longas, dificultando a transformação em material de estudo. A solução, foi organizar o assunto em tópicos.

Respostas muito genéricas e mal estruturadas: Por utilizar de um prompt superficial, ocorreu que a resposta dada foi bem generica, além de algumas respostas vieram em blocos grandes de texto. Para poder corrigir isso, foi feito uma especificação melhor da pergunta e uma organização do texto em tópicos.

# Miniguia de Estudo - O que é Malware

1. O que é Malware?
**Malware** é uma abreviação de **"malicious software"** (software malicioso). Refere-se a qualquer programa ou código de computador projetado intencionalmente para causar **danos**, interrupções em sistemas, roubo de informações privadas ou obtenção de **acesso não autorizado** a redes e dispositivos. 

É importante distinguir que, tecnicamente, **vírus e malware não são a mesma coisa**: "malware" é o termo genérico que engloba todas as ameaças, enquanto o "vírus" é apenas um tipo específico de malware capaz de se replicar.

---

# 2. Principais Tipos de Malware
Os malwares são classificados de acordo com seu comportamento e objetivo:

*   **Vírus:** Programa que se anexa a arquivos ou softwares legítimos e precisa da **ação do usuário** (como executar um arquivo) para se propagar.
*   **Worms (Vermes):** Diferente dos vírus, são autônomos e se espalham sozinhos por redes explorando vulnerabilidades, sem precisar de um programa hospedeiro ou intervenção humana.
*   **Cavalos de Tróia (Trojans):** Disfarçam-se de programas úteis ou legítimos para enganar o usuário e, uma vez instalados, podem roubar dados ou abrir "portas" (backdoors) para outras invasões.
*   **Ransomware:** Um dos tipos mais perigosos, ele **criptografa os arquivos** da vítima e exige o **pagamento de um resgate** para devolver o acesso.
*   **Spyware:** Software espião projetado para monitorar secretamente as atividades do usuário e coletar dados sensíveis como senhas e informações bancárias.
*   **Adware:** Focado em exibir **anúncios indesejados** e invasivos, geralmente para gerar receita publicitária para os criminosos.
*   **Rootkits:** Conjunto de ferramentas que permite ao invasor manter privilégios de administrador enquanto **esconde sua presença** do sistema operacional e de softwares de segurança.
*   **Botnets:** Redes de computadores infectados (chamados de "zumbis") que são controlados remotamente para realizar ataques de larga escala, como o envio de spam ou ataques DDoS.

---

# 3. Formas de Infecção
O malware utiliza diversos vetores para penetrar nos sistemas:

*   **E-mail:** É o principal método de entrega (cerca de **96% das infecções** mundiais), ocorrendo através de anexos maliciosos ou links de **phishing**.
*   **Internet e Navegação:** Visitar sites pirateados, clicar em anúncios infectados (*malvertising*) ou sofrer downloads automáticos (*drive-by downloads*) ao acessar páginas inseguras.
*   **Dispositivos Removíveis:** Uso de **pen drives** infectados que podem carregar o código malicioso no hardware interno ou em arquivos autoexecutáveis.
*   **Vulnerabilidades de Software:** Exploração de falhas (bugs) em sistemas operacionais ou aplicativos desatualizados para contornar defesas.
*   **Engenharia Social:** Táticas psicológicas para enganar o usuário e levá-lo a clicar em links suspeitos em redes sociais, mensagens de texto (SMS) ou mensageiros.

---

# 4. Como Identificar uma Infecção (Sinais de Alerta)
Alguns sintomas comuns de que um dispositivo pode estar infectado incluem:
*   **Lentidão extrema** e travamentos frequentes.
*   Aparecimento de **pop-ups** e anúncios indesejados.
*   Redução súbita do espaço de armazenamento ou desaparecimento de arquivos.
*   Alterações nas configurações do navegador (nova página inicial ou barras de ferramentas estranhas).
*   Aumento no consumo de bateria e de dados móveis (especialmente em celulares).

---

# 5. Ações para Evitar e Prevenir Problemas
A prevenção é baseada em uma combinação de tecnologia e comportamento seguro:

*   **Instale um Antivírus/Antimalware:** Utilize soluções confiáveis que ofereçam **proteção em tempo real** e realize varreduras regulares.
*   **Mantenha Tudo Atualizado:** Sempre instale as atualizações de segurança e correções (*patches*) do sistema operacional, navegadores e aplicativos para fechar vulnerabilidades.
*   **Use Senhas Fortes e 2FA:** Crie senhas complexas e habilite a **autenticação de dois fatores** (2FA) para proteger o acesso às contas.
*   **Cuidado com Links e Anexos:** Nunca clique em links ou baixe anexos de e-mails, SMS ou mensagens de redes sociais de remetentes desconhecidos ou suspeitos.
*   **Realize Backups Regulares:** Mantenha cópias de segurança dos seus arquivos importantes em locais seguros (como na nuvem ou HDs externos desconectados) para mitigar o impacto de um possível ataque de ransomware.
*   **Baixe apenas de Fontes Oficiais:** Utilize apenas lojas oficiais (como Google Play e App Store) e evite baixar softwares de sites piratas ou redes P2P.

# Glossário de Conceitos

Malware:
Software malicioso desenvolvido para prejudicar sistemas ou roubar informações.

Vírus:
Programa que infecta arquivos e se replica quando executado.

Worm:
Malware que se espalha automaticamente através de redes.

Trojan:
Programa malicioso disfarçado de software legítimo.

Ransomware:
Malware que bloqueia sistemas ou arquivos e exige pagamento para liberá-los.

Spyware:
Software que coleta informações do usuário sem autorização.

Engenharia Social:
Técnicas utilizadas para manipular pessoas e levá-las a executar ações que comprometem a segurança.

# Conjunto de Prompts Reutilizáveis

Esses prompts podem ser reutilizados para futuras revisões sobre o tema.

Prompt para explicação básica:
"Explique de forma simples o que é malware e quais são os principais tipos."

Prompt para estudo detalhado:
"Explique detalhadamente os principais tipos de malware, incluindo vírus, worm, trojan, ransomware e spyware."

Prompt para resumo:
"Crie um resumo estruturado sobre malware voltado para estudantes iniciantes em segurança da informação."

Prompt para revisão de conteúdo:
"Crie perguntas de revisão sobre os tipos de malware para ajudar no estudo de segurança digital."
