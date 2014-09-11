Neural-networks-checklist
=========================

Small project to remember the check list of steps for neural networks. I usually hate to forget the minimal steps to have good results, so this could be a good starting point for everyone (to print and have next to you).


### Stochastic Gradient Descent



- [ ] Normalize/scale inputs. _Ref: [#1][2]_
- [ ] Initialize the weights in a good (random) way. _Ref: [#1][2]_
- [ ] Randomly shuffle the training examples. _Ref: [#1][2]_
- [ ] Experiment with the learning rates using a small sample of the training set _Ref: [#1][1]_
- [ ] During the training phase, check if you suffer from high bias or high variance. Overfit?.

### Architecture

- [ ] The default MSE error to minimize is not compulsary. A custom cost might work better.

### General

- [ ] Split the dataset into training set (70%), validation set (15%) to choose the best model and see if overfits, test set (15%) to get the final error.
- [ ] k-fold Crossvalidation?
- [ ] Outliers in the training data? Neural networks are very sensible to them. Try to exclude them (via filtering or via a custom cost function).






[1]: http://research.microsoft.com/pubs/192769/tricks-2012.pdf
[2]: http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf
