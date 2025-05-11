
# MiBandBLE

Projeto de aplicativo mobile desenvolvido com React Native e Expo, com integração via Bluetooth Low Energy (BLE) para comunicação com a pulseira Mi Band 8. Este projeto faz parte do trabalho final de curso (Projeto Integrador) da UNIVESP em 2025.

## Objetivo

Monitorar e interagir com dados da Mi Band 8 por meio de conexão Bluetooth, possibilitando funcionalidades como:

- Conexão BLE com dispositivos próximos
- Coleta de informações relevantes da pulseira (como batimentos ou movimento)
- Potencial uso em detecção de quedas para idosos

## Tecnologias Utilizadas

- React Native
- Expo
- react-native-ble-plx – biblioteca para integração BLE
- react-native-permissions
- expo-build-properties
- Android SDK + JDK 17/21 via Eclipse Adoptium

## Permissões

O app requer as seguintes permissões para funcionar corretamente:

### Android

- BLUETOOTH_SCAN
- BLUETOOTH_CONNECT
- ACCESS_FINE_LOCATION

### iOS

- BLUETOOTH_ALWAYS
- LOCATION_WHEN_IN_USE

## Como rodar

1. Clone o repositório:
   ```
   git clone https://github.com/Mutekii/Pi2025.git
   cd Pi2025
   ```

2. Instale as dependências:
   ```
   npm install
   ```

3. Execute no modo desenvolvimento:
   ```
   npx expo start
   ```

4. Para rodar no emulador Android:
   ```
   npx expo run:android
   ```

Certifique-se de que o `org.gradle.java.home` está corretamente configurado no `app.config.js` ou `app.json`, apontando para a JDK correta.

## Estrutura do Projeto

```
Pi2025/
├── assets/
├── android/
├── ios/
├── src/
│   └── components/
│   └── screens/
├── App.js
├── app.json
├── package.json
└── README.md
```

## Licença

Este projeto é de uso acadêmico e não possui uma licença de distribuição definida no momento.

Desenvolvido 
THIAGO DOS SANTOS RIBEIRO, 2213909
MIHAEL FERNANDO SANSONI, RA:2109862
RAPHAEL LUIZ DE FREITAS, RA: 1809613
CLAYTON SACILOTTI RIBEIRO DOS SANTOS, RA:2009496 

