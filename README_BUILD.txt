BUTZ KONFIGURATOR – ANDROID / GITHUB BUILD

1. Diese ZIP entpacken.
2. Ein LEERES GitHub-Repository erstellen.
3. Den INHALT dieses Ordners hochladen – nicht die ZIP selbst.
4. Im Repository müssen direkt sichtbar sein:
   - app/
   - build.gradle
   - settings.gradle
   - gradle.properties
   - .github/
5. Nach dem Upload: Actions -> Build Android APK -> Run workflow.
6. Nach einem grünen Build den Lauf öffnen.
7. Unter "Artifacts" -> "Butz-Konfigurator-APK" herunterladen.
8. ZIP des Artifacts entpacken -> Butz-Konfigurator.apk auf Android installieren.

Wichtig:
- build.gradle im Hauptordner enthält die Android-Plugin-Version 8.7.3.
- app/build.gradle enthält KEINE zweite Plugin-Version.
- Der Workflow sucht das Gradle-Projekt automatisch, falls beim Upload doch ein Unterordner entstanden ist.
