[[2021-09-29_Wed]] created + done

### scoping
- The workbench knows that transcript and summary are related, but currently there are outgoing links only in the direction from summary to transcript.
- It would be nice if we had a small pointer at the end of the paragraph, pointing back to the header in the summary.
- Example: [[0204 Love and Emptiness#^3-1]], where the fullstop at the end of the paragraph links to the header in the summary.
- possibilities
	- do not link in main, only in publish
	- link in main
	- maybe need to transform the links into http links (but that's maybe excessive, given that the summary only appears once in the graph)
- needs a **TranscriptSummaryPage**._collectParagraphDescriptions()_, which returns a list of tuples which can be used as lookup
- which punctuation to use:
	- ꘎ admonition
	- ᙮ audio
	- ⦿ both audio and admonitions
	- else regular fullstop
- alternatives: ∘∙⦿꘎᙮