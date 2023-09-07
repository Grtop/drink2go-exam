# drink2go-exam


# сейчас работает только на **16** node!!!

## Набор инструментов для проверки проекта грейдирования

### Подготовка 
- установите зависимости `npm install`
- создайте скриншоты эталонного проекта `npm run reference` (процесс займет 5-10 минут)
- скриншоты сохраняются в папке `backstop_data/bitmaps_reference`
- положите проект для проверки в папку `project`
- соберите проект и запустите сервер командой `npm run preview`
- проверьте, что проект собран и открывается в браузере http://localhost:3000
- сервер со студенческим проектом должен быть запущен, откройте новый терминал 
- запускайте отдельные тесты командами `npm run test-03`
- отчет о проверке откроется в браузере
- файл отчета сохранен в `backstop_data/html_report/index.html`

### Этап тестирования
- `npm run test-06` **HTML2-Б11** служит для проверки PixelPerfect на разных разрешениях
- `npm run test-ff` **HTML1-TEST-01** покажет отображение проекта в FireFox
- `npm run test-03` **HTML1-TEST-03** показывает поведение на широком / узком экране
- `npm run test-05` **HTML1-TEST-05** показывает базовые текстовые стили
- `npm run test-08` **HTML1-TEST-08** покажет элементы, которые изменяют размеры при взаимодействии
- `npm run test-07` **HTML1-TEST-07** показывает состояния интерактивных элементов
- `npm run html-04` **HTML1-HTML-04** проверит отправку форм
- `npm run test-logo` **HTML2-Б19** покажет адаптацию логотипа
- `npm run test-swiper` **JS1-Б1** покажет поведение слайдера
- `npm run test-menu` **JS1-Б1** покажет поведение меню

### Проверка кода
- `npm run linthtml` **HTML1-PROJ-01** покажет ошибки html
- `npm run stylelint` **HTML1-PROJ-01** покажет ошибки sass
- `npm run bemlinter` **HTML2-Б5** покажет ошибки BEM
- `npm run w3c` **HTML1-HTML-07** Валидация HTML
- `npm run lint-js` **JS1-Б11** покажет ошибки js

# Вспомогательные инструменты для ручной проверки наставником

### Этап ревью
- `npm run test-04` **HTML1-TEST-04** показывает переполнение / недополнение элементов
- `npm run img-01` **HTML1-IMG-01** покажет контентные / декоративные изображения
- `npm run html-03` **HTML1-HTML-03** покажет набор ссылок и кнопок
