# ⬡ VoidClient — Minecraft Launcher

Krasser Minecraft Launcher mit Mod Manager, Microsoft Login und direktem Minecraft Start.

## 🚀 Setup (einmalig)

1. **Node.js** installieren: https://nodejs.org (LTS Version)
2. Diesen Ordner irgendwo auf deinem PC speichern (z.B. `C:\VoidClient`)
3. CMD im Ordner öffnen (Shift + Rechtsklick → "In Terminal öffnen")
4. Pakete installieren:
```
npm install
```

## ▶ Starten (zum Testen)
```
npm start
```

## 📦 .EXE bauen (Windows Installer)
```
npm run build
```
Die fertige `.exe` liegt dann in: `dist/VoidClient Setup 2.0.0.exe`

## Was der Client kann:
- ✅ Microsoft Account Login (echter Mojang Login)
- ✅ Minecraft starten (alle Versionen)
- ✅ Mod Manager mit Modrinth Suche
- ✅ Mods herunterladen & löschen  
- ✅ RAM einstellen
- ✅ Custom Titlebar (kein Windows-Standard)
- ✅ Dein Lila Void Design 🟣

## Minecraft Daten:
Alles liegt in `%AppData%\.voidclient`
