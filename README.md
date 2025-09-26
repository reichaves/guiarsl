# 🛡️ Guia RSL / RSL Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Language: PT/EN](https://img.shields.io/badge/Language-PT%2FEN-blue.svg)](https://github.com/reichaves/guia-rsl)
[![RSL Standard](https://img.shields.io/badge/RSL-Standard-green.svg)](https://rslstandard.org)

Um guia multilíngue (PT/EN) para implementação do RSL (Really Simple Licensing) - o padrão aberto que permite aos criadores de conteúdo proteger suas obras contra uso não autorizado por IAs.

A multilingual guide (PT/EN) for implementing RSL (Really Simple Licensing) - the open standard that allows content creators to protect their work from unauthorized AI usage.

## 🌟 Explicação / Explanation

Você sabia que seu conteúdo pode estar sendo usado para treinar IAs sem sua autorização ou compensação?

Com o avanço das ferramentas de IA generativa, criadores de conteúdo, jornalistas e empresas enfrentam um desafio crescente: como proteger seus direitos autorais na era da inteligência artificial?

Faz pouco tempo conheci o RSL (Really Simple Licensing), um padrão aberto e descentralizado baseado no RSS (Really Simple Syndication) que permite aos publicadores definir termos de licenciamento e compensação legíveis por máquinas para crawlers e agentes de IA

Fiz este guia sobre isso - [https://reichaves.github.io/guiarsl/](https://reichaves.github.io/guiarsl/)

E hoje (26 set 2025) também a repórter Fernanda Brigatti falou sobre isso na Folha - [https://www1.folha.uol.com.br/tec/2025/09/novo-padrao-para-sites-cria-cobranca-e-camada-extra-de-protecao-a-conteudo-usado-por-ias.shtml](https://www1.folha.uol.com.br/tec/2025/09/novo-padrao-para-sites-cria-cobranca-e-camada-extra-de-protecao-a-conteudo-usado-por-ias.shtml)

O RSL Collective é a organização sem fins lucrativos que mantém e governa o padrão Really Simple Licensing (RSL), reunindo publishers, plataformas e desenvolvedores para definir regras abertas de licenciamento de conteúdo para uso por IAs

Ou seja, é uma tentativa inicial de pagamento. O volume e o tipo de crawling por IAs cresceram rapidamente, com queda de tráfego de referência para sites jornalísticos e aumento de bots de “training”. Players de infraestrutura reagiram: a Cloudflare passou a bloquear por padrão crawlers de IA, lançou “pay per crawl” e “AI crawl control” (inclui respostas HTTP 402 “payment required”). Esses movimentos mostram que só o robots.txt é insuficiente e que um “caminho de licenciamento” estava faltando

Hoje, na prática no Brasil, se um veículo ou publisher aderir ao RSL o que se ganha é sobretudo sinalização técnica e política. Não há um fluxo garantido de receita, não há relatos de Big Techs já pagando via RSL. Mas pode ser um caminho inicial de criar um esforço coletivo mundial de pressão e parceria com o RSL Collective. No relato de lançamento, o TechCrunch afirma que RSL cria uma “organização coletiva de licenciamento … que pode negociar termos e coletar royalties” para publishers [https://techcrunch.com/2025/09/10/rss-co-creator-launches-new-protocol-for-ai-data-licensing/](https://techcrunch.com/2025/09/10/rss-co-creator-launches-new-protocol-for-ai-data-licensing/)


Did you know that your content may be used to train AIs without your authorization or compensation?

With the rise of generative AI tools, content creators, journalists, and companies face a growing challenge: how to protect their copyrights in the age of artificial intelligence?

Not long ago, I learned about RSL (Really Simple Licensing), an open and decentralized standard based on RSS (Really Simple Syndication) that allows publishers to define machine-readable licensing and compensation terms for AI crawlers and agents.

I made this guide about it – [https://reichaves.github.io/guiarsl/](https://reichaves.github.io/guiarsl/)

And today (September 26, 2025), reporter Fernanda Brigatti also wrote about it in Folha – [https://www1.folha.uol.com.br/tec/2025/09/novo-padrao-para-sites-cria-cobranca-e-camada-extra-de-protecao-a-conteudo-usado-por-ias.shtml](https://www1.folha.uol.com.br/tec/2025/09/novo-padrao-para-sites-cria-cobranca-e-camada-extra-de-protecao-a-conteudo-usado-por-ias.shtml)

The RSL Collective is the nonprofit organization that maintains and governs the Really Simple Licensing (RSL) standard, bringing together publishers, platforms, and developers to define open rules for content licensing for AI use.

In other words, it is an initial attempt at establishing payment. The volume and type of AI crawling has grown rapidly, with declining referral traffic to news sites and an increase in “training” bots. Infrastructure players reacted: Cloudflare began blocking AI crawlers by default, launched “pay per crawl” and “AI crawl control” (including HTTP 402 “payment required” responses). These moves show that robots.txt alone is insufficient and that a “licensing pathway” was missing.

Today, in practice in Brazil, if a news outlet or publisher adopts RSL, what they gain is mainly technical and political signaling. There is no guaranteed revenue stream, and there are no reports of Big Techs already paying via RSL. But it may be an initial path to creating a global collective effort of pressure and partnership with the RSL Collective. In its launch coverage, TechCrunch stated that RSL creates a “collective licensing organization … that can negotiate terms and collect royalties” for publishers [https://techcrunch.com/2025/09/10/rss-co-creator-launches-new-protocol-for-ai-data-licensing](https://techcrunch.com/2025/09/10/rss-co-creator-launches-new-protocol-for-ai-data-licensing)

## 🌟 Demonstração / Demo

🔗 **[Veja o Guia ao Vivo / View Live Guide](https://reichaves.github.io/guiarsl/)**

## 📋 Índice / Table of Contents

- [Sobre / About](#-sobre--about)
- [Recursos / Features](#-recursos--features)
- [Instalação / Installation](#-instalação--installation)
- [Como Usar / How to Use](#-como-usar--how-to-use)
- [Tecnologias / Technologies](#-tecnologias--technologies)
- [Contribuindo / Contributing](#-contribuindo--contributing)
- [Autor / Author](#-autor--author)
- [Licença / License](#-licença--license)

## 🎯 Sobre / About

### Português

O **Guia RSL** é uma ferramenta educacional que ajuda criadores de conteúdo, jornalistas e empresas a implementarem o padrão RSL (Really Simple Licensing) em seus sites. Com o avanço das IAs generativas usando conteúdo sem autorização, o RSL oferece uma solução técnica para definir termos de uso, incluindo bloqueio, monetização ou atribuição obrigatória.

### English

The **RSL Guide** is an educational tool that helps content creators, journalists, and companies implement the RSL (Really Simple Licensing) standard on their websites. With generative AIs using content without authorization, RSL offers a technical solution to define usage terms, including blocking, monetization, or mandatory attribution.

## ✨ Recursos / Features

- 🌐 **Interface Bilíngue**: Português (BR) e Inglês com troca instantânea
- 📱 **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- 🎨 **Interface Moderna**: Gradientes, animações suaves e design intuitivo
- 📋 **Códigos Prontos**: Exemplos de implementação com botão de copiar
- 🔄 **Tabs Interativas**: Diferentes modelos de licença organizados
- ❓ **FAQ Completo**: Respostas para as principais dúvidas
- 💾 **Memória de Preferência**: Salva o idioma escolhido pelo usuário
- 🚀 **Zero Dependências**: HTML puro, CSS e JavaScript vanilla

## 🚀 Instalação / Installation

### Opção 1: GitHub Pages

```bash
# Clone o repositório
git clone https://github.com/reichaves/guia-rsl.git

# Entre no diretório
cd guia-rsl

# O arquivo index.html contém todo o site
# Faça commit e push para seu repositório

# Ative o GitHub Pages nas configurações do repositório
# Seu site estará disponível em:
# https://[seu-usuario].github.io/guia-rsl/
```

### Opção 2: Servidor Web Local

```bash
# Clone o repositório
git clone https://github.com/reichaves/guia-rsl.git

# Entre no diretório
cd guia-rsl

# Use qualquer servidor HTTP local, por exemplo:
python -m http.server 8000
# ou
npx serve
# ou
php -S localhost:8000
```

### Opção 3: Upload Direto

Simplesmente faça upload do arquivo `index.html` para qualquer servidor web ou hospedagem.

## 💻 Como Usar / How to Use

### Para Implementar RSL no Seu Site:

1. **Escolha seu modelo de licença** no guia interativo
2. **Copie o código XML** fornecido
3. **Crie um arquivo** `license.xml` na raiz do seu site
4. **Adicione a linha** `License: https://seusite.com/license.xml` ao seu `robots.txt`
5. **Teste a implementação** acessando os arquivos criados

### Para Personalizar o Guia:

```html
<!-- Para adicionar um novo modelo de licença -->
<div class="license-card">
    <h4>🔒 Seu Modelo Personalizado</h4>
    <p>Descrição do seu modelo</p>
</div>

<!-- Para adicionar uma nova pergunta ao FAQ -->
<div class="faq-item">
    <div class="faq-question" onclick="toggleFAQ(this)">
        <span data-lang="pt">Sua pergunta em português?</span>
        <span data-lang="en">Your question in English?</span>
        <span class="faq-icon">▼</span>
    </div>
    <div class="faq-answer">
        <p data-lang="pt">Resposta em português</p>
        <p data-lang="en">Answer in English</p>
    </div>
</div>
```

## 🛠️ Tecnologias / Technologies

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Gradientes, animações e design responsivo
- **JavaScript**: Vanilla JS para interatividade
- **LocalStorage**: Para salvar preferências do usuário
- **RSL Standard**: Implementação do padrão oficial

## 📊 Estrutura do Projeto / Project Structure

```
guia-rsl/
│
├── index.html          # Site completo (HTML, CSS, JS integrados)
├── README.md           # Este arquivo
└── LICENSE            # Licença MIT
```

## 🤝 Contribuindo / Contributing

Contribuições são bem-vindas! Por favor:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### Sugestões de Contribuição:

- 🌍 Traduções para outros idiomas
- 📝 Novos exemplos de implementação
- 🎨 Melhorias no design
- 📚 Mais perguntas e respostas no FAQ
- 🐛 Correção de bugs
- ♿ Melhorias de acessibilidade

## 📈 Roadmap

- [ ] Adicionar gerador visual de licenças
- [ ] Validador de arquivos RSL
- [ ] Integração com APIs do RSL Collective
- [ ] Modo escuro
- [ ] Versão PWA para uso offline
- [ ] Traduções adicionais (ES, FR, DE)
- [ ] Tutoriais em vídeo
- [ ] Calculadora de royalties estimados

## 👤 Autor / Author

**Reinaldo Chaves**

- 📧 Email: [reichaves@gmail.com](mailto:reichaves@gmail.com)
- 🐙 GitHub: [@reichaves](https://github.com/reichaves)
- 💼 LinkedIn: [Reinaldo Chaves](https://www.linkedin.com/in/reichaves/)

## 🙏 Agradecimentos / Acknowledgments

- [RSL Standard](https://rslstandard.org) - Pelo desenvolvimento do padrão
- [RSL Collective](https://rslcollective.org) - Pela gestão coletiva de direitos
- Comunidade de criadores de conteúdo brasileiros que inspiraram este projeto

## 📄 Licença / License

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para detalhes.

```
MIT License

Copyright (c) 2025 Reinaldo Chaves (reichaves@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🌟 Apoie o Projeto / Support the Project

Se este guia foi útil para você:

- ⭐ Dê uma estrela no GitHub
- 🔗 Compartilhe com outros criadores de conteúdo
- 📣 Divulgue nas redes sociais usando #GuiaRSL
- 🐛 Reporte bugs ou sugira melhorias
- 🤝 Contribua com código ou documentação

---

<div align="center">

**🛡️ Proteja seu conteúdo. Defina seus termos. Use RSL.**

**🛡️ Protect your content. Define your terms. Use RSL.**

Feito com ❤️ no Brasil / Made with ❤️ in Brazil

</div>
