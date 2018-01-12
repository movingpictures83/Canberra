# Canberra
# Language: R
# Input: CSV (network)
# Output: CSV (distances)

PluMa plugin that computes dissimilarity by using the Canberra distance (Lance and Williams, 1966) between samples.

The plugin accepts input as a CSV file with rows as samples and columns community data members, with entry (i, j) containing
the normalized abundance of member j in sample i.

The plugin produces an output CSV file with rows and columns representing samples, and entry (i, j) storing
the dissimilariy between sample i and sample j.
