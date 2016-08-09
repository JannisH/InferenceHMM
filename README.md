# Inference using HMM
Inference using HMM for a T9 text input method <br/>

A small book(.txt file) is parsed and 2 gram transition matrix is computed. Along with that non-informative emission matrix is assumed. Max-product(viterbi) algorithm is used to infer the best possible word the user intended to enter. <br/>

key sequences given were - 6224463 and 53276464 which returned machind and learogng.<br/>

* there is some issue with backward propogation which I wish to fix soon.<br/>

