# lifestyles  

lifestyles is a Python package for performing conjoint analysis. What is conjoint analysis? I'm glad you asked! Conjoint analysis is an alternative survey analysis technique. Instead of asking survey partcipants about how they feel about specific characteristics, instead the particpants are asked to evaluate holistically. For example, suppose you are interested in creating a new lemonade, and want to understand better what your potential customer's preferences are. We _could_ design a survey like:


> Q1. How much sugar do you prefer in your lemonade?
>  - [ ] No sugar
>  - [ ] 1 sugar
>  - [ ] 2 sugar

> Q2. Would you prefer lemon inside your lemonade?
>  - [ ] Yes
>  - [ ] No
 
There are some drawbacks to this survey design. We have isolated the attributes of the lemonade, so participants must also compare in isolation. This isn't how consumers make choices. Instead they compare products holistically. Compare the above survey to this instead:

> Q1. Which lemonade would you prefer to purchase
> - [ ] Medium sugar, ice cold and high intensity flavour
> - [ ] No sugar, ice cold and mild lemon and mild mint flavour
>  
> Q2. On a scale of 1 to 10, how likely are you to purchase the following lemonade? Warm, honey-sweetened, with strong lemon flavour. 
> 1 ♢ ♢ ♢ ♢ ♢ ♢ ♢ ♢ ♢ ♢ 10


The second survey asks us to look at drinks, and not attributes. This is much more common consumer task. Indeed, walking into a convience store for a lemonade implies the consumer will have to make these decisions. 

How can we analysis a survey like this? That's where conjoint analysis comes in. The statistical methods will decompose the consumers' choices into what attributes strongly correlate with purchase or selection.

### Work in Progress

This library is a work-in-progress, and alpha-stage development. 

### References 
 - [ Hierarchical Bayes Conjoint Analysis: Recovery of Partworth Heterogeneity from Reduced Experimental Designs. Peter J. Lenk; Wayne S](http://webuser.bus.umich.edu/plenk/HB%20Conjoint%20Lenk%20DeSarbo%20Green%20Young%20MS%201996.pdf).


