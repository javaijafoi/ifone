<div align="center">

# 📱 iFone

**O celular de mentira do mundo de #iHunt, para sortear coisas na mesa de RPG.**

O jogador "tira o celular do bolso", abre um app e ele sorteia um resultado:
um sofá para dormir, um médico que não faz perguntas, um contrato de caça.

[![Abrir no ar](https://img.shields.io/badge/%E2%96%B6%20abrir%20no%20ar-ifone--javaijafoi.vercel.app-ff2e88?style=for-the-badge)](https://ifone-javaijafoi.vercel.app)

![PWA](https://img.shields.io/badge/PWA-offline-5a0fc8?style=flat-square)
![HTML](https://img.shields.io/badge/HTML%20%2B%20JS-sem%20build-e34f26?style=flat-square)
![Feito para](https://img.shields.io/badge/feito%20para-%23iHunt%20(Fate)-ffd400?style=flat-square&labelColor=111)
![Projeto de fã](https://img.shields.io/badge/projeto%20de%20f%C3%A3-n%C3%A3o%20oficial-lightgrey?style=flat-square)

<img src="docs/img/punk.png" alt="Grade de apps do iFone no estilo Cartucho punk" width="230"> &nbsp;
<img src="docs/img/medja.png" alt="App MedJá sorteando um problema de saúde" width="230"> &nbsp;
<img src="docs/img/tijolao.png" alt="Estilo Tijolão, celular antigo de tela verde" width="230">

</div>

## 🎲 Como funciona

Cada app é uma tabela de sorteio com cara de aplicativo. Você escolhe o app, o iFone rola e mostra o resultado na hora, com direito a "sortear de novo" e "guardar" (fica salvo só no seu aparelho).

| App | Para que serve na mesa |
| --- | --- |
| 🛋️ **Sofah** | Achar um lugar para dormir |
| ➕ **MedJá** | Um médico que não faz perguntas (e quanto custa) |
| 💘 **Brinqr** | Encontros e contatos |
| ⛈️ **Tempest** | O tempo lá fora |
| 🎯 **#iHunt** | Contratos de caça |
| 💧 **Biopure** | Sangue e afins |
| 🔧 **WeTinker** | Gambiarras e consertos |

Os **pontos de destino** da mesa ficam na tela, para ajustar sem sair do app.

## 🎨 Dois estilos

- **Cartucho punk**: grade de apps em papel e tinta, com ícones em pixel art.
- **Tijolão**: celular antigo de tela verde, com teclado que funciona.

No computador aparece o aparelho inteiro. No celular fica só a tela.

## 🚀 Rodando

É um site estático, sem build. Abra o `index.html` ou sirva a pasta:

```sh
npx serve .
```

Funciona offline depois da primeira visita e pode ser instalado como app (PWA): é só usar "Adicionar à tela inicial" no navegador.

## 🧱 Tecnologias

HTML, CSS e JavaScript puros, service worker para o modo offline e `localStorage` para guardar os resultados salvos.

---

## 🌴 Mais do Peter

Este projeto faz parte do [**portfólio do Peter**](https://javaijafoi.vercel.app), uma vitrine de jogos, histórias interativas e experimentos com IA, todos no ar. Perfil no GitHub: [@javaijafoi](https://github.com/javaijafoi).

| Projeto | No ar | Código |
| --- | --- | --- |
| **Antigravitus**: Diário de aventuras num RPG de texto, jogado por agentes de IA | [abrir](https://antigravitus.vercel.app) | [repo](https://github.com/javaijafoi/antigravitus) |
| **Picotron Arena**: Dez modos de arcade num computador de fantasia | [abrir](https://picotron-arena.vercel.app) | [repo](https://github.com/javaijafoi/picotron-arcade) |
| **Jogo do Davi**: Jogo para crianças aprenderem a ler e a contar | [abrir](https://jogo-davi.vercel.app) | [repo](https://github.com/javaijafoi/Jogo-davi) |
| **Matusalém**: História interativa de mistério no Bixiga | [abrir](https://matusalem-six.vercel.app) | — |
| **Era Vargas: O Equilibrista**: Jogo 3D de decisões sobre o Brasil de 1930 a 1945 | [abrir](https://era-vargas-seliga.vercel.app) | [repo](https://github.com/javaijafoi/era-vargas-seliga) |
| **Pinta-Kara**: Desenhe no ar com as mãos, só com a webcam | [abrir](https://pinta-kara.vercel.app) | [repo](https://github.com/javaijafoi/pinta-kara) |
| **Rolador**: Dados para qualquer RPG de mesa, com cara de PICO-8 | [abrir](https://rolador-javaijafoi.vercel.app) | [repo](https://github.com/javaijafoi/rolador) |
| **Pico Poetry**: Poemas em pixel para sortear e compartilhar como imagem | [abrir](https://pico-poetry.vercel.app) | — |
| **#iHunt Chronicle**: Mesa virtual para o RPG #iHunt (em pausa) | [abrir](https://ihunt-chronicle.vercel.app) | — |
| **iHunt App**: Fork do Fari App (Fate) para mesas de #iHunt | — | [repo](https://github.com/javaijafoi/iHunt-app) |

---

Projeto de fã, sem vínculo com os autores de #iHunt.
Feito por [@javaijafoi](https://github.com/javaijafoi) · parte do [portfólio](https://javaijafoi.vercel.app).
