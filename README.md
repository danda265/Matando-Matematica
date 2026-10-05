# Matando-Matematica
jogo de cálculo# ⚡ 

## 🎮 Sobre o Jogo

** Matando á Matematica ** é um jogo espacial onde aliens invadem a tela carregando contas matemáticas. O aluno deve digitar a resposta correta para que a nave dispare um raio laser e destrua o inimigo!

Desenvolvido para ser usado em sala de aula como ferramenta lúdica de fixação de conteúdo matemático.

---

## 🚀 Como Jogar

1. O professor digita o **nome do aluno** e escolhe o **ano escolar**
2. Clique em **INICIAR MISSÃO**
3. Um alien desce com uma conta matemática escrita abaixo dele
4. Use o **teclado numérico** ou os **botões na tela** para digitar a resposta
5. Clique em **CONFIRMAR** (ou pressione **Enter**)
6. ✅ Acertou → laser dispara e explode o alien, pontos somados
7. ❌ Errou → perde uma vida
8. O jogo termina ao perder as **3 vidas**

---

## 📚 Conteúdo por Ano Escolar

| Ano | Conteúdo |
|-----|----------|
| 1° | Adição até 10, dobros, incógnita simples |
| 2° | Adição e subtração até 20, dezenas |
| 3° | Tabuada de 1 a 5, operações até 100 |
| 4° | Tabuada completa, divisão, dobro e metade |
| 5° | Multiplicação maior, frações, potência |
| 6° | Potência, raiz quadrada, porcentagem, negativos |
| 7° | Frações com denominadores diferentes, equações simples |
| 8° | Equações 1° grau, Pitágoras, potência de 2 |
| 9° | Equações 2° grau, progressões, função afim |

---

## 🕹️ Controles

| Ação | Teclado | Tela |
|------|---------|------|
| Digitar resposta | Teclas 0–9 | Botões numéricos |
| Confirmar | Enter | Botão CONFIRMAR |
| Apagar | Backspace | Botão ⌫ APAGAR |
| Negativo (7°-9°) | `-` | Botão +/- |
| Voltar ao menu | — | Botão ⬅ MENU |

---

## 🌐 Acesso Online

O jogo roda diretamente no navegador, sem instalação:

**👉 [matematica.educajogo.com.br](https://matematica.educajogo.com.br/)**

Compatível com computadores, tablets e celulares.

### Demonstração e jogo completo

O mesmo endereço abre duas versões:

- **Demonstração**, para quem não tem código de turma: 1° e 2° ano livres; do 3° ao 9° aparecem com cadeado e uma tela de venda.
- **Jogo completo**, para quem entrou com o código da turma (serviço `educajogo-acesso`): os 9 anos.

O que é do jogo completo fica no `index.html` entre `/*COMPLETO*/` e `/*/COMPLETO*/` (os anos 3 a 9 do `curriculum`). Quem monta o site (`publicar_jogo.py`, na pasta Projetos, fora deste repositório) tira esses trechos da demonstração, coloca a tela de venda, gera o completo em `_full/` e confere que nada do que é pago ficou na demonstração. Abrindo o `index.html` direto no navegador você joga o completo, porque a tela de venda só entra na montagem do site.

---

## 🛠️ Tecnologias

- **HTML5** puro — sem frameworks ou dependências
- **Canvas API** para animações do espaço, nave e aliens
- **CSS3** com animações e efeitos neon
- **JavaScript** vanilla

---

## 📁 Estrutura do Projeto

```
math-commander/
│
└── index.html       ← jogo completo (arquivo único)
```

---

## ✏️ Como Personalizar

Abra o `index.html` em qualquer editor de texto (ex: Bloco de Notas, VS Code):

- **Mudar velocidade dos aliens** → procure por `ALIEN_SPEED` e altere o valor (padrão: `40`)
- **Mudar número de vidas** → procure por `lives:3` no estado inicial
- **Adicionar questões** → cada ano tem sua seção no objeto `curriculum`

---

## 👨‍🏫 Uso em Sala de Aula

**Sugestões:**
- Projetar na lousa e os alunos respondem em voz alta
- Cada aluno jogar individualmente no computador/tablet
- Competição entre turmas pelo maior score
- Usar como revisão antes de provas

---

## 👤 Criador

**Anderson Rodrigo Costa**

Desenvolvido com fins educacionais para escolas do Ensino Fundamental.

---

## 📄 Licença

Uso livre para fins educacionais. ✔️
[README.md](https://github.com/user-attachments/files/26422923/README.md)
s do 1º ao 9º ano 
