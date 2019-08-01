{"title":"选项卡嵌套","meta":{"title":"选项卡嵌套","description":"\n<p>可以将不同类型的选项卡进行嵌套</p>\n","order":"14"},"codes":{"jsx":"import { Tab } from '@alifd/next';\n\nfunction callback(key) {\n    console.log(key);\n}\n\nReactDOM.render(\n    <Tab onChange={callback} shape=\"wrapped\">\n        <Tab.Item title=\"Tab 1\" key=\"1\">\n            <Tab shape=\"wrapped\">\n                <Tab.Item title=\"1-1\" key=\"11\">1-1</Tab.Item>\n                <Tab.Item title=\"1-2\" key=\"12\">1-2</Tab.Item>\n                <Tab.Item title=\"1-3\" key=\"13\">1-3</Tab.Item>\n            </Tab>\n        </Tab.Item>\n        <Tab.Item title=\"Tab 2\" key=\"2\">\n            <Tab shape=\"pure\">\n                <Tab.Item title=\"2-1\" key=\"21\">2-1</Tab.Item>\n                <Tab.Item title=\"2-2\" key=\"22\">2-2</Tab.Item>\n                <Tab.Item title=\"3-3\" key=\"23\">2-3</Tab.Item>\n            </Tab>\n        </Tab.Item>\n        <Tab.Item title=\"Tab 3\" key=\"3\">\n            <Tab shape=\"capsule\">\n                <Tab.Item title=\"3-1\" key=\"31\">3-1</Tab.Item>\n                <Tab.Item title=\"3-2\" key=\"32\">3-2</Tab.Item>\n                <Tab.Item title=\"3-3\" key=\"33\">3-3</Tab.Item>\n            </Tab>\n        </Tab.Item>\n        <Tab.Item title=\"Tab 4\" key=\"4\">\n            <Tab shape=\"text\">\n                <Tab.Item title=\"4-1\" key=\"41\">4-1</Tab.Item>\n                <Tab.Item title=\"4-2\" key=\"42\">4-2</Tab.Item>\n                <Tab.Item title=\"4-3\" key=\"43\">4-3</Tab.Item>\n            </Tab>\n        </Tab.Item>\n    </Tab>\n    , mountNode);\n","css":".next-tabs-content {\n    color: #333;\n    font-size: 12px;\n    padding: 12px;\n}\n"},"body":"\n\n````jsx\nimport { Tab } from '@alifd/next';\n\nfunction callback(key) {\n    console.log(key);\n}\n\nReactDOM.render(\n    <Tab onChange={callback} shape=\"wrapped\">\n        <Tab.Item title=\"Tab 1\" key=\"1\">\n            <Tab shape=\"wrapped\">\n                <Tab.Item title=\"1-1\" key=\"11\">1-1</Tab.Item>\n                <Tab.Item title=\"1-2\" key=\"12\">1-2</Tab.Item>\n                <Tab.Item title=\"1-3\" key=\"13\">1-3</Tab.Item>\n            </Tab>\n        </Tab.Item>\n        <Tab.Item title=\"Tab 2\" key=\"2\">\n            <Tab shape=\"pure\">\n                <Tab.Item title=\"2-1\" key=\"21\">2-1</Tab.Item>\n                <Tab.Item title=\"2-2\" key=\"22\">2-2</Tab.Item>\n                <Tab.Item title=\"3-3\" key=\"23\">2-3</Tab.Item>\n            </Tab>\n        </Tab.Item>\n        <Tab.Item title=\"Tab 3\" key=\"3\">\n            <Tab shape=\"capsule\">\n                <Tab.Item title=\"3-1\" key=\"31\">3-1</Tab.Item>\n                <Tab.Item title=\"3-2\" key=\"32\">3-2</Tab.Item>\n                <Tab.Item title=\"3-3\" key=\"33\">3-3</Tab.Item>\n            </Tab>\n        </Tab.Item>\n        <Tab.Item title=\"Tab 4\" key=\"4\">\n            <Tab shape=\"text\">\n                <Tab.Item title=\"4-1\" key=\"41\">4-1</Tab.Item>\n                <Tab.Item title=\"4-2\" key=\"42\">4-2</Tab.Item>\n                <Tab.Item title=\"4-3\" key=\"43\">4-3</Tab.Item>\n            </Tab>\n        </Tab.Item>\n    </Tab>\n    , mountNode);\n````\n\n````css\n.next-tabs-content {\n    color: #333;\n    font-size: 12px;\n    padding: 12px;\n}\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nfunction callback(key) {\n    console.log(key);\n}\n\nReactDOM.render(React.createElement(\n    _next.Tab,\n    { onChange: callback, shape: \"wrapped\" },\n    React.createElement(\n        _next.Tab.Item,\n        { title: \"Tab 1\", key: \"1\" },\n        React.createElement(\n            _next.Tab,\n            { shape: \"wrapped\" },\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"1-1\", key: \"11\" },\n                \"1-1\"\n            ),\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"1-2\", key: \"12\" },\n                \"1-2\"\n            ),\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"1-3\", key: \"13\" },\n                \"1-3\"\n            )\n        )\n    ),\n    React.createElement(\n        _next.Tab.Item,\n        { title: \"Tab 2\", key: \"2\" },\n        React.createElement(\n            _next.Tab,\n            { shape: \"pure\" },\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"2-1\", key: \"21\" },\n                \"2-1\"\n            ),\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"2-2\", key: \"22\" },\n                \"2-2\"\n            ),\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"3-3\", key: \"23\" },\n                \"2-3\"\n            )\n        )\n    ),\n    React.createElement(\n        _next.Tab.Item,\n        { title: \"Tab 3\", key: \"3\" },\n        React.createElement(\n            _next.Tab,\n            { shape: \"capsule\" },\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"3-1\", key: \"31\" },\n                \"3-1\"\n            ),\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"3-2\", key: \"32\" },\n                \"3-2\"\n            ),\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"3-3\", key: \"33\" },\n                \"3-3\"\n            )\n        )\n    ),\n    React.createElement(\n        _next.Tab.Item,\n        { title: \"Tab 4\", key: \"4\" },\n        React.createElement(\n            _next.Tab,\n            { shape: \"text\" },\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"4-1\", key: \"41\" },\n                \"4-1\"\n            ),\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"4-2\", key: \"42\" },\n                \"4-2\"\n            ),\n            React.createElement(\n                _next.Tab.Item,\n                { title: \"4-3\", key: \"43\" },\n                \"4-3\"\n            )\n        )\n    )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Tab <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">function</span> <span class=\"token function\">callback</span><span class=\"token punctuation\">(</span><span class=\"token parameter\">key</span><span class=\"token punctuation\">)</span> <span class=\"token punctuation\">{</span>\n    console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span>key<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab</span></span> <span class=\"token attr-name\">onChange</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>callback<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>wrapped<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Tab 1<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>1<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab</span></span> <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>wrapped<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>1-1<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>11<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">1-1</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>1-2<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>12<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">1-2</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>1-3<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>13<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">1-3</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Tab 2<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>2<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab</span></span> <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>pure<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>2-1<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>21<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">2-1</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>2-2<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>22<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">2-2</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>3-3<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>23<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">2-3</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Tab 3<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab</span></span> <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>capsule<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>3-1<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>31<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">3-1</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>3-2<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>32<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">3-2</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>3-3<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>33<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">3-3</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Tab 4<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>4<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab</span></span> <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>text<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>4-1<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>41<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">4-1</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>4-2<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>42<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">4-2</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>4-3<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>43<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">4-3</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab</span></span><span class=\"token punctuation\">></span></span>\n    <span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">.next-tabs-content {\n    color: #333;\n    font-size: 12px;\n    padding: 12px;\n}</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\"><span class=\"token selector\">.next-tabs-content</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">color</span><span class=\"token punctuation\">:</span> #333<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">font-size</span><span class=\"token punctuation\">:</span> 12px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">padding</span><span class=\"token punctuation\">:</span> 12px<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}