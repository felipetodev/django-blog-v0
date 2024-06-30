# Fullstack Blog App

Django + Next.js Blog App ✨

## 🛠️ Stack

- [**Django**](https://www.djangoproject.com/) - A high-level Python Web framework that encourages rapid development and clean, pragmatic design.
- [**Django Rest Framework**](https://www.django-rest-framework.org/) - A powerful and flexible toolkit for building Web APIs.
- [**Django CORS Headers**](https://pypi.org/project/django-cors-headers/) - A Django application for handling the server headers required for Cross-Origin Resource Sharing (CORS).
- [**Next.js**](https://nextjs.org/) - The React Framework for Production.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript with syntax for types.
- [**Tailwindcss**](https://tailwindcss.com/) - A utility-first CSS framework for rapidly building custom designs.
- [**shadcn/ui**](https://ui.shadcn.com/) - Customizable design system components.

## 🚀 Getting Started

You will need:

- [Python 3.10+](https://www.python.org/downloads/)
- [Node.js 18+ (LTS)](https://nodejs.org/en/download/package-manager)

1. [Clone](https://github.com/felipetodev/django-blog) this repository:

```bash
git clone https://github.com/felipetodev/django-blog.git

2. Install dependencies:

```bash
# Django
cd backend
pip install -r requirements.txt

# Next.js
cd frontend
npm install
```

3. Run the development server:

```bash
# Django
cd backend/blog_project
python manage.py makemigrations blog
python manage.py migrate
python manage.py runserver

# Next.js
cd frontend
npm run dev
```

4. You can access the Django API at `http://localhost:8000/api/posts/` and the Next.js app at `http://localhost:3000/`.

## Features

- [x] Create, Read, Update, Delete Posts (API)
- [x] Pagination
- [x] Dark Mode
- [x] Responsive Design
- [x] Content revalidation
- [x] SSR
- [x] SSG
- [x] ISG
- [x] Dynamic Routes + Static Paths
- [x] Redirects
- [x] Server Actions
- [x] Error Handling

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
