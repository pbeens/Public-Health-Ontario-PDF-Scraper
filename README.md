# Public-Health-Ontario-PDF-Scraper
 
This quick hack was written to download PDFs from Ontario's Public Health website. 

It has a number of limitations which should be fixed if used again:

* it only traverses two levels of links
* PDFs with "?sc_lang=fr" in the URL should be skipped as they are duplicates
* PDFs should be skipped from the URL list when looking for more URLs as this takes a long time and does not actually find more links
* You must manually download the PDF files (zip'd) to your computer

This program is designed to run in Colab only.