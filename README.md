```javascript
<script>let sliders = document.querySelector('.slider');
    const prevBtn = document.querySelector('.prevBtn');
    const nextBtn = document.querySelector('.nextBtn');

    nextBtn.addEventListener('click', () => {
        sliders.scrollBy({ left: 200, behavior: 'smooth' });
    });

    prevBtn.addEventListener('click', () => {
        sliders.scrollBy({ left: -200, behavior: 'smooth' });
    });

</script>
```
