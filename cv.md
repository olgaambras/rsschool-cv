### rsschool-cv

## Olga Ambras

### Junior Frontend Developer

**e-mail:** hello.olga.ambras@gmail.com  
**phone:** +380 99 035 78 77

**telegram:** @olga_ambras  
**GitHub:** olgaambras  
**Discord:** Olga.Ambras

---

##### Briefly about myself...

> I started my career in interior design, but along with that, I became interested in photography of food and objects. It became my profession for 5 years.  
> Working with medium and small businesses, I learned how to take "delicious" photos and communicate with both business owners and colleagues in the team.  
> But the desire to try new things motivated me to study graphic design, website layout and programming languages.  
> Now I am completely passionate about front-end development and I want to achieve high professional success in this!

- ability to systematize and optimize information
- immersion in the essence of the problems
- developed soft skills, ability to communicate
- teamwork skills
- diligence

---

##### Skills and Proficiency:

- HTML5, CSS3
- JavaScript (Basics)
- GitHub
- VS Code
- Figma, Adobe Photoshop, Lightroom

---

##### Code example:

```

const tabs = document.getElementById('tabs');
const content = document.querySelectorAll('.content');

const changeClass = el => {
    for (let i = 0; i < tabs.children.length; i++) {
        tabs.children[i].classList.remove('active');
        el.classList.add('active');
    }
}

tabs.addEventListener('click', e => {
    const currTab = e.target.dataset.btn;
    changeClass(e.target);
    for (let i = 0; i < content.length; i++) {
        content[i].classList.remove('active');
        if (content[i].dataset.content === currTab) {
            content[i].classList.add('active');
        }
    }
})

```

---

##### Education:

Kharkiv National University  
of Construction and Architecture (interior design)

##### Courses:

- HTML and CSS [ru.code-basics.com]
- JavaScript/Front-end Sourse IT Course (completed)
- «JavaScript/Front-end. Stage 0» RS Schools Course (in progress)
  > keep learning...

---

##### Languages:

- English - A2 (in process)
- Ukrainian - native
- Russian - native
