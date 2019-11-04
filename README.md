# schema-org-shex
ShEx tools for schema.org

* schema-jsonld-to-shexc: convert schema.org's jsonld to ShExC<br/>
`./bin/schema-jsonld-to-shexc doc/schema.jsonld > doc/schema.shexc` # create [doc/schema.shexc](doc/schema.shexc)<br/>
  switches: includeLabels, includeComments in `const`s at top. Creates [doc/schema-annotated.shexc](doc/schema-annotated.shexc)
