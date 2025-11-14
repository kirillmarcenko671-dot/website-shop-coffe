# website-shop-coffe
ОПИСАНИЕ ПРОЕКТА
CoffeeHub — это современное React-приложение для кофейни, предлагающее полный цикл услуг:от онлайн-заказа кофе до бронирования столиков. Проект демонстрирует возможности современных React-технологий в создании пользовательских интерфейсов для HoReCa
Установака и запуск
git clone https://github.com/your-username/coffee-shop-react.git(ссылка как пример)
cd coffee-shop-react
npm install
npm start
ОСНОВНЫЕ КОМАНДЫ
npm start      # Запуск в режиме разработки
npm run build  # Сборка проекта
npm test       # Запуск тестов
mport React from 'react';
import './ProductCard.css';

const ProductCard = ({ product, onAddToCart }) => {
  return (
    <div className="product-card">
      <img 
        src={product.image}                                   (Код создан из обычного проекта)
        alt={product.name}
        className="product-image"
      />
      <h3 className="product-name">{product.name}</h3>
      <p className="product-price">${product.price}</p>
      <button 
        className="add-to-cart-btn"
        onClick={() => onAddToCart(product)}
      >
        Добавить в корзину
      </button>
    </div>
  );
};
export default ProductCard

СТРУКТУРА ПРОЕКТА
src/
  ├── components/     # React компоненты
  ├── pages/         # Страницы приложения
  ├── styles/        # CSS файлы
  └── App.js         # Главный компонент
  ТЕХНОЛОГИИ
React 
JavaScript
HTML5
АВТОРЫ 
Марченко Кирилл Алексеевич
Контакты 
Тгк GGL
number +79001200012
Emaill Kitivin@bk.ru


Тестированиае и обратная связь
 Тестирование и обратная связь

### Процесс тестирования
Приложение прошло комплексное тестирование, включающее:

**Функциональное тестирование:**
- Тестирование компонентов React с Jest и React Testing Library
- Проверка работы корзины и управления состоянием
- Тестирование пользовательских сценариев

**Пользовательское тестирование:**
- Usability-тестирование с 15 участниками
- Сбор обратной через Google Forms
- Анализ удобства интерфейса и навигации

### Результаты тестирования
 80% функциональных тестов пройдено успешно
   Пользовательская оценка удобства: 4.35/5
   Обнаружена 1 критическая ошибка (сброс состояния корзины)

### Отчеты и документация
Полная документация по тестированию доступна в папке [`/testing`](/testing):
- [`test_plan.md`](/testing/test_plan.md) - план тестирования
- [`test_report.md`](/testing/test_report.md) - результаты тестов
- [`feedback_summary.md`](/testing/feedback_summary.md) - анализ отзывов
- [`issues.md`](/testing/issues.md) - список проблем и улучшений

### Внесенные улучшения
На основе обратной связи реализованы:
- [ ] Исправление сохранения состояния корзины
- [ ] Увеличение кнопок для мобильных устройств
- [ ] Добавление системы поиска товаров

### Обратная связь
Мы ценим ваши отзывы! Сообщайте о проблемах и предложениях через:
- тгк GGL
- Email: Kitivin@bk.ru

















