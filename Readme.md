<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">

  [Descrição do desafio](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-react-native)
</h3>

---

## ⚙ Tecnologias utilizadas

  - React Native
  - styles-components
  - react-native-vector-icons
  - @react-native-community/async-storage
  - @react-navigation
  - json-server
  - Context API

## 💻 Instruções para executar o projeto

```bash
  # clonando o repositório
  git clone https://github.com/AugustoMarcelo/fundamentos-react-native.git

  # acessando a pasta
  cd go-marketplace

  # realizando o download das dependências
  yarn

  # inicializando o servidor fake de produtos
  yarn json-server server.json -p 3333

  # proxy reverso
  adb reverse tcp:3333 tcp:3333

  # executando aplicação no dispositivo
  yarn react-native
  yarn android
  yarn ios
```

## 📸 Preview

<h1 align="center">
  <img height="600" src="https://user-images.githubusercontent.com/11545976/80264263-f5b21c00-8669-11ea-9850-9fd51048db2c.gif">
</h1>
