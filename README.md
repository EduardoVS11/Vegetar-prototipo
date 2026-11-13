# Vegetar

Protótipo navegável para uma plataforma de descoberta de restaurantes e mercados com opções veganas, vegetarianas e para outras restrições alimentares.

O projeto reúne a experiência do consumidor e o fluxo de cadastro e gestão para estabelecimentos, com interface mobile-first inspirada no protótipo desenvolvido no Figma.

## Funcionalidades

- Exploração de estabelecimentos por categorias e filtros alimentares;
- Busca, resultados em lista e mapa;
- Página de detalhes do estabelecimento, avaliações e denúncia;
- Autenticação, cadastro e perfil de usuário;
- Cadastro guiado para restaurantes;
- Painel mobile para empresas com métricas, gráfico, avaliações, descontos, perfil e plano.

## Tecnologias

- React 19
- Vite
- CSS puro
- Lucide React
- Poppins (`@fontsource/poppins`)

## Como executar

Pré-requisito: Node.js 20 ou superior e pnpm.

```bash
git clone <url-do-repositorio>
cd vegetar-react
pnpm install
pnpm dev
```

Depois, abra a URL mostrada no terminal — normalmente `http://localhost:5173`.

Para criar a versão de produção:

```bash
pnpm build
```

## Acesso ao painel da empresa

Na tela inicial, selecione **Entrar** → **Acesso para restaurantes**. O fluxo permite realizar o cadastro ou entrar diretamente no painel demonstrativo.

## Observação

Este é um protótipo de interface. Os dados e ações são simulados localmente e não há integração com backend nesta versão.
