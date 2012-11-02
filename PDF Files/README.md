#PDF Files
All pages must be available in XHTML 1.0 Strict. PDFs should be provided only as an alternative.

Please see the Internet Presence Policy site for guidance on how to present PDFs:
(icweb.ic.gc.ca/eic/site/ipp-ppi.nsf/eng/h_00345.html)

##Linking to a PDF
If you are linking to a document that is available only as a PDF, if possible, link to the page that references the PDF rather than link directly to the PDF.

##Referencing Alternative Formats on Web Pages
When an alternative format (e.g., PDF, RTF, Word, WordPerfect, etc.) is provided, the link to the alternative version should appear on the main XHTML page that contains the same content as the PDF.

##KB/Ko
Include "(PDF, the file size KB and the number of pages)" in parentheses after the link.

In English, the file size is indicated by KB (note both capital letters). In French, the file size is indicated by Ko (capital "K" and lower-case "o"). Include a space between the number and the letters (e.g., 100 KB).

All PDF files should be coded as follows.

###English
&lt;p&gt;&lt;a href="../vwapj/PDFFileName.pdf" title="File Name"&gt;&lt;em&gt;File Name&lt;/em&gt;&lt;/a&gt; (&lt;acronym title="Portable Document Format"&gt;PDF&lt;/acronym&gt;, XX&nbsp;&lt;acronym title="kilobyte"&gt;KB&lt;/acronym&gt;, XX&nbsp;pages)&lt;/p&gt;

&lt;epic action="include" file="ESZO-7B4TCN" title="PDF — Information on how to download a PDF reader/PDF — Information sur la fa&ccedil;on de t&eacute;l&eacute;charger le lecteur PDF" format="-1"&gt;

###French
&lt;p&gt;&lt;a href="../vwapj/PDFFileName.pdf" title="File Name"&gt;&lt;em&gt;File Name&lt;/em&gt;&lt;/a&gt; (&lt;acronym title="format de document portable"&gt;PDF&lt;/acronym&gt;, XX&nbsp;&lt;span class="abbr" title="kilo-octet"&gt;&lt;abbr title="kilo-octet"&gt;Ko&lt;/abbr&gt;&lt;/span&gt;, XX&nbsp;pages)&lt;/p&gt;

&lt;epic action="include" file="ESZO-7B4TCN" title="PDF — Information on how to download a PDF reader/PDF —- Information sur la fa&ccedil;on de t&eacute;l&eacute;charger le lecteur PDF" format="-1"&gt;

Note: Although the number of pages is not required by Treasury Board, it is good practice to add this.

##PDF Code From the Shared Assets Database
The PDF codes below are available in the Shared Assets Database. See the section in this guide titled "EPIC Shared Assets: Prod Database" for instructions on how to add this database to your system and how to add the required PDF codes to your page.
Text That Appears Before the PDF Link

If the document is provided only as a PDF, please include the following code just prior to the PDF link.

###PDF — Accessibility Notice — Link to Contact Us Page
&lt;epic action="include" file="ESZO-7CFSKT" title="PDF — Accessibility Notice — Link to Contact Us Page/PDF — Avis d"accessibilité — Liens à Contactez-nous" format="-1"&gt;

When viewed on a web browser, the code above will show as:

&lt;hr /&gt;
&lt;p&gt;If the following document is not accessible to you, please &lt;a href="http://www.ic.gc.ca/eic/site/ic1.nsf/eng/h_00014.html"&gt;contact us&lt;/a&gt; to obtain other appropriate formats.&lt;/p&gt;
&lt;hr /&gt;

##Text That Appears After the PDF Link
All pages with links to PDF files must include information on how to download a PDF Reader at the bottom of the page.

###PDF— Information on how to download a PDF reader
&lt;epic action="include" file="ESZO-7B4TCN" title="PDF — Information on how to download a PDF reader/PDF — Information sur la façon de télécharger le lecteur PDF" format="-1"&gt;

When viewed on a web browser, the code above will show as:

&lt;hr /&gt;
&lt;p&gt;To access the Portable Document Format (&lt;acronym title="Portable Document Format"&gt;PDF&lt;/acronym&gt;) version you must have a &lt;acronym title="Portable Document Format"&gt;PDF&lt;/acronym&gt; reader installed. If you do not already have such a reader, there are numerous &lt;acronym title="Portable Document Format"&gt;PDF&lt;/acronym&gt; readers available for free download or for purchase on the Internet:&lt;/p&gt;
&lt;ul&gt;&lt;li&gt;&lt;a href="http://get.adobe.com/reader/otherversions/"&gt;Adobe Reader&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href="http://www.foxitsoftware.com/pdf/reader/"&gt;Foxit Reader&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href="http://www.foolabs.com/xpdf/download.html"&gt;Xpdf&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href="http://www.visagesoft.com/products/pdfreader/"&gt;eXPert &lt;acronym title="Portable Document Format"&gt;PDF&lt;/acronym&gt; Reader&lt;/a&gt;&lt;/li&gt;&lt;/ul&gt;

**References**
Alternative format — Sample treatment of non-XHTML documents:
(www.tbs-sct.gc.ca/clf2-nsi2/tb-bo/dimf-dodf-eng.asp)

Accessible alternate format of documents on websites:
(www.tbs-sct.gc.ca/clf2-nsi2/clfs-nnsi/clfsp-nnsii-eng.asp#cn_3_aaf)

## File Metadata
### Document File Metadata

All files must contain, at the minimum, the following metadata:
* Title;
* Author; and
* Site Product Code.

For instructions on how to enter metadata in various file formats, refer to Appendix B of the Industry Canada Metadata Guidelines.

### Document Title Metadata
The title metadata shall be as such:

[document-type-code]-[document-number]—[document-full-title]

where

[document-type-code]
    is the code from Appendix A which identifies the document's type and is always written in upper-case
* Bulletins
 	* Electricity =	E
  * Gas =	G
	* Mass =	M
	* Volume =	V
	* General =	GEN
	* Statistical Methods and Sampling Plans =	S
* Specifications
 	* Electricity =	S-E
	* Gas =	S-G
	* Mass =	SGM
	* Volume = SVM
	* Statistical Methods and Sampling Plans =	S-S
* Provisional Specifications
 	* Electricity =	PS-E
	* Gas =	PS-G
	* Statistical Methods and Sampling Plans =	PS-S
* Terms and Conditions
 	* Mass =	TC
	* Volume =	TC
* Procedures
 	* All 	 
* Table of Volume Correction Factors
	* Volume =	VCF
[document-number]
    is the zero-padded two-digit number of the document
[document-full-title]
    is the document's full title in the language of the document

Exceptions:

The document number, and preceding hyphen ("-"), are only used for numbered documents.

Some unnumbered documents do not have a document type code. In such cases the document type code and em-dash ("—") that follows it are omitted.

### Document Author Metadata
The author of a document is always "Measurement Canada" for English language documents and "Mesures Canada" for French language documents.

### Document Publication Environment Site Product Code Metadata

The Site Product Code for the site to which the document will be published:
* Internet 	701
* intranet 	471