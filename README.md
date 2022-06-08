# Sample PDFs

- [double_entry.pdf](.pdfs/double_entry.pdf): I created this PDF to answer [this question](https://graphicdesign.stackexchange.com/q/157066/174346) about being able to "double enter" info in a form field.

- [ERAP_2_Template.pdf](.pdfs/ERAP_2_Template.pdf): My standard PDF.

- [ige.pdf](.pdfs/ige.pdf): PDF is missing the charmap table for some fonts, so text extraction for a class of text in the PDF fails; see [PyMuPDF Issue 1717](https://github.com/pymupdf/PyMuPDF/issues/1717#issuecomment-1137621530).

- [page32.pdf](.pdfs/page32.pdf): Person was trying to use tabula to get the table out, and wanted shaded cells to be preserved (which tabula was dropping because they do not contain text); UniPDF behaves the same way.  I kept thinking I'd try to program something to "fill in" shaded cells with an "x" so table extractors would have something to return.