# גלגל השאלות

אתר סטטי בקובץ אחד (`index.html`). לוחצים על הגלגל ומקבלים שאלה.

## העלאה ל-GitHub Pages
1. יוצרים ריפוזיטורי חדש בשם `question-wheel` ומעלים אליו את `index.html`.
2. נכנסים ל-Settings, ואז Pages.
3. בקטע Build and deployment בוחרים Deploy from a branch, ענף `main` ותיקייה `/ (root)`, ולוחצים Save.
4. אחרי דקה בערך האתר זמין בכתובת `https://<שם-המשתמש>.github.io/question-wheel/`.

## שינוי שאלות
פותחים את `index.html` ומחפשים את `var DEFAULTS = [`. כל שורה ברשימה היא שאלה אחת.

## העלאה ל-Railway
1. ב-Railway: New Project ← Deploy from GitHub repo ← בוחרים `question-wheel`.
2. Railway מזהה את `package.json` ומריץ `npm start` (שרת סטטי על הפורט ש-Railway נותן).
3. ב-Settings ← Networking לוחצים Generate Domain כדי לקבל לינק ציבורי.
