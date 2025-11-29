# Modern Pricing Table with Toggle 💰

[🇵🇱 Wersja polska / Read in Polish](README.pl.md)

A clean, fully responsive, and modern Pricing Table template built with **HTML**, **CSS**, and **Vanilla JavaScript**. It features a toggle switch for Monthly/Yearly billing with automatic price updates and discount calculations.

Perfect for SaaS landing pages, service providers, and startup projects.

## Live Demo 👀

👉 **[Check out the Live Demo here](https://hsr88.github.io/modern-pricing-table-template/)**

![Pricing Table Preview](https://i.ibb.co/qPPpPKg/Zrzut-ekranu-2025-11-29-162847.png)


## Features 🚀

* **⚡ Zero Dependencies:** Built with pure HTML5, CSS3, and JS. No Bootstrap or jQuery required.
* **📱 Fully Responsive:** Stacks cards vertically on mobile devices and uses a grid layout on desktops.
* **🔄 Interactive Toggle:** Switch between Monthly and Yearly billing instantly.
* **🧮 Auto-Calculation:** JavaScript logic handles price switching (e.g., 20% discount visualization).
* **✨ Modern UI:** Hover effects, smooth transitions, and "Best Value" highlighting.
* **📂 Modular:** Separated into `index.html`, `style.css`, and `script.js` for easy maintenance.

## Project Structure 📁

```text
/
├── index.html   # Main HTML structure
├── style.css    # All styling and responsive rules
├── script.js    # Logic for the pricing toggle
└── README.md    # Documentation
```

How to Use ⚙️
Clone or Download this repository.

Link the style.css in your <head> tag.

Add the HTML structure to your page.

Link the script.js at the end of your <body>.

Configuration
You don't need to touch the JavaScript code to change prices. Simply edit the data-attributes in the HTML file:

HTML
```
<div class="plan-price" 
     data-monthly="49"     data-yearly="39">     49 zł
</div>
```

Customization 🎨

Colors: Change the main accent color in style.css (look for #6c5ce7).

Currency: Just change the text inside the HTML tags (e.g., replace zł with $).

License 📄
This project is licensed under the MIT License - feel free to use it in your personal and commercial projects.
```
Made by [hsr88]
```
