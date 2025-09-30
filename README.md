# test-assessments
In this repository I'm going to store all my solutions to test assessments


## DOiT test assessment

**Description:**
This is little Next.js project (React + Redux toolkit). The readme in the project contains information, instruction, for local start, architecture explanation, and some information about e2e tests

> Overall time needed: 20+ hours

What I've implemented:
- Full CRUD on JSONPlaceholder resource
- Everything has been built with Material UI component library
- 4 diferent pages
- Havigation via sidebar
- State management with Redux toolkit
- All fetch querias are handled by RTK Query
  
[Link to DOiT test assessment](https://github.com/DanFromUkraine/DOiT-test-assessment)

---

## DevelopsToday test assessment

**Description:**
This is little UI component library well-tested and documented. It includes 3 components. Each of 3 components has few states, depending on passed parameters. 

**Form Text Input Component:**
>Estimated time spent: ~1 hour
>
Description: simple input component built with react-hook-form. It uses FormProvider to share the form context. It was one of the easier components to implement (time above does not include Storybook configuration).

**Toast Component**
>Estimated time spent: ~2 hours

Description: Initially this looked like a simple task, but the fade animation added complexity. I spent a lot of time discovering that a decrementing z-index can be used to hide the Toast after the animation completes. The bug where the Toast would "flinch" on page reload was tricky to fix with CSS alone.

**Sidebar component**
>Estimated time spent: ~3.5 hours

Description: This component includes an animation for expanding and collapsing submenus implemented with requestAnimationFrame. I implemented a JS-based height measurement and animation because transitioning reliably from height: 0 to height: auto with pure CSS was not suitable for this use case.

[Link to DevelopsToday test assessment](https://github.com/DanFromUkraine/test-task-DevelopsToday)
