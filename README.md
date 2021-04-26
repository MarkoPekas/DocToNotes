# DocToNotes

Convert documents to images of handwritten notes

I'll update the list of dependencies and stuff later.

Just change the example.docx to your file and run pyb.ipynb and boom, the output folder will be full of sweet images.

Just add your poppler path to this line:
pages = convert_from_path('scriptalized.pdf', 300, poppler_path = r"G:\poppler... ")
