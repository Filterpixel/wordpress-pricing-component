# wordpress-pricing-component

```
<iframe src="https://filterpixel.github.io/wordpress-pricing-component/" id="custom-pricing-css-0109"></iframe>
```

1. Using external CSS: insert the pricing-custom-media.css
2. Using script: Inject this script(uses event-listener)
    ```
    <script>
    let iframe = document.getElementById('custom-pricing-css-0109');
    function resizeIframe() {
       console.log(window.innerWidth);
        if (window.innerWidth <= 800) {
            iframe.style.width = '100%';
            iframe.style.height = '700px';
        } else {
            iframe.style.width = '800px';
            iframe.style.height = '400px';
        }
    }
    window.addEventListener('resize', resizeIframe);
    resizeIframe();
    </script>

    ```