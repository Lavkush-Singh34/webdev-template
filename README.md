# webdev-template
Semantic HTML tags provide meaning to the content they enclose, making it easier for browsers, search engines, and developers to understand the structure and significance of web pages. Here are some common semantic HTML tags and their uses:

1. **`<header>`**: Represents introductory content, typically a group of introductory or navigational aids. It often contains headings, logo, search forms, and other introductory elements.

    ```html
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    ```

2. **`<nav>`**: Defines a set of navigation links. This is used to group links that allow users to navigate the website.

    ```html
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    ```

3. **`<main>`**: Specifies the main content of the document, which is directly related to the central topic of the document. There should be only one `<main>` element per document.

    ```html
    <main>
        <h2>Main Content</h2>
        <p>This is the primary content of the page.</p>
    </main>
    ```

4. **`<section>`**: Represents a standalone section that contains thematic content. It usually includes a heading.

    ```html
    <section>
        <h2>About Us</h2>
        <p>Information about our company.</p>
    </section>
    ```

5. **`<article>`**: Represents a self-contained piece of content that could be distributed and reused independently, like a blog post, news article, or forum post.

    ```html
    <article>
        <h2>Blog Post Title</h2>
        <p>This is a blog post. It stands alone as an independent piece of content.</p>
    </article>
    ```

6. **`<aside>`**: Defines content that is tangentially related to the content around it, often presented as a sidebar. This could include pull quotes, advertisements, or links to related content.

    ```html
    <aside>
        <h2>Related Links</h2>
        <ul>
            <li><a href="#link1">Related Link 1</a></li>
            <li><a href="#link2">Related Link 2</a></li>
        </ul>
    </aside>
    ```

7. **`<footer>`**: Represents the footer for its nearest sectioning content or sectioning root element. Typically contains information about the author, copyright, links to terms of use, and other relevant information.

    ```html
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
        <nav>
            <a href="#privacy">Privacy Policy</a>
            <a href="#terms">Terms of Service</a>
        </nav>
    </footer>
    ```

8. **`<figure>`** and **`<figcaption>`**: The `<figure>` tag specifies self-contained content, like illustrations, diagrams, photos, code listings, etc. The `<figcaption>` tag provides a caption for the `<figure>` element.

    ```html
    <figure>
        <img src="image.jpg" alt="A descriptive image">
        <figcaption>This is an image caption.</figcaption>
    </figure>
    ```

9. **`<mark>`**: Highlights text that is of particular relevance or importance in a given context.

    ```html
    <p>Please read the <mark>important notice</mark> before proceeding.</p>
    ```

10. **`<time>`**: Represents a specific period in time. Can be used for dates and times, and has an optional `datetime` attribute to specify the machine-readable format.

    ```html
    <time datetime="2024-05-17">May 17, 2024</time>
    ```

Using these semantic tags helps improve the accessibility and SEO of your web pages, ensuring they are easier to understand for both users and machines.
---
# Some Best `Emmet sortcuts` for VsCode.
1.
```html
div.main>nav>div.main-nav.flex>a.company-logo+div.nav-links>ul.flex>li*6>a.hover-links
```

2.
```html
div.main>nav>div.main-nav.flex>a.company-logo[href="#"]{Neil Oscar}+div.nav-links>ul.flex>li*6>a.hover-links-$[href="#"]{nav-$}
```

