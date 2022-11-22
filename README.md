# notchagency.github.io / test commit

- [] remove webflow badge
```
replace .w-webflow-badge{position:fixed !important;display:none
.w-webflow-badge{position:fixed !important;display:none
```

- [] contact form across all pages
```js
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
    <script type="text/javascript">
        (function () {
            // https://dashboard.emailjs.com/admin/account
            emailjs.init('NsbB25AJfi5XYC5dm');
        })();
    </script>
    <script type="text/javascript">
        window.onload = function () {
            document.getElementById('email-form').addEventListener('submit', function (event) {
                event.preventDefault();
                form_data = document.getElementById('email-form')

                // these IDs from the previous steps
                emailjs.sendForm('service_qfzsnoc', 'template_t9b5hi5', form_data)
                    .then(function () {
                        console.log('SUCCESS!');
                    }, function (error) {
                        console.log('FAILED...', error);
                    });
            });
        }
    </script>
```

- [] in all styles

```css
textarea {
  resize: none !important;
}
```