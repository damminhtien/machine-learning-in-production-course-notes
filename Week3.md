# Week 3: Define data and establish baseline
### 3.1 Why data definition is hard?
+ The labels may be inconsistent
+ Preparing data well will have huge impact on success of ML project

### 3.2 More label ambiguity examples
+ Data definition questions:
  + What is the input x?
    + Lighting? Contract? Resolution?
    + What features need to be included?
  + What is the target label y?
    + How we can ensure labeler give inconsistent labels?

### 3.3 Major types of data problems
+ Unstructured versus structured data
  + Unstructured data
    + May or may not have huge collection of unlabeled examples x
    + Humans can label more data
    + Data augmentation more likely to be helpful
  + Structured data
    + May be more difficult to obtain more data
    + Human labeling may not be possible (with some exeptions)
+ Small versus big data
  + Small data
    + Clean labels are critical
    + Can manually look through dataset and fix labels
    + Can get all the labelers to talk to each other
  + Big data
    + Emphasis on data process