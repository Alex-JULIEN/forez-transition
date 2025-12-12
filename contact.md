---
layout: default
title: Contact
---

<h1 class="page-title">Contact</h1>

<section class="page-content">
  <p>Pour toute demande : <strong>contact@forez-transition.fr</strong></p>
  <p>Ou remplissez ce court message :</p>

  <form action="mailto:contact@forez-transition.fr" method="post" enctype="text/plain" class="contact-form">
    <label>Nom<br><input name="Nom" type="text" required></label>
    <label>Entreprise<br><input name="Entreprise" type="text"></label>
    <label>Message<br><textarea name="Message" rows="5" required></textarea></label>
    <p><button class="btn-primary" type="submit">Envoyer</button></p>
    <p class="small">Formulaire statique : ouvre le client mail local. Si tu veux un formulaire stocké, on intègre Netlify Forms ou Formspree.</p>
  </form>
</section>
