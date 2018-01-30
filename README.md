## Design Solutions
 * Dynamic element creation using plain javascript
   * At the parseContent function. The object is parsed with each item is checked whether it is a category or a product then assigned to a parent element in a hierarchy to help with the design implementation
 * Utility and Constants reference
   * Created separate objects for common functions and constants to help maintainability and readability for the code
 * error-handling
   * the json object is given as-is therefore null/undefined checking is included for most objects to ensure a display even if a key is missing

## Design Decisions

 * Responsive Design
   * Allow the products display correctly on both Desktop and mobile by using media query.
   * Use of 'em' instead of 'px' for size scalability.
 * Color Contrast Ratio Check
   * check color contrast of background and text for readablity
 * Browser Compatibility
   * Checked on latest version of Chrome, Firefox and IE Edge.
 * Basic bootstrap components
   * used the column components to control the width display
