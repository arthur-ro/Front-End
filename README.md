# 📋 Formulário de Cadastro de DEVs

Formulário simples criado em **HTML** e **CSS** para praticar conceitos de formulários, validação de campos e estilização responsiva. Ideal para exercícios de front-end e para mostrar como construir um formulário de contato/cadastro básico.

---

## 🧩 Funcionalidades
- Campos: Nome, Email, Área de atuação (Front-end / Back-end / Full-stack), Senioridade, Tecnologias, Experiência.
- Validação básica de email usando `type="email"` (exige `@`).
- Layout responsivo e botão estilizado.
- Uso de radio/checkbox para seleção de senioridade e tecnologias.

> **Observação sobre "Senioridade"**  
> O campo de senioridade é apenas informativo — opções comuns: **Júnior** (iniciantes, ex.: quem começou há meses), **Pleno** e **Sênior**. No formulário você pode marcar **Júnior** por padrão se quiser.

---

## 🗂 Estrutura do repositório (exemplo)
```
Full-Stack/
└─ Aula-2/
   ├─ formulario.html
   ├─ formulario.css
   └─ assets/ (opcional: imagens, etc.)
```

---

## 🚀 Como usar (local)
1. Clone o repositório ou baixe os arquivos.
2. Abra `Aula-2/formulario.html` no navegador (duplo-clique) ou use uma extensão "Live Server" do VSCode para visualização ao vivo.
3. Teste a validação do campo email e responsividade redimensionando a janela.

---

## ✍️ Exemplo rápido: deixar "Júnior" selecionado por padrão
No HTML (radio de senioridade):
```html
<input type="radio" name="senioridade" id="junior" value="junior" checked>
<label for="junior">Júnior</label>
```

---

## 🛠️ Melhorias sugeridas
- Validação avançada com JavaScript
- Submissão para um backend (API)
- Melhorar acessibilidade (labels, aria-*)
- Tornar o layout ainda mais responsivo para celulares

---

## 🤝 Contribuições
Pull requests são bem-vindos! Se for contribuir, crie uma branch, faça as alterações e abra um PR explicando o que você mudou.

---

## 📜 Licença
MIT — sinta-se livre para usar e modificar.

---

## 👨‍💻 Autor
**Arthur Caetano** — https://github.com/arthur-ro
