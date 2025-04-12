# Paper.css - A Minimalist, almost Classless CSS Framework
Paper.css is a minimal, almost class-free CSS framework that gives your plain HTML a clean, paper-like aesthetic out of the box. No complex setups. No bloated utilities. Just semantic HTML and a sprinkle of style — with one optional class, because we couldn’t resist.

Demo [link](https://paper-css-tawny.vercel.app/) 

## Features
**almost Classless:** minimalist design with single wrapper class. Style is applied globally.

**Responsive:** Paper.css adapts to different screen sizes without extra effort.

**Simple:** Minimalistic design with a paper-like background and smooth typography.

**Customizable:** Easily change colors and fonts to match your theme with simple variables.

**Zero dependencies:** Only CSS, no JavaScript.

## Installation
#### Option 1: Link via CDN
You can include **Paper.css** by linking directly to the CDN:

`<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/legendgokul/Paper.css/paper_css/paper.min.css">`

Wrap the body content within a div with class **page_content**

## Usage
Paper.css is designed to work with your existing HTML without much changes. Just write your content with semantic HTML tags and wrap the content inside a ***page_content*** class, and Paper.css will handle the styling automatically.

Example HTML structure:
```
<body>
    <div class="page_content">
        <!-- Header section for the top content of the page -->
        <header>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Blog</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <article>          
                <section>
                    <h2>Introduction to the Paper Theme</h2>
                    <p>This website is built with a paper-like theme...</p>
                </section>
            </article>
        </main>
        <footer>
            <p>Copyright &copy; 2025</p>
        </footer>
    </div>
</body>
```


## Paper.css will automatically apply styles to:

- Text and headings
- Forms (inputs, buttons, textareas)
- Tables
- Links
- Lists
- Code blocks
- Semantics elements
- Buttons

## Customization
Paper.css comes with customizable variables that allow you to change the appearance to fit your project. You can modify these values to control colors, typography, and more.

Here are some of the available variables:


```
:root {
    --background-body: #1373A9; /* Background color of the body */
    --content-background-color: #fff; /* Background color of content area */
    --font-family: Verdana, Arial, sans-serif; /* Font family */
    --header-color: #00486B; /* Color for header tags */
    --primary-color: #FFD966; /* Primary button and header background */
    --secondary-color: #ffffff; /* Light background for paper-like design */
    --border: #00486B; /* Border color */
}
```
You can simply modify the values of these variables to match your project's color scheme.

## to create min.css
`cat paper.css baseStyle.css codeStyle.css formStyle.css listStyle.css semanticsStyle.css tableStyle.css typographyStyle.css > paper.min.css`

## Contributing
We welcome contributions! If you'd like to help improve Paper.css, feel free to submit a pull request or open an issue for any bugs or feature requests.

**Steps to Contribute**:
1. Fork this repository.
2. Create a new branch (git checkout -b feature-name).
3. Make your changes and commit them (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-name).
5. Submit a pull request.

## License
Paper.css is open-source and licensed under the MIT License.
