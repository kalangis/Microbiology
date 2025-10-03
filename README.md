# Microbiology Class

Welcome to the **Microbiology Class Repository**! 🎓🦠  
This repository contains interactive study tools, lecture notes, and lab exercises for microbiology. The goal is to make studying fun and accessible, with quizzes and games for each lab.

---

## How to Use

1. Click the link to open the interactive HTML game or lab resource.
2. You can play the quizzes directly in your browser.
3. New labs and quizzes will be added over time, so check back regularly.

---

## Lab Games & Quizzes

{% assign labs = site.static_files | where_exp:"file","file.path contains 'Lab'" %}
{% for lab in labs %}
- [{{ lab.path | split: "/" | last | split: "." | first }}]({{ lab.path }})
{% endfor %}

> All lab quizzes are interactive and built in HTML/JavaScript.  

---

## Repository Structure


