# Assignment-4-Shoe-Page

Hosted Link:- https://lok-ii.github.io/Assignment-4-Shoe-Page/


![Screenshot 2023-08-08 182918](https://github.com/Lok-ii/Assignment-4-Shoe-Page/assets/129180844/b67eef06-9553-480d-aedb-6fe70c58f7d2)

    The <body> section contains two <div> elements with classes "container" and "main-content".

    First one is used for the background gradient which is rotated slighlty.
    Second one is used to created the text and img inside a container.

![Screenshot 2023-08-08 182912](https://github.com/Lok-ii/Assignment-4-Shoe-Page/assets/129180844/7d05a6f1-7cad-49ad-94d2-0ddd2dabcbd1)
![Screenshot 2023-08-08 182900](https://github.com/Lok-ii/Assignment-4-Shoe-Page/assets/129180844/09d69da4-b7e4-42f0-807e-57c80881ed90)

    For the text section, <h1> is used for the heading and <p> tag is used for the paragraphs written inside the <div> tag with "main-content" class.
    <img> tag is used to display the image of the shoe on the right side.

    All these sections and elements are styled using the CSS properties.

    CSS properties used:-

        The background-color property sets the background color of the <body> to light grey.
        The .container class creates a fixed-position, rotated container with a gradient background, a shadow, and specific positioning. Gradient background is created using 'background' property and 'lineear-gradient()' as value. 'Box-shadow' is used to create shadow. 'transform' is used to transform the element(here it is used to rotate the element). And some other dimensional properties to set width height and it's position.

        The .main-content class is styled to have an inline-block display, gradient background, shadow, and specific dimensions and margins.

        The <h1> and <p> elements inside .main-content have max-width and margin properties to control their layout.

        The <img> element is absolutely positioned to the right of its parent, with specified dimensions and positioning. The :hover pseudo-class is used to apply styles to the <img> element when hovered, changing its position and size.
        The .lastpara class adjusts the position and width of the last paragraph.
        
