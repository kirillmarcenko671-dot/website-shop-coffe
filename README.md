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
