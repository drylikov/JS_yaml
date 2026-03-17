# YAML

CommonJS JavaScript YAML parser, fast and tiny. Although this implementation
does not currently support the entire YAML specification, feel free to
fork the project and submit a patch :) 

# Usage

    require('yaml').eval(string_of_yaml)
    
# Currently Supports

  * Comments
  * Sequences (arrays)
  * Maps (hashes)
  * Inline sequences
  * Inline maps
  * Nesting
  * Primitive scalars (integers, floats, booleans, etc)
  * Extended bools (enabled, disabled, yes, no, on, off, true, false)
  
## Installation

    $ npm install yaml
    
# Testing

Update git submodules and run:

    $ make test















































