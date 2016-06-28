Dear Dr. Markel,

Thank you for reviewing our manuscript "Ten Simple Rules for Digital
Data Storage" and considering our resubmission. We appreciate the
thoughtful feedback reviewers have provided and incorporated their
comments into our revised manuscript. Below is a detailed accounting
of our changes, with reviewer submissions highlighted in bold.


**_Reviewer #1:_** _The manuscript enumerates a set of "rules" that
promote up-front thought during experimental design regarding the long
term storage of data generated. Each of the ten rules has a specific
focus on one aspect that researchers should consider. The authors
clearly communicate the rules with relevant supporting observations. A
few minor issues:_

**Rules 4 and 5 seem like variations on the same rule -- keeping the
data accessible. It would be helpful to differentiate these rules a
bit more.**


 We have differentiated the rules by focusing on data file formats in
 Rule 4 and data structure in Rule 5. We believe data can be tidy
 (rule 5) but in a closed format (rule 4) or vice versa. While we
 agree with the reviewers comment that these rules focus on a similar
 theme, it is easy to imagine a scenario where a scientist might put
 very tidy data in a closed format such as JMP or Excel files. We have
 renamed Rule 5 to "Data should be structured for analysis" and also
 substantially restructured the paragraphs of rule 5 to enhance this
 distinction.

**Line 21: is a good advice => is good advice**

We have fixed this typo.

**Line 136: States that an example of machine readable open format
that would not be easy to process include Microsoft word, but in the
preceding rule (Rule 4) it states that Microsoft excel is not an open
format. Perhaps just keep PDF as the example.**

We removed this line from rule 5.

**Lines 140-144: discussing source code doesn't really fit in this
section. Perhaps move these lines to the section about metadata (Rule
7).**

We removed the reference to metadata as the reviewer notes it is
probably not truly metadata but is more like provenance of an
analysis. However we feel it is important to highlight that structured
data facilitates the transparency of an analysis and have kept those
lines in.

**Line 147: variable is a column => variable as a column**

We have fixed this typo.

**Line 147-148: unit is a table => unit as a table**

We have fixed this typo.

**Line 161: standards-compliant data, it _is_ easier to build**

We have fixed this typo.

**Line 200: meta-data in in well => meta-data in well**

We have fixed this typo

**Line 201: Extraneous close paren ) after JSON**

We have deleted this dangling parentheses.

**Line 244: Seems like an appeal to authority. Replace explicit
reference to Kristen Briney**

Line 252-253: We have removed this appeal and replaced it with a
citation to the blog post.

**Line 245: Include a caution with respect to Rule 8 (ensure that the
offsite "cloud" storage is as secure as the primary storage)**

Line 253-254: We added an additional clause that advises users to be
sure that offsite storage is secure

**Line 311: include oxford comma "animals, fungi, and microbes"**

An oxford comma has been added.

**Line 337-338: ways to programatically query databases through**

This sentence has been restructured


**_Reviewer #2:_** _Dr. Hart and co-authors presented a comprehensive
review on the essential aspects of digital data storage. While
situation in reality can become very complicated, these ten simple
rules can still provide good and useful guidance for researchers to
develop data storage and management systems. Actually, we have pretty
much followed these rules in our own practices. The manuscript was
concise and well written.

Minor suggestions:_

**Page 2, Line 50: "can help" -> "can help to"**

We have have added the word to

**Page 3, Line 89: "can be difficult to impossible for others" -> "can
be difficult for others"**

We have deleted the word "impossible"

**_Reviewer #3:_** _This manuscript discusses ten simple rules for
digital data storage. The ten rules provide simple guidelines for how
researchers across a variety of disciplines can store their data for
long-term access and ensure that the data are usable by others in the
future. Compared with other "ten Simple Rules" papers on scientific
data management and curation, this manuscript further addresses
another facet of data, longer term storage best practices. The
manuscript represents the collaboration among co-authors from a wide
variety of academic backgrounds, who are all part of the Software
Carpentry project._

**The manuscript could benefit from addressing specific needs for the
storage of biological and biomedical data to be more in scope with the
main themes of the journal.**

We have added several examples in our rules that are specific to
biomedical data to address this concern. In particular:

Line 24-26: We suggest GenBank as an example place to archive sequence
data 

Line 64-66: We suggest using community tools for formatting
sequence data and ecological metadata 

Line 177-178: We give an example of version numbers
that are specific to NCBI repositories

We believe these help bring the manuscript more in line with the main
themes of the journal as the author suggests.
