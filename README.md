# Fetch GTIN From A GS1 Digital Link URI
Demo on how to extract a GTIN from a GS1 Digital Link URI as e.g. encoded in a 2D data carrier such as a QR code

## Background
As of 2027, retail scanning systems must be ready to read the Global Trade Item Number (GTIN) not only from a linear EAN or UPC barcode, but also from a 2D code. For further information, see e.g. https://www.gs1.org/industries/retail/2D-barcodes. 

## Purpose of this repository
Though not the only option, the most promising data carrier from today's perspective (as e.g. it also allows for direct consumer interaction) might be the QR code encoding a GS1 Digital Link URI. 

The GS1 Digital Link URI Syntax Standard (see https://ref.gs1.org/standards/digital-link/uri-syntax/) provides a Regular Expression (RegEx) to recognise GS1 data structures. See section 6.1 Recognising a GS1 Digital Link URI. 

Based on this RegEx, this repository contains a (hopefully) comprehensible demonstration on how GS1 data can be extracted from such a URI - just access provided [Jupyter Notebook](https://github.com/RalphTro/fetchGTINFromGS1DigitalLinkURI/blob/main/gtinRecognitionInGs1DigitalLinkURIs2DCommunity.ipynb).   

## On Jupyter Notebooks 
In simple words, a Jupyter Notebook is a convenient way to switch between explanatory text and executable code. It is based on open source software and standards. 
