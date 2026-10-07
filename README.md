# Harmonia das Orelhas

Site institucional da **Patrícia Lima**, especialista em furo humanizado, correção de lóbulo (lobuloplastia), com atendimento no Grande ABC e em São Paulo.

- **Cliente:** Patrícia Lima
- **Site publicado:** https://patricia.imaguiar.com.br/
- **Instagram:** [@paty.harmoniadasorelhas](https://www.instagram.com/paty.harmoniadasorelhas/)

## Sobre o projeto

Página única (one-page), responsiva, focada em converter visitantes em agendamentos pelo WhatsApp. Apresenta a profissional, os serviços e o atendimento, com botões de contato direto.

## Tecnologias

- HTML5 e CSS3 puros (estilos embutidos no `index.html`), sem build e sem dependências
- JavaScript puro para interações simples (menu e cabeçalho)
- Google Fonts: Cormorant Garamond e Poppins
- Imagens em WebP e PNG
- Hospedagem: GitHub Pages

## Estrutura de pastas

```
.
├── index.html        # página única do site
├── img/              # imagens, logo, emblema e favicon
└── README.md
```

## Como rodar localmente

Não precisa instalar nada. Abra o `index.html` no navegador ou, se preferir um servidor local:

```bash
python -m http.server 8000
```

Depois acesse http://localhost:8000.

## Publicação

O site é publicado automaticamente pelo GitHub Pages a partir da branch `main`, pasta raiz. Qualquer push na `main` atualiza o site em poucos minutos.

## Observações

As fotos do site foram selecionadas do perfil público da profissional no Instagram. As fotos de atendimento são usadas como ilustração, não como documentação clínica.

## Antes e depois da lobuloplastia

A seção `#resultados` mostra um comparador com divisor. Enquanto não há fotos, aparece um aviso "Em breve". Para adicionar um caso: salve as imagens (WebP, proporção 4:5) em `img/resultados/`, copie o bloco `<figure class="ba">` que está comentado em `index.html` e remova o bloco `ba-vazio`. Use só fotos de clientes que autorizaram.
