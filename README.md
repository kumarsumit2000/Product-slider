![Alt text]([https://github.com/kumarsumit2000/NumberGuess/blob/main/Screenshot%202024-07-26%20204933.png](https://raw.githubusercontent.com/kumarsumit2000/Product-slider/master/Screenshot%202024-08-10%20063134.png))

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
