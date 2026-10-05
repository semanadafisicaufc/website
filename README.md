# Semana da Física · PPG-Fis — UFC 2026

Site do evento. 05—09 de outubro de 2026, Bloco de Empreendedorismo da UFC,
Campus do Pici, Fortaleza-CE.

## Publicação

O site é **um único arquivo**: `index.html`. Todas as imagens, logos, fontes e
o template de resumo em PDF estão embutidos dentro dele. Não existe pasta de
assets para subir, e por isso nada pode faltar no upload.

Para GitHub Pages: suba o `index.html` na raiz do repositório, depois
Settings → Pages → Deploy from a branch → `main` / `/ (root)`.

## Arquivos

| Arquivo | Função |
| --- | --- |
| `index.html` | O site inteiro. É o único necessário. |
| `.nojekyll` | Evita que o Jekyll interfira no Pages |
| `README.md` | Este arquivo |
| `instagram-divulgacao.dc.html` | Artes de divulgação (feed + story) |
| `divulgacao/` | As artes exportadas em PNG |

Os dois últimos não fazem parte do site e podem ser removidos.

## Editar conteúdo

Textos, datas, palestrantes, premiados e organizadores ficam na classe
`Component`, ao final do `index.html`:

- `ui.pt` / `ui.en` — todos os textos dos dois idiomas
- `speakersData` — palestrantes (`status: 'confirmed'` ou `'pending'`)
- `organizersData` — comissão organizadora
- `sponsorLogos` — logos de apoio, na ordem exibida
- `days` — cronograma

O formulário de inscrição/submissão é um link do Google Forms, buscável por
`forms.gle` no arquivo.

As imagens estão embutidas como data URI. Para trocar uma foto, envie a nova
imagem no chat do projeto e ela é reinserida no lugar certo.
