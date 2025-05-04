---
title: "Kontakt"
description: "Kontaktieren Sie die Obentra GmbH für Fragen oder Anfragen."
url: "/contact/"
layout: "default"
---

Wenn Sie Fragen haben oder mit uns in Kontakt treten möchten, nutzen Sie bitte das folgende Formular oder wenden Sie sich direkt an uns:

---

## Anschrift

**Obentra GmbH**  
Baslerstrasse 45  
4600 Olten  
Schweiz

📞 Telefon: <span id="phone-placeholder"><em>wird geladen…</em></span>  
📧 E-Mail: <span id="email-placeholder"><em>wird geladen…</em></span>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const phone = "+41" + " 62" + " 561 44 68";
    const link_phone = `<a href="tel:${phone}">${phone}</a>`;
    document.getElementById("phone-placeholder").innerHTML = link_phone;
  });
</script>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const email = "kontakt@obentra.ch";
    const link_email = `<a href="mailto:${email}">${email}</a>`;
    document.getElementById("email-placeholder").innerHTML = link_email;
  });
</script>

---

## Kontaktformular

<style>
  .contact-form {
    padding: 1.5rem;
    border-radius: 8px;
    max-width: 600px;
    margin: 2rem auto;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    background-color: #f9f9f9;
    color: #222;
  }

  .contact-form label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: 600;
  }

  .contact-form input,
  .contact-form textarea {
    width: 100%;
    padding: 0.5rem;
    margin-bottom: 1rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1rem;
    background-color: #fff;
    color: #000;
  }

  .contact-form button {
    background-color: #0863ccff;
    color: white;
    padding: 0.6rem 1.2rem;
    border: none;
    border-radius: 50px;
    font-weight: 600;
    cursor: pointer;
  }

  .contact-form button:hover {
    background-color: #074890ff;
  }

  .contact-form p {
    font-size: 0.9em;
    color: #555;
    margin-top: 1rem;
  }

  .contact-form a {
    text-decoration: none;
  }

  .contact-form a:hover {
    text-decoration: underline;
  }

  /* Hextra-compatible dark mode (based on html.dark class) */
  html.dark .contact-form {
    background-color: #1f1f1f;
    color: #eee;
    box-shadow: 0 2px 10px rgba(255, 255, 255, 0.05);
  }

  html.dark .contact-form input,
  html.dark .contact-form textarea {
    background-color: #2b2b2b;
    border: 1px solid #444;
    color: #fff;
  }

  html.dark .contact-form button {
    background-color: #0863ccff;
  }

  html.dark .contact-form button:hover {
    background-color: #074890ff;
  }

  html.dark .contact-form p {
    color: #bbb;
  }

  html.dark .contact-form a {
    color: #0863ccff;
    text-decoration: underline;
  }
</style>

<form action="https://formsubmit.co/ec53aecd96e0a715f382725b5f60bd58?no-ip" method="POST" class="contact-form">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_subject" value="Kontaktanfrage über die Website">
  <input type="hidden" name="_next" value="https://www.obentra.ch/form-submit-success">

<label for="name">Ihr Name</label>
<input type="text" id="name" name="name" required>

<label for="email">Ihre E-Mail-Adresse</label>
<input type="email" id="email" name="email" required>

<label for="message">Ihre Nachricht</label>
<textarea id="message" name="message" rows="5" required></textarea>

<button type="submit">Nachricht senden</button>

  <p>
    Mit dem Absenden des Formulars erklären Sie sich damit einverstanden, dass Ihre Angaben zur Beantwortung Ihrer Anfrage verwendet werden.
    Weitere Informationen finden Sie in unserer <a href="/privacy-policy/">Datenschutzerklärung</a>.
  </p>
</form>