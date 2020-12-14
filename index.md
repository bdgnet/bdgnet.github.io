## O nas

<div class="about-us">
Od 2018 łączymy pasjonatów technologii .Net z Bydgoszczy oraz okolic. Organizujemy cykliczne spotkania, które są miejscem wymiany doświadczeń oraz umożliwiają spotkanie osób o podobnych zainteresowaniach. Wszystkie osoby są mile widziane.
</div>

## Spotkania:

{% for post in site.posts %}
  <h3>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </h3>
{% endfor %}
