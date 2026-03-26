# [SymfonyLive Paris 2026](https://live.symfony.com/2026-paris/) talks

> [!IMPORTANT]
> <ins>If you're a speaker, please consider sharing your insights in a blog post</ins>, it would really help beginners and uplift the entire community! 🤗

> [!NOTE]
> - All talks are in **French**.
> - You can send feedback and love to speakers on their social networks.
> - Social posts during the event: [Bluesky](https://bsky.app/search?q=%23symfony_live+since%3A2026-03-25+until%3A2026-03-29) · [Mastodon](https://mastodon.social/tags/symfony_live) · [Twitter](https://x.com/search?q=(%23symfony_live%20OR%20%40symfonylive)%20until%3A2026-03-29%20since%3A2026-03-25%20-filter%3Areplies&f=live)

#### Blog post & videos about the event

- _Your blog post here? [Modify this file and send a PR](https://github.com/SymfonyLive/paris-2026-talks/edit/main/README.md)_

---

## Keynote · Concevoir des TUI en PHP : le composant Symfony Terminal

<dl>
  <dt>Description</dt>
  <dd>Avec la migration des agents de codage de l'IDE vers le terminal, les TUI (Text User Interface) connaissent une véritable renaissance. Cette session introduit le nouveau composant Symfony Terminal, un toolkit TUI intégralement développé en PHP. Nous explorerons son architecture, les primitives exposées, et la manière dont il permet de concevoir des interfaces terminal riches et interactives au sein des applications Symfony. Ne manquez pas l'ouverture de la pull request en direct sur scène !</dd>
</dl>

~~Slides~~  
~~Video~~  
[Blog post](https://symfony.com/blog/introducing-the-symfony-tui-component)  
[PR of the new component](https://github.com/symfony/symfony/pull/63778)

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
💻 on [![github](icon/github.svg) @fabpot](https://github.com/fabpot)  <sup>[💚](https://github.com/sponsors/fabpot)</sup>  
✍ on [🌐 fabien.potencier.org](https://fabien.potencier.org)  
💬 on [![bluesky](icon/bluesky.svg) @fabien.potencier.org](https://bsky.app/profile/fabien.potencier.org)
· [![mastodon](icon/mastodon.svg) @fabpot@mastodon.social](https://mastodon.social/@fabpot)
· [![twitter](icon/twitter.svg) @fabpot](https://twitter.com/fabpot)
· [![linkedin](icon/linkedin.svg) @fabienpotencier](https://www.linkedin.com/in/fabienpotencier)

---

## Chiffrez vos données avec Doctrine, en restant recherchable

<dl>
  <dt>Description</dt>
  <dd>Stocker l'email, la date de naissance ou le numéro de sécurité sociale de vos utilisateurs en clair est un risque majeur en cas de fuite de base de données. Avec un chiffrement robuste coté applicatif, on peut rendre la donnée illisible par la base de données. Mais alors il impossible de faire un WHERE email = :valeur. Comment sécuriser vos données sensibles sans sacrifier les fonctionnalités métier indispensables ? Nous verrons comment implémenter le chiffrement par champ coté client avec Doctrine et un système de gestion de clé. Les algorithmes à utiliser, gestion des clés et leur rotation : apprenez à transformer votre base de données en coffre-fort sans perdre votre capacité à la requêter.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Jérôme Tamarelle](https://connect.symfony.com/profile/gromnan)  
💻 on [![github](icon/github.svg) @GromNaN](https://github.com/GromNaN)  
✍ on [🌐 dev.to/gromnan](https://dev.to/gromnan/)  <sup>[![rss](icon/rss.svg)](https://dev.to/feed/gromnan/)</sup>  
💬 on [![twitter](icon/twitter.svg) @GromNaN](https://twitter.com/GromNaN)
· [![linkedin](icon/linkedin.svg) jerometamarelle](https://www.linkedin.com/in/jerometamarelle)

---

## 100 crons par seconde, le Scheduler se venge

<dl>
  <dt>Description</dt>
  <dd>On est partis d’un cron solitaire, tournant discrètement dans l’ombre d’un serveur. Aujourd’hui, on orchestre un Scheduler Symfony distribué, déployé sur Kubernetes, capable de piloter des centaines de tâches en parallèle avec fiabilité. Ce talk raconte cette migration pleine d’enseignements — entre verrous, scalabilité horizontale, observabilité, et une bonne dose de magie Symfony. Vous y découvrirez comment un simple cron s’est transformé en un système robuste, mais aussi les nombreux pièges rencontrés en chemin : - des problèmes d’observabilité difficiles à diagnostiquer, - des locks Symfony qui bloquent tout le scheduler, - et quelques surprises liées au scaling horizontal. Bref, une aventure concrète, pleine de sueur, de logs, de metric, et de solutions ingénieuses.</dd>
</dl>

[Slides](https://speakerdeck.com/jaugustin/100-crons-par-seconde-le-scheduler-se-venge)  
~~Video~~  
~~Blog post~~

By [Jérémie Augustin](https://connect.symfony.com/profile/jaugustin)  
💻 on [![github](icon/github.svg) @jaugustin](https://github.com/jaugustin)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @jaugustin](https://twitter.com/jaugustin)

---

## Passez à la vitesse supérieure avec le JsonStreamer

<dl>
  <dt>Description</dt>
  <dd>Vos APIs sont trop lentes à répondre ? L'indexation massive de documents dans Elasticsearch devient un cauchemar de performance ? Le temps de sérialisation ralenti vos traitements batch ? Découvrez JsonStreamer, le nouveau composant Symfony qui révolutionne la sérialisation JSON en streaming et booste drastiquement la vitesse de vos serialisations ! À travers ce cas pratique, vous découvrirez comment nous avons transformé notre pipeline d'indexation et les enseignements que vous pouvez en tirer pour vos propres projets !</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Gary Pegeot](https://connect.symfony.com/profile/gary-p)  
💻 on [![github](icon/github.svg) @GaryPEGEOT](https://github.com/GaryPEGEOT)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @GPegeot](https://twitter.com/GPegeot)
· [![linkedin](icon/linkedin.svg) gary-pegeot](https://www.linkedin.com/in/gary-pegeot-a0139b6b)

---

## Développer un Coding Agent en PHP : dans les coulisses du "Harness"

<dl>
  <dt>Description</dt>
  <dd>Alors que le benchmarking de modèles est omniprésent, le modèle ne représente en réalité que la moitié de la solution. Cette conférence plonge dans les rouages d'un Coding Agent conçu entièrement en PHP et démontre que "le harness" — l'infrastructure qui entoure le modèle — détermine réellement la qualité du résultat. Nous analyserons le fonctionnement interne d'un "harness" : gestion du contexte, orchestration des outils, construction des prompts et boucles de rétroaction. Venez assister à une démonstration en direct propulsée par les fibers PHP ... la preuve que PHP est parfaitement taillé pour ces enjeux !</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
💻 on [![github](icon/github.svg) @fabpot](https://github.com/fabpot)  <sup>[💚](https://github.com/sponsors/fabpot)</sup>  
✍ on [🌐 fabien.potencier.org](https://fabien.potencier.org)  
💬 on [![bluesky](icon/bluesky.svg) @fabien.potencier.org](https://bsky.app/profile/fabien.potencier.org)
· [![mastodon](icon/mastodon.svg) @fabpot@mastodon.social](https://mastodon.social/@fabpot)
· [![twitter](icon/twitter.svg) @fabpot](https://twitter.com/fabpot)
· [![linkedin](icon/linkedin.svg) @fabienpotencier](https://www.linkedin.com/in/fabienpotencier)

---

## Du web au mobile avec Symfony & Hotwire Native

<dl>
  <dt>Description</dt>
  <dd>Et si votre application Symfony pouvait alimenter à la fois le web et des applications mobiles natives, sans tout réécrire en Swift, Kotlin ou React Native ? Dans ce talk, nous verrons comment Symfony, combiné à Hotwire Native, permet une approche write once, ship everywhere. À partir d’une application web Symfony classique, nous montrerons comment réutiliser le même backend, les vues et la logique métier pour livrer des applications iOS et Android natives, performantes et maintenables. Nous aborderons notamment : L’architecture de Hotwire Native et son intégration avec Symfony Le partage de code entre le web et le mobile Des cas d’usage concrets (QR code, NFC, scan de documents) Les compromis face aux approches 100 % natives ou React Native Ce talk s’adresse aux développeurs Symfony, CTO et tech leads souhaitant lancer des applications mobiles plus rapidement, réduire les coûts de maintenance et conserver une stack simple, sans sacrifier l’expérience utilisateur.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Imad ZAIRIG](https://connect.symfony.com/profile/zairigimad)  
💻 on [![github](icon/github.svg) @zairigimad](https://github.com/zairigimad)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @zairigimad](https://twitter.com/zairigimad)

---

## L’IA au service des devs : Anatomie d'un assistant de Code Review

<dl>
  <dt>Description</dt>
  <dd>Tout a commencé avec une idée simple : Et si l’IA pouvait rendre nos revues de code plus cohérentes, plus rapides… et un peu moins pénibles ? Chez Yousign, cette question est née d’un besoin plus large : Comment faire évoluer la pratique de Code Review à l’échelle, sans perdre la rigueur ni la culture d’équipe ? L’enjeu n’était pas seulement technique, mais organisationnel : Faire du Code Review un moment d’apprentissage partagé, au service de la qualité et de la transmission. Et c’est là que l’IA entre en jeu, non pas pour remplacer le regard humain, mais pour aider à structurer, amplifier et diffuser les bonnes pratiques à travers toute l’équipe. Un retour d’expérience honnête et pragmatique sur la place que peut prendre l’IA dans nos pratiques de développement et d’équipe.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Thomas Boileau](https://connect.symfony.com/profile/tboileau)  
💻 on [![github](icon/github.svg) @TBoileau](https://github.com/TBoileau)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @toham_tech](https://twitter.com/toham_tech)

---

## Symfony + FrankenPHP : une DX comme vous n'en avez jamais vu

<dl>
  <dt>Description</dt>
  <dd>Oubliez tout ce que vous savez sur la mise en place d'un environnement de développement PHP. Fini les configurations complexes de php-fpm, les galères de permissions sur Docker ou la lenteur de la régération du cache de l'application à chaque rafraîchissement (Sylius, je te vois). En 2026, FrankenPHP a non seulement révolutionné la production, mais il redéfinit totalement la Developer Experience (DX) de Symfony. Dans ce talk, je vous montrerai comment nous avons repoussé les limites du serveur d'application pour offrir un workflow fluide, instantané et moderne.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
💻 on [![github](icon/github.svg) @dunglas](https://github.com/dunglas)  <sup>[💚](https://github.com/sponsors/dunglas)</sup>  
✍ on [🌐 dunglas.dev](https://dunglas.dev/)  <sup>[![rss](icon/rss.svg)](https://dunglas.dev/feed/)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @dunglas.dev](https://bsky.app/profile/dunglas.dev)
· [![mastodon](icon/mastodon.svg) @dunglas@mastodon.social](https://mastodon.social/@dunglas)
· [![twitter](icon/twitter.svg) @dunglas](https://twitter.com/dunglas)
· [![linkedin](icon/linkedin.svg) dunglas](https://www.linkedin.com/in/dunglas)

---

## Reconfigurer Symfony en temps réel avec des sidekicks applicatifs

<dl>
  <dt>Description</dt>
  <dd>PHP a longtemps été pensé comme un langage strictement stateless : une requête, un processus, puis tout recommence. FrankenPHP change profondément ce contrat en permettant de lancer des workers PHP long-running directement au sein d’une application Symfony. Dans cette conférence, je propose un nouveau pattern : les sidekicks applicatifs. Des workers PHP spécialisés, hors cycle HTTP, qui écoutent leur environnement et reconfigurent l’application en temps réel — sans polling, sans TTL approximatifs, sans redeploy.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
💻 on [![github](icon/github.svg) @nicolas-grekas](https://github.com/nicolas-grekas)  <sup>[💚](https://github.com/sponsors/nicolas-grekas)</sup>  
✍ on [🌐 medium.com/@nicolas.grekas](https://medium.com/@nicolas.grekas)  <sup>[![rss](icon/rss.svg)](https://medium.com/feed/@nicolas.grekas)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @nicolasgrekas.bsky.social](https://bsky.app/profile/nicolasgrekas.bsky.social)
· [![mastodon](icon/mastodon.svg) @nicolasgrekas@phpc.social](https://phpc.social/@nicolasgrekas)
· [![twitter](icon/twitter.svg) @nicolasgrekas](https://twitter.com/nicolasgrekas)
· [![linkedin](icon/linkedin.svg) @nicolasgrekas](https://linkedin.com/in/nicolasgrekas)

---

## Doctrine inheritance

<dl>
  <dt>Description</dt>
  <dd>Vous avez déjà eu envie de faire hériter des tables comme des classes lorsque vous modélisez votre base de données ? Vous devriez lier une entité à plusieurs autres de type similaire ? Doctrine prend en charge l’héritage pour gérer cela proprement. Par exemple, vous pouvez définir une entité de base User et l’étendre avec des classes Admin et Customer (chacune avec sa propre table ou une table partagée). On verra ensemble les stratégies disponibles, quand les utiliser, ainsi que les pièges courants. Aucune connaissance préalable de l’héritage Doctrine n’est requise !</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Rémi Janot](https://connect.symfony.com/profile/rjanot)  
💻 on [![github](icon/github.svg) @rjanot](https://github.com/rjanot)  
_✍ blog not found_  
💬 on [![linkedin](icon/linkedin.svg) rjanot](https://www.linkedin.com/in/rjanot)

---

## ClickHouse pour les développeurs Symfony

<dl>
  <dt>Description</dt>
  <dd>On a tous une MySQL ou une PostgreSQL dans notre stack Symfony et elles font un super job. Pour autant, pour de l'analytique, des logs ou des métriques, lorsqu'on a besoin de performance temps-réel à grande échelle ou gros volume, on peut atteindre facilement leurs limites. C'est à ce moment que ClickHouse vous sauve. Dans ce talk, nous verrons : - L'architecture des bases de données orientées colonnes et dans quels cas elles nous épatent - Comment interagir avec ClickHouse dans une app Symfony - Comment déployer ClickHouse en quelques lignes - Les fonctionnalités clés pour construire des dashboards temps-réel - Des exemples concrets d'agrégations avec des benchmarks - Des trucs et astuces et des bonnes pratiques.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Romain Neutron](https://connect.symfony.com/profile/romain)  
💻 on [![github](icon/github.svg) @romain](https://github.com/romain)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @romain](https://twitter.com/romain)
· [![linkedin](icon/linkedin.svg) romainneutron](https://www.linkedin.com/in/romainneutron)

---

## JSON + SQL : hérésie ou élégance ? Retour d'expérience

<dl>
  <dt>Description</dt>
  <dd>Aujourd’hui nous vous proposons un réel retour d’expérience au sein d’un projet Symfony ambitieux qui nous a amené à revoir complètement notre manière d’organiser les données métier. La modélisation de données dynamiques, et notamment d'un modèle EAV apportent souvent beaucoup de complexité et de lourdeur à un modèle relationnel. Nous vous proposons de montrer la flexibilité qu'offre les SGBD récents + JSON dans des cas concrêts. Quels sont les avantages de modéliser des données avec des champs JSON ? Pourquoi cela offre des moyens de requêtages particulièrement puissants avec JSON (extract/contains/table) mais également de mise à jour en masse ciblé ? Comment exploiter ces fonctionnalités et surtout comment les encadrer proprement côté Symfony grâce à des UDF DQL, DTOs typés et validations ciblées ?</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Rémy Bonfils](https://connect.symfony.com/profile/remy_bonfils)  
_✍ blog not found_  

And [Olivier FOURNY](https://connect.symfony.com/profile/ofourny)  
_✍ blog not found_  

---

## Embeddings en PHP : Symfony AI en pratique

<dl>
  <dt>Description</dt>
  <dd>On parle beaucoup d’IA, mais rarement de ce qu’on peut *vraiment* en faire dans un projet PHP. Avec Symfony AI, il devient enfin possible de manipuler des modèles d’embeddings, de génération ou de classification sans quitter son écosystème habituel. Dans ce talk, on explore concrètement l’usage des **embeddings** avec Symfony AI, à travers un exemple simple : rapprocher automatiquement des pages web par similarité.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Grégoire Pineau](https://connect.symfony.com/profile/lyrixx)  
💻 on [![github](icon/github.svg) @lyrixx](https://github.com/lyrixx)  <sup>[💚](https://github.com/sponsors/lyrixx)</sup>  
✍ on [🌐 jolicode.com/blog](https://jolicode.com/qui-sommes-nous/equipe/gregoire-pineau)  <sup>[![rss](icon/rss.svg)](https://jolicode.com/feed.rss)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @lyrixx.bsky.social](https://bsky.app/profile/lyrixx.bsky.social)
· [![mastodon](icon/mastodon.svg) @lyrixx@mastodon.social](https://mastodon.social/@lyrixx)
· [![twitter](icon/twitter.svg) @lyrixx](https://twitter.com/lyrixx)

---

## Édition simultanée : facile avec Symfony UX

<dl>
  <dt>Description</dt>
  <dd>Plus besoin de développer une application frontend séparée en Javascript pour créer des applications web rapides et interactives. Avec Hotwire Turbo, le HTML et ses fragments se chargent de façon asynchrone, et grâce à Turbo Streams, vous pouvez même pousser des mises à jour directement du backend vers le frontend. Hotwire Stimulus vient compléter Turbo avec un outil élégant pour ajouter la logique Javascript uniquement là où elle est indispensable. Le tout est parfaitement intégré dans Symfony grâce aux composants Symfony UX.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [David Buchmann](https://connect.symfony.com/profile/dbu)  
💻 on [![github](icon/github.svg) @dbu](https://github.com/dbu)  
✍ on [🌐 davidbu.ch/mann/blog](https://davidbu.ch/mann/blog)  <sup>[![rss](icon/rss.svg)](https://davidbu.ch/mann/atom.xml)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @dbu@phpc.social](https://phpc.social/@dbu)
· [![twitter](icon/twitter.svg) @dbu](https://twitter.com/dbu)
· [![linkedin](icon/linkedin.svg) david-buchmann-…](https://linkedin.com/in/david-buchmann-5308654)

---

## Les nouveaux design patterns IA avec Symfony

<dl>
  <dt>Description</dt>
  <dd>Les fonctionnalités modernes d’IA exigent plus qu’un simple appel d’API rapide. Dans cette présentation, vous découvrirez comment de nouveaux patterns émergent pour rendre les LLM fiables, testables et prêts pour la production, au sein d’une stack Symfony. Idéal pour ceux qui ont expérimenté les LLM et qui ont désormais besoin d’un plan directeur pour livrer des fonctionnalités d’IA fiables en production.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
💻 on [![github](icon/github.svg) @tgalopin](https://github.com/tgalopin)  
✍ on [🌐 titouangalopin.com](https://titouangalopin.com)  
💬 on [![twitter](icon/twitter.svg) @tgalopin](https://twitter.com/tgalopin)
· [![linkedin](icon/linkedin.svg) titouangalopin](https://linkedin.com/in/titouangalopin)

---
