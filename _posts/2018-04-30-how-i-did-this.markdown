---
layout: post
title:  "Πώς λειτουργεί το blog"
date:   2018-04-30 10:01:28 +0300
categories: jekyll tech
description: Μερικές εντολές ώστε να φτιάξεις και εσύ ένα blog σαν αυτό το υπέροχο που βλέπεις.
---
Δεν περίμενα ποτέ ότι θα έγραφα txt κείμενο και θα διατηρούσα blog. Ναι, τόσο απλά. Θα περιγράψω τα βήματα και ελπίζω να βγουν λίγα στο τέλος. Χρησιμοποιώ Ubuntu, αλλά οι οδηγίες είναι γενικές και δεν διαφέρουν πολύ για τα windows ή τα mac. Χρειάζεστε εγκατάσταση της `ruby` και του `git`.

# GitHub
Κάπου πρέπει να υπάρχει η σελίδα σου. Προτιμώ το github για το **δωρεάν** αλλά και για την **κοινότητα**.

1. Δημιουργείς λογαριασμό στο github.com διαλέγοντας ένα `username`.

2. Δημιουργείς `New repository` και το ονομάζεις όπως το `username` που διάλεξες και κολλάς το `github.io`, δηλαδή το όνομα θα είναι `"username".github.io`.

# Υπολογιστής
1. Σε τερματικό γράφουμε την εντολή
    ```bash
git clone "username".github.io
    ```

2. Έτσι δημιουργείται ένας φάκελος με το όνομα `"username".github.io`. Μπείτε στο φάκελο με την εντολή `cd "username".github.io` και σβήστε τα πάντα εκτός από τον φάκελο .git.

3. Εγκαταστήστε το jekyll με την εντολή
  ```shell
gem install jekyll bundler
jekyll new blog
  ```

4. Μετάφερε όλα τα αρχεία από τον φάκελο `blog` στο φάκελο "username".github.io.

5. Αλλάξτε στο αρχείο `_config.yml`
  - Βάλτε `#` μπροστά από τη γραμμή `gem "jekyll", "~> ?.?.?"`
  - Βγάλτε το `#` μπροστά από το `gem "github-pages", group: :jekyll_plugins`.

6. `jekyll serve` και το site σας τρέχει τοπικά στη διεύθυνση `localhost:4000`.

7. `git push` και το site σας τρέχει στο [github](https://github.com).

# Extra
Για να γράφω μαθηματικά με $\LaTeX$ χρησιμοποιώ [Mathjax](www.mathjax.org). Για να λειτουργήσει θα πρέπει...

1. Να αντιγράψετε τον φάκελο `_layouts` από το `theme` του jekyll στο φάκελο με το blog.

2. Στα αρχεία `page.html` και `post.html` βάλετε τον κώδικα:

```javascript
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    extensions: ["tex2jax.js"],
    jax: ["input/TeX", "output/HTML-CSS"],
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
      processEscapes: true
    },
    "HTML-CSS": { availableFonts: ["TeX"] }
  });
</script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-MML-AM_CHTML' async></script>

```
***

# Σύνδεσμοι για εγκατάσταση

1. [Ruby](https://www.ruby-lang.org/)
2. [Git](https://git-scm.com/)
3. [Jekyll](https://jekyllrb.com/)
4. [Github](https://github.com/)
5. [MathJax](https://www.mathjax.org/)

# Σύνδεσμοι για γράψιμο

1. [MarkDown](https://daringfireball.net/projects/markdown/syntax)
2. [KramDown](https://kramdown.gettalong.org/quickref.html)
3. [$\LaTeX$](https://en.wikibooks.org/wiki/LaTeX/Mathematics)
