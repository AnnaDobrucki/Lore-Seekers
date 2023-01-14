## Testing

Through-out testing I found an array of bugs, however using [Dev Tools](https://developer.chrome.com/docs/devtools/) I found ways of debugging them. 

 1. I had a consistent problem of my hero image and footer borders changing shape when I was making the site responsive to other screen sizes. After some time I realised using %'s for both height and width, meant that if the screen got smaller so too would the curvature of the border. I then fixed the value to *em* and the border remains curved and responsive.

 2. I used Lighthouse to check my overall performance and accessability scores, whilst doing so, found a name error in one of my labels that hadn't been spotted and since fixed.

 3. In one of my earlier versions, my workshop badges were consistanly producing problems. Dev tools helped me realise that because of the size of the element itself I would have to use different CSS to place them where I wanted on the page. (Again) My mentor Gareth McGirr, pushed me to look at the 'Flex' attribute, giving me a helpful game called [Froggy](https://www.flexboxfroggy.com) to understand the method and implement it.

 4. Dev tools was my go to for understanding my sites responisveness, and correcting media quieries. My site is responsive for the below:
   * iPhone SE
   * iPhone XR
   * iPhone 12 Pro
   * Pixel 5
   * Samsung Galaxy S8+
   * Samsung Galaxy S20 Ultra
   * iPad Air
   * iPad Mini
   * Surface Pro 7
   * Surface Duo
   * Samsung Galaxy A51
   * Nest Hub
   * Nest Hub Max