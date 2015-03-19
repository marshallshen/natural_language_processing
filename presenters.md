# Presenters

#### Entities are nested under an {entity => {...}}, and never have attributes top level (including responses)

\[details here\]

#### Sub-ojects/entities/association objects should be represented by a separate presenter, which could be used as a response in granular update endpoints

\[details here\]

#### A presenter should only be for a single instance of an entity. Associations with multiple should use a singular presenter, but just add a plural array around it.

\[details here\]

#### The presenter should define a name as the top level key, unless if the presenter is only used for an association (i.e. only used for plural/multiple associations).

\[details here\]

#### Presenters should never load data.

\[details here\]

