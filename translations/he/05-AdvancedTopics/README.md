<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "b96f2864e0bcb6fae9b4926813c3feb1",
  "translation_date": "2025-06-26T14:09:57+00:00",
  "source_file": "05-AdvancedTopics/README.md",
  "language_code": "he"
}
-->
# נושאים מתקדמים ב-MCP

פרק זה מיועד לכסות סדרת נושאים מתקדמים ביישום Model Context Protocol (MCP), כולל אינטגרציה מולטימודלית, סקלאביליות, שיטות עבודה מומלצות לאבטחה ואינטגרציה ארגונית. נושאים אלו חשובים לבניית אפליקציות MCP יציבות ומוכנות לפרודקשן, שיכולות לעמוד בדרישות מערכות AI מודרניות.

## סקירה כללית

השיעור הזה בוחן מושגים מתקדמים ביישום Model Context Protocol, תוך התמקדות באינטגרציה מולטימודלית, סקלאביליות, שיטות אבטחה מומלצות ואינטגרציה ארגונית. נושאים אלה חיוניים לבניית אפליקציות MCP ברמת פרודקשן שיכולות להתמודד עם דרישות מורכבות בסביבות ארגוניות.

## מטרות הלמידה

בסיום השיעור תוכל/י:

- ליישם יכולות מולטימודליות במסגרת MCP
- לתכנן ארכיטקטורות MCP סקלאביליות לתרחישי דרישה גבוהה
- ליישם שיטות אבטחה מיטביות התואמות לעקרונות האבטחה של MCP
- לשלב את MCP עם מערכות ופריימוורקים של AI ארגוני
- לאופטם ביצועים ואמינות בסביבות פרודקשן

## שיעורים ופרויקטים לדוגמה

| קישור | כותרת | תיאור |
|-------|---------|---------|
| [5.1 אינטגרציה עם Azure](./mcp-integration/README.md) | אינטגרציה עם Azure | למדו כיצד לשלב את שרת ה-MCP שלכם ב-Azure |
| [5.2 דוגמה מולטימודלית](./mcp-multi-modality/README.md) | דוגמאות מולטימודליות ב-MCP | דוגמאות לתגובות קול, תמונה ומולטימודליות |
| [5.3 דוגמת OAuth2 ב-MCP](../../../05-AdvancedTopics/mcp-oauth2-demo) | הדגמת OAuth2 ב-MCP | אפליקציית Spring Boot מינימלית המציגה OAuth2 עם MCP, הן כשרת הרשאות והן כשרת משאבים. מדגימה הנפקת טוקנים מאובטחת, נקודות קצה מוגנות, פריסת Azure Container Apps ואינטגרציה עם API Management. |
| [5.4 Root Contexts](./mcp-root-contexts/README.md) | הקשרים שורשיים | למדו עוד על הקשר שורשי ואיך ליישם אותם |
| [5.5 ניתוב](./mcp-routing/README.md) | ניתוב | למדו על סוגי ניתוב שונים |
| [5.6 דגימה](./mcp-sampling/README.md) | דגימה | למדו כיצד לעבוד עם דגימה |
| [5.7 סקיילינג](./mcp-scaling/README.md) | סקיילינג | למדו על סקיילינג |
| [5.8 אבטחה](./mcp-security/README.md) | אבטחה | אבטחו את שרת ה-MCP שלכם |
| [5.9 דוגמת חיפוש אינטרנטי](./web-search-mcp/README.md) | חיפוש אינטרנטי ב-MCP | שרת ולקוח Python MCP המשתלבים עם SerpAPI לחיפוש בזמן אמת באינטרנט, חדשות, מוצרים ושאלות ותשובות. מדגים תיאום כלים מרובים, אינטגרציה עם API חיצוני וטיפול שגיאות חזק. |
| [5.10 סטרימינג בזמן אמת](./mcp-realtimestreaming/README.md) | סטרימינג | סטרימינג של נתונים בזמן אמת הפך לקריטי בעולם מונחה הנתונים של היום, בו עסקים ואפליקציות זקוקים לגישה מיידית למידע לקבלת החלטות בזמן. |
| [5.11 חיפוש אינטרנט בזמן אמת](./mcp-realtimesearch/README.md) | חיפוש אינטרנט | חיפוש אינטרנט בזמן אמת - כיצד MCP משנה את חיפוש האינטרנט בזמן אמת באמצעות מתן גישה סטנדרטית לניהול הקשר בין דגמי AI, מנועי חיפוש ואפליקציות. |
| [5.12 אימות Entra ID עבור שרתי Model Context Protocol](./mcp-security-entra/README.md) | אימות Entra ID | Microsoft Entra ID מספק פתרון ניהול זהויות וגישה מבוסס ענן חזק, המסייע להבטיח שרק משתמשים ואפליקציות מורשים יוכלו לתקשר עם שרת ה-MCP שלכם. |

## הפניות נוספות

לקבלת המידע העדכני ביותר על נושאים מתקדמים ב-MCP, עיינו ב:
- [תיעוד MCP](https://modelcontextprotocol.io/)
- [מפרט MCP](https://spec.modelcontextprotocol.io/)
- [מאגר GitHub](https://github.com/modelcontextprotocol)

## נקודות מפתח

- יישומי MCP מולטימודליים מרחיבים את יכולות ה-AI מעבר לעיבוד טקסט
- סקלאביליות חיונית לפריסות ארגוניות וניתנת למענה באמצעות סקיילינג אופקי ואנכי
- אמצעי אבטחה מקיפים מגנים על הנתונים ומבטיחים בקרת גישה נאותה
- אינטגרציה ארגונית עם פלטפורמות כמו Azure OpenAI ו-Microsoft AI Foundry משפרת את יכולות ה-MCP
- יישומים מתקדמים של MCP נהנים מארכיטקטורות אופטימליות וניהול זהיר של משאבים

## תרגיל

תכנן/י יישום MCP ברמת ארגון עבור מקרה שימוש ספציפי:

1. זהה דרישות מולטימודליות למקרה השימוש שלך
2. פרט את בקרות האבטחה הדרושות להגנת נתונים רגישים
3. עצב ארכיטקטורה סקלאבילית שיכולה להתמודד עם עומסים משתנים
4. תכנן נקודות אינטגרציה עם מערכות AI ארגוניות
5. תעד צווארי בקבוק פוטנציאליים בביצועים ואסטרטגיות הפחתה

## משאבים נוספים

- [תיעוד Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
- [תיעוד Microsoft AI Foundry](https://learn.microsoft.com/en-us/ai-services/)

---

## מה הלאה

- [5.1 אינטגרציית MCP](./mcp-integration/README.md)

**כתב ויתור**:  
מסמך זה תורגם באמצעות שירות תרגום מבוסס בינה מלאכותית [Co-op Translator](https://github.com/Azure/co-op-translator). למרות שאנו שואפים לדיוק, יש לשים לב כי תרגומים אוטומטיים עלולים להכיל שגיאות או אי-דיוקים. יש להתייחס למסמך המקורי בשפת המקור כמקור הסמכותי. למידע קריטי מומלץ להשתמש בתרגום מקצועי על ידי מתרגם אנושי. אנו לא נושאים באחריות לכל אי-הבנה או פרשנות שגויה הנובעים משימוש בתרגום זה.