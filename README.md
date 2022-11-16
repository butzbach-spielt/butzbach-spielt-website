[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/butzbach-spielt/butzbach-spielt-website)

# butzbach-spielt-website

This project is a static website for a local group of board game enthusiats located in Butzbach, Germany. The website is generated by a static site generator [e11y](https://www.11ty.dev/) and uses [tailwindcss](https://tailwindcss.com/) for styling. The architecture of this project is designed to support easy editing of content by using Markdown and [Netlify CMS](https://www.netlifycms.org/).

The webiste is deployed on netlify and the URL is https://butzbach-spielt.netlify.app

## Anleitung für Autoren

_This description is written in German as it is targeted at German readers_

### Vorbedingungen

* GitHub Account --> [Registrieren](https://github.com/signup)
* Schreibzugriff auf dieses Repo. Dafür schreibst du deinen GitHub Usernamen in die [Signal Gruppe](https://signal.group/#CjQKIEf3UOxVQjG-FSlMlw2MOpABw4ynH4l3p375Bw1mIsCnEhAyDYcuci46goUtuKj5bra8).


### Adminbereich

Im Adminbereich lassen sich Änderungen auf der Website machen, ohne dass du direkt mit einem Codeeditor oder mit GitHub MergeRequests arbeiten musst. Das ganze passiert dann automatisch im Hintergrund.

* Gehe auf https://butzbach-spielt.netlify.app/admin und authentifiziere dich mit deinem GitHub Account. 
* Bearbeite einen bestehenden Eintrag oder lege einen neuen an.
* Speichere und schaue dir danach den Preview an (oben rechts: _View Preview_). Es kann etwa eine Minute dauern bis der Preview aktualisiert wurde nachdem du gespeichert hast.
* Wenn du mit deinen Änderungen zufrieden bist, speichere und ändere den Status auf _In review_
* Lass jemand anderen aus der Website Gruppe die Änderungen reviewen und diese dann _mergen_, also in den _main_-Zweig übernehmen. Dadurch werden die Änderungen dann auf der öffentlichen Seite übernommen.
