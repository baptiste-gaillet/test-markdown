> ## Le service Go-Rénove
> **{0-quoi}A quoi sert Go-Rénove ?**
> Le service Go-Rénove a été conçu pour donner aux bailleurs sociaux une vue d'ensemble de leur parc de bâtiment et de sa performance énergétique.<br />
> Ce service permet aussi de cibler certains bâtiments d'intérêt et de consulter une fiche d'information détaillée des caractéristiques de ce bâtiment<br />
> **{0-qui}Qui porte le service Go-Rénove ?**
> Le service Go-Rénove est réalisé et maintenu par le [CSTB (Centre Scientifique et Technique du Bâtiment)](https://www.cstb.fr/), établissement public de recherche et d'expertise dans le secteur du bâtiment, au service de l'intérêt général.<br />
> Le projet Go-Rénove constitue l'un des 9 projets portés par le programme [PROFEEL](https://programmeprofeel.fr/) regroupant les organisations professionnelles du bâtiment mobilisées pour apporter des solutions innovantes à l'enjeu de rénovation énergétique du parc de bâtiments existant.<br />
> **{0-google}Pourquoi Go-Rénove n’utilise pas les services Google ?**
> Les conditions d’utilisation des services Google ne sont malheureusement pas compatibles avec le modèle Go Rénove.<br />
> *Mis à jour le 27/02/2023*<br />
> **{0-societes}Pour les services transverses des GIE ou sociétés de coordination serait-il possible d'avoir un compte consolidé pour les sociétés sur lesquelles nous intervenons ?**
> Cette possibilité est à l’étude. Pour un besoin urgent contactez-nous via le formulaire de contact.<br />
> *Mis à jour le 27/02/2023*<br />

> ## Les données
> **{1-fiabilite}Pourquoi la fiabilité d'un indicateur est-elle variable d'un bâtiment à l'autre ? [🔗](https://bailleur.basenationalebatiment.fr/faq#Fiabilite)**
> Chaque indicateur est calculé à partir d'une liste de caractéristiques spécifiques au bâtiment. Selon les bâtiments, ces caractéristiques sont plus ou moins disponibles.<br />
> Par exemple, un bâtiment ayant fait l'objet d'un DPE disposera d'informations techniques supplémentaires.<br />
> Les caractéristiques indisponibles font l'objet d'une prédiction, grâce à un algorithme d'intelligence artificielle développé pour Go-Rénove, fonctionnant par analogie avec le reste du parc de bâtiments français.<br />
> Ces prédictions présentent une marge d'erreur que nous savons quantifier et qui nous permet d'évaluer la fiabilité finale de l'indicateur.<br />
> **{1-consommation}Quelles sont les données de consommation électriques disponibles ?**
> Les consommations électriques sont tirées de l'open data publié par le SDES. Le secret statistique impose une agrégation à l'adresse et uniquement dans le cas de plus de 10 compteurs à l'adresse.<br />
> Il n'y a pas de consommation au logement ou au palier.<br />
> Source légale : <https://www.legifrance.gouv.fr/codes/id/LEGIARTI000041693480/2020-03-07><br />
> *Mis à jour le 27/02/2023*<br />
> **{1-lexique}Est-il possible d'avoir un lexique des champs disponibles dans un export de données ?**
> Au niveau de la fiche du bâtiment qui liste les caractéristiques, vous pouvez consulter une description de la caractéristique sélectionnée.<br />
> Si celle-ci s'avère insuffisante, vous avez la possibilité de contacter Go-Rénove via le formulaire de contact pour obtenir plus d'informations.<br />
> *Mis à jour le 27/02/2023*<br />
> **{1-croisement}Comment Go-Rénove définit la notion de bâtiment et parvient à croiser avec les données de consommation d’énergie qui exploitent un découpage différent ?**
> Le CSTB a élaboré un algorithme spécifique. Les détails sont consultables à l’adresse suivante :<br />
> [Documentation BDNB](https://gitlab.com/BDNB/base_nationale_batiment/-/wikis/M%C3%A9thodologie/methodo_v07_publique#vii32-croiser-des-donn%C3%A9es-quantitatives)<br />
> <a href="https://www.example.com/my great page" target="_blank" rel="noopener">Documentation BDNB test en href</a><br />
> *Mis à jour le 27/02/2023*<br />
> **{1-copropriete}Traitement des données pour les bâtiments en copropriété ?**
> Dans Go-Rénove Bailleurs, les logements appartenant à des propriétaires bailleurs différents sont distingués.<br />
> Chaque bailleur voit le nombre de logements correspondant à son parc. Dans la fiche bâtiment, Go-rénove distingue le nombre total de logements et le nombre de logements sociaux.<br />
> *Mis à jour le 27/02/2023*<br />
> **{1-extraction}Est-il possible d’extraire les données d’un parc de bâtiments ?**
> Oui, l'outil bailleurs permet d'extraire toutes les données associées à un parc sous forme de fichier CSV.<br />
> *Mis à jour le 27/02/2023*<br />
> **{1-precision}Quelle est la précision de métrés ?**
> La précision des métrés est celle des sources de Go-Rénove. Pour chaque information affichée vous disposez, dans la fiche du bâtiment, de la source utilisée pour les calculs.<br />
> Le tracé géométrique du bâtiment est issu de la BDTopo, qui inclut les débords de toitures éventuelles, et se base sur une résolution à +/- 50cm.<br />
> La hauteur moyenne fournie par l'IGN peut être assez juste à +/-1 m pour un immeuble simple à toit plat, mais plus approximative sur un volume complexe.<br />
> Nous travaillons à une meilleure estimation à partir des données LIDAR IGN, mais la couverture du territoire ne devrait être complète qu'en 2025.<br />
> *Mis à jour le 27/02/2023*<br />
> **{1-materiaux} Est-ce que l’information de matériaux des toitures est disponible ? [🔗](/faq#materiaux)**
> Nous identifions les matériaux de toiture effectivement. En revanche, la forme de toiture n'est pas encore connue, engendrant une erreur importante potentielle.<br />
> Nous travaillons à cette identification avec les LIDAR IGN.
> *Mis à jour le 27/02/2023*<br />
> **{1-bnbid} Est-il possible d’utiliser l’identifiant de bâtiment Go-Rénove pour faire le lien avec notre référentiel privé ? [🔗](/faq#bnbid)**
> Il est actuellement préférable d’utiliser l’adresse postale pour faire la connexion avec les données Go-Rénove.<br />
> *Mis à jour le 27/02/2023*<br />
