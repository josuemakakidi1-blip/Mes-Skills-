# Vellum + Magnet (écosystème « l'aimant et le métal ») · Business plan

**Verdict: Not yet**

- ✓ Each client-mois (abonnement Magnet Pro) earns $11.65 before fixed costs (58% contribution).
- ✓ Year 1 operating profit: $2,241.
- ✓ Break-even is 11 client-mois (abonnement Magnet Pro)s a day against a capacity of 80.
- ✗ 3 of 20 simulated buyers buy (15%, the bar is 25%).

| key number | |
| --- | ---: |
| Price | $20.00 a client-mois (abonnement Magnet Pro) |
| Profit margin at plan | 48% per client-mois (abonnement Magnet Pro) |
| Break-even | 11 client-mois (abonnement Magnet Pro)s a day |
| Year 1 operating profit | $2,241 |
| Startup spend | $118 |
| Cash needed before it pays for itself | $257 |
| Startup money earned back | month 6 |
| Buyer panel | 3 buy · 17 pass |

## The idea

- What it is: Vellum, une agence de création de sites web déjà en activité à Kinshasa, s'associe à Magnet, une application de prospection automatique (trouver des prospects, envoyer un premier message personnalisé, relancer automatiquement) sur WhatsApp, puis Facebook et LinkedIn.
- Who it is for (proposition, à valider par le panel) : les PME, commerces et indépendants de Kinshasa (restaurants, salons, boutiques, agences, commerciaux, freelances, coachs) qui vendent par WhatsApp et n'ont pas d'équipe commerciale.
- What it sells, at what price (HYPOTHÈSES de départ, à tester ; prix en USD, monnaie d'usage pour le B2B à Kinshasa) :
  - Magnet seul : abonnement mensuel, hypothèse ~15 USD/mois (formule Solo).
  - Site Vellum + Magnet intégré (bouton WhatsApp intelligent qui capte et relance les visiteurs) : création du site en paiement unique (hypothèse ~150 à 300 USD) + abonnement Magnet mensuel.
  - Boucle interne : Magnet prospecte pour Vellum ; les entreprises contactées qui n'ont pas de site se voient proposer un site Vellum.
- Where and how: Kinshasa (RDC), d'abord Gombe et les communes commerçantes ; vente par WhatsApp, démarchage direct et bouche-à-oreille ; paiement Mobile Money (M-Pesa, Orange Money, Airtel Money) ou cash USD ; livraison 100 % en ligne.
- Budget and constraints: fondateur solo, 0 USD de capital de départ, seulement le temps et la détermination. Vellum est déjà opérationnel et finance le développement de Magnet. Le MVP de Magnet (recherche + premier contact sur WhatsApp) sort ce mois-ci (octobre 2026). Facebook et LinkedIn viendront après.
- Status: idée/écosystème au stade du lancement ; aucun client Magnet payant à ce jour ; les tarifs et le nombre de clients actuels de Vellum n'ont pas été communiqués.

## Summary

**Verdict : PAS ENCORE (Not yet).** Les chiffres tiennent, mais seulement 3 acheteurs simulés sur 20 achètent (15 %, la barre est 25 %). **Ce qui doit changer : la confiance, pas le prix.** 11 des 17 « non » sont des problèmes de confiance (« ça fait arnaque », « je ne connais pas Vellum », « ma réputation »). La correction passe par l'offre (pilotes gratuits payés au résultat, installation en personne, validation de chaque message), puis par une **vraie** preuve : les pilotes du plan de lancement (`/founder-launch`) et un nouveau passage du panel (`/founder-consumer`) avec le nouveau pitch.

**Ce que c'est.** Vellum (agence web déjà active à Kinshasa) et Magnet (app qui trouve des prospects, leur écrit sur WhatsApp et relance automatiquement) vendent ensemble un « système client » aux PME, agences et indépendants de Kinshasa qui n'ont pas d'équipe commerciale.

**Les trois chiffres** (Magnet Pro à 20 USD/mois, coûts en grande partie estimés) : chaque client laisse **11,65 USD** de marge (58 %) ; **seuil de rentabilité : 11 clients actifs** ; **année 1 : +2 241 USD** de bénéfice d'exploitation (+2 123 USD après les 118 USD de démarrage), si la montée à 52 clients se fait.

**Conseil et panel.** Le conseil vote 3 « financer si » (4,3/10). Il est unanime sur deux risques : le blocage WhatsApp/Meta et l'absence de preuve. Le panel confirme la confiance comme frein n° 1 et montre où sont les acheteurs : PME, agences et indépendants « ambitieux digital » ; **0 % chez les petits commerces de quartier**. Désaccord : le conseil voit dans la boucle Vellum ↔ Magnet un canal (Monopole) ou une dispersion (Produit). Le panel juge 25 USD trop cher pour l'ensemble (zone acceptable 5 à 20 USD), mais pas pour les segments qui achètent.

**Le plus gros risque** : envoyer hors des règles de WhatsApp et faire bloquer les numéros des clients. **Réponse** : API WhatsApp Business officielle uniquement, validation de chaque message, « ne plus recevoir », petits volumes ciblés.

**Pour démarrer** : environ **257 USD** de trésorerie avant que Magnet se paie (à financer par 1 ou 2 sites Vellum), puis le premier test : faire tourner Magnet pour Vellum, ensuite 10 pilotes.

**Cette semaine** : ouvrir le compte officiel WhatsApp Business Platform (Cloud API) au nom de Vellum, faire vérifier l'entreprise par Meta et confirmer le prix réel d'un message en RDC.

## What the board said

**Vote : 3 « financer si » (FUND IF), 0 « financer », 0 « refuser ». Note moyenne : 4,3 / 10.**
(Lentille Offre 5/10 · Lentille Monopole 4/10 · Lentille Produit 4/10 — mémos complets dans `board/`.)

Les trois lentilles résument des cadres publiés ; ce ne sont pas les auteurs qui parlent.

### Les risques soulevés par plusieurs membres (en premier)

1. **WhatsApp / Meta (les 3 membres).** Si Magnet envoie hors de l'API officielle, Meta peut bannir le numéro du client : le produit détruirait son principal outil de vente. Avec l'API officielle, il y a un coût par message et des règles d'opt-in à intégrer dans le prix.
2. **Aucune preuve (les 3).** Aucun client Magnet payant, aucun résultat mesuré sur Vellum, prix et clients actuels de Vellum non communiqués.
3. **Trop de choses à la fois / pas de cible unique (Produit + Monopole).** Agence, outil, bouton, 3 réseaux sociaux, 6 cibles : il faut une seule promesse pour un seul segment.
4. **Spam et réputation (Monopole + Produit).** Un premier message raté, envoyé au nom du client, abîme sa réputation ; un Gombe saturé de messages automatiques fait chuter les taux de réponse.
5. **Prix trop bas (Offre).** À ~15 USD/mois, Magnet ressemble à une marchandise ; il faut vendre un résultat empilé et tester un prix plus haut.

### Désaccords
- Le Monopole voit dans la boucle Vellum ↔ Magnet un vrai canal de distribution ; le Produit y voit d'abord de la dispersion.
- L'Offre pense que le prix peut monter (30-50 USD) si l'offre est empilée ; les autres ne se prononcent pas sur le prix mais doutent de la barrière à la copie.

### Conditions à cocher (le reste du pack les teste)
- [ ] Choisir une voie WhatsApp conforme (API officielle, opt-in/opt-out, petit volume) et intégrer le coût réel par message — **CFO**
- [ ] Une promesse, une cible de départ — **marketing / panel**
- [ ] Prouver sur Vellum d'abord (taux de réponse mesuré), puis 3 à 5 clients pilotes payants accompagnés à la main — **launch**
- [ ] Vendre un résultat empilé (site + captation + relance + messages rédigés + rapport) avec une garantie conditionnelle — **pricing**
- [ ] Tester un prix nettement au-dessus de 15 USD/mois — **pricing**
- [ ] Signer 10 clients Magnet payants dans un segment avant d'ouvrir Facebook et LinkedIn — **launch**
- [ ] Tester le parcours complet jusqu'au paiement Mobile Money — **launch**
- [ ] Identifier la barrière (données locales, intégration site + Magnet, marque de confiance) — **brand / marketing**

### La version la plus forte que le conseil voit

Pas « une agence + une app », mais **un « système client WhatsApp » clé en main pour un seul type de commerce de Kinshasa** : Vellum livre un site simple qui capte les contacts, Magnet relance automatiquement et proprement (API officielle) ceux qui ont laissé leur numéro ou qui ont été contactés en B2B ciblé, et Vellum rédige les messages et envoie un rapport chaque semaine. Payable en Mobile Money, vendu avec une preuve chiffrée tirée de Vellum lui-même. C'est plus étroit que ce qui a été pitché : moins de réseaux, une seule cible, et la relance (pas l'envoi en masse) comme cœur du produit.

## The competition

Recherche faite le 27/10/2026, sources publiques uniquement. Limite importante : je n'ai trouvé **aucune agence web kinoise publiant ses prix** ni aucun outil de prospection local à Kinshasa ; les fourchettes de prix des sites viennent presque toutes d'un seul prestataire (Kolonell) qui vend ces services : ce sont des chiffres marketing, pas des tarifs vérifiés. Les avis clients des concurrents n'ont pas pu être lus (pages d'avis non relevées) : la section « plaintes » est donc **mince** et à compléter sur le terrain.

### 1. Le tableau (du plus direct au moins direct)

| Concurrent | Type | Prix comparable | Ce qu'il vend |
|---|---|---|---|
| [Bulk senders + extracteurs Google Maps](https://codecanyon.net/search/google-maps-leads) | Direct, bas de gamme | ~19 à 99 USD, paiement unique | Extraction de numéros + envoi en masse non officiel |
| [WATI](https://www.capterra.co.za/reviews/204314/wati) | Direct (WhatsApp) | dès 59 USD/mois + messages | Plateforme WhatsApp Business API |
| [Waalaxy](https://emelia.io/fr/software/waalaxy/prix) | Direct (LinkedIn) | 0 € limité ; 19 à 49 €/mois (sources divergentes) | Prospection LinkedIn automatisée |
| [MapsScraper](https://alternativeto.net/software/mapsscraper/about/) | Indirect | 0 à 9,90 USD/mois | Trouver des prospects sur Google Maps |
| [Apify Maps Leads](https://apify.com/tugelbay/google-maps-leads) | Indirect | 3,50 USD / 1 000 leads | Idem, à l'usage |
| [Intégrateur WhatsApp sur mesure](https://kolonell.com/fr/blog/automatiser-relances-clients-whatsapp-business-api-distributeur-yaounde-2026) | Indirect | 2,5 à 4 M FCFA + 35 000-120 000 FCFA/mois | Relances WhatsApp automatisées sur mesure |
| [Agences web de Kinshasa](https://kolonell.com/fr/blog/meilleure-agence-web-kinshasa-types-prestataires-budgets-usd-2026) | Direct pour Vellum | vitrine ~1 300 à 4 000 USD | Sites vitrines |
| Prospection manuelle | Substitut | 0 USD, des heures | Le problème que Magnet attaque |
| [Apporteurs d'affaires](https://kolonell.com/fr/blog/prospection-whatsapp-apporteur-affaires-pme-2026) | Substitut | commission | Un humain qui ramène des clients |

### 2. Fourchette de prix

- **Outil de prospection (mensuel)** : le plus bas 0 USD (versions gratuites limitées), médiane ~20-50 USD/mois, le plus haut ~60-100 USD/mois (WATI, Waalaxy avec email) — tous pensés pour des marchés européens/internationaux, payés par carte bancaire.
- **Site vitrine à Kinshasa** (fourchettes Kolonell, non vérifiées) : bas ~1 300 USD, typique 2 500-4 000 USD. C'est très au-dessus de ce qu'un petit commerce kinois peut payer : il y a vraisemblablement tout un marché informel de freelances moins chers, **non documenté en ligne** (à vérifier sur le terrain).
- **Coût d'un message WhatsApp officiel en RDC** (tiers, à confirmer sur la grille Meta) : ~0,0225 USD par message marketing, ~0,004 USD par message utilitaire, réponses de service gratuites ([sent.dm](https://docs.sent.dm/docs/guides/whatsapp-pricing), [Meta](https://developers.facebook.com/docs/whatsapp/pricing)).

### 3. Carte de positionnement (texte)

Axes : **adapté au marché kinois** (paiement Mobile Money, français, WhatsApp d'abord, accompagnement humain) ↔ **outil générique international** ; et **automatisé et conforme** ↔ **manuel ou risqué**.

- Générique + conforme : WATI, Waalaxy (chers, carte bancaire, pas pensés pour Kinshasa).
- Générique + risqué : bulk senders Gumroad/CodeCanyon (pas chers, mais bannissement des numéros).
- Local + manuel : prospection à la main, apporteurs d'affaires, freelances web.
- **Local + automatisé + conforme : case vide.** C'est là que Vellum + Magnet peut se placer.

### 4. Les plaintes (mince : moins de 3 sources chacune)

- **Bannissement des numéros WhatsApp** quand un compte neuf envoie en masse ([Kolonell](https://kolonell.com/fr/blog/whatsapp-business-prospection-pme-afrique-2026)) — thème mince mais critique pour Magnet.
- **Envoi non consenti = hors règles WhatsApp et lois anti-spam/données** (risque signalé à propos des bulk senders).
- **Prix et modes de paiement** inadaptés : outils en € ou USD par carte, coût des messages en plus.
- Avis WATI / Waalaxy non lus : à compléter.

### 5. Le trou dans le marché

Personne ne vend, à Kinshasa, **en francais, payable en Mobile Money, un « système client » complet** : un site qui capte les visiteurs + des relances WhatsApp automatiques + de l'aide humaine pour démarrer. Les outils internationaux sont trop chers et trop complexes ; les outils pas chers font bannir les numéros ; les agences vendent un site « joli » qui ne vend pas.

Attention : le trou n'existe **que si Magnet reste du bon côté des règles WhatsApp** (API officielle, messages à des gens qui ont donné leur numéro ou au minimum un premier message B2B ciblé, petit volume, opt-out). Un Magnet qui envoie en masse à des numéros extraits se retrouve dans la case « bulk sender », celle qui se fait bannir.

### 6. La menace

- **Copie la plus rapide** : n'importe quel freelance kinois peut revendre un bulk sender Gumroad à 20 USD comme « son logiciel ». Défense : la conformité, les résultats prouvés et le service.
- **Meta lui-même** (outils natifs WhatsApp Business de plus en plus riches) et les plateformes API (WATI, Interakt...) si elles ajoutent le Mobile Money et le français.

## The buyer panel

**3 buy · 17 pass** (15% buy) out of 20 simulated buyers. Seed 255962, so the same cards can be dealt again.

These are simulated buyers, not customers. Use this to find objections and weak spots, then confirm the big ones with real people before you spend.

### By segment

| group | buyers | buy rate |
| --- | ---: | ---: |
| Petite agence (marketing, événementiel, immobilier) | 2 | 50%  (thin) |
| PME établie à Gombe (5 à 30 employés) | 5 | 20%  (thin) |
| Freelance, commercial indépendant ou coach | 5 | 20%  (thin) |
| Petit commerce de quartier (salon, restaurant, boutique) | 8 | 0% |

### By buying behaviour

| group | buyers | buy rate |
| --- | ---: | ---: |
| Ambitieux digital | 3 | 100%  (thin) |
| Chasseur de prix | 3 | 0%  (thin) |
| Tout sur WhatsApp perso | 5 | 0%  (thin) |
| Délègue à un proche | 3 | 0%  (thin) |
| Bouche-à-oreille | 3 | 0%  (thin) |
| Méfiant des arnaques en ligne | 3 | 0%  (thin) |

### By income

| group | buyers | buy rate |
| --- | ---: | ---: |
| $11,000 and up | 8 | 38% |
| $7,000 to $11,000 | 7 | 0%  (thin) |
| under $7,000 | 5 | 0%  (thin) |

### Why they pass

| reason | buyers | in their words |
| --- | ---: | --- |
| trust | 11 | "Moi-même quand je reçois un message d'un numéro inconnu, je pense directement à une arnaque et je supprime, alors pourquoi les gens réagiraient autrement avec mes messages ? Et 25 dollars chaque mois, c'est beaucoup pour moi alors que mon statut WhatsApp ne me coûte rien." (P001) · "Je ne connais pas Vellum, et je ne vais pas laisser une appli inconnue écrire à des clients en mon nom. Mes clients viennent du bouche-à-oreille et de mes groupes WhatsApp, si un message automatique sonne faux c'est ma réputation qui prend." (P004) |
| need | 2 | "Mes clients, ce sont les gens du quartier qui passent devant et ceux qui voient mon statut le matin, pas des restaurants de Gombe à prospecter. 25 dollars par mois pour envoyer des messages à des inconnus, ce n'est pas pour un petit commerce comme le mien." (P002) · "Mes clients viennent du bouche-à-oreille et de mes statuts WhatsApp, ça marche déjà. 25 dollars par mois, c'est presque une semaine de ce que je gagne, pour envoyer des messages à des inconnus qui ne me connaissent pas." (P007) |
| price | 2 | "25 dollars chaque mois, c'est trop pour mon petit commerce, mes clients viennent du quartier et du bouche-à-oreille. Et ces applications, c'est pour les grandes entreprises, pas pour moi." (P006) · "25 dollars chaque mois, c'est trop pour moi quand il y a des mois où je ne gagne presque rien. Mes clients viennent par recommandation, je ne vois pas pourquoi payer une machine pour envoyer des messages à des inconnus." (P013) |
| habit | 2 | "Mes clients viennent par recommandation depuis des années, ça marche, je ne vois pas pourquoi payer une application pour envoyer des messages à des inconnus. Et avec les coupures d'internet et de courant, je n'ai pas le temps d'apprendre un nouvel outil." (P009) · "Mes clients viennent par recommandation et par mes groupes WhatsApp de commerçants, ça marche déjà. Payer 25 dollars par mois pour qu'une machine écrive à des inconnus en mon nom, je ne vois pas pourquoi, surtout que je gagne peu." (P012) |

### Why they buy

| reason | buyers | in their words |
| --- | ---: | --- |
| convenience | 2 | "10 dollars pour un mois, en M-Pesa, et c'est leur équipe qui installe et écrit les premiers messages : je n'ai rien à apprendre, je teste et je vois si des clients répondent. Si le rapport ne montre pas de vrais clients au bout du mois, j'arrête." (P003) · "À 10 dollars avec l'équipe qui installe tout et rédige les premiers messages, je n'ai rien à apprendre, donc j'essaie un mois pour voir si ça m'amène vraiment des clients. Mais à 25 dollars par mois après, je reste seulement si je vois des clients qui paient dans le rapport." (P017) |
| need | 1 | "Je passe des heures à chercher des clients moi-même sur WhatsApp, et à 10 dollars le premier mois sans engagement, avec l'équipe qui installe tout, je peux essayer sans grand risque. Mais je teste un mois, je ne promets rien pour la suite." (P010) |

### What would flip a no

- Voir un commerçant comme moi, ici à Kinshasa, me montrer qu'il a vraiment gagné des clients qui ont payé grâce à ça, et pouvoir essayer gratuitement d'abord.
- Voir un commerçant comme moi, dans mon quartier, me montrer sur son téléphone des vrais clients qui sont venus acheter grâce à ça, et pouvoir essayer gratuitement d'abord.
- Une commerçante de mes groupes WhatsApp que je connais qui me montre ses vrais résultats, avec des clients gagnés grâce à Magnet.
- Un essai gratuit de deux semaines, ou payer seulement après un premier client trouvé, avec un commerçant que je connais à Kinshasa qui me montre que ça a marché pour lui.
- Voir un commerce comme le mien dans mon quartier qui a vraiment gagné des clients avec ça, et payer seulement quand ça ramène quelqu'un.
- Voir un indépendant comme moi à Kinshasa, que je connais, qui a gagné des clients payants avec ça le premier mois, et pouvoir tester pour presque rien sans risque pour mon numéro.
- Voir un patron que je connais à Gombe qui l'utilise depuis quelques mois et qui a vraiment signé des clients sans abîmer sa réputation, et pouvoir valider chaque message avant qu'il parte.
- Qu'un patron de PME que je connais à Gombe me montre qu'il a signé de vrais clients grâce à ça, et que Vellum s'occupe de tout sans que j'aie à toucher l'application.
- Voir une commerçante comme moi, que je connais ou qu'on me recommande, qui a vraiment gagné des clients avec ça, et pouvoir essayer gratuitement ou presque avant de payer.
- Un commerçant que je connais dans mes groupes WhatsApp qui me montre qu'il a vraiment gagné des clients qui paient grâce à ça.
- Payer seulement quand un nouveau client vient vraiment chez moi grâce à l'application, pas un abonnement fixe.
- Qu'un agent de Vellum passe à ma boutique à Gombe, installe tout devant moi, et que je ne paie qu'après avoir vu des clients arriver grâce aux messages, ou qu'un commerçant que je connais me montre ses résultats.

Buyers say they would buy **1.0 times** in the first month on average.

20 buyers gave all four price answers. Run founder-pricing's van_westendorp.py on the answers folder.

## Pricing

Sources : réponses du panel simulé (`pricing-curve.md`), prix des concurrents (`competitors.md`), marge du CFO (`cfo.md`). Les réponses de prix d'acheteurs simulés servent à choisir **quoi tester**, ce n'est pas une preuve.

### 1. Le prix : Magnet Pro à 20 USD/mois

- **Panel (20 acheteurs)** : zone acceptable **4,92 à 19,88 USD** pour l'ensemble ; 25 USD est **au-dessus**. Mais le panel mélange deux mondes : les petits commerces de quartier (0 % d'achat, « trop cher » dès 10-15 USD) et les PME, agences et indépendants « ambitieux » (ceux qui achètent : ils trouvent cher à 20-35 USD et refusent à 35-60 USD).
- **Concurrents** : outils internationaux 19 à 59 USD/mois + coût des messages (Waalaxy, WATI), payés par carte ; bulk senders 19-99 USD une fois mais risque de bannissement.
- **Marge (outil CFO)** : à 20 USD, contribution 11,65 USD, seuil **11 clients**, marge 48 % à 60 clients. À 12 USD le seuil monte à 33 clients : **ne pas descendre sous 15 USD** avec 300 messages inclus.

→ **20 USD/mois** pour la cible principale (PME, agences, indépendants), juste au-dessus du plafond du panel global mais dans la zone des acheteurs réels du panel, sous WATI/Waalaxy, et avec une marge saine.

### 2. L'échelle (bon / mieux / meilleur)

| Formule | Prix | Inclus | Pour qui | Pourquoi monter |
|---|---|---|---|---|
| **Essentiel** | 12 USD/mois | 100 messages/mois, relance auto, rapport | Freelances, petits commerces | Prix d'entrée sous le seuil « cher » des petits commerces (10-15 USD) ; contribution ~8,8 USD (estimation : 100 msg = 2,25 USD) |
| **Pro** ⭐ | 20 USD/mois | 300 messages, messages rédigés par Vellum, rapport hebdo, validation de chaque message avant envoi | PME, agences, commerciaux | 3× plus de messages + c'est Vellum qui écrit |
| **Business (Vellum + Magnet)** | 150 USD une fois + 25 USD/mois (12 mois) | Site Vellum avec bouton WhatsApp qui capte et relance les visiteurs + Magnet Pro | PME qui n'ont pas de site | Un « système client » complet ; site ~10× moins cher que les vitrines kinoises publiées (~1 300 à 4 000 USD, source Kolonell, non vérifiée) |

Le prix du site Vellum (150 USD) n'a **pas** été testé par le panel et je ne connais pas les prix actuels de Vellum : à ajuster sur vos vrais tarifs.

### 3. L'offre de lancement : « Pilote 0 risque » (10 places, jusqu'au 30 novembre 2026)

Ce que le panel a demandé presque à chaque « non » : **voir un résultat avant de payer** et **quelqu'un de Vellum en vrai**. Donc :
- Installation **en personne** à Gombe, messages rédigés et validés avec le client.
- **Premier mois gratuit** ; le client paie le mois 2 (20 USD) **seulement si le rapport montre au moins 3 réponses intéressées**. Sinon, il part sans rien payer.
- En échange : accepter de montrer ses résultats (avec accord écrit) comme étude de cas.
- Coût pour Magnet : ~6,75 USD de messages par pilote (68 USD pour 10, déjà dans le budget de démarrage du CFO). C'est un prix sous le coût variable pendant 1 mois, assumé et limité à 10 pilotes.

Pas de faux prix barré, pas de « dernières places » inventées.

### 4. Ce qu'il faut tester avec de vrais clients

- **Test A : 15 USD vs 20 USD** pour le Pro : proposer chaque prix à la moitié des prospects PME (message WhatsApp avec lien de paiement Mobile Money), mesurer le taux de paiement sur 30 jours.
- **Test B : abonnement vs paiement au résultat** (ex. 5 USD par prospect qui répond « intéressé ») sur les petits commerces : c'est la forme de prix qu'ils ont réclamée.

### 5. Les objections de prix du panel (verbatim, simulées, à ne pas utiliser comme témoignages)

1. « 25 dollars chaque mois, c'est trop pour moi quand il y a des mois où je ne gagne presque rien. » (P013)
2. « 25 dollars par mois, c'est presque une semaine de ce que je gagne, pour envoyer des messages à des inconnus. » (P007)
3. « À 25 dollars par mois après, je reste seulement si je vois des clients qui paient dans le rapport. » (P017)

## The numbers

### Note du CFO (en clair)

**Comment lire ce tableau** : l'unité est « 1 client abonné pendant 1 mois ». L'outil affiche « a day » : ici, lisez **« clients actifs ce mois-ci »** (on a mis 1 jour par mois pour que le calcul tombe juste). La montée en charge (`ramp`) est le nombre de clients **actifs** chaque mois, désabonnements déjà déduits.

- **La marge** : chaque client à 20 USD/mois laisse **11,65 USD** après ses propres coûts (58 %). Avec 60 clients actifs, la marge nette est de **48 %**.
- **Le seuil de rentabilité** : **11 clients actifs** suffisent à couvrir les 120 USD de frais fixes mensuels.
- **La ligne à surveiller : le prix (et donc le volume de messages inclus).** À 12 USD, le seuil passe à **33 clients** et la marge à 14 % ; à 15 USD, 19 clients ; à 25 USD, 8 clients. Le coût des messages WhatsApp (6,75 USD pour 300 messages) est la plus grosse charge variable : c'est un tarif tiers à confirmer sur la grille officielle de Meta.
- **Trésorerie** : il faut **257 USD** avant que Magnet se paie tout seul (pertes des 3 premiers mois + 118 USD de démarrage). Avec 0 USD au départ, cet argent doit venir de **Vellum** (1 ou 2 sites vendus) ou des pilotes payants. Si les ventes arrivent deux fois moins vite, il faut 421 USD et l'année 1 ne rapporte que 401 USD.
- **Trois façons d'améliorer la marge** (calculées, pas devinées) :
  1. Monter le prix de 20 à 25 USD pour les PME/agences : contribution 16,65 USD, seuil 8 clients, marge 59 %.
  2. Réduire les messages marketing payants en poussant le prospect à répondre (les réponses ouvrent une fenêtre de service gratuite de 24 h) : chaque tranche de 100 messages évités = 2,25 USD de coût en moins par client.
  3. Vendre le site Vellum avec Magnet : chaque site paie à lui seul plusieurs mois de frais fixes (non modélisé ici, voir pricing).
- **Conditions du conseil liées à l'argent** : le coût réel par message est intégré (condition remplie *sur estimation*) ; le prix au-dessus de 15 USD est modélisé (20 USD) mais le panel le juge cher pour les petits commerces (voir pricing).

**Ce qui n'est PAS dans ces chiffres** : votre salaire (0 USD, vous vivez de Vellum), les impôts et taxes congolais (TVA 16 % éventuelle sur le prix), le désabonnement réel, les coupures de service. Ce n'est pas un conseil financier, fiscal ou juridique : faites vérifier la structure et la fiscalité par un comptable avant de facturer.


Every number below comes from the input file. Nothing is looked up or guessed.

### One client-mois (abonnement Magnet Pro)

| line | per client-mois (abonnement Magnet Pro) |
| --- | ---: |
| Price | $20.00 |
| Messages WhatsApp marketing via API officielle (300 x 0,0225 USD, tarif tiers RDC, à confirmer) | -$6.75 |
| Frais Mobile Money (~3 %, estimation) | -$0.60 |
| Données prospects (extraction ~500 fiches, estimation) | -$0.50 |
| Part serveur / IA de rédaction (estimation) | -$0.50 |
| **Contribution** (what each client-mois (abonnement Magnet Pro) leaves to pay the fixed costs) | **$11.65** (58%) |

### The margin that matters

Fixed costs: $120 a month (Hébergement serveur Magnet (estimation) $15, Forfait internet / data + crédit téléphone (estimation) $35, Transport pour démos et installations à Gombe (estimation) $30, Impression flyers + petites pubs Facebook (estimation) $40, Rémunération fondateur (0 : payé par Vellum au départ) $0).

- **Break-even: 11 client-mois (abonnement Magnet Pro)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (60 a day): **48%** of every sale, after every cost.
- Capacity: 80 a day.

### Year 1, month by month

| month | client-mois (abonnement Magnet Pro)s a day | revenue | profit | cumulative (after $118 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 3 | $60 | -$85 | -$203 |
| 2 | 6 | $120 | -$50 | -$253 |
| 3 | 10 | $200 | -$4 | -$257 |
| 4 | 14 | $280 | $43 | -$214 |
| 5 | 18 | $360 | $90 | -$124 |
| 6 | 23 | $460 | $148 | $24 |
| 7 | 28 | $560 | $206 | $230 |
| 8 | 33 | $660 | $264 | $495 |
| 9 | 38 | $760 | $323 | $817 |
| 10 | 43 | $860 | $381 | $1,198 |
| 11 | 48 | $960 | $439 | $1,638 |
| 12 | 52 | $1,040 | $486 | $2,123 |

- **Year 1 operating profit: $2,241** on $6,320 of revenue.
- After the $118 startup spend: $2,123.
- Startup money earned back: month 6.
- Cash you need before it pays for itself: **$257**.

### What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 48% | 11 | $2,241 |
| Price -10% | 43% | 13 | $1,609 |
| Volume -20% | 46% | 11 | $1,505 |
| Unit costs +15% | 42% | 12 | $1,846 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.

## Marketing

Budget : ~40 USD/mois (ligne « flyers + petites pubs » du CFO). Le reste se fait en temps, pas en argent.

### 1. Ce que dit le panel
- **Première cible** : PME de Gombe, petites agences, freelances/commerciaux **ambitieux digital** (les 3 acheteurs du panel étaient tous dans ces groupes). Les petits commerces de quartier : 0 % → ne pas les viser en premier (ou plus tard via l'Essentiel / le paiement au résultat).
- **Objection n° 1 : la confiance (11 « non » sur 17).** « Ça fait arnaque », « je ne connais pas Vellum », « ma réputation ». Chaque message marketing doit y répondre.
- **Ce qui fait basculer** : un patron qu'ils connaissent qui montre ses vrais résultats + essai sans risque + quelqu'un de Vellum en vrai.

### 2. Positionnement

Trois versions :
1. *Pour les PME et agences de Kinshasa qui perdent des heures à chercher des clients sur WhatsApp, Magnet est l'assistant de prospection qui trouve, écrit et relance pour vous, sans risquer votre numéro, contrairement aux applis d'envoi en masse qui font bloquer les comptes.*
2. *Pour les patrons de Gombe qui oublient de relancer, Magnet relance à votre place, avec des messages que vous validez, et vous dit chaque semaine qui a répondu.*
3. *Vellum + Magnet : le site qui vend et la relance qui ramène, installés en personne à Kinshasa, payables en Mobile Money.*

**Recommandée : la n° 2.** Elle répond directement à la peur de « messages en mon nom » (validation) et met en avant la relance, le cœur que le conseil veut garder. Le panel a dit vouloir « valider chaque message avant qu'il parte » (P008).

### 3. Canaux (3 retenus)

| Canal | Pourquoi | Coût | Comment savoir que ça marche |
|---|---|---|---|
| **Démarchage en personne à Gombe** (démo de 10 min sur téléphone) | La confiance se gagne en vrai ; demandé par le panel | Transport (~30 USD/mois) | Démos faites / pilotes signés |
| **Magnet lui-même** (prospection B2B ciblée des PME, agences) | La meilleure preuve : « ce message vous a été envoyé par Magnet » | Coût des messages | Taux de réponse ≥ 10 % |
| **Groupes WhatsApp de commerçants/entrepreneurs + statuts** | C'est là que vit la cible ; bouche-à-oreille entre patrons | 0 USD | Demandes entrantes |

**Pas maintenant** : pubs Facebook massives (budget), LinkedIn (après 10 clients, condition du conseil), TikTok.

### 4. Campagne de 30 jours (lancement public = 15 décembre 2026, après les pilotes)

| Dates | Canal | Ce qui sort |
|---|---|---|
| 1-7 déc. (J-14 à J-8) | Statuts + groupes | Étude de cas pilote n° 1 (avec accord écrit) : chiffres réels du rapport |
| 8-14 déc. (J-7 à J-1) | Gombe en personne | 5 démos par jour ; « liste d'attente lancement » |
| 15 déc. (J0) | Tous | Ouverture : offre de lancement (voir pricing) jusqu'au 31 décembre |
| 16-31 déc. | Magnet + groupes | 2 posts/semaine : coulisses, un rapport anonymisé, une FAQ « mon numéro est-il en sécurité ? » |

Quand il n'y a rien de neuf : montrer l'écran du rapport, expliquer une règle WhatsApp, raconter une journée de démos.

### 5. Dix accroches (chacune répond à une objection du panel)

1. « Vous validez chaque message avant qu'il parte. Rien ne part sans vous. » (réputation)
2. « Ce message vous a été envoyé par Magnet. Si vous le lisez, ça marche. » (preuve)
3. « Vous ne payez le 2e mois que si vous avez eu au moins 3 réponses. » (prix / confiance)
4. « API WhatsApp officielle : votre numéro ne risque rien. » (blocage)
5. « On vient l'installer chez vous, à Gombe. » (Vellum inconnu)
6. « Combien de clients avez-vous oublié de relancer ce mois-ci ? » (besoin)
7. « 20 USD par mois = moins qu'un seul client perdu. » (prix)
8. « Un bouton « ne plus recevoir » dans chaque message. Vous restez poli. » (spam)
9. « Pas d'application à apprendre : Vellum s'occupe de tout. » (temps / coupures)
10. « Rapport chaque lundi : qui a répondu, qui relancer. » (preuve)

Aucun faux avis, aucune fausse statistique, aucune citation du panel présentée comme témoignage.

### 6. Budget et chiffres à suivre
- **Répartition** : 30 USD transport/démos, 10 USD impression ; pubs Facebook = 0 jusqu'à 10 clients.
- **Le maximum à payer pour gagner un client** : contribution 11,65 USD/mois × durée de vie supposée 6 mois ≈ **70 USD** (la durée de vie est une hypothèse ; le panel ne donne qu'un mois d'achat).
- **3 chiffres par semaine** : démos faites (objectif 15+), taux de réponse aux messages Magnet (alerte si < 5 %), pilotes → payants (alerte si < 3 sur 10).

## Brand

### 1. Les noms : vous en avez déjà deux, on les vérifie

**Vellum** (agence) et **Magnet** (app) existent déjà. Plutôt que dix nouveaux noms, voici le risque et trois variantes.

- **Risque Magnet** : « Magnet » est un nom très utilisé, notamment par une application connue de gestion de fenêtres sur Mac, et par beaucoup d'autres produits. Risques : confusion, recherche Google noyée, domaine `magnet.com` indisponible, et possible conflit de marque dans la classe 9 (logiciels) et 35 (publicité/marketing).
- **Variantes à garder en réserve** :
  1. **Magnet by Vellum** : garde le nom, le distingue, renforce l'écosystème.
  2. **Magneto** / **Magnetik** : sonne bien en lingala/français, plus déposable (à vérifier).
  3. **Bilanga** ou **Kokanga** (mot local évoquant « attraper », à valider avec des locuteurs) : très distinctif, ancré à Kinshasa.

**Recommandation : « Magnet by Vellum »** pour le lancement, avec un domaine du type `magnet.vellum.cd` ou `getmagnet.cd`.

**Vérifications à faire vous-même (je ne peux faire que des recherches publiques ; seul un avocat confirme, et rien n'est protégé tant que vous ne l'avez pas déposé) :**
- **Marque** : la RDC n'est pas membre de l'OAPI ; le dépôt se fait au niveau national (service de la propriété industrielle du ministère de l'Industrie, à confirmer). Cherchez d'abord « Magnet » et « Vellum » dans la [base mondiale des marques de l'OMPI](https://branddb.wipo.int), classes **9, 35, 42**.
- **Domaines** : vérifier `.cd`, `.com`, `.africa` chez un registraire.
- **Comptes** : Instagram, TikTok, Facebook, WhatsApp Business, LinkedIn : `@magnetbyvellum`, `@vellum.cd`.
- **Confusion** : aucun concurrent kinois trouvé avec ces noms (recherche limitée).

### 2. Promesse, slogan, voix

- **Promesse** : *« Vos prospects relancés chaque semaine, avec des messages que vous validez. »*
- **Slogans (3 options)** :
  1. « Vellum crée l'aimant. Magnet attire le métal. » (le vôtre, gardez-le pour la marque mère)
  2. « Magnet cherche. Vous signez. »
  3. « Plus jamais un client oublié. »
- **Voix (3 adjectifs)** :
  - **Direct** : à faire « 20 USD/mois, 300 messages » ; à éviter « solution révolutionnaire ».
  - **Rassurant** : à faire « Rien ne part sans votre accord » ; à éviter promettre des clients garantis.
  - **Kinois** : à faire tutoiement possible, exemples de Gombe, Limete ; à éviter un ton de start-up parisienne.
- **Avant / après (pitch)** : *Avant* : « une application qui trouve des prospects pour ton business, leur envoie un premier message WhatsApp personnalisé à ton nom ». *Après* : « Magnet trouve des clients pour ton business, prépare les messages, **tu les valides**, puis il relance pour toi. Chaque lundi, tu vois qui a répondu. »

### 3. L'identité visuelle (brief)

- **Couleurs** :
  - Bleu nuit `#0F1B3D` (confiance, sérieux ; fond et texte) — texte blanc dessus : contraste ~17:1 ✔ AA
  - Rouge aimant `#E63946` (énergie, l'aimant ; boutons, accents) — texte blanc dessus : ~4,0:1, **réservez-le aux gros textes/boutons gras** (AA grands textes) ou utilisez `#C1121F` (~5,9:1 ✔ AA)
  - Blanc cassé `#F8F5F0` (fonds) — texte bleu nuit dessus ✔ AA
- **Polices (gratuites, Google Fonts, licence OFL)** : **Sora** pour les titres, **Inter** pour les textes.
- **Logo** : un aimant en U stylisé dont les pôles sont deux bulles de discussion. Il doit être lisible en **icône 32 px**, en statut WhatsApp, sur un flyer noir et blanc. À éviter : le logo WhatsApp, le vert WhatsApp (marque déposée de Meta), les éclairs clichés.
- **Les 5 premiers points de contact** :
  1. Le **premier message Magnet** reçu par un prospect (c'est votre vitrine !) : poli, signé, avec « ne plus recevoir ».
  2. La **démo sur téléphone** à Gombe.
  3. Le **reçu Mobile Money + message de bienvenue**.
  4. Le **rapport du lundi**.
  5. La **réponse à la première plainte** (« j'ai reçu un message que je n'ai pas demandé ») : excuse, retrait immédiat, explication.

Pas de conseil juridique sur les marques.

## Launch plan

Aujourd'hui : mardi 27 octobre 2026. Vous êtes seul, avec 0 USD : chaque tâche a donc pour responsable **vous**, sauf mention contraire.

### 1. Le test avant de dépenser : 10 pilotes « 0 risque »

| | |
|---|---|
| **Test** | Service/agence → **pilotes payants** à la clé : 10 PME/agences/freelances de Gombe, installation en personne, mois 1 gratuit, mois 2 à 20 USD **seulement si ≥ 3 réponses intéressées** (voir pricing). |
| **Avant les pilotes** | Faire tourner Magnet **pour Vellum** pendant 2 semaines (condition du conseil) : 200 prospects, mesurer taux de réponse et rendez-vous. |
| **Ligne de succès, écrite à l'avance** | Vellum : ≥ 10 % de réponses et ≥ 2 sites vendus. Pilotes : **≥ 5 clients sur 10 paient le mois 2**. |
| **Comparaison panel** | Le panel simulé donne 15 % d'achat (borne haute). Si les vrais pilotes font moins bien, croyez les vrais pilotes et revenez au prix/à l'offre. |

### 2. Le compte à rebours

| Semaine | Tâches | Échéance |
|---|---|---|
| **27 oct. - 2 nov.** | ⚠️ *Chemin critique* : décider la voie WhatsApp → ouvrir un compte **WhatsApp Business Platform (Cloud API)** officiel, vérifier l'entreprise Vellum dans Meta Business, faire valider les modèles de messages. Confirmer le prix par message RDC sur la grille Meta. | 2 nov. |
| **3 - 9 nov.** | MVP : ajouter **validation du message par le client avant envoi** + bouton « ne plus recevoir ». Lancer Magnet pour Vellum (200 prospects). | 9 nov. |
| **10 - 16 nov.** | Mesurer les résultats Vellum. Ouvrir le compte marchand Mobile Money (M-Pesa / Orange / Airtel). Vérifier statut juridique (RCCM de Vellum, ajout de l'activité logicielle) avec un comptable. | 16 nov. |
| **17 - 30 nov.** | ⚠️ *Chemin critique* : signer et installer les **10 pilotes** en personne. Page simple Vellum « Magnet » avec prix. Profils sociaux `@magnetbyvellum`. | 30 nov. |
| **1 - 14 déc.** | Rapports pilotes chaque lundi. Première étude de cas (accord écrit). Liste d'attente. Campagne J-14 (voir marketing). | 14 déc. |
| **15 déc.** | **Lancement public** (après une « journée portes ouvertes » le 12 déc. avec les pilotes et leurs amis). | 15 déc. |

Facebook et LinkedIn : **pas avant 10 clients payants** (condition du conseil).

### 3. Le jour du lancement (15 décembre)

| Heure | Quoi |
|---|---|
| 7 h | Statut WhatsApp + post dans 5 groupes : étude de cas pilote + offre jusqu'au 31 déc. |
| 8 h | Magnet envoie la vague du jour (50 PME ciblées), messages validés la veille |
| 9 h - 13 h | Tournée de démos à Gombe (liste de 10 rendez-vous pris d'avance) |
| 14 h - 16 h | Répondre à toutes les réponses dans la fenêtre de 24 h (gratuite) |
| 17 h | Encaisser, envoyer messages de bienvenue |
| 19 h | Bilan : démos, réponses, paiements |
| **Si ça casse** | API bloquée / modèle refusé : passer en relance manuelle depuis WhatsApp Business, prévenir les clients, ne jamais contourner avec un outil non officiel. Coupure de courant : batterie externe + forfait data de secours. |

### 4. Les 30 premiers jours

| Chiffre (chaque semaine) | Cible | Seuil d'alerte → action |
|---|---|---|
| Clients actifs (CFO : seuil = 11) | 14 au mois 4 | < 6 au mois 2 → revoir prix / offre |
| Taux de réponse aux messages Magnet | ≥ 10 % | < 5 % → réécrire les messages, mieux cibler |
| Plaintes « spam » / blocages | 0 | ≥ 1 blocage → pause, revoir ciblage et volumes |
| Démos → clients | ≥ 30 % | < 15 % → revoir la démo |

**Revues** :
- **J+7** : les messages sont-ils validés et envoyés sans incident ? Quelqu'un a-t-il payé ?
- **J+14** : quel segment répond le mieux ? On garde une seule cible.
- **J+30** : combien de clients actifs vs les 3 prévus en mois 1 par le CFO ? On ajuste le prix (test 15 vs 20 USD) et on décide si on ouvre l'Essentiel ou le paiement au résultat aux petits commerces.

## Not done yet

- The offer: run /founder-offer
- Operations: run /founder-ops

_The panel is simulated buyers and the numbers are projections from your inputs. Confirm demand with real customers and costs with real quotes before you spend. Not financial, legal or tax advice._
