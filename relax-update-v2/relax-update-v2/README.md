# Relax update — Resume Fit + Tailor

Overwrite into `lava295/first-app` and push `main`:

```
app/src/main/AndroidManifest.xml
app/src/main/java/app/relax/MainActivity.kt
app/src/main/java/app/relax/Engine.kt
app/src/main/java/app/relax/Alerts.kt
app/src/main/java/app/relax/Resume.kt          ← NEW
app/src/main/res/xml/file_paths.xml           ← NEW
app/src/main/res/drawable/ic_launcher_foreground.png
app/src/main/res/mipmap-*/…
app/src/main/res/values/colors.xml
```

## Resume Fit (offline, honest)

1. Open **Resume** tab → Upload PDF or DOCX (text-based).
2. Skills + bullets are extracted and stored on-device only.
3. On any job card tap **Fit** (or Quick fit on Resume tab).
4. See score 0–100, matched vs missing keywords.
5. Get tailored headline / summary / bullets that **only rephrase your real work** with JD vocabulary you already own.
6. Missing JD skills are listed but **never invented**.
7. **Share tailored resume** → text file via system share sheet.

No API key. No cloud. No hallucinated experience.
