# DNC-CSS-Frameworks

## Installation

On the top bar, click "Terminal" > "New" and type " npm install -g sass" in the command terminal. This will install SASS.

Next, type "sass --version" to make sure SASS has been installed properly.

Now you can compile your Sass code to CSS using the sass command sass input.scss output.css You can also use the --watch flag sass --watch input.scss output.css

## Usage and customization Instructions

Changes to colours, spacing, and font sizes can be made in the \_variables.scss files and once compiled the applicable classes will be created trough the css file.

Naming conventions follow a similar structure to Bootstrap for things like padding and margin (i.e. p represents padding, and mt represents margin top)

Utility classes use a prefix followed by a hyphen and a value
i.e. pb-2 for padding bottom x 2

utility classes include:
Padding: p, pl, pr, pt, pb - with values of 1, 2
Margin: m, ml, mr, mt, mb - with values of 1, 2
Font Size: fs - with values
