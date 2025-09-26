# 🛡️ Guia RSL / RSL Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Language: PT/EN](https://img.shields.io/badge/Language-PT%2FEN-blue.svg)](https://github.com/reichaves/guia-rsl)
[![RSL Standard](https://img.shields.io/badge/RSL-Standard-green.svg)](https://rslstandard.org)

Um guia multilíngue (PT/EN) para implementação do RSL (Really Simple Licensing) - o padrão aberto que permite aos criadores de conteúdo proteger suas obras contra uso não autorizado por IAs.

A multilingual guide (PT/EN) for implementing RSL (Really Simple Licensing) - the open standard that allows content creators to protect their work from unauthorized AI usage.

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
