# 'Enehana Club - About Page Maintenance
Along side with the annual updates, it is important to keep a consistent website.

## Objective
Breifly explain the website's about page content and keys.

## Information Dump
### Part 1 - Properly Storing Alumni Leadership Information
ARCHIVE GRADUATING LEADERSHIP
* **BEFORE THE SCHOOL YEAR IS OVER GET THE FOLLOWING INFORMATION FROM THE SENIORS GRADUATING**
    * College and Major
    * Another recent photo (optional -- but the last chance to submit a newer photo)
    * Linkedin (if appliciable)
    * GitHub (if appliciable)
    * DTE distinction pursuit
        * *If appliciable:* DTE Portfolio link

### Part 2 - New/Current Leadership Information
* Add yourself (or current Web Masters) to the README.md
    * **FORMATTING AS FOLLOWS:** "[NAME FIRST AND LAST NAME](LINK TO GITHUB) 'GRADUATION YEAR (LAST TWO DIGITS)"
* **INFORMATION NEEDED FROM NEW/CURRENT BOARD MEMBES**
    * Graduating Year
    * Board Position (if appliciable)
    * Linkedin (if appliciable)
    * GitHub (if appliciable)
    * _if you're the webmaster, add that to your tags on the bottom_

### Part 3 - Font Awesome Key
CHECK INFORMATION
_we use icons as our buttons throughout the page (nav bar, footer, icosn on the about page, etc.)_
**BELOW IS A KEY OF THE ICONS WE USE, THEIR FA IDEA AND THEIR PURPOSE ON THE ABOUT PAGE**
* GitHub: to link github (ICON ID: fa-github)
* LinkedIn: to link linkedin (ICON ID: fa-linkedin)
* File Code: for the current webmaster(s) (ICON ID: fa-file-code)
* Medal: for those that pursued a distinction sucessfully (ICON ID: fa-medal)
* People Group: for the founding members (ICON ID: fa-people-group)

### Part 4 - (Current) Leadership Formatting
**Leadership Content Wrapper(s)**
``` 
<div id="board-members">
    <h1 class="text-center pb-2">Our Board</h1>
    <div class="row d-flex align-items-center">
        <!-- INFORMATION ABOUT EACH BOARD MEMBER -->
    </div>
</div>
```

**Leadership Example Content Template**
```
<div class="col">
    <img src="assets/about/staff/< punahou login information >.jpg" alt="picture of Name 'graduation-year-abbreviation">
    <h3>NAME (FIRST AND LAST)</h3>
    <p style="margin-bottom: 0;"><b>GRADUATING YEAR</b></p>
    <p style="font-size: small"><b>Position: </b>???</p>
    <div class="staff-icons"></div>
</div>
```

* IMAGE: source information - assets/about/staff/< PUNAHOU LOGIN INFORMATION >.jpg
* STAFF ICONS: LINKEDIN/GITHUB - OPTIONAL: based on what is had
```
<div class="staff-icons">
    <a href="https://www.linkedin.com/in/lindsay-minami-990041254/" target="_blank" class="btn btn-link btn-floating btn-lg text-dark" role="button" data-mdb-ripple-color="dark"><i class="fa fa-linkedin"></i></a>
    <a href="https://github.com/FlowerCake13" target="_blank" class="btn btn-link btn-floating btn-lg text-dark" role="button" data-mdb-ripple-color="dark"><i class="fa fa-github"></i></a>
    <p>
        <i class="fa fa-people-group"></i> Founding Member
        <i class="fa fa-file-code"></i> Web Master
    </p>    
</div>
```

### Part 5 - Alumni Formatting
**Alumni Content Wrapper(s)**
``` 
<div id="alumni">
    <h1 class="text-center pb-2">Our Alumni</h1>
    <!-- BUILD THE NEW YEARS ON TOP - I.E 2024, 2023, 2022 -->
    <div id="GRADUATING YEAR" class="row d-flex align-items-center year">
        <h1>GRADUATING YEAR</h1>
        <!-- INFORMATION ABOUT EACH BOARD MEMBER -->
    </div>
</div>
```
**Alumni Example Content Template**
```
<div class="col">
    <img src="assets/about/staff/< punahou login information >.jpg" alt="picture of Name 'graduation-year-abbreviation">
    <h3>NAME (FIRST AND LAST)</h3>
    <p style="margin-bottom: 0;"><b>College: </b>????</p>
    <p style="font-size: small"><b>Major: </b>????</p>
    
    <div class="staff-icons"></div>
</div>
```
**Alumni Staffer Icons**
```
<div class="staff-icons">
    <a href="<LINKEDIN LINK>" target="_blank" class="btn btn-link btn-floating btn-lg text-dark" role="button" data-mdb-ripple-color="dark"><i class="fa fa-linkedin"></i></a>
    <a href="<GITHUB LINK>" target="_blank" class="btn btn-link btn-floating btn-lg text-dark" role="button" data-mdb-ripple-color="dark"><i class="fa fa-github"></i></a>

    <p>
        <a href="<DTE DISTINCTION PORTFOLIO LINK>" target="_blank" class="btn btn-link btn-floating btn-lg text-dark" role="button" data-mdb-ripple-color="dark"><i class="fa fa-medal"></i></a> DTE Recipient '23
        <br>
        <i class="fa fa-people-group"></i> Founding Member
    </p>         
</div>
```

---
## Additional Resrouces
<!-- TECHNICAL RESOURCES -->
### Technical Resources
- [Font Awesome Icons](https://fontawesome.com/icons)
- [W3Schools](https://www.w3schools.com/)
- [Bootstrap Documentation](https://getbootstrap.com/)
- [CSS Tricks: Flexbox Cheet Sheet](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Google Fonts](https://fonts.google.com/)
    <!-- CURRENT FONTS BEING USED: BARLOW CONDENSED (WGHT 500), BARLOW (WGHT 800), MONTSERRAT -->
- *[Instaling Git](https://github.com/git-guides/install-git)*
- *[Instaling Git/Using Git](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html)*
- *[Commiting Code Via Github.com (via file upload)](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)*
<!-- ACADEMIC/SCHOOL RESOURCES -->
### Academic/School Resources
- ['Enehana's Club Website](https://enehanapunahou.github.io/)
- ['Enehana's Club GitHub](https://github.com/enehanapunahou)
- ['Enehana Club Instagram](https://www.instagram.com/enehana.punahou/)
- [Punahou's DTE (Design Technology Engineering) Homepage](https://www.punahou.edu/design-technology-and-engineering)
- [Cyber Safe Seniors Homepage](https://www.gocybersafe.org/)