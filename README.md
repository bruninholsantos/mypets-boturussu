# My Pets Boturussu — Clínica Veterinária

Site institucional da clínica veterinária My Pets Boturussu (Parque Boturussu, São Paulo/SP).
Endereço oficial: **https://clinicamypets.com.br**

- Especialidades: Cardiologia, Dermatologia, Endocrinologia, Nefrologia e Urologia, Odontologia, Oftalmologia, Oncologia, Ortopedia, Pneumologia e Medicina Felina
- Convênios: Doglife, Petlife e Petlove
- Horário: segunda a sexta 9h às 18h · sábado 9h às 17h

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | Site (uma página), com metadados de SEO, Open Graph e dados estruturados (Schema.org `VeterinaryCare`) |
| `CNAME` | Domínio próprio no GitHub Pages (`clinicamypets.com.br`) |
| `robots.txt` / `sitemap.xml` | Orientam o Google a indexar o site |
| `site.webmanifest`, `favicon.ico`, `assets/icon-*.png`, `assets/apple-touch-icon.png` | Ícones da aba, do celular e do atalho na tela inicial |
| `assets/og-image.jpg` | Imagem que aparece ao compartilhar o link (WhatsApp, Instagram, Facebook) |
| `404.html` | Página de erro que volta para o início |

## Domínio (DNS)

No painel onde o domínio foi registrado (ex.: Registro.br), crie:

- 4 registros **A** para `clinicamypets.com.br` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- 1 registro **CNAME** para `www` → `bruninholsantos.github.io`

Depois, em **Settings → Pages**, confirme o domínio e marque **Enforce HTTPS**.
