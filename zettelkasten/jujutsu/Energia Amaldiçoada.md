---
tags:
  - Fundamentos
  - TODO
---
### [Voltar Ao Sumário](../../index) [Voltar A Raiz](Jujutsu) [Página Anterior]()
--- 
# **Energia Amaldiçoada**

A **Energia Amaldiçoada (<ruby>呪 <rt>じゅ</rt> 力 <rt>りょく</rt></ruby> _Juryoku_)** é o poder, a chama, a energia que serve de combustível de toda a paranormalidade  

<style>
	/* Definição das variáveis do tema "obsidianite" */
	:root {
	  --background-primary: #100e17;
	  --background-primary-alt: #0d0b12;
	  --background-secondary: #191621;
	  --background-secondary-alt: #0d0b12;
	  --text-normal: #bebebe;
	  --text-accent: #0fb6d6;
	  --text-sub-accent: #f4569d;
	  --text-dim: #45aaff;
	  --text-faint: #7aa2f7;
	  --text-title-h1: var(--text-accent);
	  --text-title-h2: #cbdbe5;
	  --text-title-h3: #cbdbe5;
	  --text-title-h4: #cbdbe5;
	  --text-title-h5: #cbdbe5;
	  --text-link: #b4b4b4;
	  --text-a: #6bcafb;
	  --text-a-hover: #6bcafb;
	  --text-mark: #263d92;
	  --code-background: var(--background-secondary);
	  --interactive-accent: rgba(14, 210, 247, 0.5);
	  --interactive-accent-hover: rgba(14, 210, 247, 0.8);
	  --interactive-before: #5e6565;
	  --blockquote-border: #4aa8fb;
	  --tag-background: rgba(14, 210, 247, 0.15);
	  --interactive-accent-rgb: #3dd7fb;
	  --font-family-editor: 'Rubik';
	  --font-family-preview: 'Rubik';
	  --bg-sub-accent-55: rgba(244, 86, 157, 0.55);
	  --bg-accent-55: rgba(14, 210, 247, 0.55);
	  --bg-accent-25: rgba(14, 210, 247, 0.25);
	  --text-highlight-bg: rgba(244, 86, 157, 0.25);
	  --background-modifier-border: rgba(14, 210, 247, 0.05);
	  --table-border-color: rgb(14, 210, 247, 0.15);
	  --test-color: rgb(122, 162, 247);
	  --editor-border-color: #101014;
	}
	
	/* Estilo do corpo da página */
	body {
	  font-family: 'Rubik', sans-serif;
	  background-color: var(--background-primary);
	  color: var(--text-normal);
	  margin: 0;
	  padding: 0;
	}
	
	/* Contêiner principal */
	.container {
	  max-width: 800px;
	  margin: 0 auto;
	  padding: 20px;
	  background-color: var(--background-secondary);
	  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
	}
	
	/**-------------------**
	| HEADING STYLES
	**--------------------**/
	h1,
	h2,
	h3,
	h4,
	h5,
	h6 {
	  font-family: var(--default-font);
	  font-weight: 600;
	}
	
	.HyperMD-header.HyperMD-header-2,
	.HyperMD-header.HyperMD-header-3,
	.HyperMD-header.HyperMD-header-4,
	.HyperMD-header.HyperMD-header-5,
	.HyperMD-header.HyperMD-header-6 {
	  border-bottom: 1px solid;
	  border-width: 1px;
	  border-image-slice: 1;
	  border-image-source: linear-gradient(to right, var(--text-sub-accent), #100e17, #100e17, #100e17);
	}
	
	.HyperMD-header {
	  padding: 20px;
	}
	
	.markdown-preview-section h1,
	.cm-header-1 {
	  font-size: 34px;
	  color: var(--text-title-h1);
	}
	
	.markdown-preview-section h2,
	.cm-header-2 {
	  font-size: 26px;
	  color: var(--text-title-h2);
	}
	
	.markdown-preview-section h3,
	.cm-header-3 {
	  font-size: 22px;
	  color: var(--text-title-h3);
	}
	
	.markdown-preview-section h4,
	.cm-header-4 {
	  font-size: 18px;
	  color: var(--text-title-h4);
	}
	
	.markdown-preview-section h5,
	.cm-header-5 {
	  font-size: 18px;
	  color: var(--text-title-h5);
	}
	
	.markdown-preview-section h6,
	.cm-header-6 {
	  font-size: 18px;
	  color: var(--text-title-h5);
	}
	
	/** headings */
	.markdown-preview-view h2,
	.markdown-preview-view h3,
	.markdown-preview-view h4,
	.markdown-preview-view h5,
	.markdown-preview-view h6 {
	  /* padding-top: 1.25rem; */
	  margin: 45px 0 20px 0;
	  position: relative;
	  padding-bottom: 10px;
	  border-bottom: 1px solid;
	  border-width: 35%;
	  border-image-slice: 1;
	  border-image-source: linear-gradient(to right, var(--text-sub-accent), #100e17, #100e17, #100e17);
	}
	
	.view-header-icon {
	  color: var(--text-accent);
	}
	
	/** Adding different # colors **/
	
	.cm-formatting.cm-formatting-header.cm-header {
	  color: var(--text-accent);
	  opacity: 0.45;
	}
	
	/**-------------------**
	| HR STYLES
	**--------------------**/
	
	/** hr styles -- PREVIEW MODE */
	.cm-line hr,
	.markdown-preview-view hr {
	  margin-block-start: 4em;
	  margin-block-end: 4em;
	  border: none;
	  height: 0;
	  border-bottom: 1px solid;
	  border-image-slice: 1;
	  border-width: 1px;
	  border-image-source: linear-gradient(to right, transparent, var(--text-accent), transparent);
	}
	
	.cm-line hr::after,
	.markdown-preview-view hr::after {
	  content: '§';
	  display: inline-block;
	  position: absolute;
	  left: 50%;
	  transform: translate(-50%, -50%) rotate(60deg);
	  transform-origin: 50% 50%;
	  padding: 0.5rem;
	  color: var(--text-sub-accent);
	  background-color: var(--background-primary);
	}
	/**-------------------**
	| STRONG/BOLD STYLES
	**--------------------**/
	
	.cm-strong,
	strong {
	  -webkit-background-clip: text;
	  -webkit-text-fill-color: transparent;
	  padding: 0;
	  color: #7aa2f7;
	  background-color: #7aa2f7;
	  background-image: linear-gradient(62deg, #87c2fd 0%, #dcb9fc 100%) !important;
	}
	
	strong .math.math-inline .MathJax {
	  position: inherit !important;
	}
	
	.cm-strong .cm-selection,
	strong::selection {
	  -webkit-text-fill-color: var(--text-faint);
	}
	
	/**-------------------**
	| <KBD> STYLING
	**--------------------**/
	
	.cm-strong kbd,
	strong kbd {
	  -webkit-text-fill-color: initial;
	}
	
	/**-------------------**
	| ITALIC STYLES
	**--------------------**/
	
	.cm-em,
	em {
	  color: #bb9af7 !important;
	  font-family: OperatorMonoSSmLig-Book, Rubik, var(--default-font) !important;
	}
	
	.cm-em.cm-formatting-em {
	  display: inline-flex;
	  width: 0.45rem;
	  font-size: 0.6rem;
	  vertical-align: text-top;
	}
	
	/**-------------------**
	| LISTING STYLES (ul, li, ol)
	**--------------------**/
	
	.cm-s-obsidian span.cm-formatting-list {
	  color: var(--text-accent);
	}
	
	.markdown-source-view.mod-cm6 .cm-indent::before {
	  border-width: 2px;
	  border-color: var(--text-accent);
	  margin-left: -1px;
	  opacity: 0.35;
	  transition: opacity 500ms linear ease-in-out;
	}
	
	.markdown-source-view.mod-cm6 .cm-active-indent::before {
	  opacity: 0.8;
	}
	/* Estilo dos links */
	
	.cm-s-obsidian span.cm-link:not(.cm-formatting-link) .cm-underline,
	.cm-s-obsidian span.cm-hmd-internal-link .cm-underline {
	  color: var(--text-normal);
	  -webkit-text-fill-color: var(--text-normal);
	  background-position: 0 100%;
	  background-repeat: repeat-x;
	  background-size: 5px 5px;
	  text-decoration: none;
	}
	
	cm-s-obsidian span.cm-link:not(.cm-formatting-link) .cm-underline {
	  background-image: linear-gradient(
	    to bottom,
	    var(--bg-sub-accent-55) 0%,
	    var(--bg-sub-accent-55) 100%
	  );
	}
	
	.cm-s-obsidian span.cm-formatting-link {
	  color: var(--text-faint) !important;
	  opacity: 0.25;
	}
	
	/** preview mode **/
	.external-link {
	  padding: 0;
	}
	
	.internal-link,
	.external-link {
	  color: var(--text-normal);
	  background-position: 0 100%;
	  background-repeat: repeat-x;
	  background-size: 5px 5px;
	  text-decoration: none;
	  transition: background 350ms ease-in-out;
	}
	
	.cm-s-obsidian span.cm-link:not(.cm-formatting-link) .cm-underline,
	.external-link {
	  background-image: linear-gradient(
	    to bottom,
	    var(--bg-sub-accent-55) 0%,
	    var(--bg-sub-accent-55) 100%
	  );
	  transition: background 350ms ease-in-out;
	}
	
	.cm-s-obsidian span.cm-hmd-internal-link .cm-underline,
	.internal-link {
	  background-image: linear-gradient(to bottom, var(--bg-accent-55) 0%, var(--bg-accent-55) 100%);
	  transition: background 350ms ease-in-out;
	}
	
	.internal-link:hover,
	.cm-s-obsidian span.cm-hmd-internal-link .cm-underline:hover {
	  -webkit-text-fill-color: #fff;
	  color: #fff;
	  background-size: 4px 50px;
	  text-decoration-line: none !important;
	}
	
	.cm-s-obsidian span.cm-link:not(.cm-formatting-link) .cm-underline:hover,
	.external-link:hover {
	  -webkit-text-fill-color: #fff;
	  color: #fff;
	  background-size: 4px 50px;
	  text-decoration-line: none !important;
	}
	
	/* link */
	a,
	.internal-link,
	.cm-hmd-internal-link,
	.cm-link {
	  text-decoration: none !important;
	  color: var(--text-normal);
	  position: relative;
	  z-index: 1;
	}
	
	.cm-url {
	  color: var(--text-faint) !important;
	  opacity: 0.4;
	  font-weight: normal;
	}
	
	.cm-formatting-image {
	  color: var(--text-accent) !important;
	  opacity: 0.7;
	}
	
	/* link hover color */
	a:hover,
	.internal-link:hover {
	  text-decoration: none !important;
	  color: var(--text-accent);
	}
	
	/**-------------------**
	| TAG STYLING
	**--------------------**/
	
	.cm-s-obsidian span.cm-hashtag {
	  position: relative;
	  color: var(--text-accent);
	  opacity: 1;
	  font-family: var(--tag-font-family);
	  font-style: italic;
	  text-decoration: none;
	  font-size: 0.86rem;
	  font-weight: 500;
	}
	
	.cm-s-obsidian span.cm-hashtag:hover {
	  text-decoration-line: underline;
	  text-decoration-color: var(--text-accent);
	}
	
	.cm-s-obsidian span.cm-formatting-hashtag {
	  color: var(--text-faint);
	}
	
	/** tags */
	a.tag {
	  background-color: var(--tag-background);
	  color: var(--text-accent);
	  white-space: nowrap;
	  border-radius: var(--tag-radius);
	  padding: var(--tag-padding-y) var(--tag-padding-x);
	  font-family: var(--tag-font-family);
	  text-decoration: none;
	  font-style: italic;
	  font-size: 0.86rem;
	  font-weight: 500;
	}
	
	a.tag:hover {
	  border-color: var(--text-accent);
	  opacity: 1;
	  background-color: var(--tag-background) !important;
	  text-decoration: underline !important;
	  text-decoration-color: var(--text-accent);
	}
	
	h1 a.tag,
	h2 a.tag,
	h3 a.tag,
	h4 a.tag,
	h5 a.tag,
	h6 a.tag {
	  font-size: inherit !important;
	}
	/* Estilo das citações */
	blockquote {
	  background-color: var(--bg-sub-accent-55);
	  border-left: 5px solid var(--blockquote-border);
	  margin: 1em 0;
	  padding: 20px;
	}
	
	/* Imagem alinhada ao centro */
	.center-image {
	  display: block;
	  margin: 0 auto;
	}
	
	/* Estilo para listas */
	ul, ol {
	  margin: 0 0 20px 20px;
	}
	
	/* Estilo para código (opcional) */
	pre {
	  background-color: var(--code-background);
	  border: 1px solid var(--background-primary-alt);
	  padding: 10px;
	  overflow-x: auto;
	  font-family: 'Courier New', monospace;
	}
	
	code {
	  font-family: 'Courier New', monospace;
	  background-color: var(--code-background);
	  border: 1px solid var(--background-primary-alt);
	  padding: 2px 4px;
	}
	
	/* Estilo para data e autor */
	.date-author {
	  font-size: 14px;
	  color: var(--text-faint);
	  margin-top: 10px;
	}</style>