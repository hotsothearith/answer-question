                HTML
1.	What is the purpose of the <!DOCTYPE html> declaration?
  	The <!DOCTYPE html> declaration tells the browser that the document is written in HTML5, which is the latest HTML standard. It ensures that the browser renders the page in standard mode, providing consistent and expected behavior across different browsers.
2.	What is the purpose of the <meta charset="UTF-8">  tag?
  	This meta tag specifies the character encoding for document as UTF-8, which is the most common encoding. UTF-8 supports nearly all characters and symbols, ensuring proper display of different languages and special characters.
3.	What is the  difference between <section>, <div> and <article> element?
  -	<section> : it is the groups that related content by theme, typically with a heading.
  -	<div> : A generic container with no semantic meaning, often used for styling and layout.
  -	<article> : Represents standalone content, like a blog post or new item, that could be independently distributed or syndicated
                CSS
1.	What is the difference between display flex and grid
  	Display flex :
    o	One dimensional : Aligns item s a single row or column.
    o	Flexible : Great for simple layouts like navbars and centering items.
  	Display grid : 
    o	Two-dimensional : control both rows and columns.
    o	Precise : Ideal for complex layout, like page structures.
2.	How to make responsive in CSS
   	Relative Units : Use % and em for flexible widths and font sizes
    o	Example : .container { width: 80%; font-size: 1.5em; }
  	Flexbox/Grid : Both adept to screen size use flex-wrap
    o	Example : .container { display: flex; flex-wrap: wrap; }
   	Media queries : Adjust styles for specific screen widths 
    o	Example : @media (max-width: 768px) { .container { flex-direction: column; } }
  	Responsive image : Set images to max-width: 100%;
    o	img { max-width: 100%; height: auto; }
3.	What’s the difference between inline, block, and inline-block element in CSS?
  	Inline : only takes up as much width as its content; width and height properties are ignored.
  	Block : Occupies the full width of it container, starting on a new line, and report width/height properties.
  	Inline-block : acts like inline for follow purposes doesn’t force a new line but allows setting width and height like a block.
                  SASS
1.	What is the Purpose of SASS  ? 
     	The Purpose of SASS is to make writing and managing CSS easier , more efficient, and scalable, especially for large or complex project.
2.	How does SASS compilation work ?
    	SASS compilation converts  .scss or .sass file into standard .css file that browser can read
    	How it works : 
      o	Write Sass code : use Sass features (like variable and nesting) in a sass file
    	Example : $primary-color: #3498db; body { color: $primary-color; }
      o	Compile with a Tool : use a Sass compiler ( like node-sass or Dart Sass ) to process .scss files.
      o	Get CSS output : The compiler generates a .css file for the browser.
    	body { color: #3498db; }
3.	What do Mixins use for ?
    	Mixins in Sass are used to create reusable blocks of CSS. They allow you to define styles once and reuse them throughout your code, which reduces repetition and makes maintenance easier.
