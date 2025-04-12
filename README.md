# 📝 MyBlog - A Django Blogging Platform

MyBlog is a simple, extensible blog platform built using Django. It features post creation, user authentication, and a responsive UI using Bootstrap.

## 🚀 Getting Started

Follow these steps to run the project locally on your machine.

---

## 📦 Clone the Repository

```bash
git clone https://github.com/your-username/myblog.git
cd myblog
```

---

## 🧪 Set Up a Virtual Environment

Use Python's built-in venv module to isolate project dependencies.

```bash
# Create a virtual environment named 'env'
python -m venv env

# Activate the environment
# Windows
env\Scripts\activate

# macOS/Linux
source env/bin/activate
```

---

## 📥 Install Dependencies

Install all the required packages listed in `requirements.txt`.

```bash
pip install -r requirements.txt
```

> If you run into issues, make sure you're using Python 3.8 or higher.

---

## ⚙️ Environment Configuration

If needed, create a `.env` file in the project root to define environment variables:

```env
DEBUG=True
SECRET_KEY=your-secret-key
ALLOWED_HOSTS=127.0.0.1,localhost
```

Then, load it in `settings.py` using `python-decouple` or `os.environ`.

---

## 🛠 Apply Database Migrations

Run the following commands to set up the database:

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## 👤 Create a Superuser (Optional)

To access the Django admin interface:

```bash
python manage.py createsuperuser
```

---

## ▶️ Run the Development Server

Start the local server:

```bash
python manage.py runserver
```

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser to view the application.

---

## 📁 Project Structure

```
myblog/
├── blog/               # Django app for blog features
├── myblog/             # Project configuration
├── templates/          # HTML templates
├── static/             # Static files (CSS, JS, etc.)
├── manage.py           # Management script
├── requirements.txt    # Project dependencies
└── README.md
```

---

## 🛡 License

This project is licensed under the MIT License. See `LICENSE` for more details.

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📫 Contact

Maintained by [Your Name](mailto:your.email@example.com)

GitHub: [github.com/your-username](https://github.com/your-username)
