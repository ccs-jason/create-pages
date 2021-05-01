# contributors
 ---
 user: https://github.com/TheRealSonicFan
 image: https://static.wikia.nocookie.net/sonic/images/2/2d/TSR_Sonic.png
 name: Zhiyuan LIN
 ---
 Hello! I am Andy. Great to meet everyone.

{% for staff_member in site.staff_members %}
  <h2>
    <a href="{{ staff_member.url }}">
      {{ staff_member.name }} - {{ staff_member.position }}
    </a>
  </h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
