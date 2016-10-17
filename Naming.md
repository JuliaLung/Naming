# About Names

- [Best Practice](https://github.com/JuliaPraxis/Naming/blob/master/Naming.md#best-practice)
- [Our Conventions](https://github.com/JuliaPraxis/Naming/blob/master/Naming.md#our-conventions)
- [Shortend Forms](https://github.com/JuliaPraxis/Naming/blob/master/Naming.md#shortend-forms)

-------

## Best Practice

- Prefer clarity to brevity  
  - :ok:  VectorArithmetic, dominant_gene
  - :x:  VecArith, dominant

- Prefer specificity to generality  
  - :ok:  VectorArithmetic, heat_it
  - :x:  VectorProcessing, heat_building
  
- prefer familiarity to jargon   
  - :ok:  ColorVision
  - :x:  TristimulusEncoding

- Be consistent
  - :ok:  get_direction, get_angle
  - :x:  get_direction, derive_angle
  
- Use acronyms only when there is no chance of confusion
  - :ok:  ParseHTML, two_line_element
  - :x:  ParseHypertextMarkupLanguage, tle

- Do not use "Julia" in names
  - :ok:  Lint
  - :x:  LintJulia

## Our Conventions

- Name packages, module and types using titlecase  
  - :ok:  Space, SpaceTime
  - :x:  space, spaceTime

- Name functions and variables using lowercase  
  with __'\_'__ as a word separator unless words are short
  - :ok:  abserr, abs_error, build_robot
  - :x:  abserror, buildRobot
  
- Name constants using uppercase  
  with __'\_'__ as a word separator almost always
  - :ok:  GREEN, NEW_SOCKET
  - :x:  Green, NEWSOCKET

- Use the plural form to package a type
  - :ok:  Robots
  - :x:  Robot

- Use the singular form to define a type
  - :ok:  Robot
  - :x:  Robots

- For package, module or type names with an initial acronym  
  write the acronym in uppercase then use titlecase:
  - :ok:  CSSParser, HTMLLinkChecker
  - :x:  CSSparser, HTMLlinkChecker
  
## Shortend Forms

- Some abbreviations appear often.  Collaboration is easier when everyone uses the same ones.   
  - [Table of Abbreviations](https://github.com/JuliaPraxis/Naming/blob/master/shortforms.md)
   
------  
    
Please see the manual on [Package Names](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package)
and [Function Names](http://docs.julialang.org/en/latest/manual/style-guide/#use-naming-conventions-consistent-with-julia-s-base).