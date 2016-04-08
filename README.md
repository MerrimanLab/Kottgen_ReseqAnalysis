# Kottgen_ReseqAnalysis

With GLIDA, the LDExplorer and the ReseqMetaAnalysis tools now well underway, it is time to test these out in anger. I have previously trialed some basic functionality on LD datasets, but here we are going to unleash it on the Kottgen dataset.

The Kottgen set is an ideal test set for us, as the lab is very familiar with it. It differs slightly from the datasets I have been using previously, mostly because we are able to get a full set of GWAS summary statistics. Given that we have trusty p-values in this summary data set, we will want to produce typical locus-zoom plots for this set (p-values on the Y axis, position on the X-axis and coloured by LD). This will require some extra functionality in GLIDA.

Planned exploratory analysis so far:  

  1. Create classical locus zooms from the summary data. Including LD and p-values.  
  2. Identify interesting regions in the Leffler summary data (included in this repo) and plot these same regions from the Kottgen summary data.
  3. Get a p-value-based ReseqMetaAnalysis option up and running.
