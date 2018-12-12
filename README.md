# RDF Generation for Workshops
Using YARRRML mapping language, CSV files with the data, and the RML-Mapper engine, we generate the correspoding RDF graph for showing the information in the Workshop web page.

## How to do it?
- Generate your YARRRML mapping using its [spec](http://rml.io/yarrrml/)
- Use the [parser](https://github.com/RMLio/yarrrml-parser) to transform YARRRML to RML 
- Use docker or java to generate the RDF graph based on your CSVs with [RML-Mapper](https://github.com/RMLio/rmlmapper-java)