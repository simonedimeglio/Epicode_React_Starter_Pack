# Componenti React 

I componenti sono i blocchi fondamentali di un'applicazione React. Possono essere pensati come mattoni con cui costruire l'interfaccia utente.

## Creazione di un Componente

### Definizione tramite funzione regolare

    import React from 'react';
    
    function NomeComponente() {
      return (
        <div>
          <h1>Ciao React</h1>
        </div>
      );
    }
    
    export default NomeComponente;


### Definizione tramite funzione assegnata

    import React from 'react';
    
    const NomeComponente = function() {
      return (
        <div>
          <h1>Ciao React</h1>
        </div>
      );
    }
    
    export default NomeComponente;

### Definizione tramite Arrow Function

    import React from 'react';
    
    const NomeComponente = () => {
      return (
        <div>
          <h1>Ciao React</h1>
        </div>
      );
    }
    
    export default NomeComponente;

## Utilizzo di un componente

Una volta definito un componente, può essere utilizzato ovunque nell'applicazione come qualsiasi altro elemento HTML. Ad esempio:

    // Importa il componente creato
    import NomeComponente from './NomeComponente';
    
    // Utilizza il componente all'interno di un altro componente o nel punto desiderato dell'applicazione
    function App() {
      return (
        <div>
          <NomeComponente />
        </div>
      );
    }
