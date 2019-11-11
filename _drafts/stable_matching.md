---
layout: post
title:  "Πως προκύπτουν οι βάσεις στις πανελλαδικές και όχι μόνο"
date:   2019-06-25 23:59:28 +0300
categories: maths
image: 
description: Παρανοήσεις και ξεκαάρισμα στον τρόπο που προκύπτουν οι βάσεις σε οποιαδήποτε διαδικασία περιέχει προτίμηση και διαλογή.
comments: true
---

# Αφορμή
Ακούμε κάθε χρόνο τα ίδια και τα ίδια:

* θα βάλω τις σχολές ξεκινώντας από αυτές που πιάνω...
* μα τι δύσκολα θέματα βάλανε στα παιδιά μας. Δεν πρόκειται να περάσει πουθενά...

# Ισχύει;
Εννοείται όχι! ΞΕΡΑ.

* Τις σχολές τις βάζουμε ΜΟΝΟ σύμφωνα με τις προτιμήσεις μας και όχι με τις βάσεις (που μάλιστα είναι και περσινές)
* η δυσκολία επηρεάζει τις βάσεις άρα ο καλός παραμένει καλός

# Ώρα για μάθημα
Δεν θα μπω σε μαθηματικά, αλλά νομίζω με ένα παράδειγμα θα καταλάβετε πολλά

Ας είναι 4 υποψήφιοι, ο Α1, ο Α2, ο Α3 και ο Α4 που θέλουν να μπουν στις σχολές Β1, Β2. Στη σχολή Β1 εισέρχονται 2 άτομα και στη Β2 1 άτομο.

| Υποψήφιος | Έγραψε | Προτίμηση 1 | Προτίμηση 2 |
| :-------: | :----: | :---------: | :---------: |
|Α1|17|Β1|Β2|
|Α2|18|Β2|Β1|
|Α3|19|Β1||
|Α4|19|Β2|Β1|

Ξεκινάμε τυχαία με έναν υποψήφιο π.χ. τον Α1. Η πρώτη του προτίμηση είναι η Β1 άρα κοιτάμε τις θέσεις της.

| | Σχολή Β1 | Σχολή Β2 |
| --- | :---: | :---: |
| Θέση 1 | | |
| Θέση 2 | |  -  |

Έχει μία διαθέσιμη και άρα μπαίνει στην Β1. Οι σχολές πλέον είναι

| | Σχολή Β1 | Σχολή Β2 |
| --- | :---: | :---: |
| Θέση 1 | Α1 (17) | |
| Θέση 2 | |  -  |

και οι υποψήφιοι

| Υποψήφιος | Έγραψε | Προτίμηση 1 | Προτίμηση 2 |
| :-------: | :----: | :---------: | :---------: |
|Α1|17|~~Β1~~|Β2|
|Α2|18|Β2|Β1|
|Α3|19|Β1||
|Α4|19|Β2|Β1|

Πάμε στον Α2. Η πρώτη του προτίμηση είναι η σχολή Β2. Στην σχολή Β2 δεν υπάρχει άτομο, άρα εισέρχεται κανονικά. Πλέον οι υποψήφιοι και οι σχολές είναι:

| | Σχολή Β1 | Σχολή Β2 |
| --- | :---: | :---: |
| Θέση 1 | Α1 (17) | Α2 (18 |
| Θέση 2 | |  -  |

| Υποψήφιος | Έγραψε | Προτίμηση 1 | Προτίμηση 2 |
| :-------: | :----: | :---------: | :---------: |
|Α1|17|~~Β1~~|Β2|
|Α2|18|~~Β2~~|Β1|
|Α3|19|Β1||
|Α4|19|Β2|Β1|

Πάμε στον Α3. Πρώτη (και μοναδική) προτίμηση είναι η Β1. Στην Β1 έχει μια διαθέσιμη θέση αλλά και ξεπερνάει τον Α1 στον βαθμό. Πλέον οι υποψήφιοι και οι σχολές είναι:

| | Σχολή Β1 | Σχολή Β2 |
| --- | :---: | :---: |
| Θέση 1 | Α3 (19) | Α2 (18) |
| Θέση 2 | Α1 (17) |  -  |

| Υποψήφιος | Έγραψε | Προτίμηση 1 | Προτίμηση 2 |
| :-------: | :----: | :---------: | :---------: |
|Α1|17|~~Β1~~|Β2|
|Α2|18|~~Β2~~|Β1|
|Α3|19|~~Β1~~||
|Α4|19|Β2|Β1|

Και πάμε στον Α4. Η πρώτη του επιλογή είναι η Β2. Στην Β2 υπάρχει ο Α2 με βαθμό 17 άρα τον εκτοπίζει και παίρνει την θέση του. Πλέον οι υποψήφιοι και οι σχολές είναι:

| | Σχολή Β1 | Σχολή Β2 |
| --- | :---: | :---: |
| Θέση 1 | Α3 (19) | Α4 (19) |
| Θέση 2 | Α1 (17) |  -  |

| Υποψήφιος | Έγραψε | Προτίμηση 1 | Προτίμηση 2 |
| :-------: | :----: | :---------: | :---------: |
|Α1|17|~~Β1~~|Β2|
|Α2|18|~~Β2~~|Β1|
|Α3|19|~~Β1~~||
|Α4|19|~~Β2~~|Β1|

Τώρα που ο Α2 εκτοπίστηκε έχει και δεύτερη επιλογή τη σχολή Β1. Στην Β1 εκτοπίζει τον Α1. Πλέον οι υποψήφιοι και οι σχολές είναι:

| | Σχολή Β1 | Σχολή Β2 |
| --- | :---: | :---: |
| Θέση 1 | Α3 (19) | Α4 (19) |
| Θέση 2 | Α2 (18) |  -  |

| Υποψήφιος | Έγραψε | Προτίμηση 1 | Προτίμηση 2 |
| :-------: | :----: | :---------: | :---------: |
|Α1|17|~~Β1~~|Β2|
|Α2|18|~~Β2~~|~~Β1~~|
|Α3|19|~~Β1~~||
|Α4|19|~~Β2~~|Β1|

Ο Α1 τώρα έχει και δεύτερη επιλογή τη σχολή Β2. Εκεί δεν μπαίνει αφού ο Α4 τον ξεπερνάει στον βαθμό. Δηλαδή οι σχολές διαμορφώνονται ως εξής:

| | Σχολή Β1 | Σχολή Β2 |
| --- | :---: | :---: |
| Θέση 1 | Α3 (19) | Α4 (19) |
| Θέση 2 | Α2 (18) |  -  |

Και *η βάση* για την σχολή Β1 είναι 18, ενώ της σχολής Β2 19.

# Στην ουσία
Την ημέρα λοιπόν της κρίσεως όλοι μαθαίνουμε τις βάσεις και τίποτα από την παραπάνω διαδικασία. Κοιτάς λοιπόν την βαθμολογία σου και ξέρεις αν πέρασες ή όχι. Στο παράδειγμα λοιπόν ο Α1 αφού θα δει ένα 18 και ένα 19 θα περάσει ένα μαύρο καλοκαίρι.

# Αλγόριθμος?
Ο παραπάνω αλγόριθμος για όσους ενδιαφέρονται ονομάζεται [stable marriage problem](https://en.wikipedia.org/wiki/Stable_marriage_problem) (επίσης stable matching problem ή SMP). 

# Bonus:
Για όσους θέλουν να παίξουν (ακόμα και να δουν σε πράξη το παραπάνω παράδειγμα), υπάρχουν καλοθελητές που έφτιαξαν εφαρμογές online.

* 