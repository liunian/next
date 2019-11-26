{"title":"进度条不同状态","meta":{"title":"进度条不同状态","description":"\n<p>用户可以通过 <code>state</code> 属性自定义当前进度的展现状态，可取值为 <code>normal</code>, <code>success</code>, <code>error</code> 分别表示普通、成功、失败这三种状态。</p>\n","order":"3"},"codes":{"jsx":"import { Progress } from '@alifd/next';\n\nReactDOM.render(<div className=\"\">\n    <Progress percent={20} shape=\"circle\" state=\"normal\" className=\"custom-progress\" />\n    <Progress percent={95} shape=\"circle\" state=\"success\" className=\"custom-progress\" />\n    <Progress percent={95} shape=\"circle\" state=\"error\" className=\"custom-progress\" />\n</div>, mountNode);\n","css":".custom-progress {\n    margin: 0 20px;\n}\n"},"body":"\n\n````jsx\nimport { Progress } from '@alifd/next';\n\nReactDOM.render(<div className=\"\">\n    <Progress percent={20} shape=\"circle\" state=\"normal\" className=\"custom-progress\" />\n    <Progress percent={95} shape=\"circle\" state=\"success\" className=\"custom-progress\" />\n    <Progress percent={95} shape=\"circle\" state=\"error\" className=\"custom-progress\" />\n</div>, mountNode);\n````\n\n````css\n.custom-progress {\n    margin: 0 20px;\n}\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nReactDOM.render(React.createElement(\n    \"div\",\n    { className: \"\" },\n    React.createElement(_next.Progress, { percent: 20, shape: \"circle\", state: \"normal\", className: \"custom-progress\" }),\n    React.createElement(_next.Progress, { percent: 95, shape: \"circle\", state: \"success\", className: \"custom-progress\" }),\n    React.createElement(_next.Progress, { percent: 95, shape: \"circle\", state: \"error\", className: \"custom-progress\" })\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Progress <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span><span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Progress</span></span> <span class=\"token attr-name\">percent</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">20</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>circle<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">state</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>normal<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>custom-progress<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Progress</span></span> <span class=\"token attr-name\">percent</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">95</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>circle<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">state</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>success<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>custom-progress<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Progress</span></span> <span class=\"token attr-name\">percent</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">95</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>circle<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">state</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>error<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>custom-progress<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">.custom-progress {\n    margin: 0 20px;\n}</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\"><span class=\"token selector\">.custom-progress</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">margin</span><span class=\"token punctuation\">:</span> 0 20px<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}