Read `AGENTS.md` before starting. 


We are adding the design system and UI primitive components. 

Install and configure `shadcn/ui`. 


Add these shared CN components:
- buttons
- card
- dialogue
- input
- tabs
- textarea
- scroll area

Do not modify the generated `component/ui/*` files after installation. 


Also install `lucide-react`. 
Create 'lib/utils.ts' with a reusable `cn()` helper for merging Tailwind classes.


Ensure all components match the existing dark theme in `globals.css`. 


### Check when done. 

- All components import without errors. 
- 'cn()' works properly. 
- No default lighting styling appears. 