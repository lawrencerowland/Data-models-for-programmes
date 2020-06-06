# Digital Transformation Data model

# Which version of the model ?

[Schema-Option-1](xx) shows the schema, but not the instances. It is a higher-level schema, suitable for those who like to think of relationships between a few types of entity. This would be suitable for most programmes, because it is so general. It can be opened in YEd Desktop, YEd Live or Neo4j. 


[Schema-Option-2](xx) is also a schema-only. It shows a schema that works just as well, but it is at slightly lower level- with more entities relating to the specific organisation it is modelled on. This would be more suitable for working closely with a particular programme team, who think in a concrete way about their particular organisation. Because of this, it is more specific, and less applicable to other organisations and Digital programmes. It can be opened in YEd Desktop, YEd Live or Neo4j. 

It is worth comparing these two schemas - and seeing how there are  many schemas that are likely to work for a particular situation. In this case, I worked From Option-2 to Option-1, as I looked at the particulars of the organisation, and then moved up a layer of abstraction.  

[Schema-and-instance] is the full data model, with all the specific data for this portfolio example, based upon the schema.It can be opened in YEd Desktop, YEd Live or Neo4j. 

[Full-model] is the same as the model above, but it can only be opened in YEd Live. This is because it has been developed by working within Neo4j, and then using a YEd tool that is available in Neo4j called Neo4j Explorer - and it uses some special format settings that do not work in YEd live and so dont show node labels. 