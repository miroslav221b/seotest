# SEO Test Site

Тестовий сайт для лабораторної роботи з технічного SEO-аудиту ([Lab 01](https://github.com/olroi421/course-seo/blob/main/labs/lab-01.md)).

**Live URL:** https://miroslav221b.github.io/seotest/

## Увімкнення GitHub Pages (обовʼязково один раз)

Без цього кроку зʼявиться помилка *«There isn't a GitHub Pages site here»*.

1. Відкрийте: [github.com/miroslav221b/seotest/settings/pages](https://github.com/miroslav221b/seotest/settings/pages)
2. **Build and deployment → Source:** оберіть **GitHub Actions**
3. Збережіть. Після push у `main` workflow **Deploy GitHub Pages** опублікує сайт (1–3 хв).

**Альтернатива:** Source → **Deploy from a branch** → Branch `main`, Folder `/ (root)` → Save.

Перевірка: [miroslav221b.github.io/seotest/](https://miroslav221b.github.io/seotest/)

## Google Search Console

Після публікації додайте ресурс `https://miroslav221b.github.io/seotest/` і верифікуйте через HTML-файл або meta-тег.

Надішліть sitemap: `https://miroslav221b.github.io/seotest/sitemap.xml`

## Навмисні проблеми для аудиту

| Проблема | Приклад URL |
|----------|-------------|
| Биті посилання (404) | Посилання з головної на `/missing-page.html` |
| Ланцюг редиректів | `/redirect/step1.html` → step2 → step3 |
| Дублікат контенту | `/content/duplicate-a.html` та `duplicate-b.html` |
| Сторінка без title | `/issues/no-title.html` |
| Дубльовані title | Кілька сторінок з однаковим `<title>` |
| Зображення без alt | `/issues/images-no-alt.html` |
| Відсутній meta description | `/issues/no-description.html` |
| Дуже довгий title | `/issues/long-title.html` |
| Сторінка-сирота | `/orphan.html` (немає внутрішніх посилань) |
