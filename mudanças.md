# Adriana Maia Studio — Plano de Alterações da Landing Page

> Base de instruções para o code aplicar. Origem: respostas reais da Adriana no briefing (`perguntas-adriana-maia.docx`), comparadas com a implementação atual (`index.html`, `style.css`, `script.js`).

## Legenda de status
- ✅ **Pronto** — conteúdo definido, pode implementar agora
- ⏳ **Aguardando material** — depende de arquivo/info que a cliente ainda vai enviar
- ❓ **Decisão pendente** — precisa de uma resposta antes de mexer

---

## 1. HERO

### ✅ 1.1 Trocar o headline principal
**Arquivo:** `index.html` → `.hero__headline`

- **De:** `Seu olhar<br/>merece<br/>o melhor.`
- **Para:** `Seu olhar<br/>em destaque.`

> ✅ **Resolvido:** ela escreveu em caixa alta só por hábito de digitação, não era intencional. Manter a estilização atual do hero (display itálico, caixa baixa).

### ✅ 1.2 Subtítulo — manter
`+1.000 mulheres com olhares transformados` está aprovado, **sem alterações**. Nada a adicionar.

### ⏳ 1.3 Trocar a foto do hero
**Arquivo:** `index.html` → `.hero__photo` (`src="images/AdrianaHero.png"`)

A Adriana **não** quer a foto atual (blazer branco) — vai mandar outra. Quando chegar, substituir o arquivo mantendo o mesmo nome ou atualizar o `src` + o `<link rel="preload">` no `<head>`.

---

## 2. SERVIÇOS

**Arquivo:** `index.html` → seção `#servicos`, cards `.service-card`

A lista oficial da Adriana (marcada como "OK") difere da atual. Atualizar os 5 cards:

### ✅ Card 1 — Sobrancelhas
Lista nova:
- Design Personalizado
- Nanopigmentação
- Brow Lamination
- Natural Browns
- Henna / Tinturas
- Protocolo de Regeneração de Sobrancelhas

> **Atenção:** "Flow Brows" sai da lista de serviços (não consta na lista atualizada dela). Mas "Flow Brows" ainda aparece nas legendas da galeria — ver item 4.2 antes de remover globalmente.

### ✅ Card 2 — Olhos
Lista nova:
- Lash Lifting

> Remover "Fios Wild" (não está na lista atualizada).

### ✅ Card 3 — Lábios
Lista nova:
- Revitalização Labial
- Henna Labial

### ✅ Card 4 — Cabelos
- Protocolo de Regeneração Capilar e Barba

> Sugestão: ajustar o título do card de "Regeneração Capilar" para "Regeneração Capilar & Barba".

### ✅ Card 5 — Formação / Cursos
Conteúdo novo (Curso VIP — atendimento individual "para melhor aproveitamento e aprendizado do aluno"):
- Design de Sobrancelhas
- Lash Lifting de Cílios
- Brow Lamination

> **Decisão (❓):** manter como card simples OU criar uma seção dedicada "Cursos" com a descrição do formato VIP e CTA próprio de inscrição via WhatsApp? Recomendo manter no card por enquanto e evoluir depois.

### ✅ 2.2 Preços
**Sem mudança** — só botão de WhatsApp para consulta (já é o comportamento atual). Não adicionar preços.

---

## 3. SOBRE MIM

### ✅ 3.1 Reescrever o texto + conquistas
**Arquivo:** `index.html` → seção `#sobre`, `.about__content` (parágrafos + `.about__achievements`)

**Copy sugerida para aprovação da Adriana:**

> Parágrafo 1:
> "Sou Adriana Maia, especialista em sobrancelhas e realce do olhar. Há quase 10 anos atuo na área da beleza em Joinville/SC, dedicada a revelar a beleza autêntica de cada mulher — com técnica, intenção e muito cuidado."

> Parágrafo 2:
> "Minha formação reúne escolas renomadas como Natália Beauty, Lovena Maison, Academi e Ana Freitas, entre outras. Fui nomeada Especialista em Sobrancelhas pela ANAQ — Prêmio de Qualidade Brasil, com reconhecimento de Excelência no Segmento e o Selo Diamante de Qualidade."

**Lista de conquistas (`.about__achievements`) atualizada:**
- Quase **10 anos** de atuação na área da beleza
- Nomeada **Especialista em Sobrancelhas** pela ANAQ — Prêmio de Qualidade Brasil (Selo Diamante de Qualidade)
- Indicada **duas vezes** ao Prêmio Mulheres Empreendedoras
- **Artista Destaque** no segmento de sobrancelhas em SC, PR e RS — Embaixadora Ouro da edição
- **Capa da Revista Sucesso**, contando sua trajetória como empreendedora
- Mais de **1.000 clientes** atendidas

### ❓ 3.1b Link da Revista Sucesso
A Adriana perdeu o link e pediu pra pegar no Instagram dela (@adrianamaiastudio). **Tarefa do Gui:** recuperar o link e decidir se vira um link clicável no item "Capa da Revista Sucesso". (Posso tentar ajudar a localizar se quiser.)

### ⏳ 3.2 Trocar a foto da seção Sobre
**Arquivo:** `index.html` → `.about__photo` (`src="images/AdrianaFoto2.png"`)

A Adriana **não** quer a foto atual (cerejeiras) — vai mandar outra. Substituir quando chegar.

### ✅ 3.3 / Credenciais
**Arquivo:** `index.html` → seção `.credentials`

A info do prêmio foi respondida no item 3. Sugestão opcional: enriquecer os 3 blocos de credenciais para refletir as premiações novas (ex.: trocar o bloco "Premiada em Excelência" por "Selo Diamante de Qualidade — ANAQ"). **Decisão da Adriana.**

---

## 4. GALERIA

**Arquivo:** `index.html` → seção `#galeria`, `.gallery-item`

### ⏳ 4.1 Adicionar e trocar fotos
A Adriana quer **adicionar mais** e **trocar algumas** das 5 fotos atuais. Vai enviar o material novo.

### ⏳ 4.2 Revisar legendas
As legendas (`Design Personalizado`, `Lash Lifting`, `Flow Brows`, `Brow Lamination`...) precisam ser conferidas foto a foto. A Adriana perdeu o link de visualização e vai ajustar depois de ver. **Não remover/alterar legendas até ela revisar.**

---

## 5. DEPOIMENTOS

**Arquivo:** `index.html` → seção `.testimonials`, `.testimonial-card`

### ✅ 5.1 Substituir depoimentos de exemplo por reais
Avaliações reais extraídas do perfil do Google (Adriana Maia Studio — Especialista em Sobrancelhas). Substituir os 4 cards fictícios por estes (todos ⭐⭐⭐⭐⭐). Atribuir por primeiro nome + "Avaliação no Google":

**1. Nicoli N.**
> "Faço minha sobrancelha com a Adri há mais de 9 anos e não troco ela por nada. Detalhista e extremamente cuidadosa com cada fio. Fiz a nanopigmentação e ficou perfeita, bem natural do jeito que eu amo."

**2. Luana N.**
> "Faço sobrancelha com a Adriana há quase 10 anos e falo com convicção que é a melhor! Ela é muito detalhista e sempre preza pela naturalidade, o que é indiscutível para mim!"

**3. Patrícia C.**
> "Excelente profissional. Tem um verdadeiro talento para realçar a beleza natural! Seu espaço é super aconchegante, com produtos de alta qualidade. Seu conhecimento e atenção em cada detalhe me transmitem confiança."

**4. Letícia O.**
> "Atendimento humanizado e de excelência, espaço incrível e bem organizado. Com certeza é o melhor design de Joinville."

**5. Luís E.**
> "Maravilhosa, ótima profissional. Foi um sucesso, amei o resultado! Você está de parabéns."

**6. Graziela C.**
> "Adriana Maia é uma excelente profissional. Fiz o processo de regeneração das minhas sobrancelhas com ela e fiquei extremamente satisfeita com o resultado. Minhas sobrancelhas estavam falhadas, com áreas onde já não havia mais pelos..."
> ⚠️ *Texto cortado no print ("...Mais"). Gui pegar a versão completa no Google antes de publicar, ou usar apenas a parte visível.*

**Reservas (depoimentos curtos, caso queira mais):**
- Deise B. — "Sobrancelha perfeita"
- Luiza P. — "O lugar é incrível, muito atenciosa"
- J Tol — "I loved the service, Adriana is amazing!" *(em inglês)*

> **Notas para o code:**
> - Fiz limpeza leve de digitação (acentos/pontuação); o sentido foi mantido fiel ao original.
> - Hoje o slider tem 4 cards — usar os 6 principais. O slider de `script.js` já suporta scroll horizontal com qualquer quantidade, não precisa mexer no JS.
> - Remover o atributo de cidade fictício ("Joinville/SC", "Jaraguá do Sul/SC") dos cards atuais — substituir por "Avaliação no Google" ou deixar só o nome.

---

## 6. CONTATO E AGENDAMENTO

### ✅ 6.1 Adicionar horário de funcionamento
**Arquivo:** `index.html` → criar bloco de horários na seção `#contato` e/ou no footer.

Conteúdo:
- **Atendimento somente com hora marcada, via WhatsApp**
- Segunda a sexta: **09h00–11h30** e **14h00–20h00**
- Sábado: **somente alguns protocolos, com agendamento prévio**

> Atualizar também o JSON-LD `BeautySalon` no `<head>` com `openingHours` para SEO.

### ✅ 6.2 Corrigir endereço + adicionar mapa
**Arquivo:** `index.html` → footer `.footer__contact` + JSON-LD

- Endereço completo: **Servidão Antônio João de Oliveira, 93 — Boehmerwald, Joinville/SC** (adicionar o bairro, que falta hoje; "BOHEMERWALTD" no briefing = Boehmerwald)
- Adicionar **mapa do Google** (embed `<iframe>` ou link) apontando para o endereço. Definir se vai dentro da seção `#contato` ou no footer.

### ✅ 6.3 Adicionar canal Google
Adicionar destaque de que ela é encontrada no Google como **"Adriana Maia Studio — Especialista em Sobrancelhas"**. Sugestão: link no footer apontando para o perfil/busca do Google Business.

---

## 7. VISUAL

### ⏸️ 7.1 Ajuste de cor — adiado
A Adriana marcou "Quero ajustar alguma cor", mas decidiram **manter como está hoje até resolverem mudar**. Nada a fazer agora.

> Quando voltarem ao assunto, resolver junto a inconsistência: o `DesignSistem.md` define `--vinho: #6B1040`, mas o `style.css` usa `--vinho: #55082C` (comentado como "cor exata do fundo da logo"). Definir qual é o vinho oficial.

### ❓ 7.2 / 7.3 Referências e vetos
Sem referências de inspiração e sem vetos definidos ainda — ela vai revisar e avisar. Nada a fazer agora.

---

## 8. DOMÍNIO E PUBLICAÇÃO

### ⏳ 8.1 Domínio
Ela tem o `adrianamaiastudio.com.br` mas precisa confirmar onde está hospedado e mandar os acessos. Aguardando.

### — 8.2 Data de lançamento
Sem data definida. Nada a fazer.

---

## Checklist resumido (para o code)

### Fazer agora ✅
- [ ] Hero: trocar headline para "Seu olhar em destaque."
- [ ] Serviços: atualizar os 5 cards conforme lista da seção 2
- [ ] Sobre: reescrever parágrafos + lista de conquistas (seção 3.1)
- [ ] Contato: adicionar bloco de horários + atualizar JSON-LD
- [ ] Footer: corrigir endereço (adicionar bairro Boehmerwald)
- [ ] Contato/Footer: adicionar mapa do Google
- [ ] Footer: adicionar canal "encontre no Google"
- [ ] Depoimentos: substituir os 4 fictícios pelos 6 reais do Google (seção 5.1)
- [ ] (Opcional) Atualizar ano do copyright no footer (2025 → 2026)

### Aguardando material da cliente ⏳
- [ ] Nova foto do hero
- [ ] Nova foto da seção Sobre
- [ ] Fotos novas + trocas da galeria
- [ ] Revisão das legendas da galeria
- [ ] Texto completo do depoimento da Graziela C. (cortado no print)
- [ ] Link da Revista Sucesso (pegar no Instagram)
- [ ] Acessos do domínio/hospedagem

### Decisões pendentes ❓
- [ ] Card de Cursos simples ou seção dedicada?
- [ ] Atualizar bloco de credenciais com os prêmios novos?

### Resolvido ✔️
- Headline em caixa baixa (não era caixa alta proposital)
- Cor mantida como está até decidirem mudar
- Depoimentos reais coletados do Googleleia 