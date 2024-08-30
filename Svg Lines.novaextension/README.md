

<style>
	body {  }
	h1 { margin-bottom: 0; }
	h2 { margin: 0; padding: 0 0 16px 0; }
	h2 { border-bottom : 1px solid #FFF0; }
	hr { margin: 96px 0 48px 0; border-radius: 3px}
	p { letter-spacing: 0.05em; font-size: 16px; }
	
	
	
	/* body {  font-family: sans-serif; } */
	/* h1 { margin-bottom: 0; } */
	/* h2 { margin: 0; padding: 0 0 16px 0; } */
	/* hr { margin: 96px 0 48px 0; border-radius: 3px; opacity: 0.5} */
	/* p { letter-spacing: 0.05em; font-size: 16px; } */
	/* a { text-underline-offset: 5px;} */
	
	
	
	
	@media (prefers-color-scheme: light) {
	  body { background-color: whitesmoke; color: black; }
	  p { color: #666; }
	
	
	
	  .headergrid > div p { color: #888; }
	  .headergrid > div p strong { color: #555; }
	  .headergrid > div h6 { color: #888; }
	
	  details summary { border-bottom: 1px solid #bbb; }
	  details summary:hover { background-color: #ffffff; }
	  details summary > div:last-child { background: linear-gradient(90deg, #ddd, #ddd); }
	  
	  table thead { border-top: 1px solid #bbb; border-bottom: 1px solid #bbb; }
	  table thead tr { background-color: whitesmoke; border-top: 1px solid #bbb;  }
	  table thead tr:nth-child(even) { background-color: whitesmoke;  }
	  table thead tr th { border: none; background-color: none; color: #999; border-right: 1px solid #bbb; }
	  
	  table tbody tr { background-color: #D8D8D8; border: none;}
	  table tbody tr:nth-child(even) { background-color: #E4E4E4; }
	  table tbody tr td { border: none; border-bottom: 1px solid #bbb; }
	
	  span.shortcut { background-color: #f3f3f3; color:#333; }
	  span.elmt { color: white; background-color: crimson; }
	  span.attr { color: white; background-color: dodgerblue; }
	  span.xmpl { color: white; background-color: limegreen; }
	
	
	
	  .contentgrid > div { background: linear-gradient(45deg, #ffffffff, #ffffffff); box-shadow: 0 0 24px #0001;  }
	  .contentgrid > div p {   }
	  .contentgrid > div p span { color: #444; border-bottom: 4px solid #444; }
	}
	
	@media (prefers-color-scheme: dark) {
	  body { background-color: #1A1A1A; color: #CCC; }
	  /* linear-gradient(135deg, #282828 0%, #1A1A1A 10% ) */
	
	  p { color: #777; }
	
	
	  .headergrid > div p { color: #555; }
	  .headergrid > div h6 { color: #666; }
	
	  details summary { border-bottom: 1px solid #333; }
	  details summary:hover { background-color: #111111; }
	  details summary > div:last-child { background: linear-gradient(90deg, #2a2a2a, #2a2a2a); }
	  
	  table thead { border-top: 1px solid #333; border-bottom: 1px solid #333; }
	  table thead tr { background-color: #1A1A1A;  }
	  table thead tr:nth-child(even) { background-color: #1A1A1A; border-top: 1px solid #333;  }
	  table thead tr th { border: none; background-color: none; color: #666; border-right: 1px solid #333; }
	  
	  table tbody tr { background-color: #232323; border: none;}
	  table tbody tr:nth-child(even) { background-color: #202020; }
	  table tbody tr td { border: none; border-bottom: 1px solid #2A2A2A; }
	
	  span.shortcut { background-color: #111; color:#7a9; }
	  span.elmt { color: crimson;    background-color: #211; }
	  span.attr { color: dodgerblue; background-color: #112; }
	  span.xmpl { color: limegreen;  background-color: #121; }
	
	
	
	  .contentgrid > div { background: linear-gradient(45deg, #252525, #353535) }
	  .contentgrid > div p {   }
	  .contentgrid > div p span { color: #bbb; border-bottom: 4px solid #bbb; }
	
	
	
	}
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	details { margin-bottom: 0px; }
	details summary {
	  position: relative;
	  display: flex; flex-direction: row; justify-content: flex-start; align-items: center;
	  width: 100%; padding: 12px 0;
	  cursor: pointer;
	  outline: 0px solid limegreen;
	}
	details summary:hover { }
	
	details summary > div { }
	details summary > div:first-child {width: 75%; }
	details summary > div:last-child {width: 25%; border-radius: 8px; padding: 4px; }
	details summary > div svg { display: block; width: 100%; }
	
	
	table { font-size: 12px; border-collapse: collapse; width: 100%; margin: 0;}
	table tr { }
	table tr:nth-child(even) { }
	
	table thead { }
	table thead tr:nth-child(even) { }
	
	table tr th, table tr td { box-sizing: border-box;}
	table tr th { padding: 8px 4px 2px 4px;  text-align: left; font-weight: 400; text-transform: uppercase; font-size: 10px; letter-spacing: 0.1em; }
	table tr td { padding: 8px 0;  }
	
	table.detable tr th:nth-child(1) { width: 15%; padding: 8px 0 2px 0; }
	table.detable tr th:nth-child(2) { width: 40px; }
	table.detable tr th:nth-child(3) { width: 20% }
	table.detable tr th:nth-child(4) { width: 120px }
	table.detable tr th:nth-child(5) { width: auto; padding: 8px 0 2px 12px; }
	table.detable tr th:last-child { border:none; }
	table.detable tr td:nth-child(1) { width: 15%; color: #777; font-family: monospace; font-size: 9px; padding: 0 0 0 16px;  }
	table.detable tr td:nth-child(2) { width: 40px;  font-family: monospace; font-size: 9px; padding: 0 14px 0 0; text-align: right; }
	table.detable tr td:nth-child(3) { width: 20%; opacity: 0.7; letter-spacing: 0.1em;   }
	table.detable tr td:nth-child(4) { width: 120px; font-family: monospace; font-size: 11px; padding: 0;}
	table.detable tr td:nth-child(5) { width: auto; opacity: 0.7; letter-spacing: 0.05em; padding: 0 0 0 12px; }
	
	span.shortcut { display: block; padding: 5px 2px 4px 4px; position: relative; }
	span.shortcut:before { position: absolute; content: '+'; right: 24px;  }
	span.shortcut:after { position: absolute; content: '⇥'; font-size: 19px; margin: -6px 8px 0 0; right: 0; }
	
	span.elmt,
	span.attr,
	span.xmpl { display: block; text-align: center; padding: 2px 0 2px 0; border-radius: 3px; }
	span.elmt { letter-spacing: 0.1em;  }
	span.attr { letter-spacing: -0.1em;  }
	span.xmpl { letter-spacing: -0.1em; }
	
	
	
	
	
	
	
	.headergrid { display: grid; grid-template-columns: repeat(1, 1fr); grid-template-rows: repeat(4, 1fr); }
	.headergrid > div { aspect-ratio: 1/1; position: relative; display: flex; flex-direction: column; justify-content: center; align-items: center; }
	.headergrid > div:before,
	.headergrid > div:after { position: absolute; content: ''; }
	.headergrid > div:before { bottom:-1px; right:-1px; width: 8px; height: 8px; border-bottom: 1px solid #80808066; border-right: 1px solid #80808066; }
	.headergrid > div:after { bottom:-9px; right:-9px; width: 8px; height: 8px;  border-top: 1px solid #80808066; border-left: 1px solid #80808066;}
	
	.headergrid > div:first-child { justify-content: flex-start; align-items: flex-start; }
	.headergrid > div svg { position: absolute; z-index: -1; }
	.headergrid > div p { padding: 16px 32px 16px 0; margin: 0; font-weight: 400; letter-spacing: 0.025em; line-height: 1.5em;  }
	.headergrid > div h6 { position: absolute; bottom: -8px; right: 16px; padding: 0; margin: 0; letter-spacing: 0.1em; font-weight: 200; font-size: 11px; }
	
	
	
	
	
	
	
	
	
	
	.contentgrid { display: grid; grid-template-columns: repeat(1, 1fr); gap: 16px;}
	.contentgrid > div { position: relative; padding: 72px 16px 16px 16px; border-radius: 24px; }
	
	.contentgrid > div svg { display: block; width: 44px; position: absolute; right: 24px; top: 24px; fill: none; stroke: url('#coldhot'); stroke-width: 1; }
	.contentgrid > div img { display: block; width: 44px; position: absolute; right: 24px; top: 24px; }
	.contentgrid > div p {  }
	.contentgrid > div p span {  display: inline-block; padding: 0 0 8px 0; margin-bottom: 12px; }
	.contentgrid > div p span sup {opacity: 0.4; }
	.contentgrid > div p small { display: block; font-size: 0.8rem;  }
	.contentgrid > div p small em {font-style: normal;  }
	
	
	
	
	
	.xmplgrid  { display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; padding: 16px 0 0 0; }
	.xmplgrid  img {
	  width: 100%; display: block; background-color: #fff; border-radius: 5px;
	  /* filter: invert(100%) hue-rotate(180deg); */
	}
	
	
	
	@media only screen and (min-width: 480px) {
	  .headergrid { grid-template-columns: repeat(2, 1fr); grid-template-rows: repeat(3, 1fr); }
	  .contentgrid { grid-template-columns: repeat(2, 1fr);}
	}
	@media only screen and (min-width: 640px) {
	  .headergrid { grid-template-columns: repeat(3, 1fr); grid-template-rows: repeat(3, 1fr); }
	  .contentgrid { grid-template-columns: repeat(3, 1fr);}
	}
	 @media only screen and (min-width: 1080px) {
	  .headergrid { grid-template-columns: repeat(4, 1fr); grid-template-rows: repeat(2, 1fr); }
	  .contentgrid { grid-template-columns: repeat(4, 1fr);}
	  .contentgrid > div { padding: 48px 16px 16px 16px; }
	}
	@media only screen and (min-width: 1440px) {
	  .headergrid { grid-template-columns: repeat(5, 1fr); grid-template-rows: repeat(2, 1fr); }
	  .headergrid > div:first-child { grid-column: 1 / 3; aspect-ratio: 2/1; }
	  .contentgrid { grid-template-columns: repeat(5, 1fr);}
	  .contentgrid > div:first-child { grid-column: 1 / 3; }
	}


	
</style>



# SVG Lines

<div class="headergrid">
  <div>
	  <p id="headerBaseline">A set of svg clips for your favorite editor, enabling you to play with Scalable Vector Graphics</p>
  </div>
  <div><img src="https://www.servovalve.org/nova/img/hdr1.svg"><h6>Structure</h6></div>
  <div><img src="https://www.servovalve.org/nova/img/hdr2.svg"><h6>Shapes</h6></div>
  <div><img src="https://www.servovalve.org/nova/img/hdr3.svg"><h6>Styling</h6></div>
  <div><img src="https://www.servovalve.org/nova/img/hdr4.svg"><h6>Transform</h6></div>
  <div><img src="https://www.servovalve.org/nova/img/hdr5.svg"><h6>Advanced</h6></div>
  <div><img src="https://www.servovalve.org/nova/img/hdr6.svg"><h6>Animate</h6></div>
  <div><img src="https://www.servovalve.org/nova/img/hdr7.svg"><h6>Examples</h6></div>
</div>




****

## Content

<div class="contentgrid">
  <div>
	<img src="https://www.servovalve.org/nova/img/cnt0.svg">
	<p><span id="clipCount">89 clips</span><small><em id="eltCount">40</em>&nbsp;elements, <em id="atrCount">42</em>&nbsp;attributes, <em id="xmpCount">7</em>&nbsp;examples, organized in 7&nbsp;folders.</small></p>
  </div>
  <div>
	  <img src="https://www.servovalve.org/nova/img/cnt1.svg">
	  <p><span>Structure <sup>16 clips</sup></span><small>Svg header for file or inline html, structural elements.</small></p>
  </div>
  <div>
	  <img src="https://www.servovalve.org/nova/img/cnt2.svg">
	  <p><span>Shapes <sup>12 clips</sup></span><small>Primitives shapes, text, images.</small></p>
  </div>
  <div>
	  <img src="https://www.servovalve.org/nova/img/cnt3.svg">
	  <p><span>Styling <sup>12 clips</sup></span><small>Coloring, stroking, dashing, dotting.</small></p>
  </div>
  <div>
	  <img src="https://www.servovalve.org/nova/img/cnt4.svg">
	  <p><span>Transform <sup>5 clips</sup></span><small>Translation, rotation, scale, skew.</small></p>
  </div>
  <div>
	  <img src="https://www.servovalve.org/nova/img/cnt5.svg">
	  <p><span>Advanced <sup>23 clips</sup></span><small>Deeper styling with gradient, pattern, mask.</small></p>
  </div>
  <div>
	  <img src="https://www.servovalve.org/nova/img/cnt6.svg">
	  <p><span>Animate <sup>14 clips</sup></span><small>Animate attribute, transformation, or motion.</small></p>
  </div>
  <div>
	  <img src="https://www.servovalve.org/nova/img/cnt7.svg">
	  <p><span>Examples <sup>7 clips</sup></span><small>Samples ans starting lines.</small></p>
  </div>
</div>



****

## Details

<div id="tableBox">
  <table class="detable">
	<thead>
	  <tr>
		<th colspan="5" style="font-size:18px; text-transform: inherit; letter-spacing: inherit">
		  <svg viewBox="0 0 18 18" width="17px" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
			<defs>
			  <pattern id="eltpatt" x="0" y="0" width="8" height="8" patternUnits="userSpaceOnUse">
				<circle cx="4" cy="4" r="3" fill="crimson"></circle>
			  </pattern>
			  <pattern id="atrpatt" x="0" y="0" width="8" height="8" patternUnits="userSpaceOnUse">
				<circle cx="4" cy="4" r="3" fill="dodgerblue"></circle>
			  </pattern>
			  <pattern id="xmppatt" x="0" y="0" width="8" height="8" patternUnits="userSpaceOnUse">
				<circle cx="4" cy="4" r="3" fill="limegreen"></circle>
			  </pattern>
			</defs>
			<rect x="0" y="11" width="8" height="1" fill="#555"></rect>
		  </svg>Folders
		</th>
		<!-- <th  colspan="5" style="width:auto"></th> -->
	  </tr>
	  <tr>
		<th>&nbsp;</th>
		<th>Type</th>
		<th>Title</th>
		<th>Trigger</th>
		<th>Description</th>
	  </tr>
	</thead>
  </table>

  <details>
	<summary><div>Structure </div><div><svg viewBox="0 0 256 8"><rect x="0" width="128" height="8" fill="url(#eltpatt)"></rect><rect x="128" width="0" height="8" fill="url(#atrpatt)"></rect><rect x="128" width="0" height="8" fill="url(#xmppatt)"></rect></svg></div></summary>
	<table class="detable"><tbody><tr><td>1.1</td><td><span class="elmt">&lt;/&gt;</span></td><td>svg file 1</td><td><span class="shortcut">vg-file1</span></td><td>Svg file with prepositioned elements (style + defs)</td></tr><tr><td>1.2</td><td><span class="elmt">&lt;/&gt;</span></td><td>svg file 2</td><td><span class="shortcut">vg-file2</span></td><td>Svg file with required attributes </td></tr><tr><td>1.3</td><td><span class="elmt">&lt;/&gt;</span></td><td>svg file 3</td><td><span class="shortcut">vg-file3</span></td><td>Svg file with grid (inline use)</td></tr><tr><td>1.4</td><td><span class="elmt">&lt;/&gt;</span></td><td>svg 512x512</td><td><span class="shortcut">vg-512</span></td><td>–</td></tr><tr><td>1.5</td><td><span class="elmt">&lt;/&gt;</span></td><td>svg 128x128</td><td><span class="shortcut">vg-128</span></td><td>–</td></tr><tr><td>1.6</td><td><span class="elmt">&lt;/&gt;</span></td><td>svg 64x64</td><td><span class="shortcut">vg-64</span></td><td>–</td></tr><tr><td>1.7</td><td><span class="elmt">&lt;/&gt;</span></td><td>svg 32x32</td><td><span class="shortcut">vg-32</span></td><td>–</td></tr><tr><td>1.8</td><td><span class="elmt">&lt;/&gt;</span></td><td>svg 24x24</td><td><span class="shortcut">vg-24</span></td><td>–</td></tr><tr><td>1.9</td><td><span class="elmt">&lt;/&gt;</span></td><td>view</td><td><span class="shortcut">vg-view</span></td><td>–</td></tr><tr><td>1.10</td><td><span class="elmt">&lt;/&gt;</span></td><td>defs</td><td><span class="shortcut">vg-defs</span></td><td>–</td></tr><tr><td>1.11</td><td><span class="elmt">&lt;/&gt;</span></td><td>group</td><td><span class="shortcut">vg-grou</span></td><td>Group element with transform attribute</td></tr><tr><td>1.12</td><td><span class="elmt">&lt;/&gt;</span></td><td>symbol</td><td><span class="shortcut">vg-symb</span></td><td>–</td></tr><tr><td>1.13</td><td><span class="elmt">&lt;/&gt;</span></td><td>use symbol</td><td><span class="shortcut">vg-ussy</span></td><td>–</td></tr><tr><td>1.14</td><td><span class="elmt">&lt;/&gt;</span></td><td>use element</td><td><span class="shortcut">vg-usel</span></td><td>–</td></tr><tr><td>1.15</td><td><span class="elmt">&lt;/&gt;</span></td><td>description</td><td><span class="shortcut">vg-desc</span></td><td>+ Accessibility</td></tr><tr><td>1.16</td><td><span class="elmt">&lt;/&gt;</span></td><td>title</td><td><span class="shortcut">vg-titl</span></td><td>+ Accessibility</td></tr></tbody></table>
  </details>
  <details>
	<summary><div>Shapes </div><div><svg viewBox="0 0 256 8"><rect x="0" width="96" height="8" fill="url(#eltpatt)"></rect><rect x="96" width="0" height="8" fill="url(#atrpatt)"></rect><rect x="96" width="0" height="8" fill="url(#xmppatt)"></rect></svg></div></summary>
	<table class="detable"><tbody><tr><td>2.1</td><td><span class="elmt">&lt;/&gt;</span></td><td>circle</td><td><span class="shortcut">vg-circ</span></td><td>–</td></tr><tr><td>2.2</td><td><span class="elmt">&lt;/&gt;</span></td><td>ellipse</td><td><span class="shortcut">vg-elli</span></td><td>–</td></tr><tr><td>2.3</td><td><span class="elmt">&lt;/&gt;</span></td><td>rect</td><td><span class="shortcut">vg-rect</span></td><td>–</td></tr><tr><td>2.4</td><td><span class="elmt">&lt;/&gt;</span></td><td>round rect</td><td><span class="shortcut">vg-recr</span></td><td>–</td></tr><tr><td>2.5</td><td><span class="elmt">&lt;/&gt;</span></td><td>polygon</td><td><span class="shortcut">vg-poly</span></td><td>–</td></tr><tr><td>2.6</td><td><span class="elmt">&lt;/&gt;</span></td><td>line</td><td><span class="shortcut">vg-line</span></td><td>–</td></tr><tr><td>2.7</td><td><span class="elmt">&lt;/&gt;</span></td><td>polyline</td><td><span class="shortcut">vg-poli</span></td><td>–</td></tr><tr><td>2.8</td><td><span class="elmt">&lt;/&gt;</span></td><td>path</td><td><span class="shortcut">vg-path</span></td><td>–</td></tr><tr><td>2.9</td><td><span class="elmt">&lt;/&gt;</span></td><td>text</td><td><span class="shortcut">vg-text</span></td><td>–</td></tr><tr><td>2.10</td><td><span class="elmt">&lt;/&gt;</span></td><td>text path</td><td><span class="shortcut">vg-txtp</span></td><td>–</td></tr><tr><td>2.11</td><td><span class="elmt">&lt;/&gt;</span></td><td>tspan</td><td><span class="shortcut">vg-tspn</span></td><td>–</td></tr><tr><td>2.12</td><td><span class="elmt">&lt;/&gt;</span></td><td>image</td><td><span class="shortcut">vg-imag</span></td><td>–</td></tr></tbody></table>
  </details>
  <details>
	<summary><div>Styling </div><div><svg viewBox="0 0 256 8"><rect x="0" width="0" height="8" fill="url(#eltpatt)"></rect><rect x="0" width="96" height="8" fill="url(#atrpatt)"></rect><rect x="96" width="0" height="8" fill="url(#xmppatt)"></rect></svg></div></summary>
	<table class="detable"><tbody><tr><td>3.1</td><td><span class="attr">attr</span></td><td>fill</td><td><span class="shortcut">vg-fill</span></td><td>–</td></tr><tr><td>3.2</td><td><span class="attr">attr</span></td><td>fill-rule</td><td><span class="shortcut">vg-filr</span></td><td>–</td></tr><tr><td>3.3</td><td><span class="attr">attr</span></td><td>fill-opacity</td><td><span class="shortcut">vg-fopa</span></td><td>–</td></tr><tr><td>3.4</td><td><span class="attr">attr</span></td><td>stroke</td><td><span class="shortcut">vg-strk</span></td><td>–</td></tr><tr><td>3.5</td><td><span class="attr">attr</span></td><td>stroke-width</td><td><span class="shortcut">vg-swid</span></td><td>–</td></tr><tr><td>3.6</td><td><span class="attr">attr</span></td><td>stroke-opacity</td><td><span class="shortcut">vg-sopa</span></td><td>–</td></tr><tr><td>3.7</td><td><span class="attr">attr</span></td><td>stroke-linecap</td><td><span class="shortcut">vg-slic</span></td><td>–</td></tr><tr><td>3.8</td><td><span class="attr">attr</span></td><td>stroke-linejoin</td><td><span class="shortcut">vg-slij</span></td><td>–</td></tr><tr><td>3.9</td><td><span class="attr">attr</span></td><td>stroke-miterlimit</td><td><span class="shortcut">vg-mitl</span></td><td>–</td></tr><tr><td>3.10</td><td><span class="attr">attr</span></td><td>stroke-dasharray</td><td><span class="shortcut">vg-sdar</span></td><td>–</td></tr><tr><td>3.11</td><td><span class="attr">attr</span></td><td>stroke-dashoffset</td><td><span class="shortcut">vg-sdof</span></td><td>–</td></tr><tr><td>3.12</td><td><span class="attr">attr</span></td><td>pathLength</td><td><span class="shortcut">vg-plng</span></td><td>–</td></tr></tbody></table>
  </details>
  <details>
	<summary><div>Transform </div><div><svg viewBox="0 0 256 8"><rect x="0" width="0" height="8" fill="url(#eltpatt)"></rect><rect x="0" width="40" height="8" fill="url(#atrpatt)"></rect><rect x="40" width="0" height="8" fill="url(#xmppatt)"></rect></svg></div></summary>
	<table class="detable"><tbody><tr><td>4.1</td><td><span class="attr">attr</span></td><td>translate</td><td><span class="shortcut">vg-tran</span></td><td>–</td></tr><tr><td>4.2</td><td><span class="attr">attr</span></td><td>rotate</td><td><span class="shortcut">vg-trot</span></td><td>–</td></tr><tr><td>4.3</td><td><span class="attr">attr</span></td><td>scale</td><td><span class="shortcut">vg-tsca</span></td><td>–</td></tr><tr><td>4.4</td><td><span class="attr">attr</span></td><td>skewX</td><td><span class="shortcut">vg-tskx</span></td><td>–</td></tr><tr><td>4.5</td><td><span class="attr">attr</span></td><td>skewY</td><td><span class="shortcut">vg-tsky</span></td><td>–</td></tr></tbody></table>
  </details>
  <details>
	<summary><div>Advanced </div><div><svg viewBox="0 0 256 8"><rect x="0" width="56" height="8" fill="url(#eltpatt)"></rect><rect x="56" width="128" height="8" fill="url(#atrpatt)"></rect><rect x="184" width="0" height="8" fill="url(#xmppatt)"></rect></svg></div></summary>
	<table class="detable"><tbody><tr><td>5.1</td><td><span class="elmt">&lt;/&gt;</span></td><td>linear gradient</td><td><span class="shortcut">vg-ling</span></td><td>Gradient</td></tr><tr><td>5.2</td><td><span class="elmt">&lt;/&gt;</span></td><td>radial gradient</td><td><span class="shortcut">vg-radg</span></td><td>Gradient</td></tr><tr><td>5.3</td><td><span class="elmt">&lt;/&gt;</span></td><td>stop</td><td><span class="shortcut">vg-stop</span></td><td>Gradient</td></tr><tr><td>5.4</td><td><span class="attr">attr</span></td><td>gradient units</td><td><span class="shortcut">vg-guni</span></td><td>Gradient</td></tr><tr><td>5.5</td><td><span class="attr">attr</span></td><td>gradient transform</td><td><span class="shortcut">vg-gtra</span></td><td>Gradient</td></tr><tr><td>5.6</td><td><span class="attr">attr</span></td><td>fill with gradient</td><td><span class="shortcut">vg-fgra</span></td><td>Gradient</td></tr><tr><td>5.7</td><td><span class="attr">attr</span></td><td>stroke with gradient</td><td><span class="shortcut">vg-sgra</span></td><td>Gradient</td></tr><tr><td>5.8</td><td><span class="elmt">&lt;/&gt;</span></td><td>pattern</td><td><span class="shortcut">vg-patt</span></td><td>Pattern</td></tr><tr><td>5.9</td><td><span class="attr">attr</span></td><td>patternUnits</td><td><span class="shortcut">vg-puni</span></td><td>Pattern</td></tr><tr><td>5.10</td><td><span class="attr">attr</span></td><td>patternContentUnits</td><td><span class="shortcut">vg-pcon</span></td><td>Pattern</td></tr><tr><td>5.11</td><td><span class="attr">attr</span></td><td>patternTransform</td><td><span class="shortcut">vg-ptra</span></td><td>Pattern</td></tr><tr><td>5.12</td><td><span class="attr">attr</span></td><td>fill with pattern</td><td><span class="shortcut">vg-fpat</span></td><td>Pattern</td></tr><tr><td>5.13</td><td><span class="attr">attr</span></td><td>stroke with pattern</td><td><span class="shortcut">vg-spat</span></td><td>Pattern</td></tr><tr><td>5.14</td><td><span class="elmt">&lt;/&gt;</span></td><td>mask definition</td><td><span class="shortcut">vg-mask</span></td><td>Mask</td></tr><tr><td>5.15</td><td><span class="attr">attr</span></td><td>mask a shape</td><td><span class="shortcut">vg-fmsk</span></td><td>Mask</td></tr><tr><td>5.16</td><td><span class="elmt">&lt;/&gt;</span></td><td>clip</td><td><span class="shortcut">vg-clip</span></td><td>Clip</td></tr><tr><td>5.17</td><td><span class="attr">attr</span></td><td>clip-path a shape</td><td><span class="shortcut">vg-fcli</span></td><td>Clip</td></tr><tr><td>5.18</td><td><span class="attr">attr</span></td><td>clip-rule</td><td><span class="shortcut">vg-crul</span></td><td>Clip</td></tr><tr><td>5.19</td><td><span class="attr">attr</span></td><td>clipPathUnits</td><td><span class="shortcut">vg-cpun</span></td><td>Clip</td></tr><tr><td>5.20</td><td><span class="elmt">&lt;/&gt;</span></td><td>marker</td><td><span class="shortcut">vg-mark</span></td><td>Marker</td></tr><tr><td>5.21</td><td><span class="attr">attr</span></td><td>marker-start</td><td><span class="shortcut">vg-mstt</span></td><td>Marker</td></tr><tr><td>5.22</td><td><span class="attr">attr</span></td><td>marker-mid</td><td><span class="shortcut">vg-mmid</span></td><td>Marker</td></tr><tr><td>5.23</td><td><span class="attr">attr</span></td><td>marker-end</td><td><span class="shortcut">vg-mend</span></td><td>Marker</td></tr></tbody></table>
  </details>
  <details>
	<summary><div>Animate </div><div><svg viewBox="0 0 256 8"><rect x="0" width="40" height="8" fill="url(#eltpatt)"></rect><rect x="40" width="72" height="8" fill="url(#atrpatt)"></rect><rect x="112" width="0" height="8" fill="url(#xmppatt)"></rect></svg></div></summary>
	<table class="detable"><tbody><tr><td>6.1</td><td><span class="elmt">&lt;/&gt;</span></td><td>animate attribute</td><td><span class="shortcut">vg-aatr</span></td><td>–</td></tr><tr><td>6.2</td><td><span class="elmt">&lt;/&gt;</span></td><td>animate transform</td><td><span class="shortcut">vg-atra</span></td><td>–</td></tr><tr><td>6.3</td><td><span class="elmt">&lt;/&gt;</span></td><td>animate motion</td><td><span class="shortcut">vg-amot</span></td><td>–</td></tr><tr><td>6.4</td><td><span class="elmt">&lt;/&gt;</span></td><td>motion path</td><td><span class="shortcut">vg-amop</span></td><td>–</td></tr><tr><td>6.5</td><td><span class="elmt">&lt;/&gt;</span></td><td>set</td><td><span class="shortcut">vg-aset</span></td><td>–</td></tr><tr><td>6.6</td><td><span class="attr">attr</span></td><td>from / to - svg anim</td><td><span class="shortcut">vg-afto</span></td><td>2 attributes for 2 stepped animation</td></tr><tr><td>6.7</td><td><span class="attr">attr</span></td><td>values - svg anim</td><td><span class="shortcut">vg-aval</span></td><td>–</td></tr><tr><td>6.8</td><td><span class="attr">attr</span></td><td>begin - svg anim</td><td><span class="shortcut">vg-abeg</span></td><td>–</td></tr><tr><td>6.9</td><td><span class="attr">attr</span></td><td>keyPoints - svg anim</td><td><span class="shortcut">vg-akpo</span></td><td>–</td></tr><tr><td>6.10</td><td><span class="attr">attr</span></td><td>keyTimes - svg anim</td><td><span class="shortcut">vg-akti</span></td><td>–</td></tr><tr><td>6.11</td><td><span class="attr">attr</span></td><td>keySplines - svg anim</td><td><span class="shortcut">vg-aksp</span></td><td>–</td></tr><tr><td>6.12</td><td><span class="attr">attr</span></td><td>calcMode - svg anim</td><td><span class="shortcut">vg-acal</span></td><td>–</td></tr><tr><td>6.13</td><td><span class="attr">attr</span></td><td>accumulate - svg anim</td><td><span class="shortcut">vg-acum</span></td><td>–</td></tr><tr><td>6.14</td><td><span class="attr">attr</span></td><td>additive - svg anim</td><td><span class="shortcut">vg-adit</span></td><td>–</td></tr></tbody></table>
  </details>
  <details>
	<summary><div>Examples </div><div><svg viewBox="0 0 256 8"><rect x="0" width="0" height="8" fill="url(#eltpatt)"></rect><rect x="0" width="0" height="8" fill="url(#atrpatt)"></rect><rect x="0" width="56" height="8" fill="url(#xmppatt)"></rect></svg></div></summary>
	<table class="detable"><tbody><tr><td>7.1</td><td><span class="xmpl">svg</span></td><td>example 0 - Grids</td><td><span class="shortcut">vg-x0</span></td><td>_</td></tr><tr><td>7.2</td><td><span class="xmpl">svg</span></td><td>example 1 - Shapes</td><td><span class="shortcut">vg-x1</span></td><td>–</td></tr><tr><td>7.3</td><td><span class="xmpl">svg</span></td><td>example 2 - Paths</td><td><span class="shortcut">vg-x2</span></td><td>–</td></tr><tr><td>7.4</td><td><span class="xmpl">svg</span></td><td>example 3 - Styling</td><td><span class="shortcut">vg-x3</span></td><td>–</td></tr><tr><td>7.5</td><td><span class="xmpl">svg</span></td><td>example 4 - Advanced</td><td><span class="shortcut">vg-x4</span></td><td>–</td></tr><tr><td>7.6</td><td><span class="xmpl">svg</span></td><td>example 5 - Transform</td><td><span class="shortcut">vg-x5</span></td><td>–</td></tr><tr><td>7.7</td><td><span class="xmpl">svg</span></td><td>example 6 - Animate</td><td><span class="shortcut">vg-x6</span></td><td>–</td></tr></tbody></table>
  </details>
</div>







****

## About

The search for svg in nova extensions yielded no results, so I organized my svg clips somewhat after learning about the possibility of making my own extensions.

The organization of the folders corresponds to the structure of the [course](https://www.servovalve.org/codesign_svg/) I share with my students.





****

## Future ?

→  Missing elements & attributes. 

→  Svg filters. 

→  Improving what's needed…





****

<a href="https://www.servovalve.org" target="_blank" rel="noreferrer noopener" style="opacity:0.2;"><img src="https://www.servovalve.org/mda/svg/logo-servovalve-blc.svg" width="128px" alt="go to servovalve website"></a>