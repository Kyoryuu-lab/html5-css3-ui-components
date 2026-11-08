<h1>html5-css3-ui-components</h1>
<p>Modular Frontend UI patterns, semantic HTML5 data tables, multi-level dropdown navigation layouts, and CSS3 pseudo-class state management</p>

<h2>Project description</h2>
<p>This repository provides a foundational showcase of core CSS3 layout techniques, responsive navigation patterns, and accessible HTML5 data structuring without external libraries or frameworks:</p>
<ol>
  <li>
    <dl>
      <dt><b>Multi-Level Navigation Patterns:</b></dt>
      <dd><b>Horizontal Navbar (<code>nav &gt; ul &gt; li</code>):</b> Desktop navigation with downward cascade submenus, relative-to-absolute coordinate anchors, and <code>:hover</code> visibility toggles.</dd>
      <dd><b>Vertical Flyout Menu:</b> Side-navigation hierarchy utilizing nested unordered lists with calibrated horizontal offset shifts.</dd>
    </dl>
  </li>
  <li>
    <dl>
      <dt><b>Semantic Data Tables &amp; Matrix Spanning:</b></dt>
      <dd><b>Device Specification Matrix:</b> Structured smartphone benchmark table applying row/column scopes (<code>scope="col"</code>, <code>scope="row"</code>), alternating zebra row styling via <code>tr:nth-child(odd)</code>, and collapsed borders.</dd>
      <dd><b>Complex Grid Table:</b> Geometric table layout combining multidirectional cell spans (<code>colspan</code>, <code>rowspan</code>) and discrete CSS border-spacing controls.</dd>
    </dl>
  </li>
  <li>
    <dl>
      <dt><b>Anchor Pseudo-Class State Machine:</b></dt>
      <dd>Demonstrates exact adherence to user-action state styling across all link life-cycle phases: <code>:link</code>, <code>:visited</code>, <code>:focus</code>, <code>:hover</code>, and <code>:active</code>.</dd>
    </dl>
  </li>
  <li>
    <dl>
      <dt><b>Centralized Showcase Portal:</b></dt>
      <dd>Features a responsive card-grid dashboard (<code>index.html</code>) enabling seamless live previewing via GitHub Pages.</dd>
    </dl>
  </li>
</ol>

<h2>Project files</h2>
<table>
  <tr>
    <th colspan="2">html5-css3-ui-components</th>
  </tr>
  <tr>
    <td>index.html</td>
    <td>Responsive portal dashboard linking to all individual component demos</td>
  </tr>
  <tr>
    <td>pages/horizontal-navbar.html</td>
    <td>Horizontal navigation bar demo with collapsible dropdown menus</td>
  </tr>
  <tr>
    <td>pages/vertical-menu.html</td>
    <td>Vertical flyout multi-tier navigation menu demo</td>
  </tr>
  <tr>
    <td>pages/device-comparison.html</td>
    <td>Accessible technical specification table with zebra striping and scopes</td>
  </tr>
  <tr>
    <td>pages/complex-grid-table.html</td>
    <td>High-complexity table matrix with multi-cell row and column spans</td>
  </tr>
  <tr>
    <td>pages/interactive-links.html</td>
    <td>Interactive demonstration of anchor pseudo-class state transitions</td>
  </tr>
  <tr>
    <td>css/</td>
    <td>Modular stylesheets for portal cards, layouts, menus, and typography</td>
  </tr>
  <tr>
    <td>README.md</td>
    <td>Project documentation and technical specification</td>
  </tr>
  <tr>
    <td>.gitignore</td>
    <td>Exclusion rules for editor states, OS metadata, and temporary files</td>
  </tr>
</table>

<h2>Component Overview &amp; Technical Specifications</h2>
<table>
  <tr>
    <th>Component</th>
    <th>Key HTML Elements</th>
    <th>Primary CSS Techniques</th>
  </tr>
  <tr>
    <td><b>Horizontal Navbar</b></td>
    <td><code>&lt;nav&gt;</code>, <code>&lt;ul&gt;</code>, <code>&lt;li&gt;</code>, <code>&lt;a&gt;</code></td>
    <td><code>display: inline-block</code>, <code>position: absolute</code>, <code>top: 100%</code>, <code>:hover &gt; ul</code></td>
  </tr>
  <tr>
    <td><b>Vertical Menu</b></td>
    <td><code>&lt;ul&gt;</code>, <code>&lt;li&gt;</code>, <code>&lt;a&gt;</code></td>
    <td>Nested flyout layout, <code>left: 149px</code>, <code>display: none</code> / <code>block</code></td>
  </tr>
  <tr>
    <td><b>Device Comparison Table</b></td>
    <td><code>&lt;table&gt;</code>, <code>&lt;caption&gt;</code>, <code>&lt;thead&gt;</code>, <code>&lt;th scope&gt;</code></td>
    <td><code>border-collapse: collapse</code>, <code>:nth-child(odd)</code> zebra shading</td>
  </tr>
  <tr>
    <td><b>Complex Grid Table</b></td>
    <td><code>&lt;table&gt;</code>, <code>&lt;td rowspan&gt;</code>, <code>&lt;th colspan&gt;</code></td>
    <td><code>border-spacing: 0</code>, multi-layered color borders</td>
  </tr>
  <tr>
    <td><b>Interactive Links</b></td>
    <td><code>&lt;a href&gt;</code></td>
    <td><code>:link</code>, <code>:visited</code>, <code>:focus</code>, <code>:hover</code>, <code>:active</code> styling</td>
  </tr>
</table>

<h2>Installation and launch</h2>
<ol>
  <b>
    <li>
      <dl>
        <dt>Clone repository</dt>
        <dd>
          <code>git clone https://github.com/Kyoryuu-lab/html5-css3-ui-components.git</code>
        </dd>
        <dd>
          <code>cd html5-css3-ui-components</code>
        </dd>
      </dl>
    </li>
  </b>
  <b>
    <li>
      <dl>
        <dt>Run locally</dt>
        <dd>Open <code>index.html</code> directly in any modern web browser:</dd>
        <dd>
          <code>open index.html</code> &nbsp;(macOS) &nbsp;oder&nbsp; <code>xdg-open index.html</code> &nbsp;(Linux)
        </dd>
        <dd>Or launch via lightweight Python HTTP server: <code>python3 -m http.server 8080</code></dd>
      </dl>
    </li>
  </b>
  <b>
    <li>
      <dl>
        <dt>Deploy via GitHub Pages</dt>
        <dd>In your GitHub repository settings, navigate to <b>Pages</b> &rarr; Source: <b>Deploy from a branch</b> (Branch: <code>main</code>, Folder: <code>/ (root)</code>).</dd>
      </dl>
    </li>
  </b>
</ol>
