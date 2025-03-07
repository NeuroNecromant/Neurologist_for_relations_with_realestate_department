Нейро-менеджер на Python с использованием LangChain и OpenAI
---

<strong>Задача:</strong> Разработать систему поддержки для агентов недвижимости и рекрутеров, которая использует возможности языковых моделей для предоставления ответов на вопросы и обработки информации из документов. 
Система позволяет пользователям получать точные и развернутые ответы на основе загруженных документов.

<strong><a href="https://github.com/NeuroNecromant/Neurologist_for_relations_with_realestate_department" target="_blank">Ссылка на код</a></strong>

<strong>Что сделано:</strong>

🔸 Разработка класса GPT, который управляет взаимодействием с языковыми моделями OpenAI и векторной базой данных Chroma для поиска и обработки документов.

🔸 Реализация функционала для загрузки текстовых документов из Google Docs и их векторизации для дальнейшего использования.

🔸 Поддержка различных сценариев, включая:

    • Ответы на вопросы агентов недвижимости о клиентах и сделках.
 
    • Генерация вопросов для собеседований на должность руководителя отдела продаж.
 
    • Заполнение отчетов на основе диалогов преподавателей с родителями учеников.
 
    • Анализ потребностей клиентов на основе записей диалогов.
  
🔸 Создание интерактивного интерфейса с использованием библиотеки Gradio для удобного взаимодействия с пользователями.

🔸 Логирование процессов и использование токенов для эффективного управления запросами к языковым моделям.

<strong>Используемые технологии:</strong>

🔸 Python и библиотеки LangChain и OpenAI для создания системы поддержки.

🔸 Gradio для создания пользовательского интерфейса.

🔸 Чтение и обработка документов из Google Docs для загрузки обучающих материалов.

🔸 Chroma для хранения и поиска векторных представлений текстов.

🔸 Технология обработки текста для подсчета токенов и оптимизации использования языковых моделей.

<strong>Как пользоваться:</strong>

🔻 Для начала работы с системой, запустите скрипт и откройте веб-интерфейс Gradio.

🔻 В выпадающем меню выберите нужный сценарий работы с системой (например, поддержку агентов недвижимости или рекрутеров).

🔻 Введите свой запрос в текстовое поле и нажмите кнопку для получения ответа.

🔻 При необходимости загрузите новый документ для обучения системы, используя соответствующую кнопку.

🔻 Получите ответ от языковой модели и просмотрите лог выполнения для дополнительной информации о процессе.

Этот проект предоставляет мощный инструмент для поддержки специалистов в их повседневной работе, автоматизируя и упрощая доступ к информации.
