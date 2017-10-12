HTML_tables_basics - Basic familiarity with HTML <code>&lt;table&gt;</code>
===========================================================================
 Project Objective is to get one started with Tabular Data:
 <dl>
    <dt>Rows</dt>
      <dd>Use of <code>&lt;tr&gt;</code> Element</dd>
    <dt>Cells - Table Data</dt>
      <dd>Use of <code>&lt;td&gt;</code> Element</dd>
    <dt>Headings</dt>
      <dd>Table Headers - Special cells that go at the start of a row or column
      &amp; define the type of data that row or column contains.</dd>
      <dd>Use of <code>&lt;th&gt;</code> Element</dd>
      <dd>Use of <code>scope</code> Attribute</dd>
    <dt>Making cells span multiple columns &amp; rows </dt>
    <dt>Grouping cells in a column for styling purposes </dt>
</dl>

timetable - the timetable of a languages teacher 
=================================================
 Project Objective is to highlight different columns.
 <dl>
    <dt><code>&lt;colgroup&gt;</code> &amp; <code>&lt;col&gt;</code> 
      Elements
    </dt>
      <dd>Providing common styling to colums </dd>
</dl>

spending_records - A simple table showing personal expenditures
================================================================
As tables get a bit more complex in structure, it is useful to give them more 
structural definitions which allow you to mark up a header, footer, and body 
section for the table.
<dl>
  <dt><code>&lt;thead&gt;</code> Element</dt>
    <dd>needs to wrap the part of the table that is the header — commonly the 
      first row containing the column headings, but this is not necessarily 
      always the case. 
    </dd>
    <dd>If using <code>&lt;col&gt;/&lt;colgroup&gt; element, the table header 
      should come just below those.
    </dd>
  <dt><code>&lt;tfoot&gt;</code></dt>
    <dd>needs to wrap the part of the table that is the footer — this might be 
      a final row with items in the previous rows summed, for example. You can 
      include the table footer right at the bottom of the table as you'd expect, 
      or just below the table header (the browser will still render it at the 
      bottom of the table).
    </dd>
  <dt><code>&lt;tbody&gt;</code></dt>
    <dd>needs to wrap the other parts of the table content that aren't in the 
      table header or footer. It will appear below the table header or sometimes 
      footer, depending on how you decided to structure it.
    </dd>
</dl>



Attribution
===========
Mozilla Developer Network 
[MDN Learning Area](https://developer.mozilla.org/en-US/docs/Web/HTML.html)

License - CCO 1.0 Universal
===========================
See the [LICENSE file](LICENSE) for the full license text.