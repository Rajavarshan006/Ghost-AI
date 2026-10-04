We need the base Chrome component that frames every editor screen: the top nav bar and the left side bar shell. These will be reused and extended in every chapter that follows. 

## Editor navbar

Create `component/editor/editor-navbar.tsx`

Requirements:
- Fixed-height top navbar with left, centre, and right sections.
- Left section contains the sidebar toggle button.
- Use the `panel-left-open` and `panel-left-close` icons based on the sidebar state.
- Right section stays empty for now.
- Dark background with a subtle bottom border



##Project sidebar
Create `components/editor/project-sidebar.tsx`

Requirements:
- Sidebar should not float above the editor canvas.
- Opening it should not push page content.
- Slides in from the left: accept the `is-open` property.
- Header with project title + close button
- shadcn `TABS`:
    - My Projects
    - shared
- Both tabs show an empty placeholder state. 
- Full-width `New project` button at the bottom with a `Plus` icon 


## Dialog pattern

Use the existing colour tokens from `globals.css` for dialogue styling. 

Supports :
- title, 
- description, 
- footer -actions 
Do not build actual dialogues yet. 

Check when done. 
- New components compile without TypeScript errors. 
- No lint errors. 
- Dialogue pattern is ready for future use. 