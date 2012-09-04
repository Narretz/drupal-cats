# Cats

## Comment Aggregate Translation Set

### What is it?

Cats is a Drupal 6 module / view solution for displaying all comments and comment statistics (count, new count) belonging to a translation set with each node of the set. So basically, for the English original blog entry, you see the comments of the German translation and vice versa. Additionally, it adds consistency to the node link section: teaser and full node display comment count, new comment count, and add new comment links.

### How to use

Cats is dependant on the Nodecomment module, that transforms comments into full nodes. The second dependency is Views. The module itself handles the display of comment links and statistics, and the view handles displaying all comments that belong to a translation set. The module simply needs to be enabled. Then import the view and set it as the comment view in your content types.

### Issues

The module does not add any configuration; for example, it is not possible to specify the languages for which the comments of the translation set should be displayed.

A minor issue is that the order of the Add new comments link and the Comment count changes between teaser  and full node view.

Finally, Cats has not been tested programmatically, so surprising behaviour and errors may occur.
 
