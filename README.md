# Ti*k*Z-Styling-Maple

Styling Maple graphics with Ti*k*Z and LaTeX.

- graph_Maple_Distribution.mw &nbsp;&nbsp; Maple graph generation worksheet.<br />
- graph_Maple_example_bare_input.pdf &nbsp;&nbsp; An example bare Maple graph to style.<br />
- graph_Maple_example_annotator.ltx &nbsp;&nbsp; LaTeX document that styles graphs via Ti*k*Z.<br />

The Maple worksheet graphs the standard normal cumulative distribution function. In addition to default Maple output, a bare version with the graph body but no text or axes is output. The bare version can have text and axes reconstructed with Ti*k*Z styling if passed to the LaTeX document.

Software Requirements

- Maple (for graph generation).<br />
- Perl (optional, called from Maple for PDF cropping).<br />
- TeX distribution (for Ti*k*Z, LaTeX and, optionally, pdfcrop).<br />
