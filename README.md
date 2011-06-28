# blacktie

blacktie is a simple HTML/CSS microframework to help layout and style forms. By using a simple and standardized form markup, a few CSS classes can easily change the entire layout of the form. Layouts include: top labels, left labels (with left of right alignment).

By default, blacktie provides UX best practices: labels on top of inputs.

## Usage

1. Markup your form using the sample HTML as a guide
2. Add classes `left_label` and `left_align` to the `form` tag to see the possible layouts

## Helper classes

blacktie also includes CSS helper classes for other common form layouts:

* `separated`: for fields with multiple inputs (such as breaking up a phone number)
* `inline`: for checkbox/radio inputs that should be horizontally displayed

## Notes

blacktie is built on top of HTML5 Boilerplate and its default CSS. This isn't a requirement but the CSS would require some updates without it or with a different CSS reset.
