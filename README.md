# STEPZero Collaborative Anki Deck 🧠

Bem-vindo ao projeto colaborativo de construção de flashcards Anki do STEPZero!  
Este repositório permite que alunos criem e proponham novos cards, que só entram no baralho principal após revisão e aprovação do mentor (inicialmente, o Lucas).

---

## 🚀 Como Participar

### 🧰 Requisitos
- Anki instalado
- Add-on **CrowdAnki** (código: `1788670778`)
- Conta no GitHub
- GitHub Desktop (opcional, mas recomendado)

---

### 🧑‍🎓 Opções de Acesso

#### ✅ Opção 1: Clone Direto (colaboradores adicionados manualmente)
1. O mentor adicionará você como colaborador do repositório.
2. Você receberá um convite por e-mail → aceite.
3. Depois, use o GitHub Desktop ou `git clone` para baixar o repositório.

#### 🌱 Opção 2: Fork (se o repositório estiver dentro de uma organização)
> Use esta opção se você **não é colaborador direto**, mas deseja submeter contribuições via *pull request*.

1. Acesse o repositório original.
2. Clique no botão **Fork** (canto superior direito).
3. Escolha criar o fork dentro da **mesma organização** (caso esteja visível).
4. Agora você terá sua **cópia do repositório**.
5. Clone sua cópia para o computador.
6. Após editar, envie um **pull request** com suas mudanças.

---

## 📝 Como Criar e Submeter Cards

### 1. Crie seu próprio deck
- No Anki: `Criar novo baralho` → Nomeie como: `Submission - [SeuNome]`
- Adicione seus cards normalmente

### 2. Exporte com CrowdAnki
- Vá em `Tools > CrowdAnki: Export Deck`
- Exporte para a pasta: `submissions/seunome_tema`  
  *(Ex: `submissions/ana_endocrino/`)*

### 3. Commit e Push
- No GitHub Desktop:
  - Escreva uma mensagem de commit: `Adicionei 10 cards de cardiologia`
  - Clique em “Commit to main” (ou branch pessoal, se for usando fork)
  - Depois, clique em “Push origin”

### 4. (Opcional) Crie um Pull Request
- Caso tenha usado fork, vá no GitHub e clique em **Create Pull Request**.

---

## 🧑‍🏫 Revisão dos Cards

O mentor revisará periodicamente os cards enviados:
- Se aprovado:
  - O conteúdo será adicionado ao baralho principal (`main_deck`)
  - Tags adicionadas: `approved_by_lucas`, `topic_[area]`
- Se precisar de ajustes:
  - Comentários serão feitos no GitHub ou no grupo da turma

---

## 🔄 Atualizar seu Baralho com as Aprovações

Quando novos cards forem aprovados:
1. Dê `git pull` para atualizar o repositório local
2. No Anki: `CrowdAnki > Import Deck` → selecione a pasta `main_deck`

---

## 🏷️ Convenção de Tags

Use tags nos seus cards para facilitar a organização:
- `submitted_by_[nome]` (ex: `submitted_by_ana`)
- `topic_cardiologia`, `topic_endocrino`
- `awaiting_approval`
- `approved`

---

## ✅ Dicas

- Submeta em pequenos lotes (5–10 cards por vez)
- Cards devem ter qualidade, clareza e contexto clínico
- Use linguagem objetiva, clara e voltada para revisão

---

## ❓ Suporte
Dúvidas? Fale com o mentor ou abra uma **Issue** aqui no GitHub.

Bons estudos e boas contribuições! 💪
