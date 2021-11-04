# cdt-strings

Hi, this project presents all the strings used in [CDT](https://play.google.com/store/apps/details?id=tech.tcsolution.cdt) android app.

The strings were mapped to this project so that users can report a translation error, modify the translation files (proposing a change) or even create the translation for a new language.

If you like our app and want to help us with translations, we would be very grateful. :)

**IMPORTANT:** FORK the project, make the changes and then make a Pull request (PR) so we can validate it.

### Modifying key values for a language

* Open the desired file and edit it changing some value specified in some line started with _"<string"_, _"<plurals"_ or _"<item"_
* Do not change the lines started with _"&lt;!--"_

**E.g.:** *values-pt/strings.xml*  
> &lt;!-- Key: "all_rights_reserved", English.value: "All rights reserved." --&gt;   
> &lt;string name="all_rights_reserved"&gt;Todos os direitos reservado.&lt;/string&gt;  

**Fixing a translation**   
> &lt;!-- Key: "all_rights_reserved", English.value: "All rights reserved." --&gt;   
> &lt;string name="all_rights_reserved"&gt;Todos os direitos reservados.&lt;/string&gt; 

Currently the app has support for the following languages:  

* English - EN: [values-en](./values-en/strings.xml)
* Czech - CS: [values-cs](./values-cs/strings.xml)
* Danish - DA: [values-da](./values-da/strings.xml)
* German - DE: [values-de](./values-de/strings.xml)
* Spanish - ES: [values-es](./values-es/strings.xml)
* French - FR: [values-fr](./values-fr/strings.xml)
* Indonesian - IN: [values-in](./values-in/strings.xml)
* Italian - IT: [values-it](./values-it/strings.xml)
* Japanese - JA: [values-ja](./values-ja/strings.xml)
* Korean - KO: [values-ko](./values-ko/strings.xml)
* Malay - MS: [values-ms](./values-ms/strings.xml)
* Dutch - NL: [values-nl](./values-nl/strings.xml)
* Portuguese - PT: [values-pt](./values-pt/strings.xml)
* Russian - RU: [values-ru](./values-ru/strings.xml)
* Chinese (simplified) - ZH: [values-zh](./values-zh/strings.xml)

### Creating a translated idiom

* Copy all file content present in *values-en/strings.xml* (English version) to a new file
* Change all lines started with _"<string"_, _"<plurals"_ or _"<item"_
* Do not change the lines started with _"&lt;!--"_

**E.g.:**  
> &lt;!-- Key: "all_rights_reserved", English.value: "All rights reserved." --&gt;   
> &lt;string name="all_rights_reserved"&gt;All rights reserved.&lt;/string&gt;  

**Traslating into Portuguese**  
> &lt;!-- Key: "all_rights_reserved", English.value: "All rights reserved." --&gt;   
> &lt;string name="all_rights_reserved"&gt;Todos os direitos reservados.&lt;/string&gt;  


