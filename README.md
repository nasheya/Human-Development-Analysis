# Human Development Analysis
We did some data analysis with the human development index, and this is my branch of it. You can see the other's work at: 

https://github.com/klcopp/human-development-data

https://github.com/vivekramanan/data-mining-human-development-index

My branch of it deals with analyzing the UN's human development index versus the social inclusion index and values from the World Values Survey representing general "human-ness".

The social inclusion index versus the HDI returned some pretty terrible results - got an R^2 value of 0.24.

For the World Values Survey, I picked the following values:
  * Mention some qualities that children should learn at home. (Binary values – mentioned = 1 or not mentioned = 2)
    * V15. Imagination
    * V16. Tolerance and respect for others
    * V20. Unselfishness
    * V22. Self-expression
    
  * Which of these organizations are you an active member, inactive member, or don’t belong? (Active member = 2, Inactive member = 1, Don’t belong = 0)
    * V27. Art, music, or educational organization
    * V32. Humanitarian or charitable organization
		
* Describing some people, how much are they like you? (1 = very much like me and 6 = very much not like me)
	* V70. Important to this person to think of new ideas and be creative, to do things one’s own way
	* V74B. Important for this person to help the people nearby, to care for their well-being

* How often, if at all, do you think about the meaning and purpose of life?
	* V143. (1 = Often, 2 = Sometimes, 3 = Rarely, 4 = Never)

* I see myself as someone who… (1 = Disagree strongly and 5 = Agree Strongly, and 9 = Don’t know)
	* V160E. Has few artistic interests
	* V160J. Has an active imagination

All of these features together yielded a R^2 = 0.695. 
