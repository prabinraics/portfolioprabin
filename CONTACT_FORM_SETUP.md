# Contact form setup

The portfolio uses FormSubmit's AJAX endpoint, which works with static GitHub Pages and needs no API key or server. The form posts messages to `01prabin.rai@gmail.com` and shows sending, success, and error states without leaving the page.

## One-time activation

The FormSubmit endpoint for `01prabin.rai@gmail.com` has been activated. The confirmation page showed the local preview URL (`http://127.0.0.1:5500/`).

1. Deploy the updated `Prabin_Rai_Portfolio (1).html` to GitHub Pages.
2. Submit one valid test message from the deployed site and confirm it arrives at `01prabin.rai@gmail.com` (check spam if needed).
3. If FormSubmit requests confirmation again for the deployed page, open its newest confirmation email and activate that submission too.

FormSubmit requires email confirmation before it delivers form messages. Its [documentation](https://formsubmit.co/documentation) describes the email endpoint and reply-to handling, and its [AJAX instructions](https://formsubmit.co/ajax-documentation) describe staying on the same page during submission. No private credentials are stored in the portfolio.
