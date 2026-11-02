<div dir="rtl">

# דרך כהנים

**ניווט חי לכהנים, באתר ובאפליקציית אנדרואיד.** המערכת מתכננת את הדרך כך שתעקוף בתי קברות ואזורים שכהן נמנע מהם, ומלווה את הנהג בהנחיות קוליות בעברית לכל אורך הנסיעה.

- 🌐 **אתר:** https://derech-kohanim.dinobycloud.com
- 📱 **אפליקציית אנדרואיד:** [הגרסה האחרונה להורדה](https://github.com/derech-kohanim/derech-kohanim-android/releases/latest)
- 🧪 **בדיקה סגורה ב-Google Play:** מצטרפים ל[קבוצת הבודקים](https://groups.google.com/g/derech-kohanim), ואז [מאשרים השתתפות](https://play.google.com/apps/testing/com.abaye.derechkohanim)

## מה המערכת עושה

- מסלולים שעוקפים את האזורים לפי שלוש רמות הקפדה: בסיסי, טהרת הכהנים ומחמירים.
- כשאין דרך לעקוף, אומרת את זה עוד לפני היציאה.
- ניווט פנייה אחר פנייה עם הנחיות קוליות, והתראה לפני התקרבות לאזור.
- עובדת גם ברשתות מסוננות (נטפרי) וממשיכה להדריך גם בלי קליטה.

## המאגרים

| מאגר | תיאור |
|------|--------|
| [derech-kohanim-android](https://github.com/derech-kohanim/derech-kohanim-android) | אפליקציית האנדרואיד (Kotlin, Jetpack Compose) |
| [derech-kohanim-web](https://github.com/derech-kohanim/derech-kohanim-web) | האתר (Vite, React, TypeScript) |
| [derech-kohanim-api](https://github.com/derech-kohanim/derech-kohanim-api) | השרת: חישוב ואימות מסלולים, חיפוש ומשתמשים (NestJS, PostGIS) |
| [derech-kohanim-shared](https://github.com/derech-kohanim/derech-kohanim-shared) | חוזה ה-API ושפת העיצוב המשותפים לכל הרכיבים |
| [derech-kohanim-data](https://github.com/derech-kohanim/derech-kohanim-data) | נתוני האזורים הגולמיים |

## רישיון

הקוד זמין לעיון ול**שימוש אישי חופשי, בחינם וללא הגבלה**. שימוש מסחרי או ציבורי, הפצה, פרסום פורק כפרויקט עצמאי, או שילוב רכיבים בפרויקט אחר (חינמי או בתשלום) דורשים אישור בכתב. הפרטים המלאים בקובץ `LICENSE` שבכל מאגר.

**נתוני האזורים** מקורם בהתאחדות טהרת הכהנים, וכל הזכויות בהם שמורות לה. רישיון הקוד אינו חל עליהם.

## יצירת קשר

דיווחים ומשוב אפשר לשלוח מתוך האפליקציה או האתר, או במייל cs@abaye.co.

> המערכת היא כלי עזר לתכנון הדרך ואינה תחליף לשאלת רב.

</div>

---

# Derech Kohanim

**Live navigation for Kohanim, on the web and on Android.** The system plans routes that avoid cemeteries and other sites a Kohen must not pass near, and guides the driver with spoken Hebrew instructions throughout the drive.

- 🌐 **Website:** https://derech-kohanim.dinobycloud.com
- 📱 **Android app:** [latest release](https://github.com/derech-kohanim/derech-kohanim-android/releases/latest)
- 🧪 **Google Play closed testing:** join the [testers group](https://groups.google.com/g/derech-kohanim), then [opt in](https://play.google.com/apps/testing/com.abaye.derechkohanim)

## What it does

- Routes that avoid the zones at three stringency levels.
- Tells you before you leave when no clean route exists.
- Turn-by-turn navigation with voice guidance and alerts before approaching a zone.
- Works on filtered networks (NetFree) and keeps guiding without reception.

## Repositories

| Repository | Description |
|------------|-------------|
| [derech-kohanim-android](https://github.com/derech-kohanim/derech-kohanim-android) | Android app (Kotlin, Jetpack Compose) |
| [derech-kohanim-web](https://github.com/derech-kohanim/derech-kohanim-web) | Website (Vite, React, TypeScript) |
| [derech-kohanim-api](https://github.com/derech-kohanim/derech-kohanim-api) | Server: route computation and validation, search, users (NestJS, PostGIS) |
| [derech-kohanim-shared](https://github.com/derech-kohanim/derech-kohanim-shared) | API contract and design language shared by all components |
| [derech-kohanim-data](https://github.com/derech-kohanim/derech-kohanim-data) | Raw zone data |

## License

The code is source-available and **free for personal use, without restriction**. Commercial or public use, redistribution, publishing a fork as a standalone project, or incorporating components into another project (free or paid) requires written permission. See the `LICENSE` file in each repository.

**Zone data** originates from Hitachdut Taharat HaKohanim, which holds all rights to it. The code license does not apply to it.

## Contact

Send reports and feedback from within the app or the website, or email cs@abaye.co.

> This system is a route-planning aid and does not replace consulting a rabbi.
