+++
date = '2024-10-20T16:52:38+02:00'
draft = false
title = 'Curriculum Vitae'
+++

## What Do I Do?
After being asked, *"So, what exactly do you do?"* I realised it was time to create a proper CV to showcase my work. While it seemed like a simple task, I wanted to make the process more enjoyable by turning it into a small project that would be functional and enjoyable to create.

## Why Automate the CV Process?
Updating a CV, resume, or cover letter can feel like such a hassle. Every time you add something new, it’s the same process: reformatting, shifting sections around, and hoping everything still looks right. It can easily take up hours, and it’s way too easy to forget a detail or mess up the formatting.

As someone who loves tech, this problem practically begs for a solution. So instead of manually updating these documents every time, I built a system that automatically generates and updates them with the latest information. This way, everything stays up-to-date without me needing to constantly check or tweak things.

By automating the process, I’ve saved myself a ton of time and mental energy. Now, my CV, resume, and cover letter are always ready to go with the latest updates, and I don’t have to stress about them anymore. It’s a simple, satisfying way to use tech to make life easier.

And honestly, who doesn’t love the idea of getting rid of an annoying task and letting it run smoothly in the background?

## The Tools Behind the Project
To make this happen, I used **R**, a language that’s typically known for statistical computing and data visualization but is super versatile. Specifically, I used the `vitae` library, which provides templates designed for academic CVs and resumes. I went with the `vitae::awesomecv` template, which is based on the popular Awesome CV LaTeX template. This approach streamlined the whole process and saved me from manually editing complex LaTeX files. The result is a clean, professional design that focuses on readability and structure.

## Automation with GitHub Actions
One of the coolest features of this project is the automation. I set it up using GitHub Actions, a CI/CD platform integrated into GitHub. This setup ensures that whenever I make changes or add new data, the system automatically rebuilds and updates my CV, resume, and cover letter. It’s a hands-off process that keeps everything current without me having to lift a finger once it’s configured.

This automation doesn’t just keep my documents up to date; it also ensures they’re always available to share. So whenever I need to send someone my CV or resume, I can confidently share the latest version without worrying about outdated information.

## Why This Matters
In today’s fast-paced world, keeping track of achievements and sharing them quickly is super important. Whether you're applying for jobs, speaking at conferences, or collaborating with others, having a well-maintained CV or resume is essential. Thanks to this automated system, I’m able to stay ahead of the curve and focus more on the work itself instead of getting bogged down with administrative tasks.

This project reflects my passion for using technology to solve real-world problems and make things more efficient. It showcases my technical skills while highlighting my commitment to staying organized and prepared.

## Links to my CV
Here are the links to my current CV and resume, both automatically updated through this project:
- **[My CV (PDF)](https://github.com/luisdza/curriculum-vitae/raw/main/cv.pdf)**  
- **[My Resume (PDF)](https://github.com/luisdza/curriculum-vitae/raw/main/resume.pdf)**  
- **[Source Code for the Project](https://github.com/luisdza/curriculum-vitae)**

Feel free to explore the source code behind this project! If you’re interested, you can adapt it for your own CV needs. It’s a great way to automate something we all need but often put off updating.