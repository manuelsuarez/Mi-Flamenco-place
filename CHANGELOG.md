# Changelog

### WIP

  - IMPORTANT: Moved search component to add-ons 
  - IMPORTANT: Removed form-file JavaScript
  - Added placeholder add-on
  - Added dotnav add-on
  - Added slidenav add-on
  - Added upload add-on
  - Added autocomplete add-on
  - Added simple template engine
  - Added large dialog to modal component
  - Added overflow container to utility component
  - Added text vertical alignment modifiers
  - Form-file add-on now works great with text
  - Lists are now more robust
  - Fixed page jumping to top for modal component
  - Fixed timpicker add-on events
  - Fixed markdownarea add-on browser reload issue
  - Fixed fixed breakpoint for grid divider with large gutter

**Documentation and repository**

  - Fixed form password add-on doc

### 2.4.0 (March 05, 2014)

  - IMPORTANT: Renamed uk-text-info to uk-text-primary including variable names
  - IMPORTANT: Renamed uk-notify-message-info to uk-notify-message-primary including variable names
  - IMPORTANT: Renamed @grid-large-gutter-horizontal to @grid-gutter-large-horizontal
  - IMPORTANT: Renamed @grid-large-gutter-vertical to @grid-gutter-large-vertical
  - IMPORTANT: Renamed @panel-divider-large-gutter to @panel-divider-gutter-large
  - IMPORTANT: Removed uk-modal-dialog-slide
  - Renamed some global variables in themes
  - Refactored grid component
  - Refactored modal component
  - Added grid-match only within rows option
  - Added grid width classes
  - Added grid gutter small classes
  - Added width small classes
  - Added AMD support
  - Added margin classes to utility component
  - Added border rounded to utility component
  - Added resize property to scrollables in utility component
  - Added text center small and medium classes
  - Added markdownarea style for gradient and almost flat theme
  - Added new hooks to comment, form and subnav component
  - Removed box-shadow for invalid controls in Firefox
  - Removed default input style for iOS
  - Fixed z-index issues
  - Fixed double click issue in form-file add-on
  - Fixed textarea height not being resizable
  - Fixed badge border-radius
  - Fixed wrong scaling calculation in overlay component for Chrome
  - Fixed notify padding
  - Fixed body content scrolling if modal is open
  - Fixed gap in navbar gradient and almost flat theme
  - Whitespace hack now uses font-size

**Documentation and repository**

  - Refactored add-on structure
  - Added layout examples
  - Added placeholder images in docs
  - Added holder.js for placeholder images in tests
  - Updated community section on frontpage
  - Renamed uk-width-custom to uk-width in docs and tests
  - Fixed overview test

### 2.3.1 (January 31, 2014)

  - Fixed button text decoration

### 2.3.0 (January 31, 2014)

  - IMPORTANT: Removed uk-button-expand, use uk-width-1-1 instead
  - IMPORTANT: Renamed @form-blank-outline to @form-blank-border
  - Updated to Normalize 3.0.0
  - Added more variables to all components
  - Added panel teaser to panel component
  - Added invisible to utility component
  - Added padding variable for thumbnail caption
  - Updated links in base component
  - Panel component works now with inline elements
  - Background color now set on tr elements in table component
  - Removed vertical align from breadcrumbs
  - Fixed button link in button component
  - Fixed cursor in sortable add-on
  - Fixed links in overlay-area-content
  - Fixed tooltip boundary check

**Documentation and repository**

  - Better comments for compiled CSS
  - Updated panel docs and tests
  - Fixed default theme in tests

### 2.2.0 (January 23, 2014)

  - Added alert, confirm shorcut methods to modal component
  - Added form-file add-on
  - Added primary comment to comment component
  - Added overlay-area-content to overlay component
  - Added margin-small to utility component
  - Added text-nowrap to text component
  - Added data-uk-margin to utility component
  - Switcher now activates first toggler when no uk-active class is set
  - Extended Notify message api wit content+status methods
  - Fixed Offcanvas in RTL mode
  - Fixed Tooltips in Offcanvas
  - Fixed sticky add-on jQuery error where $ is not available
  - Removed hgroup in normalize because it was deprecated in HTML5
  - Fixed data-uk-grid-match

**Documentation and repository**

  - Added form-file docs and tests
  - Updated LESS to 1.6.1
  - Updated overlay docs and tests
  - Updated utility docs and tests
  - Updated comment docs and tests
  - Optimized docs and tests with data-uk-margin

### 2.1.0 (January 07, 2014)
  - Added notify add-on
  - Added border-circle to utility component
  - Added more variables to sortable add-on
  - Added modifier to flip form icons
  - Updated form icons to work with form size modifiers
  - Replace fixed value with variable in nav component
  - Fixed background position in RTL mode
  - Fixed delayed dropdown trigger on touch devices
  - Fixed jumping when dragging sortables
  - Fixed nested comments indention on small screens
  - Fixed style for inputs without type attribute

**Documentation and repository**

  - Added new notify add-on
  - Fixed tooltip component
  - Fixed tests link

### 2.0.0 (December 11, 2013)

  - Added toggle component
  - Added form-icon to form component
  - Added datepicker add-on
  - Added form-password add-on
  - Added markdown area add-on
  - Added sortable add-on
  - Added sticky add-on
  - Added timepicker add-on
  - Added outerclick support for dropdowns in hover mode
  - Added touch events support for Windows 8 phones
  - Added miscellaneous hooks
  - Updated icon component to Font Awesome to 4.0.3
  - Changed comments to compile nicer CSS output

**Documentation and repository**

  - Refactored repository structure
  - Refactored variables
  - Added Grunt task to index new themes ( usage: grunt indexthemes )
  - Added new UIkit add-ons and components
  - UIkit tests moved to /src

### 1.2.1 (December 03, 2013)

  - Fixed off canvas scrolling on windows phones
  - Fixed search more results in search js

**Documentation and repository**

  - Updated LESS to 1.5.1

### 1.2.0 (November 01, 2013)
  - Added shake animation
  - Added boundary check to tooltip component
  - Added delay and animation option to tooltip component
  - Added margin-left and margin-right to utility component
  - Added variables for width sub-modifiers to form component
  - Added size modifier support for textarea and multiple selects
  - Added renderer option for seach component
  - Added scrollspy-nav to scrollspy component
  - Auto-initialize dynamic components using MutationObserver if supported by browser
  - Changed box-sizing for scrollable-box
  - Fixed link-muted
  - Fixed form-controls-condensed margin
  - Fixed rare customizer unknown LESS var error
  - Fixed smooth-scroll offset position

### 1.1.0 (August 21, 2013)

  - Added scrollspy component
  - Added animation component
  - Added link-muted to utility component
  - Added subtitle support for navbar items
  - Off-canvas now uses hardware accelerated translateX for bar animation
  - Added responsive tab dropdown indicator
  - Added show specific tab using id target in the url as hash
  - Added flipDropdown option to search component
  - Added possibility to change modal width via inline-style or custom class
  - Fixed responsive tabs
  - Fixed links within alert components
  - Fixed open modals in a chain
  - Fixed off-canvas scroll position bug

**Documentation and repository**

  - Added scrollspy and animation docs and tests
  - Added bower definition file
  - Automated version and download link
  - Added heading large example

### 1.0.2 (July 31, 2013)

  - Added boundary option for dropdowns
  - Removed Navbar.js
  - Removed auto dropdown flip if navbar is flipped

**Documentation and repository**

  - Updated dropdown and navbar documentation

### 1.0.1 (July 26, 2013)

  - Added focus and blur events to tooltip component
  - Added smoother off-canvas effect
  - Added hook for uk-container
  - Fixed multiple off-canvas trigger
  - Fixed `select` height for multiple and size attributes

**Documentation and repository**

  - Added import LESS functionality to customizer
  - Remove absolute paths from CSS build in customizer
  - Disabled LESS cache in tests
  - Tests initialized on domready instead of on window load
  - Updated grunt script to auto compile themes
  - Fixed several typos and links
  - Updated favicon

### 1.0.0 (July 19, 2013)

  - Initial Release
