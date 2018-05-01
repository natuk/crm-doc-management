# Specification of CRM-SIG work

## Functions

### Versioning:

* manage CRM core and extensions document versions, i.e. specifying the classes and properties (and their versions) which exist in each document, to ensure coherence among versions of extensions and CRM core versions,
* manage content changes in the class and property declarations in current document version (including scope notes),
* document arguments for each committed change and dismissed proposal

### Visualization:

* visualize class and property hierarchies
* visualize combinations of extensions with CRM core
* visualize evolution in time of CRM core and extensions

### Serialization:

* produce a formatted encoding (e.g. PDF file) for each document version
* producing an RDFS encoding for each document version

### Interpretation and best practice:

* capture discussions about classes, properties and their meaning
* recommend best practice at implementation level

## Roles

* SIG members: participate in meetings to make decisions on version and scope note changes
* version maintainers (SIG): collect contributions, editorial work, animate and moderate the discussion in the community, ensure completeness
* version contributors (SIG) : produce and discuss the content (including serializations) and propose changes
* public (non-SIG) : discuss the content, raise questions on interpretation

## Access level

* Public, contributors and SIG members raise questions, discuss proposals, comment, answer questions
* Contributors can create issues and recommend changes at any level
* Maintainers summarize/introduce issues for discussion in the SIG
* SIG members 'vote' on issues, classes definitions, ...

# Existing platforms:

* Drupal in FORTH (existing but not accessible for contributors and maintainers)
* [dataforhistory.org](http://ontologies.dataforhistory.org/) application (open, but still under development) + an internal forum / API
* GitHub (versioning, discussions, API)
