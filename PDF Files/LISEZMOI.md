#Fichiers PDF
Toutes les pages doivent être accessibles en format XHTML 1.0 Strict. Les documents PDF ne sont fournis que comme format de rechange.

Vous trouverez des directives sur la présentation des documents PDF dans le site Politique relative à la présence sur Internet :
(icweb.ic.gc.ca/eic/site/ipp-ppi.nsf/fra/h_00345.html)

##Liens vers un fichier PDF
Si vous créez un lien pointant sur un document accessible uniquement en format PDF, dans la mesure du possible, faites pointer le lien sur la page qui fait référence au document PDF plutôt que directement sur le fichier PDF.

##Références à des formats de rechange dans les pages Web
Quand un format de document de rechange (PDF, RTF, Word, WordPerfect, etc.) est fourni, le lien vers le document de rechange doit figurer dans la page XHTML principale qui a le même contenu que ce document.

##KB/Ko
Faites suivre le lien de la mention « (PDF, taille du fichier [en Ko] et nombre de pages du document) », entre parenthèses.

En anglais, la taille de fichier est indiquée en KB (deux majuscules). En français, elle est indiquée en Ko (« K » majuscule et « o » minuscule). Placez une espace entre le nombre et les lettres (p. ex., 100 Ko). Tous les fichiers PDF doivent être définis comme suit dans le code.

###Anglais
&lt;p&gt;&lt;a href="../vwapj/PDFFileName.pdf" title="File Name"&gt;&lt;em&gt;Nom du fichier&lt;/em&gt;&lt;/a&gt; (&lt;acronym title="Portable Document Format"&gt;PDF&lt;/acronym&gt;, XX&nbsp;&lt;acronym title="kilobyte"&gt;KB&lt;/acronym&gt;, XX&nbsp;pages)&lt;/p&gt;

&lt;epic action="include" file="ESZO-7B4TCN" title="PDF — Information on how to download a PDF reader/PDF — Information sur la fa&ccedil;on de t&eacute;l&eacute;charger le lecteur PDF" format="-1"&gt;

###Français
&lt;p&gt;&lt;a href="../vwapj/PDFFileName.pdf" title="File Name"&gt;&lt;em&gt;Nom du fichier&lt;/em&gt;&lt;/a&gt; (&lt;acronym title="format de document portable"&gt;PDF&lt;/acronym&gt;, XX&nbsp;&lt;span class="abbr" title="kilo-octet"&gt;&lt;abbr title="kilo-octet"&gt;Ko&lt;/abbr&gt;&lt;/span&gt;, XX&nbsp;pages)&lt;/p&gt;

&lt;epic action="include" file="ESZO-7B4TCN" title="PDF — Information on how to download a PDF reader/PDF —- Information sur la fa&ccedil;on de t&eacute;l&eacute;charger le lecteur PDF" format="-1"&gt;

Note : Bien que le nombre de pages ne soit pas exigé par le Conseil du Trésor, l'indiquer constitue une bonne pratique.

##Code PDF dans la base de documents de ressources partagées
Les codes ci-dessous relatifs aux fichiers PDF sont accessibles dans la base Notes de documents partagés. Vous trouverez les instructions nécessaires pour ajouter cette base de documents à votre système et les codes relatifs aux fichiers PDF dans votre page, dans la section du présent guide intitulée « Ressources SEEIC partagées : base de documents de production ».

##Texte précédant le lien vers le document PDF
Si le document n'est fourni qu'en format PDF, veuillez insérer le code suivant juste avant le lien vers le fichier PDF.

###PDF — Avis concernant l'accessibilité — Lien vers la page Contactez-nous
&lt;epic action="include" file="ESZO-7CFSKT" title="PDF — Accessibility Notice — Link to Contact Us Page/PDF — Avis d'accessibilité — Lien à Contactez-nous" format="-1"&gt;

Affiché dans un navigateur Web, le code ci-dessus se présente comme suit :

&lt;hr /&gt;
&lt;p&gt;Si vous ne pouvez accéder au document suivant, veuillez &lt;a href="http://www.ic.gc.ca/eic/site/ic1.nsf/fra/h_00014.html"&gt;communiquer avec nous&lt;/a&gt; pour obtenir des formats de rechange appropriés.&lt;/p&gt;
&lt;hr /&gt;

##Texte suivant le lien vers le document PDF
Veuillez inclure des explications sur la façon de télécharger un lecteur PDF au bas de toutes les pages qui contiennent des liens vers des fichiers en format PDF.

###PDF — Information sur la façon de télécharger un lecteur PDF
&lt;epic action="include" file="ESZO-7B4TCN" title="PDF — Information on how to download a PDF reader/PDF — Information sur la façon de télécharger le lecteur PDF" format="-1"&gt;

Affiché dans un navigateur Web, le code ci-dessus se présente comme suit :

&lt;hr /&gt;
&lt;p&gt;Pour consulter la version &lt;acronym title="format de document portable"&gt;PDF&lt;/acronym&gt; (format de document portable), vous devez avoir un lecteur &lt;acronym title="format de document portable"&gt;PDF&lt;/acronym&gt; sur votre ordinateur. Si vous n'en avez pas d&eacute;j&agrave; un, il existe de nombreux lecteurs &lt;acronym title="format de document portable"&gt;PDF&lt;/acronym&gt; que vous pouvez t&eacute;l&eacute;charger gratuitement ou acheter dans Internet&nbsp;:&lt;/p&gt;
&lt;ul&gt;&lt;li&gt;&lt;a href="http://get.adobe.com/fr/reader/?promoid=DAGAU"&gt;&lt;span lang="en" xml:lang="en"&gt;Adobe Reader&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href="http://www.foxitsoftware.com/pdf/reader/"&gt;&lt;span lang="en" xml:lang="en"&gt;Foxit Reader&lt;/span&gt;&lt;/a&gt; (en anglais seulement)&lt;/li&gt;
&lt;li&gt;&lt;a href="http://www.foolabs.com/xpdf/download.html"&gt;&lt;span lang="en" xml:lang="en"&gt;Xpdf&lt;/span&gt;&lt;/a&gt; (en anglais seulement)&lt;/li&gt;
&lt;li&gt;&lt;a href="http://www.visagesoft.com/products/pdfreader/"&gt;&lt;span lang="en" xml:lang="en"&gt;eXPert &lt;acronym title="format de document portable"&gt;PDF&lt;/acronym&gt; Reader&lt;/span&gt;&lt;/a&gt; (en anglais seulement)&lt;/li&gt;&lt;/ul&gt;

**Références**
Format de rechange — Exemple de traitement de documents non XHTML :
(www.tbs-sct.gc.ca/clf2-nsi2/tb-bo/dimf-dodf-fra.asp)

Formats de rechange accessibles pour les documents publiés sur les sites Web :
(www.tbs-sct.gc.ca/clf2-nsi2/clfs-nnsi/clfsp-nnsii-fra.asp#cn_3_aaf)

##Métadonnées du fichier
###Métadonnées du fichier du document
Tous les fichiers doivent contenir au minimum les métadonnées suivantes :
* Titre;
* Auteur;
* Code de produit du site.

###Métadonnée « titre du document »
La métadonnée « titre du document » est inscrite comme suit :

[code-de-type-de-document]-[numéro-du-document]—[titre-complet-du-document]

où

[code-de-type-de-document]
    indique le code qui identifie le type de document et est toujours inscrit en majuscules selon la liste suivante :
* Bulletins
 	* Électricité =	E
  * Gaz =	G
	* Masse =	M
	* Volume =	V
	* Domaine général =	GEN
	* Méthodes statistiques et plans d'étalonnage =	S
* Normes
 	* Électricité =	S-E
	* Gaz =	S-G
	* Masse =	SGM
	* Volume = SVM
	* Méthodes statistiques et plans d'étalonnage =	S-S
* Normes provisoires
 	* Électricité =	PS-E
	* Gaz =	PS-G
	* Méthodes statistiques et plans d'étalonnage =	PS-S
* Conditions
 	* Masse =	TC
	* Volume =	TC
* Procédures
 	* Toutes 	 
* Tableaux de facteurs de correction du volume
	* Volume =	VCF

[numéro-du-document]
    indique le numéro à deux chiffres du document, avec le zéro en tant que caractère de remplissage
[titre-complet-du-document]
    indique le titre complet du document dans la langue du document

Exceptions :

Le numéro du document et le trait d'union (« - ») qui le précède ne sont utilisés que pour des documents numérotés.

Certains documents non numérotés ne portent pas de code de type de document. Dans de tels cas, le code de type de document et le tiret (« — ») qui le suit sont omis.

###Métadonnée « auteur du document »
La métadonnée « auteur du document » est toujours « Mesures Canada » pour les documents rédigés en français, et "Measurement Canada" pour les documents rédigés en anglais.

###Métadonnée « code de produit du site » de l'environment de publication du document
Le code de produit du site où sera publié le document :
* Internet 	701
* intranet 	471