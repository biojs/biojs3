# BioJS v3

We - the developer and contributor to BioJS - aim to create open sourced tools that help sharing biological visualizations. Our vision is that every biological dataset in the world will be visualised with BioJS tools.

BioJS's goal is to reach as many people as possible, from deeply knowledgeable users to end users who want to implement the component with minimal effort. BioJS aims both for ease of use and extensibility, as so it has to be flexible, maintaining the usability for the less knowledgeable while allowing it to be extended for knowledgeable developers.

A BioJS component should obey the following design principles:

- *encapsulation*: a BioJS component should live in its own isolated scope.
- *reusability*: a BioJS component should be as generic as possible and hence easy to reuse. All dependencies should be part of the meto annotation.
- *modular*: a BioJS component should try to do only one thing and doing this one well (Unix philosophy).
 
Therefore when creating web components for BioJS, a contributor should follow these principles:

- Namespacing: all custom elements should start with `bio`
  * input/output functionality (like parsers) should be prefixed with `bio-io`
  * visualization should be prefixed with `bio-vis`
  * meta components (composed components) can be prefixed with `biojs-meta`

We want to help web developers and end user - not complicate their lifes.
Every change to these design principles should be ratified by the community and documented on github.

In support of these principles,

(list of contributors)
