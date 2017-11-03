A Babel compiler experiment 

Learn more about this at https://github.com/cleancoded/liquid-button

See a live example at https://cleancoded.com/assets/liquid/

 New:
- mobile compatible with touch events
- Create buttons with markup elements
- Rendered with SVGs for better view on high res panels
 
Create liquid buttons on all elements with class `liquid-button` pass all parameters as data attributes. Play around with parameters.

Most important `data-` attributes:
`data-width`: width of button
`data-height`: height of button
`data-margin`: additional space around button on svg for button overflow
`data-force-factor`: Force for each point to get back to its origin
`data-hover-factor`: Force for each point to get back to its origin while hover
`data-color1`: Background color
`data-color2`: Foreground color
`data-color3`: Highlight color
`data-text-color`: Text color

Layer settings can be made for layer `1` (background) and layer `2` (foreground)
`layer-X-viscosity`: Defines how elastic mouse interactions are
`layer-X-mouse-force`: Defines how far and strong mouse force reaches
`layer-X-force-limit`: Limits local force to specific amount