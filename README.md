# SEO Test Site

Тестовий сайт для лабораторної роботи з технічного SEO-аудиту ([Lab 01](https://github.com/olroi421/course-seo/blob/main/labs/lab-01.md)).

**Live URL:** https://miroslav221b.github.io/seotest/

## Увімкнення GitHub Pages

1. Репозиторій → **Settings** → **Pages**
2. **Source:** Deploy from branch `main`, folder `/ (root)`
3. Зберегти — сайт буде доступний через 1–2 хвилини

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
