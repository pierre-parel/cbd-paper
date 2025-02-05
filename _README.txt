DLSUdtp is a LaTeX document format for authors of De La Salle University (DLSU) dissertations, theses, proposals, or projects. 

As of the latest version, a Word template based on the LaTeX in terms of best effort is included (note that "No Markup" under the Review-Tracking tab of Word must be turned off prior printing or saving in PDF format).

The items below refer to the LaTeX template.

Line numbers are removable.

For a list of changes, please read the file _CHANGELOG.txt.  The shortened web link to the template is https://goo.gl/9YTTs2 

Best wishes for your dissertation, thesis, proposal, or project documentation endeavors.

LM
DLSU ECE Faculty

************** How to migrate to the latest version from the old ***************

(1)  Copy all your .tex and .bib files to the new folder of the template.
(2)  Open the old document.tex and the new document.tex in separate LaTeX IDE windows.
(3)  Copy each user and thesis details from the old document.tex to the new document.tex
(4)  Indicate the filenames of the approval sheet and student research ethics clearance form. The default filename is STUDENT_RESEARCH_ETHICS_CLEARANCE.pdf
(5)  Comment \ApprovalSheetSignedtrue if not yet available.
(6)  Make sure of the filename of the student research ethics clearance form.

***************************** Subdirectories ******************************

code      - Location of codes written in C and/or other programming languages.

figure    - Location of figures in the main documents.

format    - Location of the preamble and pertinent document formatting styles.

reference - Location of PDF files that can be included in the document.


********************************** Files **********************************

_README.txt                    - This file.

_CHANGELOG.txt                 - The revision history.

references.bib                 - The file where the bibliography entries (in BibTeX format) are to be placed. 

document.tex                   - The main file, where many author details and settings are placed

document_with_extra_guides_in_the_appendices.pdf - A kind of a user guide, especially the appendices. This is a minimum working example of document.tex with some useful appendices.
  
document.pdf                   - pdfLaTeX-built final output PDF file.

abbreviation.tex               - The file where abbreviations and acronyms are to be placed.

abstract.tex                   - The file where the abstract is to be placed. 

acknowledgment.tex             - The file where the acknowledgment is to be placed.

answers_to_questions.tex       - A helpful series of questions for dissertations, theses, and their proposal versions.

conclusions.tex                - The file where the conclusions are to be placed.

design_considerations.tex      - The file where the design considerations are to be placed.

glossary.tex                   - The file where the glossary entries are to be placed.

introduction.tex               - The file where the introduction is to be placed.

literature_review.tex          - The file where the prior studies in the introduction chapter are expounded.

methodology.tex                - The file where the methodology, including the implementation and evaluation, is to be placed.

notation.tex                   - The file where the mathematical notations are to be placed.

other_appendices.tex           - The file where appendices other than the usage guide are included in document_guide.pdf.

publications.tex               - The file where the related publications of the author(s) are to be placed.

results_and_discussions.tex    - The file where the results, analyses, and their discussions are to be placed.

revisions_to_the_final.tex     - The file where the revisions to the final defense document are placed based on the comments of the panel of examiners.

revisions_to_the_proposal.tex  - The file where the revisions to the proposal were done based on the comments of the panel of examiners.

theoretical_considerations.tex - The file where the conceptual and theoretical considerations are to be placed.

usage_examples.tex             - The file where usage examples were placed.

vita.tex                       - The file where the author's vita is to be placed.

article_forum_paper.tex/.doc   - The file for the arcticle paper (.tex is the LaTeX format; .doc is the Word format). Note that article_forum_paper.tex must be parsed/built separately.

erase_aux_files.cmd			   - Exeutable file for erasing auxillary files (works in Windows machines only); helpful if the auxillary files increase in size.

***************************************************************************
Legal Notice:
The codes are offered as-is without any warranty either expressed or implied; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE! 

User assumes all risk. In no event shall DLSU or any contributor to this code be liable for any damages or losses, including, but not limited to, incidental, consequential, or any other damages, resulting from the use or misuse of any information contained here.

All comments are the opinions of their respective authors and are not necessarily endorsed by DLSU.

This work is distributed under the LaTeX Project Public License (LPPL) ( http://www.latex-project.org/lppl.txt ) version 1.3, and may be used, distributed and modified. 

Retain all contribution notices and credits.
** Modified files should be clearly indicated as such, including  **
** renaming them and changing author support contact information. **
**************************************************************************