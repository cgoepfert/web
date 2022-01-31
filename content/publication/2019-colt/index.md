---
title: "When can unlabeled data improve the learning rate?"
date: 2019-06-01
publishDate: 2020-08-11T17:20:45.019701Z
authors: ["Christina Göpfert", "Shai Ben-David", "Olivier Bousquet", "Sylvain Gelly","Ilya Tolstikhin", "Ruth Urner"]
publication_types: ["1"]
abstract: "We investigate realistic conditions for when unlabeled data improves upon the minimax learning rate of a supervised learning problem and demonstrate examples where these conditions are met."
featured: true
publication: "*Conference on Learning Theory*"
url_pdf: "https://arxiv.org/pdf/1905.11866"

---

In semi-supervised classification, one is given access both to labeled and unlabeled data. As unlabeled data is typically cheaper to acquire than labeled data, this setup becomes advantageous as soon as one can exploit the unlabeled data in order to produce a better classifier than with labeled data alone. However, the conditions under which such an improvement is possible are not fully understood yet. Our analysis focuses on improvements in the *minimax* learning rate in terms of the number of labeled examples (with the number of unlabeled examples being allowed to depend on the number of labeled ones). We argue that for such improvements to be realistic and indisputable, certain specific conditions should be satisfied and previous analyses have failed to meet those conditions. We then demonstrate examples where these conditions can be met, in particular showing rate changes from 1/sqrt(l) to exp(-c*l) and from 1/sqrt(l) to 1/l. These results improve our understanding of what is and isn’t possible in semi-supervised learning.
