# PDF Template for Invoiceplane German DIN 5008 Form B

This is an PDF-Template for [Invoiceplane](https://www.invoiceplane.com/) a self-hosted open source application for managing your quotes, invoices, clients and payments.

This Template is adopted from the original one with some minor changes:
- Added *Falt-/Lochmarken* as described in [DIN 5008 / Form B](https://de.wikipedia.org/wiki/Datei:DIN_5008_Form_B.svg)
- Added sender on top of cliens address for Sichtfensterumschlag
- Altered spacing and fields due to DIN 5008
- Moved zip-code in front of city

## Installation

Simply add the files into `application/views/invoice_templates/pdf` and select them in Invoiceplane's *System Settings -> Invoices* as PDF templates.

## Example

![Screenshot](screenshot.png)
