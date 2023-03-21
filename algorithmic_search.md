# Search Algorithms


## Preliminaries

### collections and connections within them:

 - collections are finite subsets of a part of a society's culture and, to go even further, incomplete representations of society's knowledge; the connections and associations between objects present in a collection are therefore equally finite and incomplete

 - as much as we may think so: the information contained in and attached to an object always stays the information that is available on that object, algorithms can be used to extract, structure or process that information but they cannot add to it (except by guessing)

 - context: we can add to the information contained in an object record by combining, connecting and comparing the record with and to information from other sources, e.g. other records from the same collection or other data such as the internet (Wikipedia and the like), and thereby contextualising that record
 
### orderings

 - search can be framed as placing orderings over a collection -- a given search, with all of its contexts and parameters, reorders the objects in a collection from most relevant to least relevant (and then typically a cut-off on the number of relevant objects leads to a search result)
 
 - a bit of math: for a collection of $n$ objects, there are $n!$ (_read: [n factorial](https://en.wikipedia.org/wiki/Factorial)_) relevance orderings that collections; to give you an impression: if the collection has 1000 objects, the number of orderings on that collections is already larger than anything we can imagine. what this means is that we can treat the number of possible search results on a collection of the sizes we'll work with as practially not finite (i.e. infinite, though this is technically not true)

 - the set of _all_ orderings on a collection does represent all the different ways in which users could assign relevance to the ojects in that collection, including their subjective, momentary and contextual ways to do so; this fact is nice because looking at it this way, notions of subjectivity, contextuality, and even serendipity of search are _technically_ still included

 - now, in this vastness, there are basically three types of orderings (as I see it): (1) the obvious ones (ordering by date, by name, etc), (2) the unintuitive, rather useless ones (hard to characterise; these make up the vast majority of oderings) and (3) the ones in between, the ones that are both obvious _and_ unobivous enough to be interesting and that will correspond to what we're after; note that these three types are not necessarily mutually exlusive


 
what you find below are _guesses_ at how to achieve the third type of orderings; these methods for constructing search will definitely not capture all the interesting ones (it's simply still too many) and explicitly do not cover notions of subjectivity and contextuality, for instance (to be worked on)


 
 
## Knowledge Graphs

 - 
