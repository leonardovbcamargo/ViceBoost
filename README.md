# ⚡ ViceBoost — Otimização Remota & Consultoria de PC Gamer

> **Seu PC no talo para Vice City — sem gastar milhares em peças novas à toa.**

Aplicação web (MVP) desenvolvida como desafio prático de validação de negócio e construção de produto digital com IA como co-founder.

- **Aplicação publicada:** [COLE AQUI O LINK DA SUA APLICAÇÃO NO LOVABLE, ex: https://viceboost.lovable.app]
- **Status:** MVP no ar e validado com fluxo completo (Captação → WhatsApp → Painel Admin)

---

## 1. A Dor Escolhida e Por Que Vale um Negócio

Com a chegada de jogos cada vez mais exigentes (como **GTA VI** e atualizações competitivas do **Fortnite**), milhões de jogadores de PC com configurações de entrada ou intermediárias enfrentam quedas bruscas de FPS, *stuttering* e insegurança sobre se suas máquinas vão rodar os lançamentos.

Hoje, quem enfrenta esse problema cai em dois extremos:
1. Gasta milhares de reais comprando peças novas sem saber onde está o real gargalo do PC;
2. Assiste a dezenas de tutoriais genéricos na internet que muitas vezes desconfiguram o Windows ou não resolvem o problema específico do seu hardware.

O **ViceBoost** resolve essa dor oferecendo um diagnóstico técnico real do setup do jogador, otimização remota individualizada (via AnyDesk/Discord) e consultoria direta de upgrade sob medida — com ticket acessível e atendimento consultivo.

---

## 2. Tamanho de Mercado (TAM, SAM e SOM)

| Métrica | Definição no Projeto | Estimativa |
| :--- | :--- | :--- |
| **TAM** *(Mercado Total)* | Gamers de PC no Brasil (~45 milhões de jogadores, segundo levantamentos do setor como Pesquisa Game Brasil), considerando ticket médio anual de R$ 150 em serviços técnicos. | **~R$ 6,7 bilhões / ano** |
| **SAM** *(Mercado Endereçável)* | Jogadores brasileiros com PCs de entrada ou intermediários (GPUs série GTX 16, RTX 20/30, RX 6600) focados em títulos pesados/competitivos (~15% a 20% da base). | **~R$ 1 bilhão / ano** |
| **SOM** *(Mercado Obtível Inicial)* | Jogadores ativos em comunidades de Discord, grupos de hardware e páginas focadas em preparar o PC para *GTA VI* nos primeiros 6 meses (meta inicial de 100 a 150 clientes com ticket médio de R$ 79,90). | **R$ 8.000 a R$ 12.000** |

---

## 3. Business Model Canvas

| Bloco | Estratégia do ViceBoost |
| :--- | :--- |
| **Segmentos de Clientes** | Jogadores de PC (16 a 35 anos) com setups de entrada/intermediários que querem extrair o máximo de FPS no *GTA VI* e *Fortnite* sem desperdício de dinheiro. |
| **Proposta de Valor** | Diagnosticar gargalos reais e otimizar remotamente o Windows, drivers e configurações gráficas para ganhar FPS e estabilidade — ou indicar o upgrade exato que cabe no bolso. |
| **Canais** | Landing Page ViceBoost, servidores de Discord de GTA/hardware, grupos de PC Gamer e fechamento direto via WhatsApp. |
| **Relacionamento** | Atendimento consultivo 1:1 via WhatsApp + sessão remota acompanhada + lembretes pós-patch. |
| **Fontes de Receita** | **Consultoria de Upgrade** (R$ 59,90), **Otimização Remota FPS** (R$ 79,90) e **Combo Completo + Revisão Pós-Patch** (R$ 119,90). |
| **Recursos Principais** | Plataforma web (Lovable + Lovable Cloud), checklist técnico de otimização e ferramentas de diagnóstico (AnyDesk, MSI Afterburner, HWiNFO). |
| **Atividades-Chave** | Captar setups pelo formulário, alinhar e fechar no WhatsApp, executar o boost remoto e gerenciar entregas/lembretes no painel. |
| **Parcerias Principais** | Criadores de conteúdo de hardware/GTA e programas de afiliados de lojas de informática (para recomendação de peças). |
| **Estrutura de Custos** | Enxuta (*lean*): hospedagem/cloud da aplicação, ferramentas gratuitas de diagnóstico e horas técnicas de execução. |

---

## 4. Tese do MVP e O Que Ficou Manual de Propósito

### Tese Validada pelo MVP
> *"Jogadores de PC preocupados em rodar GTA VI e jogos competitivos aceitam pagar entre R$ 59,90 e R$ 119,90 por um diagnóstico personalizado e otimização remota antes de gastar dinheiro comprando hardware novo, desde que o processo seja simples e o atendimento passe confiança."*

### O Que Ficou Manual de Propósito (Lean Startup)
Para validar a demanda real antes de construir automações complexas, estas etapas foram mantidas manuais na primeira versão:
- **Pagamento:** Sem gateway integrado (Stripe/Mercado Pago); o link Pix ou cartão é enviado manualmente no WhatsApp após validar a viabilidade do setup do cliente.
- **Execução Técnica:** A otimização é conduzida ao vivo via acesso remoto (AnyDesk/Discord) seguindo checklist técnico, sem desenvolvimento de software instalável (`.exe`).
- **Disparo de Lembretes:** O painel administrativo organiza as datas de revisão pós-patch e lembretes, mas o envio da mensagem é disparado manualmente com 1 clique pelo botão do WhatsApp.

---

## 5. Telas da Aplicação

### Landing Page — Proposta de Valor (Hero Section)
<img width="1294" height="611" alt="image" src="https://github.com/user-attachments/assets/2c6318ab-650c-4878-bd1c-22c96866fec0" />

### Como Funciona (Fluxo em 3 Passos)
<img width="1298" height="469" alt="image" src="https://github.com/user-attachments/assets/87d5be13-9ff3-4dce-9345-fdd993261d9b" />

### Planos e Pacotes Disponíveis
<img width="1293" height="604" alt="image" src="https://github.com/user-attachments/assets/1bf958f6-5bdc-42bc-8596-5521da084173" />

### Formulário Interativo "Monte Seu Plano"
<img width="1298" height="603" alt="image" src="https://github.com/user-attachments/assets/e8a61b89-3d65-4246-9f09-c6a06afd9e28" />

<!-- Se tirar print do painel administrativo, basta descomentar a linha abaixo e salvar a imagem em docs/05-painel-admin.png:
### Painel Administrativo (`/admin`)
![Painel Administrativo ViceBoost](docs/05-painel-admin.png)
-->

---

## 6. Engenharia de Prompt: Mega Prompt e Iterações

O projeto foi estruturado em parceria com IA (atuando como co-founder) antes da geração de código no **Lovable**, evitando desperdício de créditos e garantindo cobertura completa do fluxo de negócio.

<details>
<summary><strong>Clique para expandir o Mega Prompt utilizado no Lovable</strong></summary>

```markdown
# Projeto: ViceBoost — Otimização Remota & Consultoria de PC Gamer para GTA VI e Fortnite

Crie uma aplicação web completa em Português (PT-BR) chamada **ViceBoost**, focada em otimização remota de desempenho (FPS/estabilidade) e consultoria de upgrade de PC Gamer para rodar jogos pesados como **GTA VI** e **Fortnite**.

Use o **Lovable Cloud** para persistência de dados e autenticação do painel administrativo (sem necessidade de configurar banco de dados externo manual).

---

## 1. Identidade Visual e Design System (Vice City Dark Mode)
- **Tema:** Dark Mode Gamer inspirado na estética neon de Vice City / GTA VI, moderno, limpo e focado em alta conversão.
- **Paleta de Cores:**
  - Fundo principal: `#0B0B12`
  - Cards e superfícies elevadas: `#141422` com bordas sutis `#26263D`
  - Cor primária (Destaque / CTAs): Neon Magenta `#FF2E93` (hover `#E01E7D`)
  - Cor secundária (Detalhes técnicos / Badges): Ciano Elétrico `#00E5FF`
  - Texto principal: `#F8FAFC`
  - Texto secundário: `#94A3B8`
  - Status: Verde `#10B981` (Concluído/Pago), Amarelo `#F59E0B` (Pendente/Em andamento), Vermelho `#EF4444` (Urgente/Atrasado).
- **Elementos Visuais:** Não gere imagens pesadas por IA. Use ícones modernos (`lucide-react`), efeitos de brilho neon sutil (glow), gradientes entre `#FF2E93` e `#00E5FF` e badges com visual de telemetria gamer.

---

## 2. Fluxo do Cliente (Página Pública `/` — Landing Page + Formulário Interativo)

### A. Cabeçalho (Navbar)
- Logo textual **ViceBoost** com ícone de raio/velocímetro e gradiente neon.
- Links de navegação rápida: *Como Funciona*, *Pacotes*, *Montar Plano* e um link discreto no rodapé/topo para *Área Admin* (`/admin`).

### B. Hero Section (Dobra Principal)
- Badge superior: `"PRONTO PARA GTA VI & FORTNITE COMPETITIVO"`
- Headline de impacto: **"Seu PC no talo para Vice City — sem gastar milhares em peças novas à toa."**
- Subheadline: *"Diagnóstico real de gargalos, otimização remota de Windows/drivers e consultoria sob medida para extrair o máximo de FPS da sua máquina."*
- CTA Principal: Botão neon **"Montar Meu Plano Agora"** (rola suavemente até o formulário).
- Prova social / Métricas visuais em cards compactos: `+35% de estabilidade em FPS`, `100% Remoto via AnyDesk`, `Atendimento Individual`.

### C. Seção "Como Funciona" (3 Passos Simples)
1. **Envie seu Setup:** Preencha sua CPU, GPU, RAM e o objetivo no formulário abaixo.
2. **Alinhamento no WhatsApp:** Receba a pré-análise, tire dúvidas e confirme o agendamento.
3. **Boost Remoto & Relatório:** Acompanhe a otimização ao vivo ou receba seu guia exato de upgrade.

### D. Seção de Pacotes (Referência de Preços)
Exiba 3 cards claros (que também podem pré-selecionar o pacote no formulário ao clicar):
1. **Consultoria de Upgrade Sob Medida — R$ 59,90** (Ideal para saber exatamente qual peça trocar sem gargalo e sem desperdiçar dinheiro).
2. **Otimização Remota FPS Boost — R$ 79,90** *(Mais Escolhido)* (Ajuste completo de Windows, drivers, plano de energia, BIOS/painel NVIDIA/AMD e configuração gráfica do jogo).
3. **Combo Completo + Revisão Pós-Patch — R$ 119,90** (Otimização remota completa + análise de upgrade + 1 retorno gratuito após grandes atualizações do jogo).

### E. Formulário Interativo "Monte Seu Plano"
Campos obrigatórios com validação amigável:
- **Nome / Nickname** (texto)
- **WhatsApp com DDD** (máscara `(99) 99999-9999`)
- **Processador (CPU)** (texto, ex: *Ryzen 5 5600 / Core i5-12400F*)
- **Placa de Vídeo (GPU)** (texto, ex: *RTX 3060 12GB / GTX 1650*)
- **Memória RAM** (select: `8GB`, `16GB`, `32GB`, `64GB+`)
- **Jogo Foco** (select: `GTA VI (Preparação/Performance)`, `Fortnite (FPS Competitivo)`, `Ambos`)
- **Pacote Escolhido** (cards clicáveis ou select: `Consultoria Upgrade (R$ 59,90)`, `Otimização Remota FPS (R$ 79,90)`, `Combo Completo + Revisão (R$ 119,90)`)
- **Observação / Problema Principal** (textarea opcional, ex: *"Queda de FPS em trocação ou dúvida se preciso trocar a placa"*)

**Ação ao Enviar o Formulário:**
1. Salva o registro automaticamente no banco de dados (tabela `leads` com status inicial `"Novo Lead"` e data de criação).
2. Exibe uma tela/modal de confirmação com resumo do pedido e um botão de destaque verde/neon **"Finalizar no WhatsApp Agora"**.
3. O link do WhatsApp (`https://wa.me/5511999999999?text=...` — deixe o número facilmente configurável no código/painel) deve abrir com uma mensagem pré-preenchida contendo todos os dados do formulário (Nome, CPU, GPU, RAM, Jogo Foco e Pacote escolhido).

---

## 3. Painel Administrativo (`/admin`) com Autenticação

Crie uma área administrativa protegida por login (e-mail e senha via Lovable Cloud Auth) com layout lateral (Sidebar) e visão geral limpa:

### A. Dashboard / Métricas no Topo
- Total de Leads captados
- Clientes Ativos / Convertidos
- Serviços Pendentes de Entrega
- Faturamento Estimado (soma dos pacotes fechados)

### B. Aba 1: Leads (Funil de Vendas)
- Tabela/Cards com todos os formulários recebidos ordenados do mais recente para o mais antigo.
- Exibe: Data, Nome, WhatsApp, Setup completo (CPU + GPU + RAM), Jogo Foco, Pacote, Status (`Novo Lead`, `Em Conversa`, `Fechado`, `Perdido`).
- **Ações rápidas em cada lead:**
  - Botão **Abrir WhatsApp** (já abre conversa com o cliente).
  - Botão **Converter em Cliente** (com 1 clique, cria um registro na tabela `clientes` copiando os dados do lead e muda o status do lead para `Fechado`, sem precisar redigitar).
  - Alterar status ou excluir lead.

### C. Aba 2: Clientes
- Lista de clientes que fecharam pacote.
- Exibe: Nome, WhatsApp, Setup (CPU/GPU/RAM), Pacote contratado, Valor pago, Data de fechamento e campo de **Anotações Técnicas** (para registrar o FPS antes/depois ou peças recomendadas).
- Permite adicionar um cliente manualmente caso feche direto pelo WhatsApp.

### D. Aba 3: Entregas & Sessões Remotas
- Controle operacional dos serviços contratados com status: `Aguardando Agendamento`, `Agendado`, `Em Execução`, `Concluído`.
- Campos para data/hora agendada da sessão remota (AnyDesk/Discord) e checklist rápido de entrega (ex: *Drivers atualizados, Windows otimizado, Config do jogo aplicada, Relatório enviado*).

### E. Aba 4: Lembretes & Pós-Venda
- Sistema de lembretes para reengajar clientes (ex: *"Revisão pós-patch GTA VI"*, *"Verificar chegada da nova GPU"*, *"Manutenção trimestral de FPS"*).
- Permite criar lembrete vinculado a um cliente com **Data do Lembrete**, **Motivo** e **Status** (`Pendente` / `Enviado`).
- Destaque visual para lembretes vencidos ou para hoje, com botão **Enviar Lembrete via WhatsApp** (abre o WhatsApp do cliente com mensagem personalizada de follow-up).

---

## 4. Requisitos Técnicos
- Totalmente responsivo (Mobile-first para quem acessa pelo link no Discord/Instagram/WhatsApp e Desktop completo para o painel `/admin`).
- Interface 100% em Português do Brasil, com formatação de moeda (`R$`) e datas (`DD/MM/AAAA`).
- Seed/dados de exemplo iniciais apenas se necessário para visualização, ou banco limpo pronto para uso real com criação de conta admin na primeira visita.
