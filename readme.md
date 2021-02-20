<!DOCTYPE html>
<html>
<head>
<title>DA_DG.md</title>
<meta http-equiv="Content-type" content="text/html;charset=UTF-8">

<style>
/* https://github.com/microsoft/vscode/blob/master/extensions/markdown-language-features/media/markdown.css */
/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

body {
	font-family: var(--vscode-markdown-font-family, -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "Ubuntu", "Droid Sans", sans-serif);
	font-size: var(--vscode-markdown-font-size, 14px);
	padding: 0 26px;
	line-height: var(--vscode-markdown-line-height, 22px);
	word-wrap: break-word;
}

#code-csp-warning {
	position: fixed;
	top: 0;
	right: 0;
	color: white;
	margin: 16px;
	text-align: center;
	font-size: 12px;
	font-family: sans-serif;
	background-color:#444444;
	cursor: pointer;
	padding: 6px;
	box-shadow: 1px 1px 1px rgba(0,0,0,.25);
}

#code-csp-warning:hover {
	text-decoration: none;
	background-color:#007acc;
	box-shadow: 2px 2px 2px rgba(0,0,0,.25);
}

body.scrollBeyondLastLine {
	margin-bottom: calc(100vh - 22px);
}

body.showEditorSelection .code-line {
	position: relative;
}

body.showEditorSelection .code-active-line:before,
body.showEditorSelection .code-line:hover:before {
	content: "";
	display: block;
	position: absolute;
	top: 0;
	left: -12px;
	height: 100%;
}

body.showEditorSelection li.code-active-line:before,
body.showEditorSelection li.code-line:hover:before {
	left: -30px;
}

.vscode-light.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(0, 0, 0, 0.15);
}

.vscode-light.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(0, 0, 0, 0.40);
}

.vscode-light.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-dark.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(255, 255, 255, 0.4);
}

.vscode-dark.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(255, 255, 255, 0.60);
}

.vscode-dark.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-high-contrast.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(255, 160, 0, 0.7);
}

.vscode-high-contrast.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(255, 160, 0, 1);
}

.vscode-high-contrast.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

img {
	max-width: 100%;
	max-height: 100%;
}

a {
	text-decoration: none;
}

a:hover {
	text-decoration: underline;
}

a:focus,
input:focus,
select:focus,
textarea:focus {
	outline: 1px solid -webkit-focus-ring-color;
	outline-offset: -1px;
}

hr {
	border: 0;
	height: 2px;
	border-bottom: 2px solid;
}

h1 {
	padding-bottom: 0.3em;
	line-height: 1.2;
	border-bottom-width: 1px;
	border-bottom-style: solid;
}

h1, h2, h3 {
	font-weight: normal;
}

table {
	border-collapse: collapse;
}

table > thead > tr > th {
	text-align: left;
	border-bottom: 1px solid;
}

table > thead > tr > th,
table > thead > tr > td,
table > tbody > tr > th,
table > tbody > tr > td {
	padding: 5px 10px;
}

table > tbody > tr + tr > td {
	border-top: 1px solid;
}

blockquote {
	margin: 0 7px 0 5px;
	padding: 0 16px 0 10px;
	border-left-width: 5px;
	border-left-style: solid;
}

code {
	font-family: Menlo, Monaco, Consolas, "Droid Sans Mono", "Courier New", monospace, "Droid Sans Fallback";
	font-size: 1em;
	line-height: 1.357em;
}

body.wordWrap pre {
	white-space: pre-wrap;
}

pre:not(.hljs),
pre.hljs code > div {
	padding: 16px;
	border-radius: 3px;
	overflow: auto;
}

pre code {
	color: var(--vscode-editor-foreground);
	tab-size: 4;
}

/** Theming */

.vscode-light pre {
	background-color: rgba(220, 220, 220, 0.4);
}

.vscode-dark pre {
	background-color: rgba(10, 10, 10, 0.4);
}

.vscode-high-contrast pre {
	background-color: rgb(0, 0, 0);
}

.vscode-high-contrast h1 {
	border-color: rgb(0, 0, 0);
}

.vscode-light table > thead > tr > th {
	border-color: rgba(0, 0, 0, 0.69);
}

.vscode-dark table > thead > tr > th {
	border-color: rgba(255, 255, 255, 0.69);
}

.vscode-light h1,
.vscode-light hr,
.vscode-light table > tbody > tr + tr > td {
	border-color: rgba(0, 0, 0, 0.18);
}

.vscode-dark h1,
.vscode-dark hr,
.vscode-dark table > tbody > tr + tr > td {
	border-color: rgba(255, 255, 255, 0.18);
}

</style>

<style>
/* Tomorrow Theme */
/* http://jmblog.github.com/color-themes-for-google-code-highlightjs */
/* Original theme - https://github.com/chriskempson/tomorrow-theme */

/* Tomorrow Comment */
.hljs-comment,
.hljs-quote {
	color: #8e908c;
}

/* Tomorrow Red */
.hljs-variable,
.hljs-template-variable,
.hljs-tag,
.hljs-name,
.hljs-selector-id,
.hljs-selector-class,
.hljs-regexp,
.hljs-deletion {
	color: #c82829;
}

/* Tomorrow Orange */
.hljs-number,
.hljs-built_in,
.hljs-builtin-name,
.hljs-literal,
.hljs-type,
.hljs-params,
.hljs-meta,
.hljs-link {
	color: #f5871f;
}

/* Tomorrow Yellow */
.hljs-attribute {
	color: #eab700;
}

/* Tomorrow Green */
.hljs-string,
.hljs-symbol,
.hljs-bullet,
.hljs-addition {
	color: #718c00;
}

/* Tomorrow Blue */
.hljs-title,
.hljs-section {
	color: #4271ae;
}

/* Tomorrow Purple */
.hljs-keyword,
.hljs-selector-tag {
	color: #8959a8;
}

.hljs {
	display: block;
	overflow-x: auto;
	color: #4d4d4c;
	padding: 0.5em;
}

.hljs-emphasis {
	font-style: italic;
}

.hljs-strong {
	font-weight: bold;
}
</style>

<style>
/*
 * Markdown PDF CSS
 */

 body {
	font-family: -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "Ubuntu", "Droid Sans", sans-serif, "Meiryo";
	padding: 0 12px;
}

pre {
	background-color: #f8f8f8;
	border: 1px solid #cccccc;
	border-radius: 3px;
	overflow-x: auto;
	white-space: pre-wrap;
	overflow-wrap: break-word;
}

pre:not(.hljs) {
	padding: 23px;
	line-height: 19px;
}

blockquote {
	background: rgba(127, 127, 127, 0.1);
	border-color: rgba(0, 122, 204, 0.5);
}

.emoji {
	height: 1.4em;
}

code {
	font-size: 14px;
	line-height: 19px;
}

/* for inline code */
:not(pre):not(.hljs) > code {
	color: #C9AE75; /* Change the old color so it seems less like an error */
	font-size: inherit;
}

/* Page Break : use <div class="page"/> to insert page break
-------------------------------------------------------- */
.page {
	page-break-after: always;
}

</style>

<script src="https://unpkg.com/mermaid/dist/mermaid.min.js"></script>
</head>
<body>
  <script>
    mermaid.initialize({
      startOnLoad: true,
      theme: document.body.classList.contains('vscode-dark') || document.body.classList.contains('vscode-high-contrast')
          ? 'dark'
          : 'default'
    });
  </script>
<h1 id="1instruction">1.Instruction</h1>
<ul>
<li>
<p>This library contains papers, codes and results of unsupervised transfer learning for classification tasks from all top conferences in recent three years.We only included results from the most commonly used open source datasets.You can click &quot;link&quot; to jump to the corresponding codes or papers, if there is one on the Internet, otherwise you will see a &quot;-&quot;.</p>
</li>
<li>
<p>In front of each table, you will see the backbone of the network used in this table.Different backbones are marked with '()'.</p>
</li>
<li>
<p>Welcome to correct mistakes or add new content.</p>
</li>
</ul>
<h1 id="2result">2.Result</h1>
<h2 id="21da">2.1.DA</h2>
<h3 id="211office-31">2.1.1.Office-31</h3>
<blockquote>
<p><strong>Backbone:</strong> <em>ResNet50</em></p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">A→W</th>
<th style="text-align:center">D→W</th>
<th style="text-align:center">W→D</th>
<th style="text-align:center">A→D</th>
<th style="text-align:center">D→A</th>
<th style="text-align:center">W→A</th>
<th style="text-align:center">Avg</th>
<th style="text-align:center">Conference</th>
<th style="text-align:center">Year</th>
<th style="text-align:center">Code Url</th>
<th style="text-align:center">Paper Url</th>
<th style="text-align:center">Title</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">JDDA-I</td>
<td style="text-align:center">82.1±0.3</td>
<td style="text-align:center">95.2±0.1</td>
<td style="text-align:center">99.7±0.0</td>
<td style="text-align:center">76.1±0.2</td>
<td style="text-align:center">56.9±0.0</td>
<td style="text-align:center">65.1±0.3</td>
<td style="text-align:center">79.2</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/A-bone1/JDDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080">link</a></td>
<td style="text-align:center">Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">JDDA-C</td>
<td style="text-align:center">82.6±0.4</td>
<td style="text-align:center">95.2±0.2</td>
<td style="text-align:center">99.7±0.0</td>
<td style="text-align:center">79.8±0.1</td>
<td style="text-align:center">57.4±0.0</td>
<td style="text-align:center">66.7±0.2</td>
<td style="text-align:center">80.2</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/A-bone1/JDDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080">link</a></td>
<td style="text-align:center">Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">PFAN(AlexNet)</td>
<td style="text-align:center">83.0±0.3</td>
<td style="text-align:center">99.0±0.2</td>
<td style="text-align:center">99.9±0.1</td>
<td style="text-align:center">76.3±0.3</td>
<td style="text-align:center">63.3±0.3</td>
<td style="text-align:center">60.8±0.5</td>
<td style="text-align:center">80.4</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/Xiewp/PFAN">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Progressive_Feature_Alignment_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Progressive Feature Alignment for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">GCAN</td>
<td style="text-align:center">82.7±0.1</td>
<td style="text-align:center">97.1±0.1</td>
<td style="text-align:center">99.8±0.1</td>
<td style="text-align:center">76.4±0.5</td>
<td style="text-align:center">64.9±0.1</td>
<td style="text-align:center">62.6±0.3</td>
<td style="text-align:center">80.6</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/Mid-Push/Moving-Semantic-Transfer-Network">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DM-ADA</td>
<td style="text-align:center">83.9±0.4</td>
<td style="text-align:center">99.8±0.1</td>
<td style="text-align:center">99.9±0.1</td>
<td style="text-align:center">77.5±0.2</td>
<td style="text-align:center">64.6±0.4</td>
<td style="text-align:center">64.0±0.5</td>
<td style="text-align:center">81.6</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/ChrisAllenMing/Mixup_for_UDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6123/5979">link</a></td>
<td style="text-align:center">Adversarial Domain Adaptation with Domain Mixup</td>
</tr>
<tr>
<td style="text-align:center">ETD</td>
<td style="text-align:center">92.1</td>
<td style="text-align:center">100.0</td>
<td style="text-align:center">100.0</td>
<td style="text-align:center">88.0</td>
<td style="text-align:center">71.0</td>
<td style="text-align:center">67.8</td>
<td style="text-align:center">86.2</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/yimzhai3/ETD">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Enhanced Transport Distance for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">KHoMM</td>
<td style="text-align:center">91.7±0.3</td>
<td style="text-align:center">98.9±0.0</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">89.1±0.3</td>
<td style="text-align:center">71.2±0.2</td>
<td style="text-align:center">70.6±0.3</td>
<td style="text-align:center">86.9</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/chenchao666/HoMM-Master">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5745/5601">link</a></td>
<td style="text-align:center">HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">CADA-W</td>
<td style="text-align:center">93.9±0.1</td>
<td style="text-align:center">99.1±0.2</td>
<td style="text-align:center">99.6±0.2</td>
<td style="text-align:center">93.2±0.3</td>
<td style="text-align:center">68.9±0.1</td>
<td style="text-align:center">68.3±0.2</td>
<td style="text-align:center">87.2</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://delta-lab-iitk.github.io/CADA/">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Attending to Discriminative Certainty for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">RDA</td>
<td style="text-align:center">95.1</td>
<td style="text-align:center">97.8</td>
<td style="text-align:center">99.8</td>
<td style="text-align:center">89.4</td>
<td style="text-align:center">72.4</td>
<td style="text-align:center">68.4</td>
<td style="text-align:center">87.2</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/zhyhan/RDA">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2004.12529">link</a></td>
<td style="text-align:center">Towards Accurate and Robust Domain Adaptation under Noisy Environments</td>
</tr>
<tr>
<td style="text-align:center">rRevGrad+CAT</td>
<td style="text-align:center">94.4±0.1</td>
<td style="text-align:center">98.0±0.2</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">90.8±1.8</td>
<td style="text-align:center">72.2±0.6</td>
<td style="text-align:center">70.2±0.1</td>
<td style="text-align:center">87.6</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thudzj/CAT">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Cluster_Alignment_With_a_Teacher_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf">link</a></td>
<td style="text-align:center">Cluster Alignment with a Teacher for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SAFN+ENT*</td>
<td style="text-align:center">90.3</td>
<td style="text-align:center">98.7</td>
<td style="text-align:center">100.0</td>
<td style="text-align:center">92.1</td>
<td style="text-align:center">73.4</td>
<td style="text-align:center">71.2</td>
<td style="text-align:center">87.6</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/jihanyang/AFN">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf">link</a></td>
<td style="text-align:center">Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BSP+DANN</td>
<td style="text-align:center">93.0±0.2</td>
<td style="text-align:center">98.0±0.2</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">90.0±0.4</td>
<td style="text-align:center">71.9±0.3</td>
<td style="text-align:center">73.0±0.3</td>
<td style="text-align:center">87.7</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DEV</td>
<td style="text-align:center">93.2</td>
<td style="text-align:center">98.4</td>
<td style="text-align:center">100.0</td>
<td style="text-align:center">92.8</td>
<td style="text-align:center">70.9</td>
<td style="text-align:center">71.2</td>
<td style="text-align:center">87.8</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Deep-Embedded-Validation">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/you19a/you19a.pdf">link</a></td>
<td style="text-align:center">Towards Accurate Model Selection in Deep Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DMRL</td>
<td style="text-align:center">90.8±0.3</td>
<td style="text-align:center">99.0±0.2</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">93.4±0.5</td>
<td style="text-align:center">73.0±0.3</td>
<td style="text-align:center">71.2±0.3</td>
<td style="text-align:center">87.9</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.03141">link</a></td>
<td style="text-align:center">Dual Mixup Regularized Learning for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">MSTN+DSBN</td>
<td style="text-align:center">93.3</td>
<td style="text-align:center">99.1</td>
<td style="text-align:center">100.0</td>
<td style="text-align:center">90.8</td>
<td style="text-align:center">72.7</td>
<td style="text-align:center">73.9</td>
<td style="text-align:center">88.3</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/wgchang/DSBN">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Domain-Specific_Batch_Normalization_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Domain-Specifific Batch Normalization for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">TADA</td>
<td style="text-align:center">94.3±0.3</td>
<td style="text-align:center">98.7±0.1</td>
<td style="text-align:center">99.8±0.2</td>
<td style="text-align:center">91.6±0.3</td>
<td style="text-align:center">72.9±0.2</td>
<td style="text-align:center">73.0±0.3</td>
<td style="text-align:center">88.4</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/4472/4350">link</a></td>
<td style="text-align:center">Transferable Attention for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SymNets</td>
<td style="text-align:center">90.8±0.1</td>
<td style="text-align:center">98.8±0.3</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">93.9±0.5</td>
<td style="text-align:center">74.6±0.6</td>
<td style="text-align:center">72.5+0.5</td>
<td style="text-align:center">88.4</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="http://sites.scut.edu.cn/GPI/main.psp">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Domain-Symmetric_Networks_for_Adversarial_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Domain-Symmetric Networks for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BDG</td>
<td style="text-align:center">93.6±0.4</td>
<td style="text-align:center">99.0±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">93.6±0.3</td>
<td style="text-align:center">73.2±0.2</td>
<td style="text-align:center">72.0±0.1</td>
<td style="text-align:center">88.5</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/6137/5993">link</a></td>
<td style="text-align:center">Bi-Directional Generation for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">CADA-A</td>
<td style="text-align:center">96.8±0.2</td>
<td style="text-align:center">99.0±0.1</td>
<td style="text-align:center">99.8±0.1</td>
<td style="text-align:center">93.4±0.1</td>
<td style="text-align:center">71.7±0.2</td>
<td style="text-align:center">70.5±0.3</td>
<td style="text-align:center">88.5</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://delta-lab-iitk.github.io/CADA/">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Attending to Discriminative Certainty for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BSP+CDAN</td>
<td style="text-align:center">93.3±0.2</td>
<td style="text-align:center">98.2±0.2</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">93.0±0.2</td>
<td style="text-align:center">73.6±0.3</td>
<td style="text-align:center">72.6±0.3</td>
<td style="text-align:center">88.5</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">STAFF</td>
<td style="text-align:center">96.4</td>
<td style="text-align:center">99.6</td>
<td style="text-align:center">99.8</td>
<td style="text-align:center">94.0</td>
<td style="text-align:center">71.7</td>
<td style="text-align:center">70.2</td>
<td style="text-align:center">88.6</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/6629/6483">link</a></td>
<td style="text-align:center">Structure-Aware Feature Fusion for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SHOT</td>
<td style="text-align:center">90.1</td>
<td style="text-align:center">98.4</td>
<td style="text-align:center">99.9</td>
<td style="text-align:center">94.0</td>
<td style="text-align:center">74.7</td>
<td style="text-align:center">74.3</td>
<td style="text-align:center">88.6</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/tim-learn/SHOT">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v119/liang20a/liang20a.pdf">link</a></td>
<td style="text-align:center">Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">ALDA</td>
<td style="text-align:center">95.6±0.5</td>
<td style="text-align:center">97.7±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">94.0±0.4</td>
<td style="text-align:center">72.2±0.4</td>
<td style="text-align:center">72.5±0.2</td>
<td style="text-align:center">88.7</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/ZJULearning/ALDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613">link</a></td>
<td style="text-align:center">Adversarial-Learned Loss for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">MDD+Implicit Alignment</td>
<td style="text-align:center">90.3±0.2</td>
<td style="text-align:center">98.7±0.1</td>
<td style="text-align:center">99.8±0.0</td>
<td style="text-align:center">92.1±0.5</td>
<td style="text-align:center">75.3±0.2</td>
<td style="text-align:center">74.9±0.3</td>
<td style="text-align:center">88.8</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/xiangdal/implicit_alignment">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v119/jiang20d/jiang20d.pdf">link</a></td>
<td style="text-align:center">Implicit Class-Conditioned Domain Alignment for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">MDD</td>
<td style="text-align:center">94.5±0.3</td>
<td style="text-align:center">98.4±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">93.5±0.2</td>
<td style="text-align:center">74.6±0.3</td>
<td style="text-align:center">72.2±0.1</td>
<td style="text-align:center">88.9</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/MDD">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/zhang19i/zhang19i.pdf">link</a></td>
<td style="text-align:center">Bridging Theory and Algorithm for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DADA</td>
<td style="text-align:center">92.3±0.1</td>
<td style="text-align:center">99.2±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">93.9±0.2</td>
<td style="text-align:center">74.4±0.1</td>
<td style="text-align:center">74.2±0.1</td>
<td style="text-align:center">89.0</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/huitangtang/DADA-AAAI2020">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/6054/5910">link</a></td>
<td style="text-align:center">Discriminative Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BCDM</td>
<td style="text-align:center">95.4±0.3</td>
<td style="text-align:center">98.6±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">93.8±0.3</td>
<td style="text-align:center">73.1±0.3</td>
<td style="text-align:center">73.0±0.2</td>
<td style="text-align:center">89.0</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2021</td>
<td style="text-align:center"><a href="https://github.com/BIT-DA/BCDM">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2012.06995">link</a></td>
<td style="text-align:center">Bi-Classififier Determinacy Maximization for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">Method1</td>
<td style="text-align:center">95.2</td>
<td style="text-align:center">98.6</td>
<td style="text-align:center">100.0</td>
<td style="text-align:center">91.7</td>
<td style="text-align:center">74.5</td>
<td style="text-align:center">73.7</td>
<td style="text-align:center">89.0</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2006.00223">link</a></td>
<td style="text-align:center">Self-adaptive Re-weighted Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">GVB-GD</td>
<td style="text-align:center">94.8±0.5</td>
<td style="text-align:center">98.7±0.3</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">95.0±0.4</td>
<td style="text-align:center">73.4±0.3</td>
<td style="text-align:center">73.7±0.3</td>
<td style="text-align:center">89.3</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/cuishuhao/GVB">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Gradually_Vanishing_Bridge_for_Adversarial_Domain_Adaptation_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Gradually Vanishing Bridge for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">MCC</td>
<td style="text-align:center">95.5±0.2</td>
<td style="text-align:center">98.6±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">94.4±0.3</td>
<td style="text-align:center">72.9±0.2</td>
<td style="text-align:center">74.9±0.3</td>
<td style="text-align:center">89.4</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/thuml/Versatile-Domain-Adaptation">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/1912.03699">link</a></td>
<td style="text-align:center">Minimum Class Confusion for Versatile Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">CADA-P</td>
<td style="text-align:center">97.0±0.2</td>
<td style="text-align:center">99.3±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">95.6±0.1</td>
<td style="text-align:center">71.5±0.2</td>
<td style="text-align:center">73.1±0.3</td>
<td style="text-align:center">89.5</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://delta-lab-iitk.github.io/CADA/">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Attending to Discriminative Certainty for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">GSDA</td>
<td style="text-align:center">95.7</td>
<td style="text-align:center">99.1</td>
<td style="text-align:center">100.0</td>
<td style="text-align:center">94.8</td>
<td style="text-align:center">73.5</td>
<td style="text-align:center">74.9</td>
<td style="text-align:center">89.7</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Unsupervised_Domain_Adaptation_With_Hierarchical_Gradient_Synchronization_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation with Hierarchical Gradient Synchronization</td>
</tr>
<tr>
<td style="text-align:center">d-SNE(ResNet101)</td>
<td style="text-align:center">96.58±0.14</td>
<td style="text-align:center">99.10±0.24</td>
<td style="text-align:center">100.00±0.00</td>
<td style="text-align:center">94.60±0.39</td>
<td style="text-align:center">75.51±0.44</td>
<td style="text-align:center">74.20±0.24</td>
<td style="text-align:center">90.01</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/aws-samples/d-SNE">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_d-SNE_Domain_Adaptation_Using_Stochastic_Neighborhood_Embedding_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">d-SNE: Domain Adaptation using Stochastic Neighborhood Embedding</td>
</tr>
<tr>
<td style="text-align:center">E-MixNet</td>
<td style="text-align:center">93.0±0.3</td>
<td style="text-align:center">99.0±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">95.6±0.2</td>
<td style="text-align:center">78.9±0.5</td>
<td style="text-align:center">74.7±0.7</td>
<td style="text-align:center">90.2</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2021</td>
<td style="text-align:center"><a href="https://github.com/zhonglii/E-MixNet">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2101.01104">link</a></td>
<td style="text-align:center">How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches?</td>
</tr>
<tr>
<td style="text-align:center">RSDA-DANN</td>
<td style="text-align:center">95.3±0.3</td>
<td style="text-align:center">99.3±0.2</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">95.2±0.2</td>
<td style="text-align:center">77.4±0.8</td>
<td style="text-align:center">76.0±0.6</td>
<td style="text-align:center">90.2</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/XJTU-XGU/RSDA">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Spherical Space Domain Adaptation with Robust Pseudo-label Loss</td>
</tr>
<tr>
<td style="text-align:center">CAN</td>
<td style="text-align:center">94.5±0.3</td>
<td style="text-align:center">99.1±0.2</td>
<td style="text-align:center">99.8±0.2</td>
<td style="text-align:center">95.0±0.3</td>
<td style="text-align:center">78.0±0.3</td>
<td style="text-align:center">77.0±0.3</td>
<td style="text-align:center">90.6</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/kgl-prml/Contrastive-Adaptation-Network-for-Unsupervised-Domain-Adaptation">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Kang_Contrastive_Adaptation_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Contrastive Adaptation Network for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">RWOT</td>
<td style="text-align:center">95.1±0.2</td>
<td style="text-align:center">99.5±0.2</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">94.5±0.2</td>
<td style="text-align:center">77.5±0.1</td>
<td style="text-align:center">77.9±0.3</td>
<td style="text-align:center">90.8</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SRDC</td>
<td style="text-align:center">95.7±0.2</td>
<td style="text-align:center">99.2±0.1</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">95.8±0.2</td>
<td style="text-align:center">76.7±0.3</td>
<td style="text-align:center">77.1±0.1</td>
<td style="text-align:center">90.8</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/huitangtang/SRDC-CVPR2020">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Unsupervised_Domain_Adaptation_via_Structurally_Regularized_Deep_Clustering_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering</td>
</tr>
<tr>
<td style="text-align:center">RSDA-MSTN</td>
<td style="text-align:center">96.1±0.2</td>
<td style="text-align:center">99.3±0.2</td>
<td style="text-align:center">100.0±0.0</td>
<td style="text-align:center">95.8±0.3</td>
<td style="text-align:center">77.4±0.8</td>
<td style="text-align:center">78.9±0.3</td>
<td style="text-align:center">91.1</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/XJTU-XGU/RSDA">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Spherical Space Domain Adaptation with Robust Pseudo-label Loss</td>
</tr>
</tbody>
</table>
<h3 id="212office-home">2.1.2.Office-Home</h3>
<blockquote>
<p><strong>Backbone:</strong> <em>ResNet50</em></p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">Ar→Cl</th>
<th style="text-align:center">Ar→Pr</th>
<th style="text-align:center">Ar→Rw</th>
<th style="text-align:center">Cl→Ar</th>
<th style="text-align:center">Cl→Pr</th>
<th style="text-align:center">Cl→Rw</th>
<th style="text-align:center">Pr→Ar</th>
<th style="text-align:center">Pr→Cl</th>
<th style="text-align:center">Pr→Rw</th>
<th style="text-align:center">Rw→Ar</th>
<th style="text-align:center">Rw→Cl</th>
<th style="text-align:center">Rw→Pr</th>
<th style="text-align:center">Avg</th>
<th style="text-align:center">Conference</th>
<th style="text-align:center">Year</th>
<th style="text-align:center">Code Url</th>
<th style="text-align:center">Paper Url</th>
<th style="text-align:center">Title</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">GCAN</td>
<td style="text-align:center">36.43</td>
<td style="text-align:center">47.25</td>
<td style="text-align:center">61.08</td>
<td style="text-align:center">37.90</td>
<td style="text-align:center">58.25</td>
<td style="text-align:center">57.00</td>
<td style="text-align:center">35.77</td>
<td style="text-align:center">42.66</td>
<td style="text-align:center">64.47</td>
<td style="text-align:center">50.08</td>
<td style="text-align:center">49.12</td>
<td style="text-align:center">72.53</td>
<td style="text-align:center">51.05</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/Mid-Push/Moving-Semantic-Transfer-Network">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center"></td>
</tr>
<tr>
<td style="text-align:center">Method2</td>
<td style="text-align:center">40.3</td>
<td style="text-align:center">51.6</td>
<td style="text-align:center">61.5</td>
<td style="text-align:center">37.9</td>
<td style="text-align:center">58.0</td>
<td style="text-align:center">58.6</td>
<td style="text-align:center">33.6</td>
<td style="text-align:center">45.9</td>
<td style="text-align:center">61.8</td>
<td style="text-align:center">50.1</td>
<td style="text-align:center">50.9</td>
<td style="text-align:center">71.7</td>
<td style="text-align:center">51.8</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/1906.09693">link</a></td>
<td style="text-align:center">Bayesian Uncertainty Matching for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">LFP</td>
<td style="text-align:center">41.53</td>
<td style="text-align:center">53.66</td>
<td style="text-align:center">64.90</td>
<td style="text-align:center">41.53</td>
<td style="text-align:center">54.57</td>
<td style="text-align:center">57.66</td>
<td style="text-align:center">38.87</td>
<td style="text-align:center">40.08</td>
<td style="text-align:center">65.97</td>
<td style="text-align:center">55.13</td>
<td style="text-align:center">47.18</td>
<td style="text-align:center">76.02</td>
<td style="text-align:center">53.10</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/4479/4357">link</a></td>
<td style="text-align:center">Exploiting Local Feature Patterns for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DPDA</td>
<td style="text-align:center">39.2</td>
<td style="text-align:center">54.4</td>
<td style="text-align:center">61.4</td>
<td style="text-align:center">50.3</td>
<td style="text-align:center">57.8</td>
<td style="text-align:center">59.9</td>
<td style="text-align:center">53.5</td>
<td style="text-align:center">40.7</td>
<td style="text-align:center">67.9</td>
<td style="text-align:center">59.4</td>
<td style="text-align:center">43.8</td>
<td style="text-align:center">68.7</td>
<td style="text-align:center">54.8</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://pdfs.semanticscholar.org/77d7/a7b36abc7cd3cf0ef492183469abb0342cc1.pdf">link</a></td>
<td style="text-align:center">Differentially Private Optimal Transport: Application to Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">RDA</td>
<td style="text-align:center">50.8</td>
<td style="text-align:center">68.7</td>
<td style="text-align:center">72.3</td>
<td style="text-align:center">55.6</td>
<td style="text-align:center">67.4</td>
<td style="text-align:center">67.9</td>
<td style="text-align:center">57.8</td>
<td style="text-align:center">50.5</td>
<td style="text-align:center">74.6</td>
<td style="text-align:center">69.5</td>
<td style="text-align:center">57.7</td>
<td style="text-align:center">80.2</td>
<td style="text-align:center">64.4</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/zhyhan/RDA">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2004.12529">link</a></td>
<td style="text-align:center">Towards Accurate and Robust Domain Adaptation under Noisy Environments</td>
</tr>
<tr>
<td style="text-align:center">BSP+DANN</td>
<td style="text-align:center">51.4</td>
<td style="text-align:center">68.3</td>
<td style="text-align:center">75.9</td>
<td style="text-align:center">56.0</td>
<td style="text-align:center">67.8</td>
<td style="text-align:center">68.8</td>
<td style="text-align:center">57.0</td>
<td style="text-align:center">49.6</td>
<td style="text-align:center">75.8</td>
<td style="text-align:center">70.4</td>
<td style="text-align:center">57.1</td>
<td style="text-align:center">80.6</td>
<td style="text-align:center">64.9</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DWT-MEC</td>
<td style="text-align:center">50.3</td>
<td style="text-align:center">72.1</td>
<td style="text-align:center">77.0</td>
<td style="text-align:center">59.6</td>
<td style="text-align:center">69.3</td>
<td style="text-align:center">70.2</td>
<td style="text-align:center">58.3</td>
<td style="text-align:center">48.1</td>
<td style="text-align:center">77.3</td>
<td style="text-align:center">69.3</td>
<td style="text-align:center">53.6</td>
<td style="text-align:center">82.0</td>
<td style="text-align:center">65.6</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/roysubhankar/dwt-domain-adaptation">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Roy_Unsupervised_Domain_Adaptation_Using_Feature-Whitening_and_Consensus_Loss_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation using Feature-Whitening and Consensus Loss</td>
</tr>
<tr>
<td style="text-align:center">BSP+CDAN</td>
<td style="text-align:center">52.0</td>
<td style="text-align:center">68.6</td>
<td style="text-align:center">76.1</td>
<td style="text-align:center">58.0</td>
<td style="text-align:center">70.3</td>
<td style="text-align:center">70.2</td>
<td style="text-align:center">58.6</td>
<td style="text-align:center">50.2</td>
<td style="text-align:center">77.6</td>
<td style="text-align:center">72.2</td>
<td style="text-align:center">59.3</td>
<td style="text-align:center">81.9</td>
<td style="text-align:center">66.3</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">ALDA</td>
<td style="text-align:center">53.7</td>
<td style="text-align:center">70.1</td>
<td style="text-align:center">76.4</td>
<td style="text-align:center">60.2</td>
<td style="text-align:center">72.6</td>
<td style="text-align:center">71.5</td>
<td style="text-align:center">56.8</td>
<td style="text-align:center">51.9</td>
<td style="text-align:center">77.1</td>
<td style="text-align:center">70.2</td>
<td style="text-align:center">56.3</td>
<td style="text-align:center">82.1</td>
<td style="text-align:center">66.6</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/ZJULearning/ALDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613">link</a></td>
<td style="text-align:center">Adversarial-Learned Loss for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">AADA+CCN</td>
<td style="text-align:center">50.4</td>
<td style="text-align:center">71.3</td>
<td style="text-align:center">77.5</td>
<td style="text-align:center">60.8</td>
<td style="text-align:center">70.8</td>
<td style="text-align:center">71.2</td>
<td style="text-align:center">59.1</td>
<td style="text-align:center">51.8</td>
<td style="text-align:center">76.9</td>
<td style="text-align:center">71.0</td>
<td style="text-align:center">57.4</td>
<td style="text-align:center">81.8</td>
<td style="text-align:center">67.0</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690579.pdf">link</a></td>
<td style="text-align:center">Mind the Discriminability:Asymmetric Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">ETD</td>
<td style="text-align:center">51.3</td>
<td style="text-align:center">71.9</td>
<td style="text-align:center">85.7</td>
<td style="text-align:center">57.6</td>
<td style="text-align:center">69.2</td>
<td style="text-align:center">73.7</td>
<td style="text-align:center">57.8</td>
<td style="text-align:center">51.2</td>
<td style="text-align:center">79.3</td>
<td style="text-align:center">70.2</td>
<td style="text-align:center">57.5</td>
<td style="text-align:center">82.1</td>
<td style="text-align:center">67.3</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/yimzhai3/ETD">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Enhanced Transport Distance for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">TADA</td>
<td style="text-align:center">53.1</td>
<td style="text-align:center">72.3</td>
<td style="text-align:center">77.2</td>
<td style="text-align:center">59.1</td>
<td style="text-align:center">71.2</td>
<td style="text-align:center">72.1</td>
<td style="text-align:center">59.7</td>
<td style="text-align:center">53.1</td>
<td style="text-align:center">78.4</td>
<td style="text-align:center">72.4</td>
<td style="text-align:center">60.0</td>
<td style="text-align:center">82.9</td>
<td style="text-align:center">67.6</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/4472/4350">link</a></td>
<td style="text-align:center">Transferable Attention for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SymNets</td>
<td style="text-align:center">47.7</td>
<td style="text-align:center">72.9</td>
<td style="text-align:center">78.5</td>
<td style="text-align:center">64.2</td>
<td style="text-align:center">71.3</td>
<td style="text-align:center">74.2</td>
<td style="text-align:center">64.2</td>
<td style="text-align:center">48.8</td>
<td style="text-align:center">79.5</td>
<td style="text-align:center">74.5</td>
<td style="text-align:center">52.6</td>
<td style="text-align:center">82.7</td>
<td style="text-align:center">67.6</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="http://sites.scut.edu.cn/GPI/main.psp">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Domain-Symmetric_Networks_for_Adversarial_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Domain-Symmetric Networks for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DRMEA</td>
<td style="text-align:center">52.3</td>
<td style="text-align:center">73.0</td>
<td style="text-align:center">77.3</td>
<td style="text-align:center">64.3</td>
<td style="text-align:center">72.0</td>
<td style="text-align:center">71.8</td>
<td style="text-align:center">63.6</td>
<td style="text-align:center">52.7</td>
<td style="text-align:center">78.5</td>
<td style="text-align:center">72.0</td>
<td style="text-align:center">57.7</td>
<td style="text-align:center">81.6</td>
<td style="text-align:center">68.1</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/LavieLuo/DRMEA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5943/5799">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation via Discriminative Manifold Embedding and Alignment</td>
</tr>
<tr>
<td style="text-align:center">MDD</td>
<td style="text-align:center">54.9</td>
<td style="text-align:center">73.7</td>
<td style="text-align:center">77.8</td>
<td style="text-align:center">60.0</td>
<td style="text-align:center">71.4</td>
<td style="text-align:center">71.8</td>
<td style="text-align:center">61.2</td>
<td style="text-align:center">53.6</td>
<td style="text-align:center">78.1</td>
<td style="text-align:center">72.5</td>
<td style="text-align:center">60.2</td>
<td style="text-align:center">82.3</td>
<td style="text-align:center">68.1</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/MDD">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/zhang19i/zhang19i.pdf">link</a></td>
<td style="text-align:center">Bridging Theory and Algorithm for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">STAFF</td>
<td style="text-align:center">53.3</td>
<td style="text-align:center">71.9</td>
<td style="text-align:center">80.2</td>
<td style="text-align:center">63.1</td>
<td style="text-align:center">69.8</td>
<td style="text-align:center">74.1</td>
<td style="text-align:center">65.3</td>
<td style="text-align:center">50.9</td>
<td style="text-align:center">77.8</td>
<td style="text-align:center">73.1</td>
<td style="text-align:center">56.6</td>
<td style="text-align:center">82.4</td>
<td style="text-align:center">68.2</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/cuishuhao/HAD">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/6629/6483">link</a></td>
<td style="text-align:center">Structure-Aware Feature Fusion for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SAFN*</td>
<td style="text-align:center">54.4</td>
<td style="text-align:center">73.3</td>
<td style="text-align:center">77.9</td>
<td style="text-align:center">65.2</td>
<td style="text-align:center">71.5</td>
<td style="text-align:center">73.2</td>
<td style="text-align:center">63.6</td>
<td style="text-align:center">52.6</td>
<td style="text-align:center">78.2</td>
<td style="text-align:center">72.3</td>
<td style="text-align:center">58.0</td>
<td style="text-align:center">82.1</td>
<td style="text-align:center">68.5</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/jihanyang/AFN">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf">link</a></td>
<td style="text-align:center">Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BDG</td>
<td style="text-align:center">51.5</td>
<td style="text-align:center">73.4</td>
<td style="text-align:center">78.7</td>
<td style="text-align:center">65.3</td>
<td style="text-align:center">71.5</td>
<td style="text-align:center">73.7</td>
<td style="text-align:center">65.1</td>
<td style="text-align:center">49.7</td>
<td style="text-align:center">81.1</td>
<td style="text-align:center">74.6</td>
<td style="text-align:center">55.1</td>
<td style="text-align:center">84.8</td>
<td style="text-align:center">68.7</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/6137/5993">link</a></td>
<td style="text-align:center">Bi-Directional Generation for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">Method3</td>
<td style="text-align:center">55.5</td>
<td style="text-align:center">73.5</td>
<td style="text-align:center">78.7</td>
<td style="text-align:center">60.7</td>
<td style="text-align:center">74.1</td>
<td style="text-align:center">73.1</td>
<td style="text-align:center">59.5</td>
<td style="text-align:center">55.0</td>
<td style="text-align:center">80.4</td>
<td style="text-align:center">72.4</td>
<td style="text-align:center">60.3</td>
<td style="text-align:center">84.3</td>
<td style="text-align:center">68.9</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2006.00223">link</a></td>
<td style="text-align:center">Self-adaptive Re-weighted Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">MDD+Implicit Alignment</td>
<td style="text-align:center">56.2</td>
<td style="text-align:center">77.9</td>
<td style="text-align:center">79.2</td>
<td style="text-align:center">64.4</td>
<td style="text-align:center">73.1</td>
<td style="text-align:center">74.4</td>
<td style="text-align:center">64.2</td>
<td style="text-align:center">54.2</td>
<td style="text-align:center">79.9</td>
<td style="text-align:center">71.2</td>
<td style="text-align:center">58.1</td>
<td style="text-align:center">83.1</td>
<td style="text-align:center">69.5</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/xiangdal/implicit_alignment">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v119/jiang20d/jiang20d.pdf">link</a></td>
<td style="text-align:center">Implicit Class-Conditioned Domain Alignment for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">RSDA-DANN</td>
<td style="text-align:center">51.5±0.5</td>
<td style="text-align:center">76.8±0.8</td>
<td style="text-align:center">81.1±0.2</td>
<td style="text-align:center">67.1±0.4</td>
<td style="text-align:center">72.1±0.2</td>
<td style="text-align:center">77.0±0.6</td>
<td style="text-align:center">64.2±0.3</td>
<td style="text-align:center">51.1±0.5</td>
<td style="text-align:center">81.8±0.6</td>
<td style="text-align:center">74.9±0.2</td>
<td style="text-align:center">55.9±0.2</td>
<td style="text-align:center">84.5±0.7</td>
<td style="text-align:center">69.8</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/XJTU-XGU/RSDA">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Spherical Space Domain Adaptation with Robust Pseudo-label Loss</td>
</tr>
<tr>
<td style="text-align:center">CADA-A</td>
<td style="text-align:center">56.9</td>
<td style="text-align:center">75.4</td>
<td style="text-align:center">80.2</td>
<td style="text-align:center">61.7</td>
<td style="text-align:center">74.6</td>
<td style="text-align:center">74.9</td>
<td style="text-align:center">62.9</td>
<td style="text-align:center">54.4</td>
<td style="text-align:center">80.9</td>
<td style="text-align:center">74.3</td>
<td style="text-align:center">61.1</td>
<td style="text-align:center">84.4</td>
<td style="text-align:center">70.1</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://delta-lab-iitk.github.io/CADA/">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Attending to Discriminative Certainty for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">CADA-P</td>
<td style="text-align:center">56.9</td>
<td style="text-align:center">76.4</td>
<td style="text-align:center">80.7</td>
<td style="text-align:center">61.3</td>
<td style="text-align:center">75.2</td>
<td style="text-align:center">75.2</td>
<td style="text-align:center">63.2</td>
<td style="text-align:center">54.5</td>
<td style="text-align:center">80.7</td>
<td style="text-align:center">73.9</td>
<td style="text-align:center">61.5</td>
<td style="text-align:center">84.1</td>
<td style="text-align:center">70.2</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://delta-lab-iitk.github.io/CADA/">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Attending to Discriminative Certainty for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">GSDA</td>
<td style="text-align:center">61.3</td>
<td style="text-align:center">76.1</td>
<td style="text-align:center">79.4</td>
<td style="text-align:center">65.4</td>
<td style="text-align:center">73.3</td>
<td style="text-align:center">74.3</td>
<td style="text-align:center">65.0</td>
<td style="text-align:center">53.2</td>
<td style="text-align:center">80.0</td>
<td style="text-align:center">72.2</td>
<td style="text-align:center">60.6</td>
<td style="text-align:center">83.1</td>
<td style="text-align:center">70.3</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Unsupervised_Domain_Adaptation_With_Hierarchical_Gradient_Synchronization_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation with Hierarchical Gradient Synchronization</td>
</tr>
<tr>
<td style="text-align:center">GVB-GD</td>
<td style="text-align:center">57.0</td>
<td style="text-align:center">74.7</td>
<td style="text-align:center">79.8</td>
<td style="text-align:center">64.6</td>
<td style="text-align:center">74.1</td>
<td style="text-align:center">74.6</td>
<td style="text-align:center">65.2</td>
<td style="text-align:center">55.1</td>
<td style="text-align:center">81.0</td>
<td style="text-align:center">74.6</td>
<td style="text-align:center">59.7</td>
<td style="text-align:center">84.3</td>
<td style="text-align:center">70.4</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/cuishuhao/GVB">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Gradually_Vanishing_Bridge_for_Adversarial_Domain_Adaptation_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Gradually Vanishing Bridge for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">E-MixNet</td>
<td style="text-align:center">57.7</td>
<td style="text-align:center">76.6</td>
<td style="text-align:center">79.8</td>
<td style="text-align:center">63.6</td>
<td style="text-align:center">74.1</td>
<td style="text-align:center">75.0</td>
<td style="text-align:center">63.4</td>
<td style="text-align:center">56.4</td>
<td style="text-align:center">79.7</td>
<td style="text-align:center">72.8</td>
<td style="text-align:center">62.4</td>
<td style="text-align:center">85.5</td>
<td style="text-align:center">70.6</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2021</td>
<td style="text-align:center"><a href="https://github.com/zhonglii/E-MixNet">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2101.01104">link</a></td>
<td style="text-align:center">How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches?</td>
</tr>
<tr>
<td style="text-align:center">RSDA-MSTN</td>
<td style="text-align:center">53.2±0.9</td>
<td style="text-align:center">77.7±1.0</td>
<td style="text-align:center">81.3±0.3</td>
<td style="text-align:center">66.4±0.6</td>
<td style="text-align:center">74.0±0.2</td>
<td style="text-align:center">76.5±0.6</td>
<td style="text-align:center">67.9±0.1</td>
<td style="text-align:center">53.0±0.1</td>
<td style="text-align:center">82.0±0.5</td>
<td style="text-align:center">75.8±0.6</td>
<td style="text-align:center">57.8±0.2</td>
<td style="text-align:center">85.4±0.3</td>
<td style="text-align:center">70.9</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/XJTU-XGU/RSDA">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Spherical Space Domain Adaptation with Robust Pseudo-label Loss</td>
</tr>
<tr>
<td style="text-align:center">HDAN</td>
<td style="text-align:center">56.8</td>
<td style="text-align:center">75.2</td>
<td style="text-align:center">79.8</td>
<td style="text-align:center">65.1</td>
<td style="text-align:center">73.9</td>
<td style="text-align:center">75.2</td>
<td style="text-align:center">66.3</td>
<td style="text-align:center">56.7</td>
<td style="text-align:center">81.8</td>
<td style="text-align:center">75.4</td>
<td style="text-align:center">59.7</td>
<td style="text-align:center">84.7</td>
<td style="text-align:center">70.9</td>
<td style="text-align:center">NeurIPS</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/cuishuhao/HAD">link</a></td>
<td style="text-align:center"></td>
<td style="text-align:center">Heuristic Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SRDC</td>
<td style="text-align:center">52.3</td>
<td style="text-align:center">76.3</td>
<td style="text-align:center">81.0</td>
<td style="text-align:center">69.5</td>
<td style="text-align:center">76.2</td>
<td style="text-align:center">78.0</td>
<td style="text-align:center">68.7</td>
<td style="text-align:center">53.8</td>
<td style="text-align:center">81.7</td>
<td style="text-align:center">76.3</td>
<td style="text-align:center">57.1</td>
<td style="text-align:center">85.0</td>
<td style="text-align:center">71.3</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/huitangtang/SRDC-CVPR2020">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Unsupervised_Domain_Adaptation_via_Structurally_Regularized_Deep_Clustering_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering</td>
</tr>
<tr>
<td style="text-align:center">SHOT</td>
<td style="text-align:center">57.1</td>
<td style="text-align:center">78.1</td>
<td style="text-align:center">81.5</td>
<td style="text-align:center">68.0</td>
<td style="text-align:center">78.2</td>
<td style="text-align:center">78.1</td>
<td style="text-align:center">67.4</td>
<td style="text-align:center">54.9</td>
<td style="text-align:center">82.2</td>
<td style="text-align:center">73.3</td>
<td style="text-align:center">58.8</td>
<td style="text-align:center">84.3</td>
<td style="text-align:center">71.8</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/tim-learn/SHOT">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v119/liang20a/liang20a.pdf">link</a></td>
<td style="text-align:center">Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation</td>
</tr>
</tbody>
</table>
<h3 id="213imageclef">2.1.3.ImageCLEF</h3>
<blockquote>
<p><strong>Backbone:</strong> <em>ResNet50</em></p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">I→P</th>
<th style="text-align:center">P→I</th>
<th style="text-align:center">I→C</th>
<th style="text-align:center">C→I</th>
<th style="text-align:center">C→P</th>
<th style="text-align:center">P→C</th>
<th style="text-align:center">Avg</th>
<th style="text-align:center">Conference</th>
<th style="text-align:center">Year</th>
<th style="text-align:center">Code Url</th>
<th style="text-align:center">Paper Url</th>
<th style="text-align:center">Title</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">GCAN</td>
<td style="text-align:center">68.2±0.5</td>
<td style="text-align:center">84.1±0.2</td>
<td style="text-align:center">92.2±0.1</td>
<td style="text-align:center">82.5±0.1</td>
<td style="text-align:center">67.2±0.2</td>
<td style="text-align:center">91.3±0.1</td>
<td style="text-align:center">80.9</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/Mid-Push/Moving-Semantic-Transfer-Network">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">PFAN</td>
<td style="text-align:center">68.5±0.5</td>
<td style="text-align:center">84.4±0.4</td>
<td style="text-align:center">92.2±0.6</td>
<td style="text-align:center">82.3±0.4</td>
<td style="text-align:center">66.3±0.3</td>
<td style="text-align:center">91.7±0.2</td>
<td style="text-align:center">80.9</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/Xiewp/PFAN">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Progressive_Feature_Alignment_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Progressive Feature Alignment for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">rGevGrad+CAT</td>
<td style="text-align:center">77.2±0.2</td>
<td style="text-align:center">91.0±0.3</td>
<td style="text-align:center">95.5±0.3</td>
<td style="text-align:center">91.3±0.3</td>
<td style="text-align:center">75.3±0.6</td>
<td style="text-align:center">93.6±0.5</td>
<td style="text-align:center">87.3</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thudzj/CAT">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Cluster_Alignment_With_a_Teacher_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf">link</a></td>
<td style="text-align:center">Cluster Alignment with a Teacher for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DMRL</td>
<td style="text-align:center">77.3±0.4</td>
<td style="text-align:center">90.7±0.3</td>
<td style="text-align:center">97.4±0.3</td>
<td style="text-align:center">91.8±0.3</td>
<td style="text-align:center">76.0±0.5</td>
<td style="text-align:center">94.8±0.3</td>
<td style="text-align:center">88.0</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.03141">link</a></td>
<td style="text-align:center">Dual Mixup Regularized Learning for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">CADA-A</td>
<td style="text-align:center">78.0</td>
<td style="text-align:center">91.5</td>
<td style="text-align:center">96.3</td>
<td style="text-align:center">91.0</td>
<td style="text-align:center">77.1</td>
<td style="text-align:center">95.3</td>
<td style="text-align:center">88.2</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://delta-lab-iitk.github.io/CADA/">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Attending to Discriminative Certainty for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">CADA-P</td>
<td style="text-align:center">78.0</td>
<td style="text-align:center">90.5</td>
<td style="text-align:center">96.7</td>
<td style="text-align:center">92.0</td>
<td style="text-align:center">77.2</td>
<td style="text-align:center">95.5</td>
<td style="text-align:center">88.3</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://delta-lab-iitk.github.io/CADA/">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Attending to Discriminative Certainty for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">AADA+CCN</td>
<td style="text-align:center">79.2</td>
<td style="text-align:center">92.5</td>
<td style="text-align:center">96.2</td>
<td style="text-align:center">91.4</td>
<td style="text-align:center">76.1</td>
<td style="text-align:center">94.7</td>
<td style="text-align:center">88.4</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690579.pdf">link</a></td>
<td style="text-align:center">Mind the Discriminability:Asymmetric Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">Method4</td>
<td style="text-align:center">78.3</td>
<td style="text-align:center">91.3</td>
<td style="text-align:center">96.7</td>
<td style="text-align:center">90.5</td>
<td style="text-align:center">78.1</td>
<td style="text-align:center">96.2</td>
<td style="text-align:center">88.5</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2006.00223">link</a></td>
<td style="text-align:center">Self-adaptive Re-weighted Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BCDM</td>
<td style="text-align:center">79.5</td>
<td style="text-align:center">93.2</td>
<td style="text-align:center">96.8</td>
<td style="text-align:center">91.3</td>
<td style="text-align:center">78.9</td>
<td style="text-align:center">95.8</td>
<td style="text-align:center">89.3</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2021</td>
<td style="text-align:center"><a href="https://github.com/BIT-DA/BCDM">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2012.06995">link</a></td>
<td style="text-align:center">Bi-Classififier Determinacy Maximization for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SAFN+ENT*</td>
<td style="text-align:center">80.2</td>
<td style="text-align:center">93.8</td>
<td style="text-align:center">96.7</td>
<td style="text-align:center">92.8</td>
<td style="text-align:center">78.4</td>
<td style="text-align:center">95.7</td>
<td style="text-align:center">89.6</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/jihanyang/AFN">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf">link</a></td>
<td style="text-align:center">Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">ETD</td>
<td style="text-align:center">81.0</td>
<td style="text-align:center">91.7</td>
<td style="text-align:center">97.9</td>
<td style="text-align:center">93.3</td>
<td style="text-align:center">79.5</td>
<td style="text-align:center">95.0</td>
<td style="text-align:center">89.7</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/yimzhai3/ETD">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Enhanced Transport Distance for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SymNets</td>
<td style="text-align:center">80.2±0.3</td>
<td style="text-align:center">93.6±0.2</td>
<td style="text-align:center">97.0±0.3</td>
<td style="text-align:center">93.4±0.3</td>
<td style="text-align:center">78.7±0.3</td>
<td style="text-align:center">96.4±0.1</td>
<td style="text-align:center">89.9</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="http://sites.scut.edu.cn/GPI/main.psp">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Domain-Symmetric_Networks_for_Adversarial_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Domain-Symmetric Networks for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">RSDA-DANN</td>
<td style="text-align:center">79.2±0.4</td>
<td style="text-align:center">93.0±0.2</td>
<td style="text-align:center">98.3±0.4</td>
<td style="text-align:center">93.6±0.4</td>
<td style="text-align:center">78.5±0.3</td>
<td style="text-align:center">98.2±0.2</td>
<td style="text-align:center">90.1</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/XJTU-XGU/RSDA">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Spherical Space Domain Adaptation with Robust Pseudo-label Loss</td>
</tr>
<tr>
<td style="text-align:center">RSDA-MSTN</td>
<td style="text-align:center">79.8±0.2</td>
<td style="text-align:center">94.5±0.5</td>
<td style="text-align:center">98.0±0.4</td>
<td style="text-align:center">94.2±0.4</td>
<td style="text-align:center">79.2±0.3</td>
<td style="text-align:center">97.3±0.3</td>
<td style="text-align:center">90.5</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/XJTU-XGU/RSDA">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Spherical Space Domain Adaptation with Robust Pseudo-label Loss</td>
</tr>
<tr>
<td style="text-align:center">SRDC</td>
<td style="text-align:center">80.8±0.3</td>
<td style="text-align:center">94.7±0.2</td>
<td style="text-align:center">97.8±0.2</td>
<td style="text-align:center">94.1±0.2</td>
<td style="text-align:center">80.0±0.3</td>
<td style="text-align:center">97.7±0.1</td>
<td style="text-align:center">90.9</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/huitangtang/SRDC-CVPR2020">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Unsupervised_Domain_Adaptation_via_Structurally_Regularized_Deep_Clustering_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering</td>
</tr>
<tr>
<td style="text-align:center">E-MixNet</td>
<td style="text-align:center">80.5±0.4</td>
<td style="text-align:center">96.0±0.1</td>
<td style="text-align:center">97.7±0.3</td>
<td style="text-align:center">95.2±0.4</td>
<td style="text-align:center">79.9±0.2</td>
<td style="text-align:center">97.0±0.3</td>
<td style="text-align:center">91.0</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2021</td>
<td style="text-align:center"><a href="https://github.com/zhonglii/E-MixNet">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2101.01104">link</a></td>
<td style="text-align:center">How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches?</td>
</tr>
</tbody>
</table>
<h3 id="214visda-2007visda-c">2.1.4.VisDA-2007(VisDA-C)</h3>
<blockquote>
<p><strong>Backbone:</strong> <em>ResNet101</em></p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">plane</th>
<th style="text-align:center">bcycl</th>
<th style="text-align:center">bus</th>
<th style="text-align:center">car</th>
<th style="text-align:center">house</th>
<th style="text-align:center">knife</th>
<th style="text-align:center">mcycl</th>
<th style="text-align:center">person</th>
<th style="text-align:center">plant</th>
<th style="text-align:center">sktbrd</th>
<th style="text-align:center">train</th>
<th style="text-align:center">truck</th>
<th style="text-align:center">Avg</th>
<th style="text-align:center">Congerence</th>
<th style="text-align:center">Year</th>
<th style="text-align:center">Code Url</th>
<th style="text-align:center">Paper Url</th>
<th style="text-align:center">Title</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">DPDA</td>
<td style="text-align:center">88.5</td>
<td style="text-align:center">66.2</td>
<td style="text-align:center">75.8</td>
<td style="text-align:center">59.1</td>
<td style="text-align:center">86.5</td>
<td style="text-align:center">70.4</td>
<td style="text-align:center">69.9</td>
<td style="text-align:center">71.6</td>
<td style="text-align:center">75.9</td>
<td style="text-align:center">49.3</td>
<td style="text-align:center">86.8</td>
<td style="text-align:center">39.5</td>
<td style="text-align:center">68.8</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://pdfs.semanticscholar.org/77d7/a7b36abc7cd3cf0ef492183469abb0342cc1.pdf">link</a></td>
<td style="text-align:center">Differentially Private Optimal Transport: Application to Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BSP+DANN</td>
<td style="text-align:center">92.2</td>
<td style="text-align:center">72.5</td>
<td style="text-align:center">83.8</td>
<td style="text-align:center">47.5</td>
<td style="text-align:center">87.0</td>
<td style="text-align:center">54.0</td>
<td style="text-align:center">86.8</td>
<td style="text-align:center">72.4</td>
<td style="text-align:center">80.6</td>
<td style="text-align:center">66.9</td>
<td style="text-align:center">84.5</td>
<td style="text-align:center">37.1</td>
<td style="text-align:center">72.1</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DEV</td>
<td style="text-align:center">81.8</td>
<td style="text-align:center">53.5</td>
<td style="text-align:center">83.0</td>
<td style="text-align:center">71.6</td>
<td style="text-align:center">89.2</td>
<td style="text-align:center">72.0</td>
<td style="text-align:center">89.4</td>
<td style="text-align:center">75.7</td>
<td style="text-align:center">97.0</td>
<td style="text-align:center">55.5</td>
<td style="text-align:center">71.2</td>
<td style="text-align:center">29.2</td>
<td style="text-align:center">72.4</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Deep-Embedded-Validation">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/you19a/you19a.pdf">link</a></td>
<td style="text-align:center">Towards Accurate Model Selection in Deep Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">GPDA</td>
<td style="text-align:center">83.0</td>
<td style="text-align:center">74.3</td>
<td style="text-align:center">80.4</td>
<td style="text-align:center">66.0</td>
<td style="text-align:center">87.6</td>
<td style="text-align:center">75.3</td>
<td style="text-align:center">83.8</td>
<td style="text-align:center">73.1</td>
<td style="text-align:center">90.1</td>
<td style="text-align:center">57.3</td>
<td style="text-align:center">80.2</td>
<td style="text-align:center">37.9</td>
<td style="text-align:center">73.3</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/seqam-lab/GPDA">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Unsupervised_Visual_Domain_Adaptation_A_Deep_Max-Margin_Gaussian_Process_Approach_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Visual Domain Adaptation:A Deep Max-Margin Gaussian Process Approach</td>
</tr>
<tr>
<td style="text-align:center">DMRL</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">75.5</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.03141">link</a></td>
<td style="text-align:center">Dual Mixup Regularized Learning for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DM-ADA(ResNet50)</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">-</td>
<td style="text-align:center">75.6</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/ChrisAllenMing/Mixup_for_UDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6123/5979">link</a></td>
<td style="text-align:center">Adversarial Domain Adaptation with Domain Mixup</td>
</tr>
<tr>
<td style="text-align:center">BSP+CDAN</td>
<td style="text-align:center">92.4</td>
<td style="text-align:center">61.0</td>
<td style="text-align:center">81.0</td>
<td style="text-align:center">57.5</td>
<td style="text-align:center">89.0</td>
<td style="text-align:center">80.6</td>
<td style="text-align:center">90.1</td>
<td style="text-align:center">77.0</td>
<td style="text-align:center">84.2</td>
<td style="text-align:center">77.9</td>
<td style="text-align:center">82.1</td>
<td style="text-align:center">38.4</td>
<td style="text-align:center">75.9</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SAFN</td>
<td style="text-align:center">93.6±0.2</td>
<td style="text-align:center">61.3±0.4</td>
<td style="text-align:center">84.1±0.5</td>
<td style="text-align:center">70.6±2.2</td>
<td style="text-align:center">94.1±0.5</td>
<td style="text-align:center">79.0±4.1</td>
<td style="text-align:center">91.8±0.5</td>
<td style="text-align:center">79.6±1.3</td>
<td style="text-align:center">89.9±0.7</td>
<td style="text-align:center">55.6±3.4</td>
<td style="text-align:center">89.0±0.3</td>
<td style="text-align:center">24.4±2.9</td>
<td style="text-align:center">76.1</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/jihanyang/AFN">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf">link</a></td>
<td style="text-align:center">Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">ALDA(ResNet50)</td>
<td style="text-align:center">87.0</td>
<td style="text-align:center">61.3</td>
<td style="text-align:center">78.7</td>
<td style="text-align:center">67.9</td>
<td style="text-align:center">83.7</td>
<td style="text-align:center">89.4</td>
<td style="text-align:center">89.5</td>
<td style="text-align:center">71.0</td>
<td style="text-align:center">95.4</td>
<td style="text-align:center">71.9</td>
<td style="text-align:center">89.6</td>
<td style="text-align:center">33.1</td>
<td style="text-align:center">76.5</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/ZJULearning/ALDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613">link</a></td>
<td style="text-align:center">Adversarial-Learned Loss for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">ALDA</td>
<td style="text-align:center">93.8</td>
<td style="text-align:center">74.1</td>
<td style="text-align:center">82.4</td>
<td style="text-align:center">69.4</td>
<td style="text-align:center">90.6</td>
<td style="text-align:center">87.2</td>
<td style="text-align:center">89.0</td>
<td style="text-align:center">67.6</td>
<td style="text-align:center">93.4</td>
<td style="text-align:center">76.1</td>
<td style="text-align:center">87.7</td>
<td style="text-align:center">22.2</td>
<td style="text-align:center">77.8</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/ZJULearning/ALDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613">link</a></td>
<td style="text-align:center">Adversarial-Learned Loss for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">MCC</td>
<td style="text-align:center">88.1</td>
<td style="text-align:center">80.3</td>
<td style="text-align:center">80.5</td>
<td style="text-align:center">71.5</td>
<td style="text-align:center">90.1</td>
<td style="text-align:center">93.2</td>
<td style="text-align:center">85.0</td>
<td style="text-align:center">71.6</td>
<td style="text-align:center">89.4</td>
<td style="text-align:center">73.8</td>
<td style="text-align:center">85.0</td>
<td style="text-align:center">36.9</td>
<td style="text-align:center">78.8</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/thuml/Versatile-Domain-Adaptation">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/1912.03699">link</a></td>
<td style="text-align:center">Minimum Class Confusion for Versatile Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DRMEA</td>
<td style="text-align:center">92.1</td>
<td style="text-align:center">75.0</td>
<td style="text-align:center">78.9</td>
<td style="text-align:center">75.5</td>
<td style="text-align:center">91.2</td>
<td style="text-align:center">81.9</td>
<td style="text-align:center">89.0</td>
<td style="text-align:center">77.2</td>
<td style="text-align:center">93.3</td>
<td style="text-align:center">77.4</td>
<td style="text-align:center">84.8</td>
<td style="text-align:center">35.1</td>
<td style="text-align:center">79.3</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/LavieLuo/DRMEA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5943/5799">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation via Discriminative Manifold Embedding and Alignment</td>
</tr>
<tr>
<td style="text-align:center">MSTN+DSBN</td>
<td style="text-align:center">94.7</td>
<td style="text-align:center">86.7</td>
<td style="text-align:center">76.0</td>
<td style="text-align:center">72.0</td>
<td style="text-align:center">95.2</td>
<td style="text-align:center">75.1</td>
<td style="text-align:center">87.9</td>
<td style="text-align:center">81.3</td>
<td style="text-align:center">91.1</td>
<td style="text-align:center">68.9</td>
<td style="text-align:center">88.3</td>
<td style="text-align:center">45.5</td>
<td style="text-align:center">80.2</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/wgchang/DSBN">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Domain-Specific_Batch_Normalization_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Domain-Specifific Batch Normalization for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">TPN</td>
<td style="text-align:center">93.7</td>
<td style="text-align:center">85.1</td>
<td style="text-align:center">69.2</td>
<td style="text-align:center">81.6</td>
<td style="text-align:center">93.5</td>
<td style="text-align:center">61.9</td>
<td style="text-align:center">89.3</td>
<td style="text-align:center">81.4</td>
<td style="text-align:center">93.5</td>
<td style="text-align:center">81.6</td>
<td style="text-align:center">84.5</td>
<td style="text-align:center">49.9</td>
<td style="text-align:center">80.4</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/decisionforce/TPN">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Pan_Transferrable_Prototypical_Networks_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Transferrable Prototypical Networks for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">GSDA</td>
<td style="text-align:center">93.1</td>
<td style="text-align:center">67.8</td>
<td style="text-align:center">83.1</td>
<td style="text-align:center">83.4</td>
<td style="text-align:center">94.7</td>
<td style="text-align:center">93.4</td>
<td style="text-align:center">93.4</td>
<td style="text-align:center">79.5</td>
<td style="text-align:center">93.0</td>
<td style="text-align:center">88.8</td>
<td style="text-align:center">83.4</td>
<td style="text-align:center">36.7</td>
<td style="text-align:center">81.5</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Unsupervised_Domain_Adaptation_With_Hierarchical_Gradient_Synchronization_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation with Hierarchical Gradient Synchronization</td>
</tr>
<tr>
<td style="text-align:center">SHOT</td>
<td style="text-align:center">94.3</td>
<td style="text-align:center">88.5</td>
<td style="text-align:center">80.1</td>
<td style="text-align:center">57.3</td>
<td style="text-align:center">93.1</td>
<td style="text-align:center">94.9</td>
<td style="text-align:center">80.7</td>
<td style="text-align:center">80.3</td>
<td style="text-align:center">91.5</td>
<td style="text-align:center">89.1</td>
<td style="text-align:center">86.3</td>
<td style="text-align:center">58.2</td>
<td style="text-align:center">82.9</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/tim-learn/SHOT">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v119/liang20a/liang20a.pdf">link</a></td>
<td style="text-align:center">Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BCDM</td>
<td style="text-align:center">95.1</td>
<td style="text-align:center">87.6</td>
<td style="text-align:center">81.2</td>
<td style="text-align:center">73.2</td>
<td style="text-align:center">92.7</td>
<td style="text-align:center">95.4</td>
<td style="text-align:center">86.9</td>
<td style="text-align:center">82.5</td>
<td style="text-align:center">95.1</td>
<td style="text-align:center">84.8</td>
<td style="text-align:center">88.1</td>
<td style="text-align:center">39.5</td>
<td style="text-align:center">83.4</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/BIT-DA/BCDM">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2012.06995">link</a></td>
<td style="text-align:center">Bi-Classififier Determinacy Maximization for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">RWOT</td>
<td style="text-align:center">95.1</td>
<td style="text-align:center">80.3</td>
<td style="text-align:center">83.7</td>
<td style="text-align:center">90.0</td>
<td style="text-align:center">92.4</td>
<td style="text-align:center">68.0</td>
<td style="text-align:center">92.5</td>
<td style="text-align:center">82.2</td>
<td style="text-align:center">87.9</td>
<td style="text-align:center">78.4</td>
<td style="text-align:center">90.4</td>
<td style="text-align:center">68.2</td>
<td style="text-align:center">84.0</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">CAN</td>
<td style="text-align:center">97.0</td>
<td style="text-align:center">87.2</td>
<td style="text-align:center">82.5</td>
<td style="text-align:center">74.3</td>
<td style="text-align:center">97.8</td>
<td style="text-align:center">96.2</td>
<td style="text-align:center">90.8</td>
<td style="text-align:center">80.7</td>
<td style="text-align:center">96.6</td>
<td style="text-align:center">96.3</td>
<td style="text-align:center">87.5</td>
<td style="text-align:center">59.9</td>
<td style="text-align:center">87.2</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/kgl-prml/Contrastive-Adaptation-Network-for-Unsupervised-Domain-Adaptation">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Kang_Contrastive_Adaptation_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Contrastive Adaptation Network for Unsupervised Domain Adaptation</td>
</tr>
</tbody>
</table>
<h3 id="215digitmnistuspssvhn">2.1.5.Digit(MNIST,USPS,SVHN)</h3>
<blockquote>
<p><strong>Backbone:</strong> <em>CNN</em></p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">S→M</th>
<th style="text-align:center">M→U</th>
<th style="text-align:center">U→M</th>
<th style="text-align:center">Avg</th>
<th style="text-align:center">Conference</th>
<th style="text-align:center">Year</th>
<th style="text-align:center">Code Url</th>
<th style="text-align:center">Paper Url</th>
<th style="text-align:center">Title</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">TPN</td>
<td style="text-align:center">93.0</td>
<td style="text-align:center">92.1</td>
<td style="text-align:center">94.1</td>
<td style="text-align:center">93.1</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/decisionforce/TPN">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Pan_Transferrable_Prototypical_Networks_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Transferrable Prototypical Networks for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BSP+ADDA</td>
<td style="text-align:center">91.4</td>
<td style="text-align:center">93.3</td>
<td style="text-align:center">94.5</td>
<td style="text-align:center">93.1</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BSP+DANN</td>
<td style="text-align:center">89.4</td>
<td style="text-align:center">94.5</td>
<td style="text-align:center">97.7</td>
<td style="text-align:center">93.9</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">CADA</td>
<td style="text-align:center">90.4±0.4</td>
<td style="text-align:center">95.6±0.2</td>
<td style="text-align:center">96.5±0.1</td>
<td style="text-align:center">94.2</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/4552/4430">link</a></td>
<td style="text-align:center">Consensus Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DEV</td>
<td style="text-align:center">93.18</td>
<td style="text-align:center">92.54</td>
<td style="text-align:center">96.93</td>
<td style="text-align:center">94.22</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Deep-Embedded-Validation">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/you19a/you19a.pdf">link</a></td>
<td style="text-align:center">Towards Accurate Model Selection in Deep Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">BSP+CDAN</td>
<td style="text-align:center">92.1</td>
<td style="text-align:center">95.0</td>
<td style="text-align:center">98.1</td>
<td style="text-align:center">95.1</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/thuml/Batch-Spectral-Penalization">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/chen19i/chen19i.pdf">link</a></td>
<td style="text-align:center">Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">JDDA-I</td>
<td style="text-align:center">93.1±0.2</td>
<td style="text-align:center">-</td>
<td style="text-align:center">97.0±0.2</td>
<td style="text-align:center">95.1</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/A-bone1/JDDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080">link</a></td>
<td style="text-align:center">Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">Our(Entro)</td>
<td style="text-align:center">91.5±0.3</td>
<td style="text-align:center">95.7±0.4</td>
<td style="text-align:center">98.1±0.2</td>
<td style="text-align:center">95.1</td>
<td style="text-align:center">IJCAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/1906.09693">link</a></td>
<td style="text-align:center">Bayesian Uncertainty Matching for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DM-ADA</td>
<td style="text-align:center">95.5±1.1</td>
<td style="text-align:center">96.7±0.5</td>
<td style="text-align:center">94.2±0.9</td>
<td style="text-align:center">95.5</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/ChrisAllenMing/Mixup_for_UDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6123/5979">link</a></td>
<td style="text-align:center">Adversarial Domain Adaptation with Domain Mixup</td>
</tr>
<tr>
<td style="text-align:center">JDDA-C</td>
<td style="text-align:center">94.2±0.1</td>
<td style="text-align:center">-</td>
<td style="text-align:center">96.7±0.1</td>
<td style="text-align:center">95.5</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/A-bone1/JDDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080">link</a></td>
<td style="text-align:center">Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">rRevGrad+CAT</td>
<td style="text-align:center">98.8±0.2</td>
<td style="text-align:center">94.0±0.7</td>
<td style="text-align:center">96.0±0.9</td>
<td style="text-align:center">96.3</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/thudzj/CAT">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Cluster_Alignment_With_a_Teacher_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf">link</a></td>
<td style="text-align:center">Cluster Alignment with a Teacher for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">GPDA</td>
<td style="text-align:center">-</td>
<td style="text-align:center">96.45±0.15</td>
<td style="text-align:center">96.37±0.1</td>
<td style="text-align:center">96.41</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/seqam-lab/GPDA">link</a></td>
<td style="text-align:center"><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Unsupervised_Visual_Domain_Adaptation_A_Deep_Max-Margin_Gaussian_Process_Approach_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Visual Domain Adaptation:A Deep Max-Margin Gaussian Process Approach</td>
</tr>
<tr>
<td style="text-align:center">IEDA</td>
<td style="text-align:center">98.9</td>
<td style="text-align:center">95.0</td>
<td style="text-align:center">97.5</td>
<td style="text-align:center">97.1</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://sites.google.com/site/jwchoivision/">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/6692/6546">link</a></td>
<td style="text-align:center">Visual Domain Adaptation by Consensus-Based Transfer to Intermediate Domain</td>
</tr>
<tr>
<td style="text-align:center">DMRL</td>
<td style="text-align:center">96.2</td>
<td style="text-align:center">96.1</td>
<td style="text-align:center">99.0</td>
<td style="text-align:center">97.2</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.03141">link</a></td>
<td style="text-align:center">Dual Mixup Regularized Learning for Adversarial Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">ACAL</td>
<td style="text-align:center">96.61</td>
<td style="text-align:center">98.31</td>
<td style="text-align:center">97.16</td>
<td style="text-align:center">97.36</td>
<td style="text-align:center">ICLR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/1807.00374">link</a></td>
<td style="text-align:center">Augmented cyclic adversarial learning for low resource domain adaptation</td>
</tr>
<tr>
<td style="text-align:center">ALDA</td>
<td style="text-align:center">98.6±0.1</td>
<td style="text-align:center">95.6±0.3</td>
<td style="text-align:center">98.7±0.3</td>
<td style="text-align:center">97.6</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/ZJULearning/ALDA">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613">link</a></td>
<td style="text-align:center">Adversarial-Learned Loss for Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">d-SNE</td>
<td style="text-align:center">96.45±0.20</td>
<td style="text-align:center">99.00±0.08</td>
<td style="text-align:center">98.49±0.35</td>
<td style="text-align:center">97.98</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/aws-samples/d-SNE">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_d-SNE_Domain_Adaptation_Using_Stochastic_Neighborhood_Embedding_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">d-SNE: Domain Adaptation using Stochastic Neighborhood Embedding</td>
</tr>
<tr>
<td style="text-align:center">STAFF</td>
<td style="text-align:center">97.7</td>
<td style="text-align:center">98.3</td>
<td style="text-align:center">98.1</td>
<td style="text-align:center">98.0</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/6629/6483">link</a></td>
<td style="text-align:center">Structure-Aware Feature Fusion for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">RWOT</td>
<td style="text-align:center">98.8±0.1</td>
<td style="text-align:center">98.5±0.2</td>
<td style="text-align:center">97.5±0.2</td>
<td style="text-align:center">98.30</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">SHOT</td>
<td style="text-align:center">98.9±0.0</td>
<td style="text-align:center">98.0±0.2</td>
<td style="text-align:center">98.4±0.6</td>
<td style="text-align:center">98.4</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/tim-learn/SHOT">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v119/liang20a/liang20a.pdf">link</a></td>
<td style="text-align:center">Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation</td>
</tr>
<tr>
<td style="text-align:center">DWT-MEC</td>
<td style="text-align:center">97.80±0.07</td>
<td style="text-align:center">99.01±0.06</td>
<td style="text-align:center">99.02±0.05</td>
<td style="text-align:center">98.61</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/roysubhankar/dwt-domain-adaptation">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Roy_Unsupervised_Domain_Adaptation_Using_Feature-Whitening_and_Consensus_Loss_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Unsupervised Domain Adaptation using Feature-Whitening and Consensus Loss</td>
</tr>
<tr>
<td style="text-align:center">KHoMM</td>
<td style="text-align:center">99.0±0.0</td>
<td style="text-align:center">-</td>
<td style="text-align:center">99.2±0.0</td>
<td style="text-align:center">99.1</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/chenchao666/HoMM-Master">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/5745/5601">link</a></td>
<td style="text-align:center">HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation</td>
</tr>
</tbody>
</table>
<h2 id="22dg">2.2.DG</h2>
<h3 id="221pacs">2.2.1.PACS</h3>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">Art Painting</th>
<th style="text-align:center">Cartoon</th>
<th style="text-align:center">Photo</th>
<th style="text-align:center">Sketch</th>
<th style="text-align:center">Avg</th>
<th style="text-align:center">Conference</th>
<th style="text-align:center">Year</th>
<th style="text-align:center">Code Url</th>
<th style="text-align:center">Paper Url</th>
<th style="text-align:center">Title</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Epi-FCR(AlexNet)</td>
<td style="text-align:center">64.7</td>
<td style="text-align:center">72.3</td>
<td style="text-align:center">86.1</td>
<td style="text-align:center">65.0</td>
<td style="text-align:center">72.0</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/HAHA-DL/Episodic-DG">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2019_paper.pdf">link</a></td>
<td style="text-align:center">Episodic Training for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">Feature-Critic(AlexNet)</td>
<td style="text-align:center">64.89</td>
<td style="text-align:center">71.72</td>
<td style="text-align:center">89.94</td>
<td style="text-align:center">61.85</td>
<td style="text-align:center">72.1</td>
<td style="text-align:center">ICML</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/liyiying/Feature_Critic">link</a></td>
<td style="text-align:center"><a href="http://proceedings.mlr.press/v97/li19l/li19l.pdf">link</a></td>
<td style="text-align:center">Feature-Critic Networks for Heterogeneous Domain Generalisation</td>
</tr>
<tr>
<td style="text-align:center">DMG(AlexNet)</td>
<td style="text-align:center">64.65</td>
<td style="text-align:center">69.88</td>
<td style="text-align:center">87.31</td>
<td style="text-align:center">71.42</td>
<td style="text-align:center">73.32</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/prithv1/DMG">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2008.12839">link</a></td>
<td style="text-align:center">Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">JiGen(AlexNet)</td>
<td style="text-align:center">67.63</td>
<td style="text-align:center">71.71</td>
<td style="text-align:center">89.00</td>
<td style="text-align:center">65.18</td>
<td style="text-align:center">73.78</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/fmcarlucci/JigenDG">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2019_paper.pdf">link</a></td>
<td style="text-align:center">Domain Generalization by Solving Jigsaw Puzzles</td>
</tr>
<tr>
<td style="text-align:center">MMLD(AlexNet)</td>
<td style="text-align:center">69.27</td>
<td style="text-align:center">72.83</td>
<td style="text-align:center">88.98</td>
<td style="text-align:center">66.44</td>
<td style="text-align:center">74.38</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/mil-tokyo/dg_mmld">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6846/6701">link</a></td>
<td style="text-align:center">Domain Generalization Using a Mixture of Multiple Latent Domains</td>
</tr>
<tr>
<td style="text-align:center">MASF(AlexNet)</td>
<td style="text-align:center">70.35</td>
<td style="text-align:center">72.46</td>
<td style="text-align:center">90.68</td>
<td style="text-align:center">72.46</td>
<td style="text-align:center">75.21</td>
<td style="text-align:center">NeurIPS</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/biomedia-mira/masf">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/1910.13580">link</a></td>
<td style="text-align:center">Domain Generalization via  Model-Agnostic Learning of Semantic Features</td>
</tr>
<tr>
<td style="text-align:center">MetaVIB(AlexNet)</td>
<td style="text-align:center">71.94±0.34</td>
<td style="text-align:center">73.17±0.21</td>
<td style="text-align:center">91.93±0.23</td>
<td style="text-align:center">65.94±0.24</td>
<td style="text-align:center">75.74</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.07645.pdf">link</a></td>
<td style="text-align:center">Learning to Learn with Variational Information Bottleneck for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">EISNet(AlexNet)</td>
<td style="text-align:center">70.38±0.37</td>
<td style="text-align:center">71.59±1.32</td>
<td style="text-align:center">91.20±0.00</td>
<td style="text-align:center">70.25±1.36</td>
<td style="text-align:center">75.86</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/EmmaW8/EISNet">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.09316">link</a></td>
<td style="text-align:center">Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">RSC(AlexNet)</td>
<td style="text-align:center">71.62</td>
<td style="text-align:center">75.11</td>
<td style="text-align:center">90.88</td>
<td style="text-align:center">66.62</td>
<td style="text-align:center">76.05</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/DeLightCMU/RSC">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.02454">link</a></td>
<td style="text-align:center">Self-Challenging Improves Cross-Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">JiGen(ResNet18)</td>
<td style="text-align:center">79.42</td>
<td style="text-align:center">75.25</td>
<td style="text-align:center">96.03</td>
<td style="text-align:center">71.35</td>
<td style="text-align:center">80.51</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/fmcarlucci/JigenDG">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Domain Generalization by Solving Jigsaw Puzzles</td>
</tr>
<tr>
<td style="text-align:center">MASF(ResNet18)</td>
<td style="text-align:center">80.29</td>
<td style="text-align:center">77.17</td>
<td style="text-align:center">94.99</td>
<td style="text-align:center">71.69</td>
<td style="text-align:center">81.04</td>
<td style="text-align:center">NeurIPS</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/biomedia-mira/masf">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/1910.13581">link</a></td>
<td style="text-align:center">Domain Generalization via  Model-Agnostic Learning of Semantic Features</td>
</tr>
<tr>
<td style="text-align:center">DG_via_ER(ResNet18)</td>
<td style="text-align:center">80.70±0.71</td>
<td style="text-align:center">76.40±0.34</td>
<td style="text-align:center">96.65±0.21</td>
<td style="text-align:center">71.77±1.27</td>
<td style="text-align:center">81.38</td>
<td style="text-align:center">NeurIPS</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/sshan-zhao/DG_via_ER">link</a></td>
<td style="text-align:center"><a href="https://proceedings.neurips.cc/paper/2020/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf">link</a></td>
<td style="text-align:center">Domain Generalization via Entropy Regularization</td>
</tr>
<tr>
<td style="text-align:center">DMG(ResNet18)</td>
<td style="text-align:center">76.90</td>
<td style="text-align:center">80.38</td>
<td style="text-align:center">93.35</td>
<td style="text-align:center">75.21</td>
<td style="text-align:center">81.46</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/prithv2/DMG">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2008.12840">link</a></td>
<td style="text-align:center">Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">Epi-FCR(ResNet18)</td>
<td style="text-align:center">82.1</td>
<td style="text-align:center">77.0</td>
<td style="text-align:center">93.0</td>
<td style="text-align:center">73.0</td>
<td style="text-align:center">81.5</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/HAHA-DL/Episodic-DG">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2020_paper.pdf">link</a></td>
<td style="text-align:center">Episodic Training for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">MMLD(ResNet18)</td>
<td style="text-align:center">81.28</td>
<td style="text-align:center">77.16</td>
<td style="text-align:center">96.09</td>
<td style="text-align:center">72.22</td>
<td style="text-align:center">81.83</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/mil-tokyo/dg_mmld">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6846/6700">link</a></td>
<td style="text-align:center">Domain Generalization Using a Mixture of Multiple Latent Domains</td>
</tr>
<tr>
<td style="text-align:center">EISNet(ResNet18)</td>
<td style="text-align:center">81.89±0.88</td>
<td style="text-align:center">76.44±0.31</td>
<td style="text-align:center">95.93±0.06</td>
<td style="text-align:center">74.33±1.37</td>
<td style="text-align:center">82.15</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/EmmaW9/EISNet">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.09317">link</a></td>
<td style="text-align:center">Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">MASF(ResNet50)</td>
<td style="text-align:center">82.89</td>
<td style="text-align:center">80.49</td>
<td style="text-align:center">95.01</td>
<td style="text-align:center">72.29</td>
<td style="text-align:center">82.67</td>
<td style="text-align:center">NeurIPS</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/biomedia-mira/masf">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/1910.13582">link</a></td>
<td style="text-align:center">Domain Generalization via  Model-Agnostic Learning of Semantic Features</td>
</tr>
<tr>
<td style="text-align:center">L2A-OT(ResNet18)</td>
<td style="text-align:center">83.8</td>
<td style="text-align:center">78.2</td>
<td style="text-align:center">96.2</td>
<td style="text-align:center">73.6</td>
<td style="text-align:center">82.8</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/mousecpn/L2A-OT">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.03304">link</a></td>
<td style="text-align:center">Learning to Generate Novel Domains for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">DMG(ResNet50)</td>
<td style="text-align:center">82.57</td>
<td style="text-align:center">78.11</td>
<td style="text-align:center">94.49</td>
<td style="text-align:center">78.32</td>
<td style="text-align:center">83.37</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/prithv3/DMG">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2008.12841">link</a></td>
<td style="text-align:center">Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">MixStyle(ResNet18)</td>
<td style="text-align:center">84.1±0.4</td>
<td style="text-align:center">78.8±0.4</td>
<td style="text-align:center">96.1±0.3</td>
<td style="text-align:center">75.9±0.9</td>
<td style="text-align:center">83.7</td>
<td style="text-align:center">ICLR</td>
<td style="text-align:center">2021</td>
<td style="text-align:center"><a href="https://github.com/KaiyangZhou/mixstyle-release">link</a></td>
<td style="text-align:center"><a href="https://openreview.net/pdf/45cfce2bb7de7655e5129c349f609eba35911b60.pdf">link</a></td>
<td style="text-align:center">Domain Generalization with MixStyle</td>
</tr>
<tr>
<td style="text-align:center">DSON(ResNet18)</td>
<td style="text-align:center">84.67</td>
<td style="text-align:center">77.65</td>
<td style="text-align:center">95.87</td>
<td style="text-align:center">82.23</td>
<td style="text-align:center">85.11</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670069.pdf">link</a></td>
<td style="text-align:center">Learning to Optimize Domain Specifific Normalization for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">RSC(ResNet18)</td>
<td style="text-align:center">83.43</td>
<td style="text-align:center">80.31</td>
<td style="text-align:center">95.99</td>
<td style="text-align:center">80.85</td>
<td style="text-align:center">85.15</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/DeLightCMU/RSC">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.02455">link</a></td>
<td style="text-align:center">Self-Challenging Improves Cross-Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">DG_via_ER(ResNet50)</td>
<td style="text-align:center">87.51±1.03</td>
<td style="text-align:center">79.31±1.40</td>
<td style="text-align:center">98.25±0.12</td>
<td style="text-align:center">76.30±0.65</td>
<td style="text-align:center">85.34</td>
<td style="text-align:center">NeurIPS</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/sshan-zhao/DG_via_ER">link</a></td>
<td style="text-align:center"><a href="https://proceedings.neurips.cc/paper/2020/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf">link</a></td>
<td style="text-align:center">Domain Generalization via Entropy Regularization</td>
</tr>
<tr>
<td style="text-align:center">EISNet(ResNet50)</td>
<td style="text-align:center">86.64±1.41</td>
<td style="text-align:center">81.53±0.64</td>
<td style="text-align:center">97.11±0.40</td>
<td style="text-align:center">78.07±1.43</td>
<td style="text-align:center">85.84</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/EmmaW10/EISNet">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.09318">link</a></td>
<td style="text-align:center">Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">DSON(ResNet50)</td>
<td style="text-align:center">87.04</td>
<td style="text-align:center">80.62</td>
<td style="text-align:center">95.99</td>
<td style="text-align:center">82.90</td>
<td style="text-align:center">86.64</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670070.pdf">link</a></td>
<td style="text-align:center">Learning to Optimize Domain Specifific Normalization for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">RSC(ResNet50)</td>
<td style="text-align:center">87.89</td>
<td style="text-align:center">82.16</td>
<td style="text-align:center">97.92</td>
<td style="text-align:center">83.35</td>
<td style="text-align:center">87.83</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/DeLightCMU/RSC">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.02456">link</a></td>
<td style="text-align:center">Self-Challenging Improves Cross-Domain Generalization</td>
</tr>
</tbody>
</table>
<h3 id="222vlcs">2.2.2.VLCS</h3>
<blockquote>
<p><strong>Backbone:</strong> <em>AlexNet</em></p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">Caltech</th>
<th style="text-align:center">Labelme</th>
<th style="text-align:center">Pascal</th>
<th style="text-align:center">Sun</th>
<th style="text-align:center">Avg</th>
<th style="text-align:center">Conference</th>
<th style="text-align:center">Year</th>
<th style="text-align:center">Code Url</th>
<th style="text-align:center">Paper Url</th>
<th style="text-align:center">Title</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Epi-FCR</td>
<td style="text-align:center">94.1</td>
<td style="text-align:center">64.3</td>
<td style="text-align:center">67.1</td>
<td style="text-align:center">65.9</td>
<td style="text-align:center">72.9</td>
<td style="text-align:center">ICCV</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/HAHA-DL/Episodic-DG">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2020_paper.pdf">link</a></td>
<td style="text-align:center">Episodic Training for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">JiGen</td>
<td style="text-align:center">96.93</td>
<td style="text-align:center">60.90</td>
<td style="text-align:center">70.62</td>
<td style="text-align:center">64.30</td>
<td style="text-align:center">73.19</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/fmcarlucci/JigenDG">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Domain Generalization by Solving Jigsaw Puzzles</td>
</tr>
<tr>
<td style="text-align:center">MMLD(ResNet18)</td>
<td style="text-align:center">96.66</td>
<td style="text-align:center">58.77</td>
<td style="text-align:center">71.96</td>
<td style="text-align:center">68.13</td>
<td style="text-align:center">73.88</td>
<td style="text-align:center">AAAI</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/mil-tokyo/dg_mmld">link</a></td>
<td style="text-align:center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6846/6701">link</a></td>
<td style="text-align:center">Domain Generalization Using a Mixture of Multiple Latent Domains</td>
</tr>
<tr>
<td style="text-align:center">MetaVIB</td>
<td style="text-align:center">97.37±0.63</td>
<td style="text-align:center">62.66±0.35</td>
<td style="text-align:center">70.28±0.71</td>
<td style="text-align:center">67.85±0.17</td>
<td style="text-align:center">74.54</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.07645.pdf">link</a></td>
<td style="text-align:center">Learning to Learn with Variational Information Bottleneck for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">EISNet</td>
<td style="text-align:center">97.33±0.36</td>
<td style="text-align:center">63.49±0.82</td>
<td style="text-align:center">69.83±0.48</td>
<td style="text-align:center">68.02±0.81</td>
<td style="text-align:center">74.67</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/EmmaW10/EISNet">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.09318">link</a></td>
<td style="text-align:center">Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">RSC</td>
<td style="text-align:center">97.61</td>
<td style="text-align:center">61.86</td>
<td style="text-align:center">73.93</td>
<td style="text-align:center">68.32</td>
<td style="text-align:center">75.43</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/DeLightCMU/RSC">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.02456">link</a></td>
<td style="text-align:center">Self-Challenging Improves Cross-Domain Generalization</td>
</tr>
</tbody>
</table>
<h3 id="223office-home">2.2.3.Office-Home</h3>
<blockquote>
<p><strong>Backbone:</strong> <em>ResNet18</em></p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">Art</th>
<th style="text-align:center">Clipart</th>
<th style="text-align:center">Product</th>
<th style="text-align:center">Real World</th>
<th style="text-align:center">Avg</th>
<th style="text-align:center">Conference</th>
<th style="text-align:center">Year</th>
<th style="text-align:center">Code Url</th>
<th style="text-align:center">Paper Url</th>
<th style="text-align:center">Title</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">JiGen</td>
<td style="text-align:center">53.04</td>
<td style="text-align:center">47.51</td>
<td style="text-align:center">71.47</td>
<td style="text-align:center">72.79</td>
<td style="text-align:center">61.20</td>
<td style="text-align:center">CVPR</td>
<td style="text-align:center">2019</td>
<td style="text-align:center"><a href="https://github.com/fmcarlucci/JigenDG">link</a></td>
<td style="text-align:center"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf">link</a></td>
<td style="text-align:center">Domain Generalization by Solving Jigsaw Puzzles</td>
</tr>
<tr>
<td style="text-align:center">L2A-OT</td>
<td style="text-align:center">60.6</td>
<td style="text-align:center">50.1</td>
<td style="text-align:center">74.8</td>
<td style="text-align:center">77.0</td>
<td style="text-align:center">65.6</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/mousecpn/L2A-OT">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.03304">link</a></td>
<td style="text-align:center">Learning to Generate Novel Domains for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">DSON</td>
<td style="text-align:center">59.37</td>
<td style="text-align:center">44.70</td>
<td style="text-align:center">71.84</td>
<td style="text-align:center">74.68</td>
<td style="text-align:center">62.90</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center">-</td>
<td style="text-align:center"><a href="http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670069.pdf">link</a></td>
<td style="text-align:center">Learning to Optimize Domain Specifific Normalization for Domain Generalization</td>
</tr>
<tr>
<td style="text-align:center">RSC</td>
<td style="text-align:center">58.42</td>
<td style="text-align:center">47.90</td>
<td style="text-align:center">71.63</td>
<td style="text-align:center">74.54</td>
<td style="text-align:center">63.12</td>
<td style="text-align:center">ECCV</td>
<td style="text-align:center">2020</td>
<td style="text-align:center"><a href="https://github.com/DeLightCMU/RSC">link</a></td>
<td style="text-align:center"><a href="https://arxiv.org/pdf/2007.02456">link</a></td>
<td style="text-align:center">Self-Challenging Improves Cross-Domain Generalization</td>
</tr>
</tbody>
</table>

</body>
</html>
