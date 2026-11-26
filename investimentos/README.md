# 📈 Carteira de Investimentos

Aplicação web **100% client-side** (arquivo único, sem servidor, sem cookies e pronta para GitHub Pages) desenvolvida para ajudar o investidor a **enxergar, controlar e rebalancear** sua carteira de forma simples, visual e estratégica.

---

## 💡 Qual o valor para o investidor?

Planilhas tradicionais costumam ficar pesadas, confusas e difíceis de consultar no dia a dia — especialmente quando os investimentos estão espalhados em várias corretoras e contas. Este projeto resolve isso oferecendo:

- **Visão estratégica imediata:** separa o que compõe a **Base 100%** da estratégia (Estabilidade, Diversificação, Valorização e Antifragilidade) do que fica fora dela (Corrente, Segurança, Previdência e Satélite), mostrando quanto cada bloco representa e o quão perto está da meta definida.
- **Controle multi-corretora sem fricção:** permite alternar entre a visão por **SuperPoderes** (estratégia) e **Por Local** (custódia em XP, BTG, Digital, etc.), além de filtrar rapidamente por instituição.
- **Rebalanceamento inteligente (N para N):** ajuda a responder *"se eu resgatar X ativos, quanto devo aportar em Y novos destinos?"* calculando automaticamente os valores proporcionais sobre a nova base pós-liquidação.
- **Privacidade total:** os dados nunca saem do navegador. Você importa seu CSV, analisa, simula ou edita e exporta o resultado atualizado com um clique.

---

## 🚀 Funcionalidades Principais

### 1. Importação e Exportação CSV
- Cole seu relatório separado por `;` (com ou sem cabeçalho) e carregue todos os lançamentos instantaneamente.
- Exporte a carteira atualizada em CSV padrão com um clique em **Gerar CSV** e **Copiar**.

### 2. Alocação Dinâmica e Drill-Down Interativo
- **Cards de SuperPoderes:** exibem valor total, quantidade de ativos, barra de progresso em relação ao alvo estratégico e desvio (`+` / `-` / `✓`).
- **Visão Por Local:** mostra o consolidado por instituição/corretora e o percentual sobre a carteira total.
- **Drill-Down por Cliques:** clique em qualquer card para abrir o detalhamento por **SubPoderes** e listar os ativos específicos daquele grupo.

### 3. Rebalanceamento (N para N)
- Ative o interruptor **Rebalancear** no cabeçalho para abrir o painel de simulação e execução.
- Selecione **1 ou mais lançamentos** para liquidar e adicione **1 ou mais novos destinos** (escolhendo SuperPoder, SubPoder, Local e `%` desejado).
- O sistema recalcula em tempo real a **Nova Base 100%** e o valor exato de cada novo aporte antes de aplicar as alterações na carteira.

### 4. Gestão Completa de Lançamentos
- **Formulário inteligente:** SubPoderes carregados automaticamente conforme o SuperPoder escolhido, além de autocomplete para CNPJ/ID e Nome do Ativo.
- **Tabela interativa:** ordenação por colunas, filtro por texto, edição inline e exclusão de registros.

---

## 🛠️ Como usar

1. Abra o arquivo [`index.html`](index.html) diretamente no navegador (ou publique o repositório no GitHub Pages).
2. Cole seu CSV no campo **Importar** e clique em **Abrir**, ou adicione lançamentos manualmente.
3. Explore os cards, filtre por local ou ative o modo **Rebalancear** no topo da página.
4. Ao finalizar, clique em **Gerar CSV** e **Copiar** para salvar sua carteira atualizada.
