# AuraSign

Plataforma para redirecionamento de usuários a partir de telas digitais e tags inteligentes, com rastreamento de jornada, geração de relatórios e apoio a campanhas locais.

## Visão geral

O **AuraSign** foi pensado como um MVP para conectar **telas digitais**, **tags NFC/QR** e **landing pages dinâmicas**, permitindo que um usuário aproxime o celular de uma tela ou etiqueta e seja direcionado para uma experiência digital personalizada.

A solução foi desenhada para ambientes como lojas, pontos de venda, vitrines, balcões, totens e espaços de atendimento, com foco em:

- captação de interesse no ponto físico;
- redirecionamento simples e rápido;
- coleta de métricas de interação;
- ofertas, cupons e cadastros;
- relatórios para o comerciante.

## Objetivos do projeto

- Criar uma experiência de interação por proximidade com celular.
- Redirecionar o usuário para uma URL curta e dinâmica.
- Rastrear acesso por tag e campanha.
- Exibir ofertas, vídeos, cadastros ou cupons.
- Gerar dados úteis para análise comercial.

## Funcionalidades principais

- **Tag inteligente**: NFC, QR Code ou similar, anexada próxima à tela.
- **Redirecionamento dinâmico**: URL curta configurável por campanha.
- **Landing page personalizada**: página com conteúdo, vídeo, formulário ou cupom.
- **Tracking de campanha**: uso de parâmetros UTM e identificação por tag.
- **Dashboard de relatórios**: visualização de acessos e conversões.
- **Bloqueio de conteúdo**: proteção contra alteração indevida da URL ou configuração.
- **Arquitetura flexível**: suporte para evolução futura com novos fluxos e integrações.

## Como funciona

1. O comerciante instala uma tag ao lado da tela ou ponto de exposição.
2. O cliente aproxima o celular ou escaneia o código.
3. O sistema redireciona para uma página de destino.
4. A página pode exibir oferta, vídeo, formulário ou cupom.
5. As interações são registradas para análise posterior.

## Casos de uso

- Promoções em lojas físicas.
- Campanhas em vitrines.
- Materiais interativos em pontos de venda.
- Cadastro de leads em eventos.
- Cupons e recompensas instantâneas.
- Rastreamento de interesse por localização ou filial.

## Arquitetura sugerida

- **Frontend**: página de redirecionamento e landing pages.
- **Backend**: controle de campanhas, tags, usuários e métricas.
- **Banco de dados**: armazenamento de acessos, cadastros e eventos.
- **Dashboard**: painéis de visualização e exportação de dados.
- **Integrações**: analytics, planilhas, CRM ou ferramentas de marketing.

## Tecnologias possíveis

- HTML, CSS e JavaScript
- React, Vue ou outro framework frontend
- Node.js, Python ou PHP no backend
- PostgreSQL, MySQL ou SQLite
- APIs de analytics e relatórios
- QR Code / NFC / URLs encurtadas

## Requisitos para rodar o projeto

- Node.js ou ambiente equivalente
- Banco de dados configurado
- Variáveis de ambiente definidas
- Acesso às credenciais de campanha e tracking

## Instalação

```bash
git clone https://github.com/seu-usuario/aurasign.git
cd aurasign
npm install
npm run dev
```

## Configuração

Crie um arquivo `.env` com as variáveis necessárias:

```env
APP_URL=https://seu-dominio.com
DATABASE_URL=sua_string_de_conexao
TRACKING_ENABLED=true
```

## Estrutura sugerida do projeto

```bash
aurasign/
├── src/
├── public/
├── components/
├── pages/
├── api/
├── assets/
├── docs/
└── README.md
```

## Roadmap

- MVP com redirecionamento simples.
- Suporte a múltiplas tags.
- Dashboard de métricas.
- Campanhas com UTM.
- Regras por loja ou região.
- Integração com CRM e automações.
- Melhorias de segurança e autenticação.

## Segurança

O projeto deve considerar:

- proteção das URLs dinâmicas;
- validação de acesso por campanha;
- registro de eventos sem expor dados sensíveis;
- controle de alteração de conteúdo;
- boas práticas de autenticação e permissões.

## Contribuição

1. Faça um fork do repositório.
2. Crie uma branch para sua melhoria.
3. Envie um pull request com descrição clara.
4. Mantenha o foco no MVP e na simplicidade.

## Licença

Definir de acordo com a estratégia do projeto.

## Contato

Projeto em evolução com foco em tecnologia, dados e experiência no ponto físico.
