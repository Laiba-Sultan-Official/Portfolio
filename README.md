# 🌌 Cosmic Portfolio

A visually engaging and interactive portfolio website inspired by cosmic themes. This project showcases different work categories with smooth animations and a sleek, responsive design. Built with modern HTML, CSS, and JavaScript.

---

## 🚀 Features

- 🌠 Category-based project filtering  
- ✨ Smooth animations and transitions  
- 💫 Active state highlights  
- 🌍 Fully responsive layout  
- 🔭 Simple, clean design with cosmic aesthetics  

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- Vanilla JavaScript  

---

## 🧩 How It Works

```javascript
item.addEventListener('click', function() {
  categoryItems.forEach(cat => {
    cat.classList.remove('active');
    cat.style.transform = 'translateX(0)';
  });

  this.classList.add('active');
  this.style.transform = 'translateX(8px)';

  filterProducts(this.textContent.trim());
});
