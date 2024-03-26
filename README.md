## Comandi util per il front con Angular:
Certamente, ecco alcuni comandi utili per lavorare con Ionic:

1. **Aggiungere una piattaforma (es. iOS o Android) al progetto:**
   ```
   ionic cap add ios
   ionic cap add android
   ```

2. **Sviluppare localmente l'applicazione:**
   ```
   ionic serve
   ```

3. **Compilare l'applicazione per una piattaforma specifica:**
   ```
   ionic build
   ionic build ios
   ionic build android
   ```

4. **Aprire il progetto in Xcode o Android Studio (dopo aver aggiunto la piattaforma):**
   ```
   ionic cap open ios
   ionic cap open android
   ```

5. **Sincronizzare le modifiche con la piattaforma selezionata:**
   ```
   npx cap sync ios
   npx cap sync android
   ```

6. **Aggiornare le dipendenze di Capacitor (dopo aver aggiunto plugin o modificato le risorse):**
   ```
   npx cap update
   ```

7. **Eseguire l'applicazione su un emulatore o dispositivo:**
   ```
   npx cap run ios
   npx cap run android
   ```
