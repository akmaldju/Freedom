# CSS Freedom

CSS Freedom is a light-weight, powerful, and extremely flexible CSS framework that is suitable for bringing any design idea to life without the need to leave your HTML. It includes a range of features and utilities for styling and layout, including responsive grids, pre-designed UI elements, and utility classes for quickly styling common elements.

## Getting Started

To get started with CSS Freedom, simply include the `freedom.css` file in your project.

## Benefits of Using CSS Freedom

-   **Lightweight:** CSS Freedom is designed to be lightweight and fast, ensuring minimal impact on your website's performance.
-   **Flexible:** The framework is highly flexible, allowing you to customize the styles to match your specific design requirements.
-   **Easy to Use:** CSS Freedom is easy to learn and use, with a simple and intuitive class naming convention.
-   **Responsive:** The framework includes responsive styles that adapt to different screen sizes, ensuring your website looks great on all devices.
-   **Comprehensive:** CSS Freedom provides a wide range of features and utilities, including layout, typography, components, and hover effects.

## Available Classes and Features

### Display

-   `.d-*` or `.display-*`: Sets the display property. Available options: `flex`, `inline`, `inline-grid`, `table`, `list-item`, `block`, `grid`, `none`.
-   `.position-*` or `.pos-*`: Sets the position property. Available options: `absolute`, `fixed`, `inherit`, `initial`, `relative`, `revert`, `static`, `sticky`, `unset`.
-   `.flex-order-*` or `.order-*`: Sets the flex order. Available options: 0-10.
-   `.zi-*` or `.z-index-*`: Sets the z-index. Available options: 0-10.
-   `.hide` or `.hidden`: Hides the element.
-   `.show`: Shows the element.
-   `.invisible`: Makes the element invisible.
-   `.visible`: Makes the element visible.
-   `.flex-*` or `.f-*`: Sets the flex direction. Available options: `row`, `column`.
-   `.flex-*` or `.f-*`: Sets the flex wrap. Available options: `inherit`, `initial`, `nowrap`, `revert`, `unset`, `wrap`, `wrap-reverse`.
-   `.fb-*` or `.flex-basis-*`: Sets the flex basis. Available options: 0-100.
-   `.fg-*` or `.grow-*` or `.flex-grow-*`: Sets the flex grow. Available options: 0-10.
-   `.fs-*` or `.shrink-*` or `.flex-shrink-*`: Sets the flex shrink. Available options: 0-10.
-   `.justify-content-*` or `.jc-*`: Sets the justify-content property. Available options: `center`, `justify`, `right`, `left`, `start`, `end`, `space-around`, `space-between`, `space-evenly`, `flex-start`, `flex-end`, `unset`.
-   `.align-content-*` or `.ac-*`: Sets the align-content property. Available options: `stretch`, `center`, `flex-start`, `flex-end`, `space-between`, `space-around`, `initial`, `inherit`.
-   `.align-self-*` or `.as-*`: Sets the align-self property. Available options: `auto`, `stretch`, `center`, `flex-start`, `flex-end`, `baseline`, `initial`, `inherit`.
-   `.align-items-*` or `.ai-*`: Sets the align-items property. Available options: `stretch`, `center`, `flex-start`, `flex-end`, `baseline`, `initial`, `inherit`.
-   `.overflow-*`: Sets the overflow property. Available options: `auto`, `hidden`, `scroll`, `visible`.
-   `.overflow-x-*`: Sets the overflow-x property. Available options: `auto`, `hidden`, `scroll`, `visible`.
-   `.overflow-y-*`: Sets the overflow-y property. Available options: `auto`, `hidden`, `scroll`, `visible`.
-   `.top-*`, `.bottom-*`, `.right-*`, `.left-*`: Sets the top, bottom, right, and left positions. Available options: 0-25 (increments of 4px).

### Image

-   `.img-fit-*` or `.image-fit-*` or `.img-object-fit-*` or `.image-object-fit-*` or `.img-of-*` or `.image-of-*`: Sets the object-fit property. Available options: `contain`, `cover`, `fill`, `inherit`, `initial`, `none`, `revert`, `scale-down`, `unset`.
-   `.img-rounded` or `.image-rounded`: Sets the border-radius to 6px.
-   `.img-circle` or `.image-circle`: Sets the border-radius to 50%.
-   `.img-thumbnail` or `.image-thumbnail`: Sets the thumbnail style.
-   `.img-hover-light` or `.image-hover-light`: Sets the hover light effect.
-   `.img-hover-shadow` or `.image-hover-shadow`: Sets the hover shadow effect.
-   `.img-responsive` or `.image-responsive`: Makes the image responsive.
-   `.img-filter-blur` or `.filter-blur` or `.if-blur`: Sets the blur filter.
-   `.img-filter-brightness` or `.filter-brightness` or `.if-brightness`: Sets the brightness filter.
-   `.img-filter-contrast` or `.filter-contrast` or `.if-contrast`: Sets the contrast filter.
-   `.img-filter-grayscale` or `.filter-grayscale` or `.if-grayscale`: Sets the grayscale filter.
-   `.img-filter-huerotate` or `.filter-huerotate` or `.if-huerotate`: Sets the hue-rotate filter.
-   `.img-filter-invert` or `.filter-invert` or `.if-invert`: Sets the invert filter.
-   `.img-filter-opacity` or `.filter-opacity` or `.if-opacity`: Sets the opacity filter.
-   `.img-filter-saturate` or `.filter-saturate` or `.if-saturate`: Sets the saturate filter.
-   `.img-filter-sepia` or `.filter-sepia` or `.if-sepia`: Sets the sepia filter.
-   `.img-filter-shadow` or `.filter-shadow` or `.if-shadow`: Sets the drop-shadow filter.
-   `.img-flip` or `.flip` or `.flipped`: Flips the image horizontally.
-   `.img-flip-x` or `.flip-x` or `.flipped-x`: Flips the image horizontally.
-   `.img-flip-y` or `.flip-y` or `.flipped-y`: Flips the image vertically.
-   `.img-avatar` or `.avatar`: Sets the avatar style.

### Margin

-   `.m-auto` or `.margin-auto`: Sets margin to auto.
-   `.m-*` or `.margin-*`: Sets margin. Available options: 0-25 (increments of 0.25rem).
-   `.mt-auto` or `.margin-top-auto`: Sets margin-top to auto.
-   `.mt-*` or `.margin-top-*`: Sets margin-top. Available options: 0-25 (increments of 0.25rem).
-   `.mb-auto` or `.margin-bottom-auto`: Sets margin-bottom to auto.
-   `.mb-*` or `.margin-bottom-*`: Sets margin-bottom. Available options: 0-25 (increments of 0.25rem).
-   `.mr-auto` or `.margin-right-auto`: Sets margin-right to auto.
-   `.mr-*` or `.margin-right-*`: Sets margin-right. Available options: 0-25 (increments of 0.25rem).
-   `.ml-auto` or `.margin-left-auto`: Sets margin-left to auto.
-   `.ml-*` or `.margin-left-*`: Sets margin-left. Available options: 0-25 (increments of 0.25rem).
-   `.mx-auto` or `.margin-x-auto`: Sets margin-right and margin-left to auto.
-   `.mx-*` or `.margin-x-*`: Sets margin-right and margin-left. Available options: 0-25 (increments of 0.25rem).
-   `.my-auto` or `.margin-y-auto`: Sets margin-top and margin-bottom to auto.
-   `.my-*` or `.margin-y-*`: Sets margin-top and margin-bottom. Available options: 0-25 (increments of 0.25rem).

### Padding

-   `.p-auto` or `.padding-auto`: Sets padding to auto.
-   `.p-*` or `.padding-*`: Sets padding. Available options: 0-25 (increments of 0.25rem).
-   `.pt-auto` or `.padding-top-auto`: Sets padding-top to auto.
-   `.pt-*` or `.padding-top-*`: Sets padding-top. Available options: 0-25 (increments of 0.25rem).
-   `.pb-auto` or `.padding-bottom-auto`: Sets padding-bottom to auto.
-   `.pb-*` or `.padding-bottom-*`: Sets padding-bottom. Available options: 0-25 (increments of 0.25rem).
-   `.pr-auto` or `.padding-right-auto`: Sets padding-right to auto.
-   `.pr-*` or `.padding-right-*`: Sets padding-right. Available options: 0-25 (increments of 0.25rem).
-   `.pl-auto` or `.padding-left-auto`: Sets padding-left to auto.
-   `.pl-*` or `.padding-left-*`: Sets padding-left. Available options: 0-25 (increments of 0.25rem).
-   `.px-auto` or `.padding-x-auto`: Sets padding-right and padding-left to auto.
-   `.px-*` or `.padding-x-*`: Sets padding-right and padding-left. Available options: 0-25 (increments of 0.25rem).
-   `.py-auto` or `.padding-y-auto`: Sets padding-top and padding-bottom to auto.
-   `.py-*` or `.padding-y-*`: Sets padding-top and padding-bottom. Available options: 0-25 (increments of 0.25rem).

### Block

-   `.full-screen` or `.full`: Sets the element to full screen.
-   `.fixed-top`: Sets the element to fixed position at the top.
-   `.fixed-bottom`: Sets the element to fixed position at the bottom.
-   `.bg-*` or `.background-*`: Sets the background color. Available options: `light`, `grey`, `red`, `dark-red`, `green`, `blue`, `yellow`, `fade-blue`, `transparent`.
-   `.bg-fixed` or `.background-fixed`: Sets the background attachment to fixed.
-   `.bg-scroll` or `.background-scroll`: Sets the background attachment to scroll.
-   `.opacity-*`: Sets the opacity. Available options: 0-10 (increments of 10%).

### Border

-   `.b-*` or `.border-*`: Sets the border width. Available options: 0-5.
-   `.br-*` or `.border-right-*`: Sets the border-right width. Available options: 0-5.
-   `.bt-*` or `.border-top-*`: Sets the border-top width. Available options: 0-5.
-   `.bb-*` or `.border-bottom-*`: Sets the border-bottom width. Available options: 0-5.
-   `.bl-*` or `.border-left-*`: Sets the border-left width. Available options: 0-5.
-   `.border-*`: Sets the border color. Available options: `light`, `grey`, `red`, `dark-red`, `green`, `blue`, `yellow`, `fade-blue`, `transparent`.
-   `.border-*`: Sets the border style. Available options: `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset`.
-   `.border-normal`: Sets the border-radius to 0px.
-   `.border-material`: Sets the border-radius to 3px.
-   `.border-round`: Sets the border-radius to 5px.
-   `.border-rounder`: Sets the border-radius to 8px.
-   `.border-roundest`: Sets the border-radius to 12px.

### Outline

-   `.o-*` or `.outline-*`: Sets the outline width. Available options: 0-5.
-   `.outline-*`: Sets the outline color. Available options: `light`, `grey`, `red`, `dark-red`, `green`, `blue`, `yellow`, `fade-blue`, `transparent`.
-   `.outline-*`: Sets the outline style. Available options: `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset`.

### Sizing

-   `.w-full` or `.width-full`: Sets the width to 100%.
-   `.w-screen` or `.width-screen`: Sets the width to 100vw.
-   `.w-content` or `.width-content`: Sets the width to fit-content.
-   `.w-auto` or `.width-auto`: Sets the width to auto.
-   `.w-*` or `.width-*`: Sets the width. Available options: 0-100 (increments of 1%), 0-100vw (increments of 1vw), 0-50rem (increments of 1rem), 0-50px (increments of 1px).
-   `.w-min-full` or `.width-min-full`: Sets the min-width to 100%.
-   `.w-min-screen` or `.width-min-screen`: Sets the min-width to 100vw.
-   `.w-min-content` or `.width-min-content`: Sets the min-width to fit-content.
-   `.w-min-auto` or `.width-min-auto`: Sets the min-width to auto.
-   `.w-min-*` or `.width-min-*`: Sets the min-width. Available options: 0-100 (increments of 1%), 0-100vw (increments of 1vw), 0-50rem (increments of 1rem), 0-50px (increments of 1px).
-   `.w-max-full` or `.width-max-full`: Sets the max-width to 100%.
-   `.w-max-screen` or `.width-max-screen`: Sets the max-width to 100vw.
-   `.w-max-content` or `.width-max-content`: Sets the max-width to fit-content.
-   `.w-max-auto` or `.width-max-auto`: Sets the max-width to auto.
-   `.w-max-*` or `.width-max-*`: Sets the max-width. Available options: 0-100 (increments of 1%), 0-100vw (increments of 1vw), 0-50rem (increments of 1rem), 0-50px (increments of 1px).
-   `.h-full` or `.height-full`: Sets the height to 100%.
-   `.h-screen` or `.height-screen`: Sets the height to 100vh.
-   `.h-content` or `.height-content`: Sets the height to fit-content.
-   `.h-auto` or `.height-auto`: Sets the height to auto.
-   `.h-*` or `.height-*`: Sets the height. Available options: 0-100 (increments of 1%), 0-100vh (increments of 1vh), 0-50rem (increments of 1rem), 0-50px (increments of 1px).
-   `.h-min-full` or `.height-min-full`: Sets the min-height to 100%.
-   `.h-min-screen` or `.height-min-screen`: Sets the min-height to 100vh.
-   `.h-min-content` or `.height-min-content`: Sets the min-height to fit-content.
-   `.h-min-auto` or `.height-min-auto`: Sets the min-height to auto.
-   `.h-min-*` or `.height-min-*`: Sets the min-height. Available options: 0-100 (increments of 1%), 0-100vh (increments of 1vh), 0-50rem (increments of 1rem), 0-50px (increments of 1px).
-   `.h-max-full` or `.height-max-full`: Sets the max-height to 100%.
-   `.h-max-screen` or `.height-max-screen`: Sets the max-height to 100vh.
-   `.h-max-content` or `.height-max-content`: Sets the max-height to fit-content.
-   `.h-max-auto` or `.height-max-auto`: Sets the max-height to auto.
-   `.h-max-*` or `.height-max-*`: Sets the max-height. Available options: 0-100 (increments of 1%), 0-100vh (increments of 1vh), 0-50rem (increments of 1rem), 0-50px (increments of 1px).

### Text

-   `.h1` to `.h8`: Sets the heading size.
-   `.text-bold` or `.t-bold` or `.font-bold`: Sets the font-weight to bold.
-   `.text-italic` or `.t-italic` or `.font-italic`: Sets the font-style to italic.
-   `.text-normal` or `.t-normal` or `.font-normal`: Sets the font-weight and font-style to normal.
-   `.text-uppercase` or `.t-uppercase` or `.font-uppercase`: Sets the text-transform to uppercase.
-   `.text-lowercase` or `.t-lowercase` or `.font-lowercase`: Sets the text-transform to lowercase.
-   `.text-capitalize` or `.t-capitalize` or `.font-capitalize`: Sets the text-transform to capitalize.
-   `.text-revert` or `.t-revert` or `.font-revert`: Sets the text direction to right-to-left.
-   `.text-underline` or `.t-underline` or `.font-underline`: Sets the text-decoration to underline.
-   `.text-overline` or `.t-overline` or `.font-overline`: Sets the text-decoration to overline.
-   `.text-noline` or `.t-noline` or `.font-noline`: Sets the text-decoration to none.
-   `.text-line-through` or `.t-line-through` or `.font-line-through` or `.del` or `.text-del` or `.t-del` or `.font-del`: Sets the text-decoration to line-through.
-   `.text-highlight` or `.t-highlight` or `.font-highlight` or `.mark` or `.text-mark` or `.t-mark` or `.font-mark`: Sets the highlight style.
-   `.text-quote` or `.t-quote` or `.font-quote`: Sets the quote style.
-   `.text-monospace` or `.t-monospace` or `.font-monospace`: Sets the font-family to monospace.
-   `.text-lead` or `.t-lead` or `.font-lead`: Sets the lead style.
-   `.small`: Sets the font-size to 85%.
-   `.text-*` or `.t-*` or `.font-*`: Sets the font-family. Available options: `arial-black`, `arial`, `bookman`, `comic-sans`, `courier-new`, `courier`, `cursive`, `fantasy`, `garamond`, `georgia`, `impact`, `monospace`, `palatino`, `sans-serif`, `script`, `serif`, `tahoma`, `times-new-roman`, `times`, `trebuchet`, `verdana`.
-   `.text-*` or `.t-*` or `.font-*`: Sets the text-align. Available options: `center`, `justify`, `right`, `left`, `start`, `end`, `unset`.
-   `.text-*` or `.t-*` or `.font-*`: Sets the vertical-align. Available options: `tops`, `bottom`, `middle`, `baseline`, `text-top`, `text-bottom`.
-   `.text-*` or `.t-*` or `.font-*`: Sets the text color. Available options: `light`, `grey`, `red`, `dark-red`, `green`, `blue`, `yellow`, `fade-blue`, `transparent`.
-   `.text-*` or `.t-*` or `.font-*`: Sets the font-size. Available options: `medium`, `xx-small`, `x-small`, `small`, `large`, `x-large`, `xx-large`, `smaller`, `larger`, `initial`, `inherit`.
-   `.text-*` or `.t-*` or `.font-*`: Sets the font-size in pixels. Available options: 1-50.
-   `.text-*` or `.t-*` or `.font-*`: Sets the font-size in points. Available options: 1-50.
-   `.text-*` or `.t-*` or `.font-*`: Sets the font-size in rem. Available options: 1-10.
-   `.text-*` or `.t-*` or `.font-*`: Sets the font-size in em. Available options: 1-10.

### Components

-   `.alert`: Basic alert styling.
-   `.alert-dismissible`: Dismissible alert styling.
-   `.badge`: Basic badge styling.
-   `.badge-*`: Sets the badge background color. Available options: `light`, `grey`, `red`, `dark-red`, `green`, `blue`, `yellow`, `fade-blue`, `transparent`.
-   `.badge-round`: Sets the badge border-radius to 50rem.
-   `.btn`: Basic button styling.
-   `.btn-*`: Sets the button background color. Available options: `light`, `grey`, `red`, `dark-red`, `green`, `blue`, `yellow`, `fade-blue`, `transparent`.
-   `.btn-outline-*`: Sets the button outline style. Available options: `light`, `grey`, `red`, `dark-red`, `green`, `blue`, `yellow`, `fade-blue`, `transparent`.
-   `.btn-large` or `.btn-lg`: Sets the button size to large.
-   `.btn-small` or `.btn-sm`: Sets the button size to small.
-   `.btn-smallest` or `.btn-xs`: Sets the button size to smallest.
-   `.btn-disabled` or `.disabled`: Sets the button to disabled state.
-   `.card`: Basic card styling.
-   `.card-header`: Card header styling.
-   `.card-body`: Card body styling.
-   `.card-title`: Card title styling.
-   `.card-subtitle`: Card subtitle styling.
-   `.card-img-top`: Card image top styling.
-   `.card-img`: Card image styling.
-   `.card-img-overlay`: Card image overlay styling.
-   `.card-footer`: Card footer styling.
-   `.form-group`: Form group styling.
-   `.form-control`: Form control styling.
-   `.form-control-file`: Form control file input styling.
-   `.form-control-range`: Form control range input styling.
-   `.form-inline`: Inline form styling.
-   `.custom-file`: Custom file input styling.
-   `.custom-file-input`: Custom file input element styling.
-   `.custom-file-label`: Custom file input label styling.
-   `.custom-range`: Custom range input styling.
-   `.is-valid`: Valid form control styling.
-   `.is-invalid`: Invalid form control styling.
-   `.invalid-feedback`: Invalid feedback styling.
-   `.table`: Basic table styling.
-   `.table-responsive`: Responsive table styling.
-   `.table-dark`: Dark table styling.
-   `.table-striped`: Striped table styling.
-   `.table-bordered`: Bordered table styling.
-   `.table-borderless`: Borderless table styling.
-   `.table-small`: Small table styling.

### Hover Effects

CSS Freedom includes a variety of hover effects that can be applied to any element. The hover effects are prefixed with `hover-`.

#### 2D Transitions

-   `.hover-grow`: Grow effect.
-   `.hover-shrink`: Shrink effect.
-   `.hover-pulse`: Pulse effect.
-   `.hover-pulse-grow`: Pulse grow effect.
-   `.hover-pulse-shrink`: Pulse shrink effect.
-   `.hover-push`: Push effect.
-   `.hover-pop`: Pop effect.
-   `.hover-bounce-in`: Bounce in effect.
-   `.hover-bounce-out`: Bounce out effect.
-   `.hover-rotate`: Rotate effect.
-   `.hover-grow-rotate`: Grow rotate effect.
-   `.hover-float`: Float effect.
-   `.hover-sink`: Sink effect.
-   `.hover-bob`: Bob effect.
-   `.hover-hang`: Hang effect.
-   `.hover-skew`: Skew effect.
-   `.hover-skew-forward`: Skew forward effect.
-   `.hover-skew-backward`: Skew backward effect.
-   `.hover-wobble-vertical`: Wobble vertical effect.
-   `.hover-wobble-horizontal`: Wobble horizontal effect.
-   `.hover-wobble-to-bottom-right`: Wobble to bottom right effect.
-   `.hover-wobble-to-top-right`: Wobble to top right effect.
-   `.hover-wobble-top`: Wobble top effect.
-   `.hover-wobble-bottom`: Wobble bottom effect.
-   `.hover-wobble-skew`: Wobble skew effect.
-   `.hover-buzz`: Buzz effect.
-   `.hover-buzz-out`: Buzz out effect.
-   `.hover-forward`: Forward effect.
-   `.hover-backward`: Backward effect.

#### Background Transitions

-   `.hover-fade`: Fade effect.
-   `.hover-back-pulse`: Back pulse effect.
-   `.hover-sweep-to-right`: Sweep to right effect.
-   `.hover-sweep-to-left`: Sweep to left effect.
-   `.hover-sweep-to-bottom`: Sweep to bottom effect.
-   `.hover-sweep-to-top`: Sweep to top effect.
-   `.hover-bounce-to-right`: Bounce to right effect.
-   `.hover-bounce-to-left`: Bounce to left effect.
-   `.hover-bounce-to-bottom`: Bounce to bottom effect.
-   `.hover-bounce-to-top`: Bounce to top effect.
-   `.hover-radial-out`: Radial out effect.
-   `.hover-radial-in`: Radial in effect.
-   `.hover-rectangle-in`: Rectangle in effect.
-   `.hover-rectangle-out`: Rectangle out effect.
-   `.hover-shutter-in-horizontal`: Shutter in horizontal effect.
-   `.hover-shutter-out-horizontal`: Shutter out horizontal effect.
-   `.hover-shutter-in-vertical`: Shutter in vertical effect.
-   `.hover-shutter-out-vertical`: Shutter out vertical effect.

#### Border Transitions

-   `.hover-border-fade`: Border fade effect.
-   `.hover-hollow`: Hollow effect.
-   `.hover-trim`: Trim effect.
-   `.hover-ripple-out`: Ripple out effect.
-   `.hover-ripple-in`: Ripple in effect.
-   `.hover-outline-out`: Outline out effect.
-   `.hover-outline-in`: Outline in effect.
-   `.hover-round-corners`: Round corners effect.
-   `.hover-underline-from-left`: Underline from left effect.
-   `.hover-underline-from-center`: Underline from center effect.
-   `.hover-underline-from-right`: Underline from right effect.
-   `.hover-overline-from-left`: Overline from left effect.
-   `.hover-overline-from-center`: Overline from center effect.
-   `.hover-overline-from-right`: Overline from right effect.
-   `.hover-reveal`: Reveal effect.
-   `.hover-underline-reveal`: Underline reveal effect.
-   `.hover-overline-reveal`: Overline reveal effect.

#### Shadow/Glow Transitions

-   `.hover-glow`: Glow effect.
-   `.hover-shadow`: Shadow effect.
-   `.hover-grow-shadow`: Grow shadow effect.
-   `.hover-box-shadow-outset`: Box shadow outset effect.
-   `.hover-box-shadow-inset`: Box shadow inset effect.
-   `.hover-float-shadow`: Float shadow effect.
-   `.hover-shadow-radial`: Shadow radial effect.

### Responsive Variations

All of the above classes can be used with responsive variations by adding a breakpoint suffix to the class name. The available breakpoints are defined in the `_breakpoints.scss` file.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License.
