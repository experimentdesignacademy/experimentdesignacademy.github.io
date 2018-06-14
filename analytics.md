# Analyzing Traffic
* [Google Analytics](https://analytics.google.com/)

1. Sign up for Google Analytics
All we need is some basic info about what site you'd like to monitor.

2. Add tracking code
You'll get a tracking code to paste onto your pages so Google knows when your site is visited.

3. Learn about your audience
In a few hours you'll be able to start seeing data about your site.

## New Account
* **Account Name**: Experiment Design Academy
* **Website Name**: Currency Converters
* **Website URL**: https://currencyconverters.github.io/
* **Industry Category**: Finance
* **Reporting Time Zone**: Netherlands
* Get Tracking ID
* Accept Terms of Service Agreement

Tracking ID: `UA-120869039-1`

```javascript
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-120869039-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-120869039-1');
</script>
```

## Template Configuration
Minimal will respect the following variables, if set in your site's `_config.yml`:

```code
google_analytics: [Your Google Analytics tracking ID]
```

## Verify Tracking Code
* Visit [site](https://currencyconverters.github.io/)
* View > Developer > View Source
* Scroll to bottom
* Look for `<script>` tag containing `UA-120869039-1`
