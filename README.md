# wmt15-17-humaneval

# Original dataset
- http://www.statmt.org/wmt17/metrics-task.html
-- WMT15 (DAseg-wmt-newstest2015.tar.gz}
-- WMT16 (DAseg-wmt-newstest2016.tar.gz}
- http://www.statmt.org/wmt17/results.html
-- WMT17 (wmt17-metrics-task-package.tar.gz}

# Annotations
## WMT15, WMT16 for training and development
Stored in the directory annot with filenames DAseg.newstest${year}.${type}.${lang}-en.
The lines correspond to the counterparts provided in DAseg-wmt-newstest{2015,2016}.

The sentence IDs used for our development set are stored in data_split/dev.ids.

## WMT17 for test
Soted in the directory annot with filenames DA-seglevel.newstest2017.${type}.${lang}-en.
The lines correspond to the counterparts provided in wmt17-metrics-task-package/manual-evaluation/DA-seglevel.csv (please extract corresponding lines using language-pair identifiers like cs-en in the first column).
