1 - I have made a full height component. Essentially am wrapping them all up in a single div element for the sake of simplicity here.

2 - The component, includes header, main (containing image and overlays) and footer.

3 - To be able to optimise images for responsive layouts, we can combine few methodologies. I’m using the SRCSET attr for eg, so the browser automatically fetches the image based on the viewport width and I am combining it with media query to ensure it’s seamless in terms of experience.

4 - In the production scenarios, we can use the combination of picture, source and img tags to gain full control over the speed and loading optimisations for the images, combined with media queries to be able to attain the required layout- https://prnt.sc/MPlqugeKqwli