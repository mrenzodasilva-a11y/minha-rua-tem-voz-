# 🏘️ Minha Rua Tem Voz

**A plataforma em que o morador aponta o problema, a comunidade apoia e a cidade enxerga o que precisa ser resolvido.**

🔗 **Acesse:** https://mrenzodasilva-a11y.github.io/minha-rua-tem-voz-/

> Projeto desenvolvido para o **Projeto ACICLA** por **Enzo da Silva**, criador da ideia, autor e desenvolvedor.

---

## 📌 Resumo

O **Minha Rua Tem Voz** é uma plataforma web gratuita para registrar problemas urbanos, como buracos, iluminação apagada, lixo acumulado e falta de acessibilidade. Cada relato fica público, com local, categoria e foto. Os moradores apoiam os relatos uns dos outros, e os problemas mais apoiados sobem para o topo.

Assim, reclamações que antes se perdiam em grupos de WhatsApp viram **informação organizada, visível e priorizada pela própria comunidade**.

---

## ❗ O problema

- **Reclamações espalhadas:** problemas do bairro são comentados em conversas, redes sociais e grupos, mas raramente chegam organizados a quem pode resolver.
- **Nenhuma prioridade clara:** quem decide não sabe quais problemas afetam mais pessoas.
- **Canais burocráticos:** cadastro, protocolo e formulários longos fazem o morador desistir antes de registrar.
- **Sensação de impotência:** o cidadão não vê o resultado e deixa de participar.

## 💡 A solução

Uma página simples, que abre no celular sem instalar nada e permite registrar um problema **em menos de dois minutos e sem cadastro**.

| Etapa | O que acontece |
|---|---|
| **1. Registrar** | O morador escolhe a categoria, digita o CEP (o endereço se preenche sozinho), descreve o problema e, se quiser, envia uma foto. |
| **2. Localizar** | O endereço aparece automaticamente no mapa, com o ponto exato do problema. |
| **3. Apoiar** | Outros moradores apoiam e comentam. Os relatos mais apoiados ganham destaque. |
| **4. Acompanhar** | Cada relato mostra sua situação: **Pendente**, **Em andamento** ou **Resolvido**. |

---

## ⭐ Diferenciais

- **Sem cadastro e sem instalação:** funciona direto no navegador, no celular ou no computador.
- **Prioridade feita pela comunidade:** o número de apoios mostra o que mais incomoda a população.
- **Endereço automático:** busca pelo CEP e marcação no mapa sem esforço.
- **Inclusivo:** disponível em **10 idiomas** (português, inglês, espanhol, francês, alemão, italiano, chinês, japonês, hindi e árabe).
- **Privacidade em primeiro lugar:** relatos anônimos e orientações para não expor dados pessoais, rostos ou placas.
- **Custo de operação próximo de zero:** usa serviços em nuvem com planos gratuitos e mapas abertos (OpenStreetMap).

---

## 🎯 Para quem gera valor

| Público | Benefício |
|---|---|
| **Moradores** | Um canal simples para ser ouvido e acompanhar o que acontece na rua e no bairro. |
| **Poder público** | Um retrato organizado das demandas, com local, foto e nível de apoio, que ajuda a definir prioridades. |
| **Comércio e empresas locais** | Ruas iluminadas, limpas e bem conservadas trazem mais movimento, segurança e clientes. A plataforma é também uma oportunidade de mostrar responsabilidade social com o bairro. |
| **Associações e entidades** | Dados concretos para apoiar pedidos e campanhas junto aos órgãos responsáveis. |

---

## 💼 Modelo de sustentabilidade

A plataforma é **sempre gratuita para o cidadão**. Para crescer e se manter, o projeto prevê:

1. **Parceria com o poder público:** um painel de gestão para acompanhar, responder e atualizar a situação dos relatos.
2. **Apoio de empresas e associações locais:** patrocínio e um selo de **"Empresa Amiga do Bairro"** para quem apoia o projeto.
3. **Relatórios por bairro:** resumos periódicos de demandas por região e categoria, para entidades e gestores.

---

## ✅ O que já está funcionando

- Registro de problemas com título, categoria, descrição e foto
- Preenchimento automático do endereço pelo CEP
- Mapa com localização automática do endereço e ajuste manual
- Feed público com busca por texto e filtro por categoria
- Sistema de apoios, com os mais apoiados em destaque
- Comentários em cada relato
- Indicadores na página inicial: relatos publicados e apoios recebidos
- Layout adaptado para celular
- Interface em 10 idiomas, que lembra o idioma escolhido

## 🚀 Próximos passos

- [ ] **Moderação:** botão "denunciar relato" e proteção contra spam
- [ ] **Mapa geral:** todos os relatos em um mapa, com cores por categoria
- [ ] **Painel de gestão:** atualizar a situação dos relatos (em andamento / resolvido)
- [ ] **Encaminhamento:** enviar o relato diretamente para a ouvidoria da prefeitura
- [ ] **Relatos duplicados:** avisar quando já existe um relato no mesmo local
- [ ] **Fotos mais leves e seguras:** compressão automática e remoção da localização escondida nas imagens

---

## 🛠️ Tecnologia

| Componente | Ferramenta |
|---|---|
| Interface | HTML, CSS e JavaScript |
| Banco de dados e fotos | [Supabase](https://supabase.com) |
| Mapas | [Leaflet](https://leafletjs.com) + [OpenStreetMap](https://www.openstreetmap.org) |
| Busca de CEP | [ViaCEP](https://viacep.com.br) |
| Localização do endereço | Nominatim (OpenStreetMap) |
| Hospedagem | GitHub Pages |

### Como executar

O projeto é uma única página (`index.html`), sem necessidade de instalação:

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` no navegador.

Para usar um banco de dados próprio, troque a URL e a chave pública do Supabase no início do JavaScript em `index.html`.

---

## 🏫 Sobre o projeto

O **Minha Rua Tem Voz** foi criado como projeto escolar para o **Projeto ACICLA**, com o objetivo de usar a tecnologia para aproximar moradores, comércio e poder público na construção de uma cidade melhor.

### 👤 Autor

**Enzo da Silva**: criador da ideia, autor e desenvolvedor do projeto.

> **Uma cidade melhor começa com a sua voz.**
