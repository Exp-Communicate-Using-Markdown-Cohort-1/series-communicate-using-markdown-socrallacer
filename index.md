# Probando markdown
Este commit lo realizo para ver como se visualiza el texto en esta prueba de markdown.
## Tasklist:
- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
## Estructure of my new web:(adding code to md)
```
const App = () => {
  return (
    <ScrollProvider>
      <div id="main">
        <Header />
        <Home name={siteProps.name} title={siteProps.title} />
        <About id="about" />
        <Portfolio />
        <Education />
        <Footer {...siteProps} primaryColor={primaryColor} secondaryColor={secondaryColor} />
      </div>
    </ScrollProvider>
  );
};
```
## Image of the sea (Adding images into md)
![image of the sea](https://github.com/socrallacer/sllacerweb/blob/main/src/images/inicio.jpg)
