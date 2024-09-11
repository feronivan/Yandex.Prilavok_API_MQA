## API приложения  “Яндекс.Прилавок”. Проект по ручному тестированию.
Яндекс.Прилавок — приложение для заказа продуктов.

## Задачи:
Добавлена новая функциональность в API Яндекс.Прилавка:
1. Работа с наборами:
   - возможность добавлять продукты в набор — ручка POST `/api/v1/kits/:id/products`.
2. Работа с курьерами:
   - возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит. Ручка POST `/fast-delivery/v3.1.1/calculate-delivery.xml`. 
4. Работа с корзиной:
   - возможность получить список продуктов, которые добавили в корзину. Ручка GET `/api/v1/orders/:id`;
   - возможность добавлять продукты в корзину. Ручка PUT `/api/v1/orders/:id`;
   - возможность удалять корзину. Ручка DELETE `/api/v1/orders/:id`.

[Ссылка на требования к бэкенду](https://praktikum.notion.site/8c91f759cb834ef2aa23db9d803a6373?pvs=4).

## Проделанная работа:
1. Проанализированы требования.
2. Cоставлен [чек-лист](https://docs.google.com/spreadsheets/d/1HGI7htvUf3pSkFEhyLg8QFcVcLrbJQ3VUZSGofD0eCc/edit?usp=sharing).
3. Выполнено тестирование с использованием Postman.
4. Заведены [баг-репорты](https://veronivan.youtrack.cloud/issues?q=tag:%20API).

## Инструменты
<p align="left"> 
  <a href="https://docs.google.com/" target="_blank" rel="noreferrer"><img src="https://github.com/user-attachments/assets/4fee6efd-dd5a-4c90-95f6-6aafc54ed88d" width="26" height="36" alt="Google Sheets" /></a>
  <a href="https://www.notion.so/" target="_blank" rel="noreferrer"><img src="https://github.com/user-attachments/assets/61293e5c-b3ba-4c32-8777-d74dbb8b26a0" width="36" height="36" alt="Notion" /></a>
  <a href="https://www.postman.com/" target="_blank" rel="noreferrer"><img src="https://seeklogo.com/images/P/postman-logo-0087CA0D15-seeklogo.com.png" title="postman" width="36" height="36" alt="Postman" /></a>
  <a href="https://www.jetbrains.com/youtrack/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/9/95/YouTrack_Icon.png" width="36" height="36" alt="Youtrack" /></a>
</p> 
