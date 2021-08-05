# HTML5 Document Structure

* **semantic tags**: the tag name conveys some info about the purpose of the tag
    * <header>:
        * content that appears at the top of the page
        * direct descendent of body element
    * <main>:
        * wraps main content of webpage
        * cannot be descendent of <article>, <aside>, <header>, <footer>, <nav>
    * <nav>:
        * wraps navigation links
        * can have more than one per sectioning element
    * <article>:
        * wraps self contained content, can take block and put anywhere and it would make sense
    * <section>:
        * requires context from parent to make sense
        * wraps content that is together and needs to be styled a certain way
        * use section instead of div if content would be in a document outline, otherwise div for aesthetics only
    * <aside>:
        * stuff on the side of the main info
    * <footer>:
        * stuff at the bottom of the document
        * direct descendent of body element
