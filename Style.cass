// Cart Functionality
let cartCount = 0;
const cartCountElement = document.getElementById('cart-count');
const addToCartButtons = document.querySelectorAll('.add-to-cart-btn');

addToCartButtons.forEach(button => {
  button.addEventListener('click', () => {
    cartCount++;
    cartCountElement.textContent = cartCount;
    alert(`${button.dataset.name} added to cart!`);
  });
});
