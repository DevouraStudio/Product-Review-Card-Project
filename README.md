# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge:

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshots:

![Desltop](/Screenshot.png)
![Mobile](/Screenshot2.png)

### Links:

- Solution URL: [solution URL](https://github.com/DevouraStudio/Product-Review-Card-Project)
- Live Site URL: [live site URL](https://devourastudio.github.io/Product-Review-Card-Project/)

## My process

### Built with:

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap Grid System And Responsiveness Breakpoints
- Desktop-first workflow
- CSS Media Queries
- [Bootstrap](https://getbootstrap.com/) - CSS Framework

### What I learned:

"Well, This Project Presented Its Own Unique Challenges. One Of The Main Challenges Was Implementing Two Different Images At Breakpoints To Ensure Responsiveness, Along With Effectively Utilizing The Bootstrap Grid System. These Issues Were Successfully Resolved Through The Responsive Capabilities And Clear Grid Concepts Provided By Bootstrap. While The HTML Coding And Bootstrap Concepts Were Manageable, A Significant Challenge In CSS Involved Properly Applying And Adjusting Margins And Padding For Almost All Bootstrap And HTML Elements. The Remaining Coding Tasks And Application Of My Skills Were Similar To My Previous Projects, With No Major Differences."

```html
      <div class="col-xl-6" id="First-Col">
				<img src="image-product-desktop.jpg" alt="Image Product Desktop" class="img-fluid d-none d-xl-block"
					id="Image">
				<img src="image-product-mobile.jpg" alt="Image Product Mobile" class="img-fluid d-block d-xl-none"
					id="Image-Two">
			</div>
```
```css
@media (min-width: 375px) and (max-width: 1200px) {
	body {
		padding: 5rem 1rem;
	}

	#Second-Col {
		padding: 1.5rem 3rem;
	}
}
```

### Continued development:

"To Be Honest, The Grid System And Responsiveness Of Bootstrap Were Very Exciting For Me, And I Plan To Utilize Them In Future Projects To Further Optimize My Code Wherever Possible. Using Bootstrap Is Highly Useful And Efficient, As It Not Only Simplifies The Code But Also Enhances The Understanding Of Its Concepts And Syntax. Additionally, I Have Set A Goal To Improve My Use Of Margins And Paddings In Future Projects, As They Are Both Necessary And Essential In Any Development Process."

### Useful resources:

- [MDN](https://developer.mozilla.org/en-US/) - "During This Project, I Frequently Referred to the Mozilla Developer Network (MDN) Website as a Trusted Resource for Learning and Clarifying HTML, CSS, and JavaScript. MDN Provided Clear Documentation, Practical Examples, and Best Practices That Helped Me Solve Challenges More Efficiently. Using MDN Not Only Improved My Technical Accuracy but Also Strengthened My Confidence in Applying Modern Web Standards to My Work."

- [ChatGPT](https://www.chatgpt.com/) - "Throughout This Project, I Benefited Greatly From the Guidance and Support Provided by ChatGPT. From Explaining Complex HTML, CSS, and Bootstrap Concepts to Offering Practical Code Examples and Debugging Advice, ChatGPT Helped Me Overcome Challenges More Efficiently. It's Clear Explanations and Creative Suggestions Played a Key Role in Improving My Skills, Building My Confidence, and Ensuring the Project’s Overall Quality."

- [Bootstrap](https://getbootstrap.com/) - "In This Project, I Utilized Bootstrap to Streamline the Design Process and Enhance the Visual Appeal of My Pages. By Leveraging Bootstrap’s Pre-Built Components, Utility Classes, and Customization Options, I Was Able to Maintain Consistent Styling, Organize Content Effectively, and Apply Modern Web Design Techniques More Efficiently. Using Bootstrap Helped Me Focus on Creativity and Attention to Detail While Building the Project."

## Author

- Website - [DevouraStudio](https://www.devoura.ir)
- Frontend Mentor - [@DevouraStudio](https://www.frontendmentor.io/profile/DevouraStudio)
- Github - [@DevouraStudio](https://www.github.com/DevouraStudio)
- Codepen - [@DevouraStudio](https://www.codepen.io/DevouraStudio)
