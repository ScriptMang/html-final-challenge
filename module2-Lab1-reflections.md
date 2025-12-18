Reflection Questions

1. What accessibility enhancements were the most challenging to implement, and why?
	
	The most challenging enhancement to implement was the use of semantic tags.
	I had to make sure the divs I was replacing had their classes carried over.
	Their ids had to be carried over too. On top of that I had to make sure that
	for any div I kept, there was no semantic tag that can provide the same context.
	The reason being I would have to add aria attributes to the divs which depends on context.

2. How do ARIA attributes improve the experience for users relying on assistive technologies?

	Aria attributes provide meta information for screen readers to help them navigate websites. It makes the web more accessible for those with disabilities. For those who are visually impaired there is focus mode which highlights input fields. Another, is aria live regions which announces notification updates. They can even communicate whether a download is in progress or a feed is being updated.
	They also help to point out interactive elements like buttons, textboxes, and input fields too. They also can announce error messages. 


3. What tools did you use to check color contrast, and how did they help?

	I used the chrome web tools, specifically the page inspector to hover over elements and see their contrast score. The contrast score is colored red for the worst possible contrast to orange, yellow, and  green being the best depending on the contrast score. Another part of the chrome web tools I used was the style tab after choosing the selected text element with page inspector. I use it to locate the css selector in the code to so I can change the background and font color inside the css file. Another tool I used was the chrome extension called lighthouse. Once I run  its accessiblity section it checks for contrast. 

