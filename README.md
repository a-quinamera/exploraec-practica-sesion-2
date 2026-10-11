# Práctica — Sesión 2

ExploraEC. Curso MOD3: Desarrolla Aplicaciones Móviles Robustas con Flutter e IA. Desarrollo en Windows con Antigravity.

## Ejecutar

1. Instalar Flutter SDK y Docker Desktop para las sesiones 6–8. Añadir Flutter al PATH/configurar SDK en Antigravity.
2. Abrir `Sesion-2.code-workspace` en Antigravity.
3. Desde una terminal PowerShell de Antigravity, entrar en `exploraec` y ejecutar:

```powershell
flutter pub get
flutter run -d web-server --web-port 1718 
```

4. Abrir la dirección mostrada en Brave. También están conservadas las configuraciones de ejecución originales del editor. En web debe utilizarse localhost para geolocalización/almacenamiento seguro.
5. Para las pruebas del proyecto, ejecutar `flutter test` desde la carpeta de la app cuando contenga pruebas.

Se conserva `pubspec.lock` para resolver las mismas dependencias. `.dart_tool` y `build` se regeneran mediante Flutter. No se incluye APK precompilado ni se certifica ejecución en Android.

