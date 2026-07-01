# 🎨 Tattuu — Conectando Tatuadores e Clientes

Plataforma web para descoberta de tatuadores, construída para resolver um problema real: encontrar o artista certo pra fazer uma tatuagem geralmente depende de indicação boca a boca ou de scrollar horas no Instagram. O Tattuu organiza isso — perfis, portfólio, avaliações e contato direto, tudo em um só lugar.

> 🚧 **Projeto em desenvolvimento ativo.** As funcionalidades abaixo já estão implementadas, mas o produto segue evoluindo — novas features e melhorias são adicionadas continuamente.

> 🔒 O código-fonte deste projeto é privado. Este repositório é uma vitrine com a documentação e visão geral do produto. Para ver uma demonstração ou ter acesso ao código, entre em contato.

---

## 💡 O problema que resolve

- **Para clientes:** dificuldade de descobrir tatuadores confiáveis e comparar estilos/portfólios antes de decidir
- **Para tatuadores:** falta de uma vitrine profissional própria, dependente de redes sociais genéricas pra divulgar trabalho

## ✨ Funcionalidades

**Para clientes**
- Descoberta de tatuadores com filtros
- Visualização de perfil e portfólio de cada artista
- Avaliações (reviews) de outros clientes
- Contato direto com o tatuador pela plataforma

**Para tatuadores**
- Dashboard próprio
- Gestão de portfólio
- Recebimento de avaliações e mensagens de clientes

**Geral**
- Autenticação com JWT, com fluxos e permissões separados para cliente e tatuador
- Interface responsiva, pensada mobile-first

---

## 🛠️ Stack técnica

| Camada | Tecnologias |
|---|---|
| Frontend | React 19, TypeScript, Vite, Tailwind CSS, React Router DOM |
| Backend | FastAPI (Python) |
| Banco de dados | MongoDB |
| Autenticação | JWT |

## 🧩 Decisões de arquitetura

- **Separação clara de responsabilidades**: frontend e backend desacoplados, comunicando via API REST documentada automaticamente (Swagger/OpenAPI via FastAPI)
- **Rotas protegidas** no frontend (`ProtectedRoute`) garantindo que áreas autenticadas só sejam acessadas com token válido
- **Modelagem de dados orientada a dois perfis de usuário** (cliente e tatuador), com jornadas e permissões distintas desde a autenticação
- **Componentização** organizada por domínio (auth, cards, layout, sections) pra manter o frontend escalável

---

## 📸 Capturas de tela

<!-- Adicione aqui prints ou um GIF curto mostrando o fluxo principal (ex: buscar tatuador → ver perfil → deixar review) -->

---

## 🚀 Quer ver funcionando?

O projeto está disponível para demonstração ao vivo ou concessão de acesso ao repositório mediante solicitação.

📧 [seu e-mail ou link de contato]
🔗 [LinkedIn]
