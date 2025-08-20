# Protótipo: Fala → Texto → VLibras

Este projeto é um protótipo web que permite capturar sua fala, transcrever automaticamente para texto e utilizar o [VLibras](https://vlibras.gov.br/) para traduzir o conteúdo em Libras (Língua Brasileira de Sinais).

## Funcionalidades

- **Reconhecimento de fala**: Use o microfone para transcrever sua fala em tempo real (Web Speech API).
- **Integração com VLibras**: Traduza o texto transcrito para Libras usando o widget oficial do VLibras.
- **Interface intuitiva**: Botões para iniciar/parar captura e recarregar o texto para o VLibras.
- **Compatibilidade**: Funciona melhor no Chrome ou Edge, em ambiente seguro (`https://`) ou `localhost`.

## Como usar

1. Abra o arquivo [`index.html`](index.html) em seu navegador.
2. Clique em **Iniciar captura** e fale ao microfone.
3. Veja a transcrição em tempo real.
4. O texto transcrito aparece na área "Texto a ser traduzido pelo VLibras".
5. Clique no botão azul flutuante do VLibras para traduzir o conteúdo para Libras.

## Dicas

- O reconhecimento de fala está configurado para o idioma **pt-BR**.
- Para melhor funcionamento, utilize navegadores compatíveis e acesse via HTTPS ou localhost.
- Caso o VLibras não reconheça o texto, use o botão **Recarregar texto**.

## Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Web Speech API)**
- **VLibras Widget Oficial**

## Captura de tela

![Protótipo Fala → Texto → VLibras](https://vlibras.gov.br/assets/img/vlibras.png)

## Licença

Este projeto é apenas um protótipo educacional e utiliza o widget oficial do VLibras.

---

Feito com 💙 para
