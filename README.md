# DocToNotes

Convert documents to images of handwritten notes

I'll update the list of dependencies and stuff later.

Just change the example.docx to your file and run pyb.ipynb and boom, the output folder will be full of sweet images.

Add your poppler bin path to this line:
pages = convert_from_path('scriptalized.pdf', 300, poppler_path = r"G:\poppler\bin... ")

Pray to God you have a version of Word that supports SaveAs PDF otherwise you have to manually export docx to pdf.

You also need this font istalled https://www.scriptalizer.co.uk/users/DemoFonts/PremiumUltra17.ttf
