# Semantic Sass

This repo demonstrates an approach to styling that preserves both semantic markup and cross-project reuse. The code is split into three parts:

1. The semantic markup. `index.html`. Correct semantic HTML elements, and classes describing what they represent.
2. The reusable styles. `universal.scss`. Can be used cross-project or at multiple places in this project. Defines the "how" of styling--for example, a block list.
3. The app-specific styles. `app.scss`. Maps between semantic markup and reusable styles. Defines, for example, "the todo list should be styled as a block list." Sass is needed for extension here, to decouple the semantic classes from the style implementations.
