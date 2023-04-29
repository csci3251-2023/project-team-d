# Introduction

Our team have 7 tasks.

Task 1: We will start to setup a issues system

Task 2: Setup a project board for project task tracking

Task 3: Setup a README to document our project

Task 4: Write a Hello World program in C and setup a GitHub Action to run it

Task 5: Setup a badge to check workflow status

Task 6: Update the Contributors part in README

Task 7: Setup a Github pages and add the link to README

# Code

# Contributors

{% for stu in site.stu %}
  <div>
    <img src="{{ stu.image }}" style="display: inline-block; max-width: 50px">
    <span style="font-size: 1.3em">{{ stu.user }} ({{ stu.name }})</span>
    <p>{{ stu.content | markdownify }}</p>
  </div>
{% endfor %}

