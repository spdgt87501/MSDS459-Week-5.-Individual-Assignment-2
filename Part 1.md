# MSDS459-Week-3.-Individual-Assignment-1

Part 1 - Week 4 - Knowledge Graphs

In week four, chapter 6 of the text Knowledge Graphs by Kejriwal et al., 2021 was assigned.  This chapter provides a review of various ontologies for relationship extraction (RE).  RE is a type of information extraction (IE) that focuses on the relationships between entities.  While named entity recognition (NER) can be utilized to extract named entities for the nodes in a knowledge graph, RE is needed to pull definitions for the edges in a knowledge graph that describes the relationship between the nodes (Kejriwal et al., 2021).

One of the foundational ontologies in RE is Automatic Content Extraction (ACE).  ACE is a standard for automatic processing of text data to derive entities, relationships, and events.  This standard was developed by the National Institute of Standards and Technology by annotating text data.  Multiple datasets that are now utilized to evaluate the performance of RE systems including ACE 2004, ACE 2005, and ACE 2007 were developed in the process (Kejriwal et al., 2021). 

Similar to IE, approaches to RE can be categorized as either supervised, unsupervised, or supervised.  Supervised RE requires the use of labeled data.  Two types of supervised RE are feature-based and kernel-based.  Feature based relationship extraction treats the task as a classification problem where information learned from labeled data sets is applied to unlabeled datasets to classify the relationship between entities.  This is often done probabilistically.  Kernal based on the other hand utilizes kernal functions to calculate implicit rather than explicit coordinates.  This results in a lower computational cost by specifying the kernal rather than extracting features (Kejriwal et al., 2021). 

Two prominent types of semi-supervised relationship extraction are bootstrapping and distant supervision.  In bootstrapping, a small amount of labeled relationship data for a specific relationship type is utilized to teach the system how to extract entity pairs with a similar relationship.  In contrast, distant supervision uses large sets of data containing a pair of entities with a known relationship to generate training data.  This follows the assumption that if the relationship between an entity pair is known, all mentions should follow that relationship.  Since this is not always the case, the approach is often augmented with the entity’s relationship to other features in the sentence or with representation learning (Kejriwal et al., 2021).

The final categorization as presented by Kejriwal et al., 2021 is unsupervised.  Unsupervised relationship extraction works without training data to discover relationships in text data that are not defined in advance.  The earliest approaches to unsupervised relationship extraction looked at lexical similarities between sets of text data such as news articles to determine their similarities.  More recent approaches have utilized either semantic relationships or lexical patterns.  Semantic relationships can be utilized to group entity pairs by their relation to one another.  Lexical patterns on the other hand can be utilized to apply labels automatically according to the syntactic patterns of sets of text identified as having similarity (Kejriwal et al., 2021). 


References

Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. Knowledge graphs: Fundamentals, techniques, and applications. Cambridge, MA: The MIT Press, 2021.
