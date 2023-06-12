# DNC-CSS-Frameworks

## Installation

### SCSS Installation

On the top bar, click "Terminal" > "New" and type " npm install -g sass" in the command terminal. This will install SASS.

Next, type "sass --version" to make sure SASS has been installed properly.

Now, normally you can compile your Sass code to CSS using the sass command sass input.scss output.css You can also use the --watch flag sass --watch input.scss output.css.

However for this project we will be using Gulp to compile everything for us in to our CSS file.

** Keep your terminal open **

### Gulp Installation

To start type "npm install --global gulp-cli" to make sure Gulp is running locally and works in the command line.

To compile the scss code to the linked css stylesheet simply type gulp in the command line to make this happen.

If there is an issue running gulp, the command npm run gulp can be used instead to run the gulp script.

## Usage and customization Instructions

Changes to colours, spacing, and font sizes can be made in the "\_variables.scss" file and once compiled the applicable classes will be created trough the css file.

Heading sizes must be set using the fs class, with fs-xxxl representing an H1, and following suit in descending order of size.

Buttons, Forms, Links, and Lists can be modified in their respective files in the components folder.

Naming conventions follow a similar structure to Bootstrap for things like padding and margin (i.e. p represents padding, and mt represents margin top)

Utility classes use a prefix followed by a hyphen and a value
i.e. pb-2 for padding bottom x 2

#### Utility classes include:

Padding: p, pl, pr, pt, pb - with values of 1, 2
Margin: m, ml, mr, mt, mb - with values of 1, 2
Font Size: fs - with values sm, md, lg, xl, xxl, xxxl
Font Weight: fw - with values r (regular), l (light), b (bold)
Border Radius: br - with values xs, sm, lg, full (br with no prefix for default radius)

#### Colour classes are as follows:

Text Colour: text-(name of colour)
Background Color: bg-(name of colour)
Border Colour: bc-(name of colour)

#### Default Colours

$primary: #073A59;
$secondary: #436073;
$success: #2EA690;
$warning: #839C7d;
$info: #F9F99A;
$white: #F2F2F2;
$black: #333333;
$peach: #F3EDE6;
