```python
# Привет! Я Соня 👩‍💻

class Developer:
    def __init__(self):
        self.name = "Соня"
        self.specialization = ["Machine Learning", "Android Development", "AI Automation"]
        self.current_focus = "Создание генеративных нейронных сетей и умных приложений"
        self.favorite_tech = ["TensorFlow", "Keras", "PyTorch", "Java", "Kotlin"]
        self.motto = "Кодить с умом и душой! 💡❤️"

    def about_me(self):
        return {
            "🤖 Проекты": [
                "Telegram-боты с AI",
                "Приложения с голосовым управлением",
                "Автоматизация повседневной жизни"
            ],
            "🎯 Миссия": "Создавать технологии, которые помогают людям",
            "🎸 Хобби": ["Рок-музыка", "Игры", "Творческое программирование"]
        }

    def contact(self):
        return {
            "Telegram": "https://t.me/ITgenius_l",
            "Email": "limorenkosona239@gmail.com"
        }

if __name__ == "__main__":
    me = Developer()
    print("Добро пожаловать на мой GitHub!")
    print("Исследуйте проекты и давайте творить вместе 🚀")
