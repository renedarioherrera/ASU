# Semantic Network Analysis

## Semantic Networks

- searches for patterns in relations among words
- builds on word based analyses
- treats words as actors
- word by word proximity matrix
- can be applied to codes

### types of matrices

1. profile (each can produce two proximity): case x attribute
2. proximity (case x case; attribute x attribute)

### word by word matrix

- words that are used often have more meaning
- when a  proximity matrix is derived from a profile matrix decide what measure of similarity to use
- jaccard's coefficient: measures how often both items occur, if at least one of them does
- simple matching coefficient (not recommended for text analysis)

### produce qualitative data

#### from profile matrix

- correspondence analysis
- network analysis

#### from proximity matrix

- multidimensional scaling (MDS)
- cluster analysis
- network analysis

### text management steps

1. original text
2. eliminate stop list
3. calculate frequencies
4. identify most common

- important to identify most common because low frequency words will make it more difficult to identify patterns and relationships between words
- experiment with different cut points

### semantic network analysis code based

- cluster analysis
- turn proximity cody by code matrix into picture
- each description of free list term gets translated to row in profile matrix and correspondence analysis
- pile sort produce proximity matrix leads to multidimensional scaling
- lines produced regression analysis by property fitting

#### example: free list

- free list salience (Smith's S_ & free list

#### successive free listing

- free list items are used as a probe
