
<h1 class="display-5">Organizers</h1>

<div class="organizer-list">
  {% for organizer in site.data.organizers.organizers %}
    <div class="organizer-card">
      <img src="{{ organizer.photo }}" alt="{{ organizer.name }}">
      <h3>{{ organizer.name }}</h3>
      <p><em>{{ organizer.affiliation }}</em></p>
      <p>{{ organizer.email }}</p>
      <div class="organizer-links">
        {% if organizer.home %}
          <a href="{{ organizer.home }}" target="_blank"><i class="fas fa-home"></i></a>
        {% endif %}
        {% if organizer.linkedin %}
          <a href="{{ organizer.linkedin }}" target="_blank">
  <i class="fa-brands fa-linkedin"></i>
</a>
        {% endif %}
        {% if organizer.googleScholar %}
          <a href="{{ organizer.googleScholar }}" target="_blank"><i class="fas fa-graduation-cap"></i></a>
        {% endif %}
      </div>
    </div>
  {% endfor %}
</div>

