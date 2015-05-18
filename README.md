# Datasets for Topic Modeling

On a whim, I'm centralizing some test datasets for topic modeling here. Please [contribute by pull request](http://stackoverflow.com/a/14680805/982745)!

## Folder Structure:

Datasets are organized by in the __Data__ subfolder by __Data Format > Dataset Parent Folder > Data Files__. Please keep this organizational structure (or propose a better one!) when making pull requests.

* __Data__
    - __lda-c__ (Data in Blei's _lda-c_ format)
        + __blei-ap__
            * Description: 2246 documents from the Associated Press
            * Author: David Blei
            * Source: [http://www.cs.princeton.edu/~blei/lda-c/](http://www.cs.princeton.edu/~blei/lda-c/)
    - __raw__ (Unprocessed datasets)
        + __Nematode biology abstracts__
            * Source: [https://web.archive.org/web/20040328153507/http://elegans.swmed.edu/wli/cgcbib](https://web.archive.org/web/20040328153507/http://elegans.swmed.edu/wli/cgcbib)
            * Note: Test data used by Teh, et al, in [_Hierarchical Dirichlet Processes_](http://www.cs.berkeley.edu/~jordan/papers/hierarchical-dp.pdf).
        + __20news-bydate__
            * Description: "The 20 Newsgroups data set is a collection of approximately 20,000 newsgroup documents, partitioned (nearly) evenly across 20 different newsgroups. To the best of my knowledge, it was originally collected by Ken Lang, probably for his Newsweeder."
            * Source: [http://qwone.com/~jason/20Newsgroups/](http://qwone.com/~jason/20Newsgroups/)
            * Author: Ken Lang
        + __econtalk-show-notes__
            * Description: Econtalk podcast show notes and transcripts in Markdown format. Includes all episodes through May 11, 2015.
            * Source: http://www.econtalk.org
            * Author: Tim Hopper