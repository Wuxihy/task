# task
import random


class Student:
    def __init__(self, name):
        self.name = name
        self.progress = 0
        self.gladness = random.randint(20, 30)

    def rest(self):
        # Счастье растет, а прогресс уменьшается
        pass

    def study(self):
        # Прогресс растет, а счастье уменьшается
        pass


students = [
    Student("Andrey"),
    Student("Maxim"),
    Student("Stepan")
]

days = 1
progress_winner = None
gladness_winner = None
while True:
    print(f"Day {days}")
    for student in students:
        # Случайно выбираем отдыхает или учится студент
        # random.choice([])
        student
        # Проверяем прогресс студента
        # используем переменную для выхода
    days += 1
