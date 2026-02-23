# Itach Finance (PWA)

אפליקציית ווב סטטית לניהול כלכלי משפחתי, מותאמת מובייל (RTL), עובדת אופליין (PWA) ושומרת נתונים מקומית (IndexedDB).

## קבצים
- `index.html` – כל האפליקציה (HTML+CSS+JS)
- `service-worker.js` – קבצי קאש לעבודה אופליין
- `manifest.webmanifest` – פרטי PWA + אייקונים
- `icons/icon-192.png`, `icons/icon-512.png` – אייקונים למסך הבית

## פריסה ל-GitHub Pages
1. צור ריפו פומבי חדש, למשל `itach-finance`.
2. העלה את הקבצים והתיקיות כפי שהם (כולל תיקיית `icons`).
3. ב-Settings → Pages: Source = Deploy from a branch, Branch = main, Folder = root.
4. קבל את ה-URL: `https://USERNAME.github.io/itach-finance/`.
5. ב-iPhone: פתח ב-Safari → Share → Add to Home Screen.

*עדכון גרסה*: אם אינך רואה שינויים, הוסף פרמטר `?v=2` לכתובת ה-URL כדי לעקוף Cache.
