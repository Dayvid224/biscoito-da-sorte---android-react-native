Aqui está um resumo simplificado do guia:

1. **Configuração Inicial**:
   - Certifique-se de configurar o ambiente React Native usando o [guia oficial](https://reactnative.dev/docs/set-up-your-environment).

2. **Iniciar Metro**:
   - Rode o servidor Metro (ferramenta de build) usando:
     ```sh
     npm start
     ```
     Ou:
     ```sh
     yarn start
     ```

3. **Construir e Executar o App**:
   - **Android**: Use `npm run android` ou `yarn android`.
   - **iOS**: Execute:
     ```sh
     bundle install
     bundle exec pod install
     npm run ios
     ```
     Ou `yarn ios`.

4. **Modificar o App**:
   - Faça alterações no arquivo `App.js` e veja as mudanças automaticamente com o [Fast Refresh](https://reactnative.dev/docs/fast-refresh).

