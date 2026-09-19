`whim-color-` and `whim-draw-` color and opacity classes can be used in combination with a number of `whim-bg-` classes to recolor the background elements. 

`whim-bg-diy-stamp` must be set for any `whim-bg-stamp-` classes to apply, unless a `whim-emboss-` class has been set.

`whim-bg-image-` classes will cover up most other `whim-bg-` effects. `whim-bg-filter-miximagestamp` can be used to somewhat blend an image background with other background effects.

---

In several cases, only one class in the same general group, like `whim-filter-`, can apply at one time. If multiple `whim-filter-` classes are set on the same note, the class that occurs last in the `theme.css` file will be the one that applies.

That said, groups tend to have at least a few modifier classes that naturally become apparent only when combined with at least one "core" member of the group, like `whim-mask-big` must be applied with a contentful mask class like `whim-mask-woman1-simple`.