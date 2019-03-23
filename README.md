# Grakn
A Grakn schema is the blueprint of a Grakn knowledge graph. Using a highly flexible language, we define a schema to model a domain true to nature. 
Highly interconnected data cannot be stored at scale without an underlying structure - one that is capable of expressing the complexity of the dataset, is easy to understand, and can be extended programmatically, at runtime.

To install this grakn

    Mac OS X
    $ brew install grakn
    Linux and Windows
    Download the latest release from https://grakn.ai/download?os=mac_os_x#core , unzip it in a location on your machine that is easily accessible via terminal. Having downloaded Grakn, we can now interact with the Grakn server and the Graql console.

To run on window on cmd
      
      
      grakn server start
      ./graql console -k "sample" -f "path for gql file"
      grakn server stop
