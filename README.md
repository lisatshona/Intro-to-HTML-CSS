# INTRO TO HTML-CSS

**Week 1**

HTML is a markup language used to create web pages. Hypertext defines the links between the web pages. HTML is core to front-end development work. HTML can be created using any text editor. It uses tags to structures the Web pages. Tags are used to indicate the title and the body. It has it's elements, these elements can be nested within other the elements. The elements can also have attributes. HTML is used for developing fundamentals about web programming.
Each opened tag should be closed at the end. The language uses tags to define manipulation that has been done on the text.


**HTML FORMATTING**

**HTML has 6 headlines** from h1-h6. H1 is the largest that attracts the attention of the reader, then h6 is the least important and doesn't grab much attention. To emphasize something we use Italics.
To convey a warning or highlight we use Bold words.

**HTM Lists** are important elements, we have 3 types namely ordered,unordered and definition list. Unordered lists is just a list that the order doesn't matter, each element is enclosed in then the list is wrapped to show its unorderd list. Ordered list is whereby the ordered of the list matters. Definition list is used to define terms as the word says. We use a specific tags for definition of lists. 

**HTML Quotes** are used to format a text as a quote, block quote is used to format large chuncks of text as quote and are usuallly displayed with a different background. Inline quotes format small texts as quote and are displayed with quotation marks. 

**HTML date elements** are used to display date on a web page and we use format that is understood by computer. The value attribute specifies the date to be displayed. A specific tag element is used to create a date picker and it can be used to customise the date picker. Time picker allows you to select the time of the day. Using datetime element allows you to combine both time and date ,starting with date and follows time. The datetime can be separated by leaving or T inbetween.

**HTML Code, pre and br**
Code is used to define a piece of a computer code. The content inside is displayed in the browser's default monospace font.
<br> tag inserts a single line break, it is mostly used in poems and writting addresses. It is an empty tag with no end tag.
pre tag is used to define the preformatted text which preserves the text spaces, line breaks, tabs and others that are ignored.

**HTML Superscrips, Subscripts&small text**
Superscripts is a character that is raised above the baseline more like an exponent. The tag used to create subscripts is the one lowered beyond the baseline. I can say they use characters.

**HTML Capabilities and Attributes**

They allow you to customize the appearance and functionality of your web.You can use tags to format text, create links, add images, embed videos, create tables, and more.
HTML Attributes always come in name/value which defines the properties of an element and are placed inside an element tag. Certain attributes are assigned for specific elements. ID name ensures that there is ony one element with that ID so its easy to use it and link it to Javascript. HTML has so many attributes that can be used to modify the web pages.

**ARIA Roles** are used to provide information about purpose and state of an element. This is important to users using screen readers or other assistive technology. The commonly used aria roles are buttons, links, menu, tree, lists and checkbox. Each role has it's own set  of attributes that can be used to further define the element's purpose and state.

**HTML Extra-spaces** can be very tricky but there are various ways to handle it. You can use the non-breaking space character instead of the regular space character. The non-breaking prevents browser from collapsing multiple spaces into one. Using CSS to set the white-space property to pre or pre-wrap which will prevent the browser from collapsing multiple spaces. Pre value displays text as it is in HTML source code, including multiple space. Pre-wrap value will wrap text as word boundaries, but will preserve multiple space.
Adding comments to the code makes it easier for a reader to understand the purpose of a specific line and prevent confusing if there an error.

**Navigation and Linking**

The nav tag is used to define a set of navigation links, but it is only intended for major blocks of navigation links. Not all navigation links should be inside the nav element. Links are a connection from one web source to another. It has an anchor and a direction, those are the two ends it has. The external links direct you to a source. An internal links targets a source on the same website. URL, HTTP, HTTPS must be used for communication on the web and it is neccessary for linking. 
URL is the address of a website to access the website content. They are either absolute or relative. Relative Url focus on the current's file location where's absolute start from the root of the website. CSS is used to apply the visual appearance to the menu.


**Images**

Images have 4 attributes. SRC tells browser which image to load. ALT provides the description of the image. Height and width show the size of the image. Images can be inserted using URL to access internet file or proving full path to the location of the current file. Images can be adjusted the way you want them to. Images have 4 different formats which are GIF, SVG, PNG & JPG. Responsive images will automatically adjust to fit the size of the screen. There are techniques used to make large images small but still delivering beautiful images. You are able to add a caption of your own using figcaption element. SVG can display large pictures without pixelation. You can add  chapter divisions to videos by referencing VTT file listing chapters.

**Lang element** is used to specify the language of a web page. Setting it on the main element is the best, it will apply to the whole page. Being secific about the direction is important especially if there is more than one language used, dir element is used to specify the direction.
Meta charset with is equals to UTF-8 and placed within the head element of html, this shows that there will be characters, scripts and emojis used..
Div is a block-level emement used to create sections,sidebars & everything in between. Span is inline element used to a color part of a text.

**Audio element** has openning and closing tag unlike the image element. It is used to embed sound content in documents. It may contain one audio sources or more but the browser will choose the most suitable one. 
**The video element** contains one or more source tags with different vid sources, allowing you to load, play, and pause videos as well as setting duration and volume. The text between the video tags will be displayed on the browser that do not support the video element. Video has 480p compressed using H.264 codec. Track element is used to link it to a text file and add captions to the video. Source lang attribute is used to show the language and add default attribute to make this track default when captions are enable. Chapters allow the user to jump to any part of the video. We use track element within the video element to display the caption.

**Content Identification** is the process or recognizing and categorizing different elements within an HTML webpage, this is done using html and other techniques like css. 
**Integration** is the process pf incorporating HTML code into a web page. Attributes, elements,role, tools are the ones that create the content of a web page. The head element contains all the important information that will not be displayed in a web browser then head element contains all the content. 
When searching something in a browser, the results are in HTML file, then browser will follow the instructions and give you what you want.
The head contains all the metadata that browser need to know but will not be displayed on the page. The body consist of all the content where most of action takes place.
Script element is used to load javascript file.
There are 6 important elements namely, main, head, footer, article, section, aside. They are the ones that structure the content. There is a lot of creativity when designing the webpage.

**Forms** is an html element used to input data containing interactive controls. Form element defines a form and the area where the user will enter their information. The input element allwows users to enter a value like a text field, password or checkbox. The type attribute defines the type of input element and name attribute gives the input element a name. If you forget to use the type attribute to  each input it will assume that it is a text. Value attribute is differently used for different input types.

**HTML tables** are mostly used to organize and dislay data on a web page. Table element has tr element for rows,td element for cells, th is used to define header cell in a table and has attributes. Table Header is applied on columns and on rows, it has alignment of the conten within a cell.

**CSS**

CSS is a designed language used for styling the HTML document. CSS has a rule which consistt of a selector (which points out the html element you want to style) and declaration (has property and value). The universal selector is used to style all the html elements. Group selector minimize the code because it groups all the elements with same style definition. There is external, internal an Inline CSS that work differently.

