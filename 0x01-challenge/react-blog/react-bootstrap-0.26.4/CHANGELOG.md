

Code
Issues
Pull requests
BreadcrumbsFix_My_Code_Challenge/0x01-challenge/react-blog/react-bootstrap-0.26.4
/CHANGELOG.md
Latest commit
Fuzzworth
Fuzzworth
4 months ago
History
Executable File·521 lines (367 loc) · 27 KB
File metadata and controls

Preview

Code

Blame
v0.26.4 - Wed, 07 Oct 2015 21:41:05 GMT
v0.26.3 - Wed, 07 Oct 2015 20:41:43 GMT
v0.26.2 - Wed, 07 Oct 2015 16:43:16 GMT
ca52c30 [fixed] Actually export the Image component
73daba7 [fixed] Show toggle button when using NavBrand
v0.26.1 - Mon, 05 Oct 2015 02:04:27 GMT
v0.26.0 - Sun, 04 Oct 2015 21:21:22 GMT
b7853bb [fixed] Dropdown focus behavior on click
dbb0385 [added] #1320 allow NavItem class to be set
3d13dda [fixed] #1287 ListGroupItem with onClick and header properly displays header
3f5c6e3 [added] #1181 ListGroup supports componentClass prop
b5a9f3a [added] NavBrand Component
ac37698 [added] 'Responsive embed' component
1c2d054 [fixed] Set the disabled css class so that the text is greyed out.
0348274 [fixed] Breadcrumb and BreadcrumbItem components
3c710f9 [added] Breadcrumb component
99d333f [changed] use lodash-compat for IE8 compatibility and lodash for dev
ce564cb [fixed] any props not known by DropdownMenu are passed through to the underlying ul
674d67e [added] images component
deee09d [fixed] stop rendering extra attributes on Progress bar dom nodes
02f1fec [fixed] allow null activeKey (empty) selection
656f40d [changed] 'id' prop-type made uniform throughout the project
b9a4477 [changed] use 'react-prop-types' instead of 'utils/CustomPropTypes'
v0.25.2 - Sat, 12 Sep 2015 15:59:13 GMT
f2c3b68 [changed] tab keyboard navigation to be more inline with ARIA spec
0c27403 [fixed] Don't render Grid or Row with Tabs
b847dec [added] active prop on MenuItem (again)
3a369cc [fixed] Error on opening dropdown without focusable items
bad277e [changed] Use PropTypes.node for validation and fix/add tests
533530a [added] Adds a callout to the sr-only button in Closable Alerts
1f29000 [fixed] screen-reader accessible dismiss button on alerts
c8a59c6 [fixed] OverlayTrigger hover triggers on mousenter/leave
9c69271 [fixed] OverlayTrigger event handlers are properly maintained
da1d0bc [fixed] focus returns to the toggle by default onClose
v0.25.1 - Fri, 28 Aug 2015 18:30:59 GMT
478300a [fixed] Handle falsey DropdownMenu children correctly
c450e96 [fixed] stop rendering extra attributes on Progress bar dom nodes
3ceb7af [fixed] allow null activeKey (empty) selection
a7f93ae [fixed] title is not passed to tab pane DOM node
1bee466 [changed] 'id' prop-type made uniform throughout the project
e438250 [fixed] 'isRequireForA11y' undefined/null checking
664b465 [fixed] id passthrough for MenuItem
v0.25.0 - Tue, 25 Aug 2015 18:56:33 GMT
8776128 [fixed] Affix in IE10 - scrollHeight #1073
adad32e [added] PropType validation for headerRole and panelRole
346501e [changed] DropdownButton, SplitButton, DropdownMenu, MenuItem completely rewritten
653d2ff [changed] deprecate domUtils as a public API
769781d [added] accessibility props for PanelGroup and Panels.
5f0ac64 [added] Implements a generalized left-aligned version of tabs
628d586 [changed] deprecated Position, Transition, Portal
03a6a61 [changed] deprecated the Transition duration prop
459ab0c [added] #460 ListGroupItem outputs when an onClick handler is set.
e482ede [fixed] wrong tabs switching animation for 'Tabs' component
b62e1f5 [fixed] wrong tabs switching animation for 'TabbedArea' component
d0ff625 [added] aria role "tablist" to the Nav on Tabs
e7cf455 [changed] New Tabs API
f6d32c4 [changed] deprecate 'utils/CustomPropTypes' exporting
caff9a0 [removed] Factory support
v0.24.5 - Fri, 14 Aug 2015 18:02:13 GMT
dc2a07a [fixed] Collapse exported as Fade
f53bcf5 [fixed] 'bsSize' and 'bsStyle' properties has been removed from 'Glyphicon'
v0.24.4 - Mon, 10 Aug 2015 19:33:35 GMT
b688014 [added] custom feedback icons for Input
83cdaa3 [added] formControlFeedback prop to Glyphicon
2ecac68 [fixed] Modal uses provided className again
47bd7f6 [fixed] disabled pagination buttons should not fire 'onSelect'
c60dc03 [fixed] only add aria-expanded to Collapse when an ARIA role is present
v0.24.3 - Fri, 31 Jul 2015 18:09:54 GMT
02f8966 [changed] Update dependencies
bae8ba9 [fixed] Carousel checks if it is mounted before setting state
fd8d4d2 [fixed] regression when clicking "static" modal backdrops
0f46a97 [added] Allow custom Modal dialog components
a4ce7e1 [fixed] added finalisation for the Modal when it was unbound from the tree
d89d5f3 [fixed] Modal error when backdrop is false
f410904 [added] 'xs, sm, md, lg' values for 'bsSize'
2558f32 [fixed] TabbedArea panes rendering with animation
90aece6 [changed] Simplify 'styleMaps.STYLES' to be of Array type
860d168 [fixed] allow totally custom styles via 'bsStyle'
74da76a [fixed] Prevent click on PageItem if disabled
v0.24.2 - Sat, 25 Jul 2015 00:47:07 GMT
4271eb3 [fixed] add lodash as direct dependency
v0.24.1 - Fri, 24 Jul 2015 23:12:09 GMT
e5155c6 [fixed] ensure last focused item can be focused
6a541ff [added] buttonComponentClass prop for Pagination
29fe417 [fixed] overlay classNames are maintained by overlayTrigget
d272389 [added] Overlay and OverlayTrigger accept Transition callbacks
596f40c [fixed] Modal uses bsClass prop to set its classes
86d3feb [fixed] added missed 'aria-label' prop type validation for 'ModalHeader'
58eaab0 [changed] pass transition callbacks to Modal Transition
abccff9 [changed] expose static Modal Dialog component
b5c1893 [changed] unfix 'babel' back.
v0.24.0 - Tue, 21 Jul 2015 22:13:05 GMT
924f8fb [fixed] Tooltip accepts a style prop
dd064ad [fixed] remove extraneous styling
c837d8d [fixed] Only calculate overlay position on display
fbf9ed6 [changed] Add deprecation warning that factories will be removed
a4385d3 [fixed] Portal doesn't mount extra node
6744b94 [fixed] 'modalClassName' property for 'ModalTitle'
3e6523a [added] ListGroup supports iterator as child
ec368f0 [added] Fade Component, replaces FadeMixin
0503507 [added] Collapse Component, replaces CollapsibleMixin
4fb7e0d [changed] Remove Overlay and Modal deprecations
0683df7 [fixed] 'stacked' progress with 'active' and 'striped' children
a3c5400 [fixed] Add missed 'type' property React.PropTypes. checking
a4c065e [added] links to every component / example on Components page
eb0c323 [fixed] Position.js typo componentDidUpate
9feddf9 [fixed] 'componentWillReceiveProps' method name of Position component
c64679f [fixed] Active Next and Last button in Pagination when ellipsis=true and items=0
9dae734 [fixed] Negative page number in Pagination when ellipsis=true and items=1
ffbcf39 [fixed] html id and class attributes handling for Nav
89ea6ed [fixed] Add missed propType validation for Button 'type' property
b1b6a4c [changed] Add two-release deprecation policy
e89b9bc [removed] Don't need to disable Babel cache
d12d59e [changed] Enabled "loose" Babel transpilation
01c547f [fixed] Do not use Babel cache for release build
b67081b [fixed] rootClose behavior on replaced elements
fbbb344 [fixed] bower template.
fafe46f [changed] Use named exports in index files
6e985b0 [removed] Individual files in bower release
598b9d8 [fixed] SafeAnchor event ordering
beaa1fa [changed] PaginationButton to use SafeAnchor
9c09e2a [fixed] Keyboard accessibility for anchors serving as buttons
ce5b436 [removed] Input type=submit deprecation warning.
v0.23.7 - Wed, 01 Jul 2015 15:18:30 GMT
35ea201 [fixed] Accidental breaking change in Modal trigger
v0.23.6 - Wed, 01 Jul 2015 00:48:02 GMT
1b1af04 [changed] deprecate ModalTrigger
83b4cbc [changed] Modal doesn't require ModalTrigger
d70f617 [changed] tooltips and popovers required id's for a11y
389cf3f [changed] Deprecate OverlayTrigger positioning api and "manual" trigger
5eb8666 [added] Overlay component
1638f69 [added] Position component for custom Overlays
f799110 [added] Portal component; replaces OverlayMixin
97ef415 [fixed] Modal won't steal focus from children
a8b177a [fixed] Stack overflow with nested Modals
3caa866 [changed] Update babel-loader
6ffa325 [fixed] 'componentClass' property type is 'elementType' now
0e5980f [added] 'elementType' custom prop type validator
8f582d2 [changed] Update karma-chrome-launcher. Dev dependency
d4089d0 [changed] Update eslint-plugin-mocha. Dev dependency
fd547f4 [changed] Update karma-mocha. Dev dependency.
c5797e8 [added] componentClass prop to Jumbotron
v0.23.5 - Tue, 23 Jun 2015 01:31:35 GMT
23f9d21 [changed] Add missed prop types validations.
320b7ab [changed] Update fs-extra. Dev dependency.
2ffcf5d [fixed] Popovers flicker when moving mouse amongst children of the trigger
ccc50e0 [fixed] Accessibility: Panel header uses aria-controls
1e552cc [added] Accessibility: use appropriate ARIA's when an id is given to the tabbed area
8752754 [added] Add linkId prop to NavItem
722969d [added] Accessibility, add tab roles when type "tabs"
4adaa70 [added] Accessibility: role 'alert' and aria-label to Alert component
2594dce [fixed] Modal Null Exception when react-bootstrap is loaded before the Body tag
e77bf88 [changed] Update eslint. Dev dependency.
v0.23.4 - Tue, 16 Jun 2015 00:37:04 GMT
0ce46b9 [changed] only autofocus modals when enforceFocus is true (the default)
c5855d2 [changed] createChainedFunction to chain many functions, and to throw if non-functions are provided.
d18dadb [fixed] container content no longer shifts when overflowing
66f0f92 [added] enforceFocus prop to Modal
3869ca2 [fixed] Modal doesn't "jump" when container is overflowing
v0.23.3 - Fri, 12 Jun 2015 21:46:30 GMT
9ca26e9 [added] contains "polyfill" to domUtils
3a254a1 [added] Deprecation warning for individual file use in the Bower release
73c7705 [changed] Update chai. Dev dependency.
3ca90c7 [changed] Update karma-sinon-chai. Dev dependency.
cc4e820 [changed] Update fs-extra. Dev dependency.
v0.23.2 - Mon, 08 Jun 2015 18:56:48 GMT
7211dcb [added] Add prevIcon and nextIcon props as node proptypes to Carousel
5734ec3 [added] Pagination component
2f8c454 [changed] Assert ProgressBar children can be ProgressBar only.
2c46820 [added] createSelectedEvent for consistent onSelect handling
c2ff9ad [added] property disabled on MenuItem
v0.23.1 - Tue, 02 Jun 2015 16:57:57 GMT
4d265f0 [fixed] Use babel api to avoid command line conflicts between Linux and Windows
0cfbf3b [fixed] IE8 will now close an open DropdownButton menu when clicking button
d105749 [added] utils object to exported src/index
29bc64f [changed] Remove Dev dependency babel-plugin-object-assign.
1fec852 [changed] Update karma-phantomjs-launcher. Dev dependency.
f494604 [changed] Update eslint. Dev dependency.
a4331ed [changed] Make the brand name consistent.
b213be0 [changed] Remove ES6 sources from npm distribution.
73c5ec9 [changed] Remove extraneous utils/Object.assign.js
935171f [added] Now accepting a block property on the ButtonGroup component. Closes #240.
dfec023 [added] CustomPropType.all to allow multiple validations
v0.23.0 - Tue, 26 May 2015 19:32:52 GMT
fd24317 [changed] Removed collapsable deprecated functionality.
3ebac95 [fixed] bug #731. babel ES6 import + React quirk.
0c61f46 [changed] Moving type=static out of Input
2749cfd [added] CustomPropTypes.singlePropFrom
536c3e0 [fixed] Replaced document with ownerDocument in Modal
91f0222 [changed] Update css-loader. Dev dependency.
66e41a4 [fixed] Fix scroll top calculation for overlays
5313abe [fixed] Modal is focused when opened, for improved accessibility
50d058a [fixed] server side rendering for Modal component
c57d6b0 [changed] Update css-loader. Dev dependency.
v0.22.6 - Wed, 20 May 2015 16:46:29 GMT
2a35eab [fixed] Fix CodeMirrorEditor binding
5dc0ac2 [added] Enable rootClose for OverlayTrigger
v0.22.5 - Tue, 19 May 2015 20:40:51 GMT
dc7ef19 [added] dialogClassName prop to modal to be able to pass custom css class to modal-dialog div
658fa39 [fixed] Remove unused variable
v0.22.4 - Mon, 18 May 2015 16:53:06 GMT
9d17d56 [added] Thumbnail component
db018fa [fixed] Put AMD modules under correct path
0904adc [added] Active property to MenuItem component
1658142 [added] Property for animation on Popover and Tooltip
4f37560 [fixed] Update classnames dep version for Bower
f6e7d67 [fixed] Bower cannot use code from react/lib.
1531ac9 [added] DropdownButton now applies onClick prop to Button
ecb0861 [fixed] Fix propType warning in ButtonInputExample
592a346 [fixed] Forward classes to panel title
v0.22.3 - Thu, 14 May 2015 22:19:11 GMT
96baa15 [fixed] Fix propTypes for overlays
v0.22.2 - Thu, 14 May 2015 20:36:17 GMT
03211db [fixed] Fit overlay within viewport boundary
576827f [changed] Introducing ButtonInput
v0.22.1 - Thu, 14 May 2015 17:54:32 GMT
d3f57c5 [added] TabbedArea allows disabled tabs
v0.22.0 - Wed, 13 May 2015 18:31:52 GMT
061bef2 [fixed] update link to react-router-bootstrap in README
0fb9b57 [changed] Updated extract-text-webpack-plugin. Dev dependency.
ca689c0 [changed] Updated eslint dev-dependency
0f90799 [added] react-hot-loader when developing docs
4cd5845 [added] FormGroup/Input bsSize now propgates correctly as form-group-* classes
6ce8870 [added] Introduction Page.
1c6c74b [fixed] Modal div.modal-content should not have hidden class
51a205f [changed] collapsable => collapsible property
f77c955 [changed] Updated classnames dependency
5a76e94 [added] favicon
8da11b4 [added] convenience factories for non-JSX users in lib/factories
v0.21.2 - Fri, 01 May 2015 19:36:56 GMT
a07aa20 [fixed] Bug introduced by new deprecation code.
fef8984 [fixed] #597 able to set ID on ListGroup
v0.21.1 - Wed, 29 Apr 2015 21:44:50 GMT
3767c43 [added] Added buttonClassName to DropdownButton
e59c4f8 [added] Clarification about implementing components.
0105127 [changed] Renamed Collapsable* => Collapsible*
6b9c250 [fixed] Fix for bug 547 in tools/release.
b86e03e [fixed] ListGroup rendering a ul when ListGroupItem has onClick handler
ddc8a85 [changed] Updated eslint dev-dependency
18c22ba [changed] Updated style-loader dev-dependency
01c16c1 [changed] Updated css-loader dev-dependency
c295a9a [fixed] ModalTrigger passes onFocus prop and onBlur prop to child
131669b [fixed] ModalTrigger passes onMouseOver prop and onMouseOut prop to child
1249eff [fixed] OverlayTrigger passes onClick prop to child
5f565b9 [added] Docs example of passing component to navbar brand.
7811ce2 [added] Dry run and verbose options to release process
22da8f9 [fixed] ListGroup children array bugs. Fixes #548
b17a7b3 [added] release-docs script
4fedc95 [fixed] Bug in Server vs Client side rendering of Navbar
1d8b7c7 [fixes] #516 [added] TabbedArea NavItem renderTab() className
725deaa [changed] Updated css-loader dev-dependency
eb29b11 [changed] Updated style-loader dev-dependency
bc8cd5c [fixed] Fix for bug507.
v0.21.0 - Tue, 21 Apr 2015 13:38:38 GMT
e92a64b [fixed] Handle multiple children in Badge
c1b189f [changed] Updated babel* tools. dev-dependency
a58eab5 [fixed] Fix 'import from' => 'import'
276c2bc [fixed] ProgressBar percentage issue when stacked
e1c95b3 [changed] Renamed constants to styleMaps and added styleMaps.addStyle()
20b608f [fixed] Add missed semicolons.
2111799 [fixed] Remove unused variables.
0e6b62a [fixed] typo
0c87128 [fixed] ListGroup outputs <ul> or <div> depending on ListGroupItem (defaults to <ul> if no ListGroupItem). ListGroupItem outputs <li> or <a> if href prop is set.
v0.20.3 - Fri, 10 Apr 2015 19:50:22 GMT
3ecd393 [fixed] Missing PropType Validations
8a9e95c [fixed] Include missing PropType validations
6dfcf36 [changed] Internal variables classSet to classNames
v0.20.2 - Tue, 07 Apr 2015 01:51:55 GMT
723ee4d [fixed] Release scripts usage of rimraf
7175431 [fixed] Don't try to access .ownerDocument on null
a58cff9 [fixed] Numerous ESlint warnings (Removes 145 warnings)
c6c4108 [added] Twitter follow link to docs page footer
20472b9 [fixed] Windows build
v0.20.1 - Sat, 04 Apr 2015 14:22:18 GMT
a060fbc [fixed] Re-add missing constants to public API
v0.20.0 - Tue, 31 Mar 2015 13:04:40 GMT
f1438b5 [changed] Updated eslint-plugin-react dev-dependency
c8dda3f [added] HuBoard badge and link
ee0382e [fixed] Use .ownerDocument instead of root document
182344a [changed] Updated express dev-dependency
6edadbd [changed] Updated mocha dev-dependency
64ac86d [changed] React dependency from 0.13.0 -> 0.13.1
367b870 [changed] Updated karma-chai dev-dependency
1956d2a [changed] Updated style-loader dev-dependency
76c87bf [changed] Updated ESLint dev-dependency
84b9113 [changed] Update Bootstrap to 3.3.4
bfb3e6c [added] standalone prop to Input, which will not render the form-group class
721aacc [fixed] Documentation on react install
6907e03 [changed] Renamed src/main.js -> src/index.js
5118b42 [added] Test for carousel control behaviour with wrap=true
ea479db [fixed] show carousel controls if wrap is enabled
v0.19.1 - Thu, 26 Mar 2015 19:37:01 GMT
2b7d235 [fixed] Re-added CollapsableNav to public API
v0.19.0 - Wed, 25 Mar 2015 21:25:57 GMT
98ee978 [changed] Source to ES6 using Babel and Webpack
v0.18.0 - Tue, 24 Mar 2015 02:56:15 GMT
728c2b0 [fixed] docs CodeMirror scroll height too big
d282621 [fixed] Split buttons with React 0.13
549da6e [added] react-router dependency for docs
804c24a [added] Support for React 0.13.x
4c26075 [fixed] Build status badge
70f8596 [added] Travis CI Optimization
v0.17.0 - Tue, 17 Mar 2015 15:03:27 GMT
4fae871 [added] CollapsableNav implements bootstrap markup for navbar-collapse
befed83 [fixed] All panel-* classes dynamic based on bsStyle prop
de6f7dd [fixed] CollapsableMixin fixed size
7cc4747 [fixed] Added role="button" to NavItem for aria compliance.
3b6ba7a [fixed] Col Offset/Pull/Push of zero. Fixes #406
66c439f [fixed] OverlayTrigger improvement related to #353 . Helps reduce browser reflows for lots of multiple OverlayTriggers being rendered at once. Before: http://i.imgur.com/e4UZ5l6.png , http://i.imgur.com/Tw39F9t.png After: http://i.imgur.com/bU0f7VY.png
v0.16.1 - Tue, 03 Mar 2015 23:04:19 GMT
71ff264 [added] bsSize prop to Input, supporting input groups
v0.16.0 - Fri, 27 Feb 2015 14:01:37 GMT
25b4143 [fixed] Define toggleNavKey in the propTypes
1a4ae1d [fixed] Fix rendering Navbar header when toggleNavKey is 0
13f395d [added] bsStyle prop support for Modal to set the header color
c822837 [removed] non-standard onClick props for ListGroup and ListGroupItem
1556e63 [added] Example for collapsable Navbar in docs.
v0.15.1 - Tue, 17 Feb 2015 14:30:54 GMT
587a34f [fixed] Include .npmignore so compile lib dir is published
v0.15.0 - Mon, 16 Feb 2015 02:41:59 GMT
1ef51cb [added] Changelog generation from commit messages
13baeaa [added] Release task to push and tag docs and bower repos
0193046 [changed] Move built components to lib directory
