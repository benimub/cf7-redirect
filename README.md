# cf7-redirect
Contact form 7 thank you page redirection

First of all you need to know what your form’s page id is. To get your page id, just look at the shortcode. Here’s an example: 

– as you can see, this contact form id number is 48.

Now, all you need to do is:

Switch the id number in the function to your own
Switch the thank you page URL to your relevant one
If you want to add more options, just copy and paste everything between else if and }adding more of those will give you more thank you page options.

If you don’t have a default thank you page, just remove this entire area:

 else { // Default thank you page for all forms which are not 101, 365 or 987 location = 'https://www.example.com/thank-you-3/'; }
