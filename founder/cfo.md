# Le CFO : les chiffres de Magnet Pro

## Note du CFO (en clair)

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

## One client-mois (abonnement Magnet Pro)

| line | per client-mois (abonnement Magnet Pro) |
| --- | ---: |
| Price | $20.00 |
| Messages WhatsApp marketing via API officielle (300 x 0,0225 USD, tarif tiers RDC, à confirmer) | -$6.75 |
| Frais Mobile Money (~3 %, estimation) | -$0.60 |
| Données prospects (extraction ~500 fiches, estimation) | -$0.50 |
| Part serveur / IA de rédaction (estimation) | -$0.50 |
| **Contribution** (what each client-mois (abonnement Magnet Pro) leaves to pay the fixed costs) | **$11.65** (58%) |

## The margin that matters

Fixed costs: $120 a month (Hébergement serveur Magnet (estimation) $15, Forfait internet / data + crédit téléphone (estimation) $35, Transport pour démos et installations à Gombe (estimation) $30, Impression flyers + petites pubs Facebook (estimation) $40, Rémunération fondateur (0 : payé par Vellum au départ) $0).

- **Break-even: 11 client-mois (abonnement Magnet Pro)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (60 a day): **48%** of every sale, after every cost.
- Capacity: 80 a day.

## Year 1, month by month

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

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 48% | 11 | $2,241 |
| Price -10% | 43% | 13 | $1,609 |
| Volume -20% | 46% | 11 | $1,505 |
| Unit costs +15% | 42% | 12 | $1,846 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
