# silver-mps
This chapter describes the basic MPS notions: nodes, concepts, and languages. These are key to proper understanding of how MPS works. They all only make sense when combined with the others and so we must talk about them all together. 

This section aims to give you the essence of each of the elements. For further details, you may consider checking out the sections devoted to nodes, concept (structure language), and languages (project structure).  

Abstract Syntax Tree (AST)﻿ MPS differentiates itself from many other language workbenches by avoiding the text form. Your programs are always represented by an AST. You edit the code as an AST, you save it as an AST you compile it as, well, as an AST. This allows you to avoid defining grammar and building a parser for your languages. 

You instead define your language in terms of types of AST nodes and rules for their mutual relationships. Almost everything you work with in the MPS editor is an AST-node, belonging to an Abstract Syntax Tree (AST). In this documentation we use a shorter name, node, for AST-node.
