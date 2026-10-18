# Planejamento do repositório

Documento de planejamento do **PortfolioHUB**, repositório de portfólio de Rafael Bernardes Matias, criado na entrega intermediária do desafio *Criação de Repositório com Versionamento* (Bootcamp I).

## Objetivo

Reunir projetos acadêmicos e pessoais em um só lugar, versionados com Git e publicados no GitHub, para compor um perfil profissional integrado ao LinkedIn.

## Seções do repositório

| Seção | Pasta | O que guarda |
|---|---|---|
| Projetos acadêmicos | `projetos-academicos/` | Trabalhos de cursos e da graduação |
| Projetos pessoais | `projetos-pessoais/` | Laboratórios feitos por conta própria |
| Página web | `pagina-web/` | Site publicado no GitHub Pages |
| Documentação | `docs/` | Planejamento, slides e documentos de apoio |

## Estrutura de diretórios

```text
portfolio-hub/
├── docs/
├── pagina-web/
│   ├── assets/
│   ├── css/
│   ├── js/
│   └── *.html
├── projetos-academicos/
├── projetos-pessoais/
└── README.md
```

## Projetos iniciais

1. **Intranet industrial com VLANs e serviços básicos** (acadêmico, curso da Alura), feito no Cisco Packet Tracer.
2. **Topologia corporativa com HSRP, VLANs e redundância** (pessoal, inspirado no curso do professor Gustavo Kalau), também no Packet Tracer.

## Regras de versionamento

- Um commit por mudança lógica, com mensagem no formato `tipo: descrição` (`feat:`, `docs:`, `fix:`).
- A versão inicial da página recebeu a tag anotada `v1.0`.
- Alterações são enviadas ao GitHub com `git push`, sem reescrever o histórico.
- Cada projeto novo entra na pasta da sua categoria, com documentação própria.

## Publicação e integração

- **GitHub Pages:** publicado a partir da branch `main`, pasta raiz. A página fica em `/pagina-web/`.
- **Repositório público:** com link de compartilhamento.
- **LinkedIn:** projetos adicionados à seção de projetos do perfil, com o link do repositório e da página.
