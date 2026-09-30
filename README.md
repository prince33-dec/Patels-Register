# Patel's Register Website

A responsive static landing page for the Patel's Register Android app with an APK-only download flow.

## 1. APK download

The website now shows only APK download actions. GitHub/repository links are not displayed anywhere on the website.

## 2. Publish with GitHub Pages

1. Push `index.html` and `style.css` to the repository.
2. Open GitHub → **Settings** → **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select your main branch and `/ (root)`.
5. Save.
6. GitHub will give you a Pages address.

## 3. Recommended repository structure

/
├── index.html
├── style.css
└── README.md

Your APK can remain in **GitHub Releases**. It does not need to be stored in the website folder.

## Content source

The landing page is based on the supplied Patel's Register operator manual. The manual describes staff management, attendance, overtime, loans/advances, payroll calculations, salary sharing, PDF reports, and offline backup/restore.


## User Manual PDF

The supplied operator manual is included as:

`Patels-Register-Operator-Manual.pdf`

The website links to it from the **How to Use** section and the quick manual link near the hero.
It downloads locally from the website, so you do not need a GitHub link on the page.
