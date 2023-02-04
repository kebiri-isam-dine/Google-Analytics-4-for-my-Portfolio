# Google Analytics 4 for my Portfolio




![GitHub](https://img.shields.io/github/license/kebiri-isam-dine/UniversityProjects?color=g&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/kebiri-isam-dine/UniversityProjects?color=red&style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/kebiri-isam-dine/UniversityProjects?color=yellow&style=for-the-badge)


![GitHub dev_language](https://img.shields.io/badge/GoogleAnalytics4-FF0000?style=flat&logo=google-analytics&logoColor=white)
![GitHub dev_language](https://img.shields.io/badge/JS-F1E758?style=flat&logo=javascript&logoColor=white)

![GitHub Org's stars](https://img.shields.io/github/stars/kebiri-isam-dine?style=social)
![GitHub followers](https://img.shields.io/github/followers/kebiri-isam-dine?style=social)




## About The Project
Mise en place et paramétrage de GA4 sur mon [Portfolio](https://kebiri-isam-dine.github.io/) pour l'analyse web des indicateurs et des insights qu’on peut analyser grâce à cet outil :

- Trafic global sur mon Portfolio
- Sites Web d’origine du trafic
- Trafic sur chaque page
- Informations démographiques sur les visiteurs 
- Type d’appareil utilisé par les visiteurs (mobile ou ordinateur de bureau)

### GA4 en quelques mots : 
GA4 est la dernière version de Google Analytics. Google Analytics est un service ou tableau de bord gratuit d'analyse d'audience d'un site Web ou d'applications utilisé par plus de 10 millions de sites, soit plus de 80 % du marché mondial. Il permet d’accéder à tout un éventail d’insights à propos de votre site Web et des personnes qui le consultent.


### Keywords
GA4 - Analyse web - tableau de bord 



## Mise en place

Intégrer le script suivant : [Script_Integration.js](Script_Integration.js) :

```js
< !--Google tag(gtag.js)-- >
<script async src="https://www.googletagmanager.com/gtag/js?id=G-CKRFLCDH53"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-CKRFLCDH53');
</script>
```

Adapter l'ID de mesure ``G-CKRFLCDH53`` par son ID et coller cette balise Google juste après la balise head sur toutes les pages du site Web.



## Dashboard sur mon Portfolio
<img src="/Captures/Dashboard01.png">
<img src="/Captures/Dashboard02.png">



## À RETENIR

### Web Analyse
<img src="/Captures/WebAnalyse_GA4.png">
<img src="/Captures/WebAnalyseAction_GA4.png">

### Pourquoi GA4
<img src="/Captures/Pourquoi_GA4.png">

### Concepts GA4
<img src="/Captures/Concepts_GA4.png">





## License

[GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)


## Contact

📫 How to reach me: kebiri.isam.dine@gmail.com

🌐 My Portfolio: <https://kebiri-isam-dine.github.io/>

🔗 Project Link: <https://github.com/kebiri-isam-dine/Google-Analytics-4-for-my-Portfolio>
