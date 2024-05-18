# Props 

Le "props", abbreviazione di "properties" (*proprietà*), sono un meccanismo fondamentale in React per passare dati da un componente genitore a un componente figlio. 

Le props sono essenzialmente oggetti JavaScript che contengono dati arbitrari, e vengono passate a un componente come attributi *HTML-like*.

Ecco alcuni concetti importanti da comprendere sulle props:

## Passaggio delle Props

    // Componente genitore
    function ComponenteGenitore() {
      return <ComponenteFiglio nome="John" età={30} />;
    }
    
    // Componente figlio
    function ComponenteFiglio(props) {
      return (
        <div>
          <p>Name: {props.nome}</p>
          <p>Age: {props.età}</p>
        </div>
      );
    }
