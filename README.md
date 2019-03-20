# PDF text form filler
iText5 console app to fill pdf text form from json with utf-8 text (eg Cyrilic)

Written to solve problem with invisible cyrilic text.

based upon https://itextpdf.com/en/resources/examples/itext-5/filling-out-forms

### Usage:

java -jar pdf_from_filler.jar form.pdf json.json FreeSans.ttf filled.pdf [font size]

or change source as you need

json example in json.json

---
ps

Was not tested anywhere except my project, also works with checkboxes (value must be from your field options, google it)
