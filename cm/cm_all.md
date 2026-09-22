# CommonMark 스펙 세트 (654개)

각 행 = 예제 한 개. 소스는 원본 마크다운(escape 표시). 렌더 대조는 quality_compare.xlsx 참조.

| 번호 | 파일명 | 소스 |
|---:|---|---|
| 1 | cm_0001 | <code>&nbsp;&nbsp;&nbsp;&nbsp;foo&nbsp;&nbsp;&nbsp;&nbsp;baz&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bim</code> |
| 2 | cm_0002 | <code>  &nbsp;&nbsp;&nbsp;&nbsp;foo&nbsp;&nbsp;&nbsp;&nbsp;baz&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bim</code> |
| 3 | cm_0003 | <code>    a&nbsp;&nbsp;&nbsp;&nbsp;a<br>    ὐ&nbsp;&nbsp;&nbsp;&nbsp;a</code> |
| 4 | cm_0004 | <code>  - foo<br><br>&nbsp;&nbsp;&nbsp;&nbsp;bar</code> |
| 5 | cm_0005 | <code>- foo<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bar</code> |
| 6 | cm_0006 | <code>&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;foo</code> |
| 7 | cm_0007 | <code>-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;foo</code> |
| 8 | cm_0008 | <code>    foo<br>&nbsp;&nbsp;&nbsp;&nbsp;bar</code> |
| 9 | cm_0009 | <code> - foo<br>   - bar<br>&nbsp;&nbsp;&nbsp;&nbsp; - baz</code> |
| 10 | cm_0010 | <code>#&nbsp;&nbsp;&nbsp;&nbsp;Foo</code> |
| 11 | cm_0011 | <code>*&nbsp;&nbsp;&nbsp;&nbsp;*&nbsp;&nbsp;&nbsp;&nbsp;*&nbsp;&nbsp;&nbsp;&nbsp;</code> |
| 12 | cm_0012 | <code>\!\"\#\$\%\&amp;\'\(\)\*\+\,\-\.\/\:\;\&lt;\=\&gt;\?\@\[\\\]\^\_\`\{\&#124;\}\~</code> |
| 13 | cm_0013 | <code>\&nbsp;&nbsp;&nbsp;&nbsp;\A\a\ \3\φ\«</code> |
| 14 | cm_0014 | <code>\*not emphasized*<br>\&lt;br/&gt; not a tag<br>\[not a link](/foo)<br>\`not code`<br>1\. not a list<br>\* not a list<br>\# not a heading<br>\[foo]: /url "not a reference"<br>\&amp;ouml; not a character entity</code> |
| 15 | cm_0015 | <code>\\*emphasis*</code> |
| 16 | cm_0016 | <code>foo\<br>bar</code> |
| 17 | cm_0017 | <code>`` \[\` ``</code> |
| 18 | cm_0018 | <code>    \[\]</code> |
| 19 | cm_0019 | <code>~~~<br>\[\]<br>~~~</code> |
| 20 | cm_0020 | <code>&lt;https://example.com?find=\*&gt;</code> |
| 21 | cm_0021 | <code>&lt;a href="/bar\/)"&gt;</code> |
| 22 | cm_0022 | <code>[foo](/bar\* "ti\*tle")</code> |
| 23 | cm_0023 | <code>[foo]<br><br>[foo]: /bar\* "ti\*tle"</code> |
| 24 | cm_0024 | <code>``` foo\+bar<br>foo<br>```</code> |
| 25 | cm_0025 | <code>&amp;nbsp; &amp;amp; &amp;copy; &amp;AElig; &amp;Dcaron;<br>&amp;frac34; &amp;HilbertSpace; &amp;DifferentialD;<br>&amp;ClockwiseContourIntegral; &amp;ngE;</code> |
| 26 | cm_0026 | <code>&amp;#35; &amp;#1234; &amp;#992; &amp;#0;</code> |
| 27 | cm_0027 | <code>&amp;#X22; &amp;#XD06; &amp;#xcab;</code> |
| 28 | cm_0028 | <code>&amp;nbsp &amp;x; &amp;#; &amp;#x;<br>&amp;#87654321;<br>&amp;#abcdef0;<br>&amp;ThisIsNotDefined; &amp;hi?;</code> |
| 29 | cm_0029 | <code>&amp;copy</code> |
| 30 | cm_0030 | <code>&amp;MadeUpEntity;</code> |
| 31 | cm_0031 | <code>&lt;a href="&amp;ouml;&amp;ouml;.html"&gt;</code> |
| 32 | cm_0032 | <code>[foo](/f&amp;ouml;&amp;ouml; "f&amp;ouml;&amp;ouml;")</code> |
| 33 | cm_0033 | <code>[foo]<br><br>[foo]: /f&amp;ouml;&amp;ouml; "f&amp;ouml;&amp;ouml;"</code> |
| 34 | cm_0034 | <code>``` f&amp;ouml;&amp;ouml;<br>foo<br>```</code> |
| 35 | cm_0035 | <code>`f&amp;ouml;&amp;ouml;`</code> |
| 36 | cm_0036 | <code>    f&amp;ouml;f&amp;ouml;</code> |
| 37 | cm_0037 | <code>&amp;#42;foo&amp;#42;<br>*foo*</code> |
| 38 | cm_0038 | <code>&amp;#42; foo<br><br>* foo</code> |
| 39 | cm_0039 | <code>foo&amp;#10;&amp;#10;bar</code> |
| 40 | cm_0040 | <code>&amp;#9;foo</code> |
| 41 | cm_0041 | <code>[a](url &amp;quot;tit&amp;quot;)</code> |
| 42 | cm_0042 | <code>- `one<br>- two`</code> |
| 43 | cm_0043 | <code>***<br>---<br>___</code> |
| 44 | cm_0044 | <code>+++</code> |
| 45 | cm_0045 | <code>===</code> |
| 46 | cm_0046 | <code>--<br>**<br>__</code> |
| 47 | cm_0047 | <code> ***<br>  ***<br>   ***</code> |
| 48 | cm_0048 | <code>    ***</code> |
| 49 | cm_0049 | <code>Foo<br>    ***</code> |
| 50 | cm_0050 | <code>_____________________________________</code> |
| 51 | cm_0051 | <code> - - -</code> |
| 52 | cm_0052 | <code> **  * ** * ** * **</code> |
| 53 | cm_0053 | <code>-     -      -      -</code> |
| 54 | cm_0054 | <code>- - - -    </code> |
| 55 | cm_0055 | <code>_ _ _ _ a<br><br>a------<br><br>---a---</code> |
| 56 | cm_0056 | <code> *-*</code> |
| 57 | cm_0057 | <code>- foo<br>***<br>- bar</code> |
| 58 | cm_0058 | <code>Foo<br>***<br>bar</code> |
| 59 | cm_0059 | <code>Foo<br>---<br>bar</code> |
| 60 | cm_0060 | <code>* Foo<br>* * *<br>* Bar</code> |
| 61 | cm_0061 | <code>- Foo<br>- * * *</code> |
| 62 | cm_0062 | <code># foo<br>## foo<br>### foo<br>#### foo<br>##### foo<br>###### foo</code> |
| 63 | cm_0063 | <code>####### foo</code> |
| 64 | cm_0064 | <code>#5 bolt<br><br>#hashtag</code> |
| 65 | cm_0065 | <code>\## foo</code> |
| 66 | cm_0066 | <code># foo *bar* \*baz\*</code> |
| 67 | cm_0067 | <code>#                  foo                     </code> |
| 68 | cm_0068 | <code> ### foo<br>  ## foo<br>   # foo</code> |
| 69 | cm_0069 | <code>    # foo</code> |
| 70 | cm_0070 | <code>foo<br>    # bar</code> |
| 71 | cm_0071 | <code>## foo ##<br>  ###   bar    ###</code> |
| 72 | cm_0072 | <code># foo ##################################<br>##### foo ##</code> |
| 73 | cm_0073 | <code>### foo ###     </code> |
| 74 | cm_0074 | <code>### foo ### b</code> |
| 75 | cm_0075 | <code># foo#</code> |
| 76 | cm_0076 | <code>### foo \###<br>## foo #\##<br># foo \#</code> |
| 77 | cm_0077 | <code>****<br>## foo<br>****</code> |
| 78 | cm_0078 | <code>Foo bar<br># baz<br>Bar foo</code> |
| 79 | cm_0079 | <code>## <br>#<br>### ###</code> |
| 80 | cm_0080 | <code>Foo *bar*<br>=========<br><br>Foo *bar*<br>---------</code> |
| 81 | cm_0081 | <code>Foo *bar<br>baz*<br>====</code> |
| 82 | cm_0082 | <code>  Foo *bar<br>baz*&nbsp;&nbsp;&nbsp;&nbsp;<br>====</code> |
| 83 | cm_0083 | <code>Foo<br>-------------------------<br><br>Foo<br>=</code> |
| 84 | cm_0084 | <code>   Foo<br>---<br><br>  Foo<br>-----<br><br>  Foo<br>  ===</code> |
| 85 | cm_0085 | <code>    Foo<br>    ---<br><br>    Foo<br>---</code> |
| 86 | cm_0086 | <code>Foo<br>   ----      </code> |
| 87 | cm_0087 | <code>Foo<br>    ---</code> |
| 88 | cm_0088 | <code>Foo<br>= =<br><br>Foo<br>--- -</code> |
| 89 | cm_0089 | <code>Foo  <br>-----</code> |
| 90 | cm_0090 | <code>Foo\<br>----</code> |
| 91 | cm_0091 | <code>`Foo<br>----<br>`<br><br>&lt;a title="a lot<br>---<br>of dashes"/&gt;</code> |
| 92 | cm_0092 | <code>&gt; Foo<br>---</code> |
| 93 | cm_0093 | <code>&gt; foo<br>bar<br>===</code> |
| 94 | cm_0094 | <code>- Foo<br>---</code> |
| 95 | cm_0095 | <code>Foo<br>Bar<br>---</code> |
| 96 | cm_0096 | <code>---<br>Foo<br>---<br>Bar<br>---<br>Baz</code> |
| 97 | cm_0097 | <code><br>====</code> |
| 98 | cm_0098 | <code>---<br>---</code> |
| 99 | cm_0099 | <code>- foo<br>-----</code> |
| 100 | cm_0100 | <code>    foo<br>---</code> |
| 101 | cm_0101 | <code>&gt; foo<br>-----</code> |
| 102 | cm_0102 | <code>\&gt; foo<br>------</code> |
| 103 | cm_0103 | <code>Foo<br><br>bar<br>---<br>baz</code> |
| 104 | cm_0104 | <code>Foo<br>bar<br><br>---<br><br>baz</code> |
| 105 | cm_0105 | <code>Foo<br>bar<br>* * *<br>baz</code> |
| 106 | cm_0106 | <code>Foo<br>bar<br>\---<br>baz</code> |
| 107 | cm_0107 | <code>    a simple<br>      indented code block</code> |
| 108 | cm_0108 | <code>  - foo<br><br>    bar</code> |
| 109 | cm_0109 | <code>1.  foo<br><br>    - bar</code> |
| 110 | cm_0110 | <code>    &lt;a/&gt;<br>    *hi*<br><br>    - one</code> |
| 111 | cm_0111 | <code>    chunk1<br><br>    chunk2<br>  <br> <br> <br>    chunk3</code> |
| 112 | cm_0112 | <code>    chunk1<br>      <br>      chunk2</code> |
| 113 | cm_0113 | <code>Foo<br>    bar</code> |
| 114 | cm_0114 | <code>    foo<br>bar</code> |
| 115 | cm_0115 | <code># Heading<br>    foo<br>Heading<br>------<br>    foo<br>----</code> |
| 116 | cm_0116 | <code>        foo<br>    bar</code> |
| 117 | cm_0117 | <code><br>    <br>    foo<br>    </code> |
| 118 | cm_0118 | <code>    foo  </code> |
| 119 | cm_0119 | <code>```<br>&lt;<br> &gt;<br>```</code> |
| 120 | cm_0120 | <code>~~~<br>&lt;<br> &gt;<br>~~~</code> |
| 121 | cm_0121 | <code>``<br>foo<br>``</code> |
| 122 | cm_0122 | <code>```<br>aaa<br>~~~<br>```</code> |
| 123 | cm_0123 | <code>~~~<br>aaa<br>```<br>~~~</code> |
| 124 | cm_0124 | <code>````<br>aaa<br>```<br>``````</code> |
| 125 | cm_0125 | <code>~~~~<br>aaa<br>~~~<br>~~~~</code> |
| 126 | cm_0126 | <code>```</code> |
| 127 | cm_0127 | <code>`````<br><br>```<br>aaa</code> |
| 128 | cm_0128 | <code>&gt; ```<br>&gt; aaa<br><br>bbb</code> |
| 129 | cm_0129 | <code>```<br><br>  <br>```</code> |
| 130 | cm_0130 | <code>```<br>```</code> |
| 131 | cm_0131 | <code> ```<br> aaa<br>aaa<br>```</code> |
| 132 | cm_0132 | <code>  ```<br>aaa<br>  aaa<br>aaa<br>  ```</code> |
| 133 | cm_0133 | <code>   ```<br>   aaa<br>    aaa<br>  aaa<br>   ```</code> |
| 134 | cm_0134 | <code>    ```<br>    aaa<br>    ```</code> |
| 135 | cm_0135 | <code>```<br>aaa<br>  ```</code> |
| 136 | cm_0136 | <code>   ```<br>aaa<br>  ```</code> |
| 137 | cm_0137 | <code>```<br>aaa<br>    ```</code> |
| 138 | cm_0138 | <code>``` ```<br>aaa</code> |
| 139 | cm_0139 | <code>~~~~~~<br>aaa<br>~~~ ~~</code> |
| 140 | cm_0140 | <code>foo<br>```<br>bar<br>```<br>baz</code> |
| 141 | cm_0141 | <code>foo<br>---<br>~~~<br>bar<br>~~~<br># baz</code> |
| 142 | cm_0142 | <code>```ruby<br>def foo(x)<br>  return 3<br>end<br>```</code> |
| 143 | cm_0143 | <code>~~~~    ruby startline=3 $%@#$<br>def foo(x)<br>  return 3<br>end<br>~~~~~~~</code> |
| 144 | cm_0144 | <code>````;<br>````</code> |
| 145 | cm_0145 | <code>``` aa ```<br>foo</code> |
| 146 | cm_0146 | <code>~~~ aa ``` ~~~<br>foo<br>~~~</code> |
| 147 | cm_0147 | <code>```<br>``` aaa<br>```</code> |
| 148 | cm_0148 | <code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;<br>&lt;pre&gt;<br>**Hello**,<br><br>_world_.<br>&lt;/pre&gt;<br>&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt;</code> |
| 149 | cm_0149 | <code>&lt;table&gt;<br>  &lt;tr&gt;<br>    &lt;td&gt;<br>           hi<br>    &lt;/td&gt;<br>  &lt;/tr&gt;<br>&lt;/table&gt;<br><br>okay.</code> |
| 150 | cm_0150 | <code> &lt;div&gt;<br>  *hello*<br>         &lt;foo&gt;&lt;a&gt;</code> |
| 151 | cm_0151 | <code>&lt;/div&gt;<br>*foo*</code> |
| 152 | cm_0152 | <code>&lt;DIV CLASS="foo"&gt;<br><br>*Markdown*<br><br>&lt;/DIV&gt;</code> |
| 153 | cm_0153 | <code>&lt;div id="foo"<br>  class="bar"&gt;<br>&lt;/div&gt;</code> |
| 154 | cm_0154 | <code>&lt;div id="foo" class="bar<br>  baz"&gt;<br>&lt;/div&gt;</code> |
| 155 | cm_0155 | <code>&lt;div&gt;<br>*foo*<br><br>*bar*</code> |
| 156 | cm_0156 | <code>&lt;div id="foo"<br>*hi*</code> |
| 157 | cm_0157 | <code>&lt;div class<br>foo</code> |
| 158 | cm_0158 | <code>&lt;div *???-&amp;&amp;&amp;-&lt;---<br>*foo*</code> |
| 159 | cm_0159 | <code>&lt;div&gt;&lt;a href="bar"&gt;*foo*&lt;/a&gt;&lt;/div&gt;</code> |
| 160 | cm_0160 | <code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;<br>foo<br>&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt;</code> |
| 161 | cm_0161 | <code>&lt;div&gt;&lt;/div&gt;<br>``` c<br>int x = 33;<br>```</code> |
| 162 | cm_0162 | <code>&lt;div<br>&gt; not quoted text</code> |
| 163 | cm_0163 | <code>&lt;a href="foo"&gt;<br>*bar*<br>&lt;/a&gt;</code> |
| 164 | cm_0164 | <code>&lt;Warning&gt;<br>*bar*<br>&lt;/Warning&gt;</code> |
| 165 | cm_0165 | <code>&lt;i class="foo"&gt;<br>*bar*<br>&lt;/i&gt;</code> |
| 166 | cm_0166 | <code>&lt;/ins&gt;<br>*bar*</code> |
| 167 | cm_0167 | <code>&lt;del&gt;<br>*foo*<br>&lt;/del&gt;</code> |
| 168 | cm_0168 | <code>&lt;del&gt;<br><br>*foo*<br><br>&lt;/del&gt;</code> |
| 169 | cm_0169 | <code>&lt;del&gt;*foo*&lt;/del&gt;</code> |
| 170 | cm_0170 | <code>&lt;del<br>class="foo"&gt;<br>*foo*<br>&lt;/del&gt;</code> |
| 171 | cm_0171 | <code>&lt;pre language="haskell"&gt;&lt;code&gt;<br>import Text.HTML.TagSoup<br><br>main :: IO ()<br>main = print $ parseTags tags<br>&lt;/code&gt;&lt;/pre&gt;<br>okay</code> |
| 172 | cm_0172 | <code>&lt;script type="text/javascript"&gt;<br>// JavaScript example<br><br>document.getElementById("demo").innerHTML = "Hello JavaScript!";<br>&lt;/script&gt;<br>okay</code> |
| 173 | cm_0173 | <code>&lt;textarea&gt;<br><br>*foo*<br><br>_bar_<br><br>&lt;/textarea&gt;</code> |
| 174 | cm_0174 | <code>&lt;style<br>  type="text/css"&gt;<br>h1 {color:red;}<br><br>p {color:blue;}<br>&lt;/style&gt;<br>okay</code> |
| 175 | cm_0175 | <code>&lt;style<br>  type="text/css"&gt;<br><br>foo</code> |
| 176 | cm_0176 | <code>&gt; &lt;div&gt;<br>&gt; foo<br><br>bar</code> |
| 177 | cm_0177 | <code>- &lt;div&gt;<br>- foo</code> |
| 178 | cm_0178 | <code>&lt;style&gt;p{color:red;}&lt;/style&gt;<br>*foo*</code> |
| 179 | cm_0179 | <code>&lt;!-- foo --&gt;*bar*<br>*baz*</code> |
| 180 | cm_0180 | <code>&lt;script&gt;<br>foo<br>&lt;/script&gt;1. *bar*</code> |
| 181 | cm_0181 | <code>&lt;!-- Foo<br><br>bar<br>   baz --&gt;<br>okay</code> |
| 182 | cm_0182 | <code>&lt;?php<br><br>  echo '&gt;';<br><br>?&gt;<br>okay</code> |
| 183 | cm_0183 | <code>&lt;!DOCTYPE html&gt;</code> |
| 184 | cm_0184 | <code>&lt;![CDATA[<br>function matchwo(a,b)<br>{<br>  if (a &lt; b &amp;&amp; a &lt; 0) then {<br>    return 1;<br><br>  } else {<br><br>    return 0;<br>  }<br>}<br>]]&gt;<br>okay</code> |
| 185 | cm_0185 | <code>  &lt;!-- foo --&gt;<br><br>    &lt;!-- foo --&gt;</code> |
| 186 | cm_0186 | <code>  &lt;div&gt;<br><br>    &lt;div&gt;</code> |
| 187 | cm_0187 | <code>Foo<br>&lt;div&gt;<br>bar<br>&lt;/div&gt;</code> |
| 188 | cm_0188 | <code>&lt;div&gt;<br>bar<br>&lt;/div&gt;<br>*foo*</code> |
| 189 | cm_0189 | <code>Foo<br>&lt;a href="bar"&gt;<br>baz</code> |
| 190 | cm_0190 | <code>&lt;div&gt;<br><br>*Emphasized* text.<br><br>&lt;/div&gt;</code> |
| 191 | cm_0191 | <code>&lt;div&gt;<br>*Emphasized* text.<br>&lt;/div&gt;</code> |
| 192 | cm_0192 | <code>&lt;table&gt;<br><br>&lt;tr&gt;<br><br>&lt;td&gt;<br>Hi<br>&lt;/td&gt;<br><br>&lt;/tr&gt;<br><br>&lt;/table&gt;</code> |
| 193 | cm_0193 | <code>&lt;table&gt;<br><br>  &lt;tr&gt;<br><br>    &lt;td&gt;<br>      Hi<br>    &lt;/td&gt;<br><br>  &lt;/tr&gt;<br><br>&lt;/table&gt;</code> |
| 194 | cm_0194 | <code>[foo]: /url "title"<br><br>[foo]</code> |
| 195 | cm_0195 | <code>   [foo]: <br>      /url  <br>           'the title'  <br><br>[foo]</code> |
| 196 | cm_0196 | <code>[Foo*bar\]]:my_(url) 'title (with parens)'<br><br>[Foo*bar\]]</code> |
| 197 | cm_0197 | <code>[Foo bar]:<br>&lt;my url&gt;<br>'title'<br><br>[Foo bar]</code> |
| 198 | cm_0198 | <code>[foo]: /url '<br>title<br>line1<br>line2<br>'<br><br>[foo]</code> |
| 199 | cm_0199 | <code>[foo]: /url 'title<br><br>with blank line'<br><br>[foo]</code> |
| 200 | cm_0200 | <code>[foo]:<br>/url<br><br>[foo]</code> |
| 201 | cm_0201 | <code>[foo]:<br><br>[foo]</code> |
| 202 | cm_0202 | <code>[foo]: &lt;&gt;<br><br>[foo]</code> |
| 203 | cm_0203 | <code>[foo]: &lt;bar&gt;(baz)<br><br>[foo]</code> |
| 204 | cm_0204 | <code>[foo]: /url\bar\*baz "foo\"bar\baz"<br><br>[foo]</code> |
| 205 | cm_0205 | <code>[foo]<br><br>[foo]: url</code> |
| 206 | cm_0206 | <code>[foo]<br><br>[foo]: first<br>[foo]: second</code> |
| 207 | cm_0207 | <code>[FOO]: /url<br><br>[Foo]</code> |
| 208 | cm_0208 | <code>[ΑΓΩ]: /φου<br><br>[αγω]</code> |
| 209 | cm_0209 | <code>[foo]: /url</code> |
| 210 | cm_0210 | <code>[foo]: /url "title" ok</code> |
| 211 | cm_0211 | <code>[foo]: /url<br>"title" ok</code> |
| 212 | cm_0212 | <code>    [foo]: /url "title"<br><br>[foo]</code> |
| 213 | cm_0213 | <code>```<br>[foo]: /url<br>```<br><br>[foo]</code> |
| 214 | cm_0214 | <code>Foo<br>[bar]: /baz<br><br>[bar]</code> |
| 215 | cm_0215 | <code># [Foo]<br>[foo]: /url<br>&gt; bar</code> |
| 216 | cm_0216 | <code>[foo]: /url<br>bar<br>===<br>[foo]</code> |
| 217 | cm_0217 | <code>[foo]: /url<br>===<br>[foo]</code> |
| 218 | cm_0218 | <code>[foo]: /foo-url "foo"<br>[bar]: /bar-url<br>  "bar"<br>[baz]: /baz-url<br><br>[foo],<br>[bar],<br>[baz]</code> |
| 219 | cm_0219 | <code>[foo]<br><br>&gt; [foo]: /url</code> |
| 220 | cm_0220 | <code>aaa<br><br>bbb</code> |
| 221 | cm_0221 | <code>aaa<br>bbb<br><br>ccc<br>ddd</code> |
| 222 | cm_0222 | <code>aaa<br><br><br>bbb</code> |
| 223 | cm_0223 | <code>  aaa<br> bbb</code> |
| 224 | cm_0224 | <code>aaa<br>             bbb<br>                                       ccc</code> |
| 225 | cm_0225 | <code>   aaa<br>bbb</code> |
| 226 | cm_0226 | <code>    aaa<br>bbb</code> |
| 227 | cm_0227 | <code>aaa     <br>bbb     </code> |
| 228 | cm_0228 | <code>  <br><br>aaa<br>  <br><br># aaa<br><br>  </code> |
| 229 | cm_0229 | <code>&gt; # Foo<br>&gt; bar<br>&gt; baz</code> |
| 230 | cm_0230 | <code>&gt;# Foo<br>&gt;bar<br>&gt; baz</code> |
| 231 | cm_0231 | <code>   &gt; # Foo<br>   &gt; bar<br> &gt; baz</code> |
| 232 | cm_0232 | <code>    &gt; # Foo<br>    &gt; bar<br>    &gt; baz</code> |
| 233 | cm_0233 | <code>&gt; # Foo<br>&gt; bar<br>baz</code> |
| 234 | cm_0234 | <code>&gt; bar<br>baz<br>&gt; foo</code> |
| 235 | cm_0235 | <code>&gt; foo<br>---</code> |
| 236 | cm_0236 | <code>&gt; - foo<br>- bar</code> |
| 237 | cm_0237 | <code>&gt;     foo<br>    bar</code> |
| 238 | cm_0238 | <code>&gt; ```<br>foo<br>```</code> |
| 239 | cm_0239 | <code>&gt; foo<br>    - bar</code> |
| 240 | cm_0240 | <code>&gt;</code> |
| 241 | cm_0241 | <code>&gt;<br>&gt;  <br>&gt; </code> |
| 242 | cm_0242 | <code>&gt;<br>&gt; foo<br>&gt;  </code> |
| 243 | cm_0243 | <code>&gt; foo<br><br>&gt; bar</code> |
| 244 | cm_0244 | <code>&gt; foo<br>&gt; bar</code> |
| 245 | cm_0245 | <code>&gt; foo<br>&gt;<br>&gt; bar</code> |
| 246 | cm_0246 | <code>foo<br>&gt; bar</code> |
| 247 | cm_0247 | <code>&gt; aaa<br>***<br>&gt; bbb</code> |
| 248 | cm_0248 | <code>&gt; bar<br>baz</code> |
| 249 | cm_0249 | <code>&gt; bar<br><br>baz</code> |
| 250 | cm_0250 | <code>&gt; bar<br>&gt;<br>baz</code> |
| 251 | cm_0251 | <code>&gt; &gt; &gt; foo<br>bar</code> |
| 252 | cm_0252 | <code>&gt;&gt;&gt; foo<br>&gt; bar<br>&gt;&gt;baz</code> |
| 253 | cm_0253 | <code>&gt;     code<br><br>&gt;    not code</code> |
| 254 | cm_0254 | <code>A paragraph<br>with two lines.<br><br>    indented code<br><br>&gt; A block quote.</code> |
| 255 | cm_0255 | <code>1.  A paragraph<br>    with two lines.<br><br>        indented code<br><br>    &gt; A block quote.</code> |
| 256 | cm_0256 | <code>- one<br><br> two</code> |
| 257 | cm_0257 | <code>- one<br><br>  two</code> |
| 258 | cm_0258 | <code> -    one<br><br>     two</code> |
| 259 | cm_0259 | <code> -    one<br><br>      two</code> |
| 260 | cm_0260 | <code>   &gt; &gt; 1.  one<br>&gt;&gt;<br>&gt;&gt;     two</code> |
| 261 | cm_0261 | <code>&gt;&gt;- one<br>&gt;&gt;<br>  &gt;  &gt; two</code> |
| 262 | cm_0262 | <code>-one<br><br>2.two</code> |
| 263 | cm_0263 | <code>- foo<br><br><br>  bar</code> |
| 264 | cm_0264 | <code>1.  foo<br><br>    ```<br>    bar<br>    ```<br><br>    baz<br><br>    &gt; bam</code> |
| 265 | cm_0265 | <code>- Foo<br><br>      bar<br><br><br>      baz</code> |
| 266 | cm_0266 | <code>123456789. ok</code> |
| 267 | cm_0267 | <code>1234567890. not ok</code> |
| 268 | cm_0268 | <code>0. ok</code> |
| 269 | cm_0269 | <code>003. ok</code> |
| 270 | cm_0270 | <code>-1. not ok</code> |
| 271 | cm_0271 | <code>- foo<br><br>      bar</code> |
| 272 | cm_0272 | <code>  10.  foo<br><br>           bar</code> |
| 273 | cm_0273 | <code>    indented code<br><br>paragraph<br><br>    more code</code> |
| 274 | cm_0274 | <code>1.     indented code<br><br>   paragraph<br><br>       more code</code> |
| 275 | cm_0275 | <code>1.      indented code<br><br>   paragraph<br><br>       more code</code> |
| 276 | cm_0276 | <code>   foo<br><br>bar</code> |
| 277 | cm_0277 | <code>-    foo<br><br>  bar</code> |
| 278 | cm_0278 | <code>-  foo<br><br>   bar</code> |
| 279 | cm_0279 | <code>-<br>  foo<br>-<br>  ```<br>  bar<br>  ```<br>-<br>      baz</code> |
| 280 | cm_0280 | <code>-   <br>  foo</code> |
| 281 | cm_0281 | <code>-<br><br>  foo</code> |
| 282 | cm_0282 | <code>- foo<br>-<br>- bar</code> |
| 283 | cm_0283 | <code>- foo<br>-   <br>- bar</code> |
| 284 | cm_0284 | <code>1. foo<br>2.<br>3. bar</code> |
| 285 | cm_0285 | <code>*</code> |
| 286 | cm_0286 | <code>foo<br>*<br><br>foo<br>1.</code> |
| 287 | cm_0287 | <code> 1.  A paragraph<br>     with two lines.<br><br>         indented code<br><br>     &gt; A block quote.</code> |
| 288 | cm_0288 | <code>  1.  A paragraph<br>      with two lines.<br><br>          indented code<br><br>      &gt; A block quote.</code> |
| 289 | cm_0289 | <code>   1.  A paragraph<br>       with two lines.<br><br>           indented code<br><br>       &gt; A block quote.</code> |
| 290 | cm_0290 | <code>    1.  A paragraph<br>        with two lines.<br><br>            indented code<br><br>        &gt; A block quote.</code> |
| 291 | cm_0291 | <code>  1.  A paragraph<br>with two lines.<br><br>          indented code<br><br>      &gt; A block quote.</code> |
| 292 | cm_0292 | <code>  1.  A paragraph<br>    with two lines.</code> |
| 293 | cm_0293 | <code>&gt; 1. &gt; Blockquote<br>continued here.</code> |
| 294 | cm_0294 | <code>&gt; 1. &gt; Blockquote<br>&gt; continued here.</code> |
| 295 | cm_0295 | <code>- foo<br>  - bar<br>    - baz<br>      - boo</code> |
| 296 | cm_0296 | <code>- foo<br> - bar<br>  - baz<br>   - boo</code> |
| 297 | cm_0297 | <code>10) foo<br>    - bar</code> |
| 298 | cm_0298 | <code>10) foo<br>   - bar</code> |
| 299 | cm_0299 | <code>- - foo</code> |
| 300 | cm_0300 | <code>1. - 2. foo</code> |
| 301 | cm_0301 | <code>- # Foo<br>- Bar<br>  ---<br>  baz</code> |
| 302 | cm_0302 | <code>- foo<br>- bar<br>+ baz</code> |
| 303 | cm_0303 | <code>1. foo<br>2. bar<br>3) baz</code> |
| 304 | cm_0304 | <code>Foo<br>- bar<br>- baz</code> |
| 305 | cm_0305 | <code>The number of windows in my house is<br>14.  The number of doors is 6.</code> |
| 306 | cm_0306 | <code>The number of windows in my house is<br>1.  The number of doors is 6.</code> |
| 307 | cm_0307 | <code>- foo<br><br>- bar<br><br><br>- baz</code> |
| 308 | cm_0308 | <code>- foo<br>  - bar<br>    - baz<br><br><br>      bim</code> |
| 309 | cm_0309 | <code>- foo<br>- bar<br><br>&lt;!-- --&gt;<br><br>- baz<br>- bim</code> |
| 310 | cm_0310 | <code>-   foo<br><br>    notcode<br><br>-   foo<br><br>&lt;!-- --&gt;<br><br>    code</code> |
| 311 | cm_0311 | <code>- a<br> - b<br>  - c<br>   - d<br>  - e<br> - f<br>- g</code> |
| 312 | cm_0312 | <code>1. a<br><br>  2. b<br><br>   3. c</code> |
| 313 | cm_0313 | <code>- a<br> - b<br>  - c<br>   - d<br>    - e</code> |
| 314 | cm_0314 | <code>1. a<br><br>  2. b<br><br>    3. c</code> |
| 315 | cm_0315 | <code>- a<br>- b<br><br>- c</code> |
| 316 | cm_0316 | <code>* a<br>*<br><br>* c</code> |
| 317 | cm_0317 | <code>- a<br>- b<br><br>  c<br>- d</code> |
| 318 | cm_0318 | <code>- a<br>- b<br><br>  [ref]: /url<br>- d</code> |
| 319 | cm_0319 | <code>- a<br>- ```<br>  b<br><br><br>  ```<br>- c</code> |
| 320 | cm_0320 | <code>- a<br>  - b<br><br>    c<br>- d</code> |
| 321 | cm_0321 | <code>* a<br>  &gt; b<br>  &gt;<br>* c</code> |
| 322 | cm_0322 | <code>- a<br>  &gt; b<br>  ```<br>  c<br>  ```<br>- d</code> |
| 323 | cm_0323 | <code>- a</code> |
| 324 | cm_0324 | <code>- a<br>  - b</code> |
| 325 | cm_0325 | <code>1. ```<br>   foo<br>   ```<br><br>   bar</code> |
| 326 | cm_0326 | <code>* foo<br>  * bar<br><br>  baz</code> |
| 327 | cm_0327 | <code>- a<br>  - b<br>  - c<br><br>- d<br>  - e<br>  - f</code> |
| 328 | cm_0328 | <code>`hi`lo`</code> |
| 329 | cm_0329 | <code>`foo`</code> |
| 330 | cm_0330 | <code>`` foo ` bar ``</code> |
| 331 | cm_0331 | <code>` `` `</code> |
| 332 | cm_0332 | <code>`  ``  `</code> |
| 333 | cm_0333 | <code>` a`</code> |
| 334 | cm_0334 | <code>` b `</code> |
| 335 | cm_0335 | <code>` `<br>`  `</code> |
| 336 | cm_0336 | <code>``<br>foo<br>bar  <br>baz<br>``</code> |
| 337 | cm_0337 | <code>``<br>foo <br>``</code> |
| 338 | cm_0338 | <code>`foo   bar <br>baz`</code> |
| 339 | cm_0339 | <code>`foo\`bar`</code> |
| 340 | cm_0340 | <code>``foo`bar``</code> |
| 341 | cm_0341 | <code>` foo `` bar `</code> |
| 342 | cm_0342 | <code>*foo`*`</code> |
| 343 | cm_0343 | <code>[not a `link](/foo`)</code> |
| 344 | cm_0344 | <code>`&lt;a href="`"&gt;`</code> |
| 345 | cm_0345 | <code>&lt;a href="`"&gt;`</code> |
| 346 | cm_0346 | <code>`&lt;https://foo.bar.`baz&gt;`</code> |
| 347 | cm_0347 | <code>&lt;https://foo.bar.`baz&gt;`</code> |
| 348 | cm_0348 | <code>```foo``</code> |
| 349 | cm_0349 | <code>`foo</code> |
| 350 | cm_0350 | <code>`foo``bar``</code> |
| 351 | cm_0351 | <code>*foo bar*</code> |
| 352 | cm_0352 | <code>a * foo bar*</code> |
| 353 | cm_0353 | <code>a*"foo"*</code> |
| 354 | cm_0354 | <code>* a *</code> |
| 355 | cm_0355 | <code>*$*alpha.<br><br>*£*bravo.<br><br>*€*charlie.<br><br>*𞋿*delta.</code> |
| 356 | cm_0356 | <code>foo*bar*</code> |
| 357 | cm_0357 | <code>5*6*78</code> |
| 358 | cm_0358 | <code>_foo bar_</code> |
| 359 | cm_0359 | <code>_ foo bar_</code> |
| 360 | cm_0360 | <code>a_"foo"_</code> |
| 361 | cm_0361 | <code>foo_bar_</code> |
| 362 | cm_0362 | <code>5_6_78</code> |
| 363 | cm_0363 | <code>пристаням_стремятся_</code> |
| 364 | cm_0364 | <code>aa_"bb"_cc</code> |
| 365 | cm_0365 | <code>foo-_(bar)_</code> |
| 366 | cm_0366 | <code>_foo*</code> |
| 367 | cm_0367 | <code>*foo bar *</code> |
| 368 | cm_0368 | <code>*foo bar<br>*</code> |
| 369 | cm_0369 | <code>*(*foo)</code> |
| 370 | cm_0370 | <code>*(*foo*)*</code> |
| 371 | cm_0371 | <code>*foo*bar</code> |
| 372 | cm_0372 | <code>_foo bar _</code> |
| 373 | cm_0373 | <code>_(_foo)</code> |
| 374 | cm_0374 | <code>_(_foo_)_</code> |
| 375 | cm_0375 | <code>_foo_bar</code> |
| 376 | cm_0376 | <code>_пристаням_стремятся</code> |
| 377 | cm_0377 | <code>_foo_bar_baz_</code> |
| 378 | cm_0378 | <code>_(bar)_.</code> |
| 379 | cm_0379 | <code>**foo bar**</code> |
| 380 | cm_0380 | <code>** foo bar**</code> |
| 381 | cm_0381 | <code>a**"foo"**</code> |
| 382 | cm_0382 | <code>foo**bar**</code> |
| 383 | cm_0383 | <code>__foo bar__</code> |
| 384 | cm_0384 | <code>__ foo bar__</code> |
| 385 | cm_0385 | <code>__<br>foo bar__</code> |
| 386 | cm_0386 | <code>a__"foo"__</code> |
| 387 | cm_0387 | <code>foo__bar__</code> |
| 388 | cm_0388 | <code>5__6__78</code> |
| 389 | cm_0389 | <code>пристаням__стремятся__</code> |
| 390 | cm_0390 | <code>__foo, __bar__, baz__</code> |
| 391 | cm_0391 | <code>foo-__(bar)__</code> |
| 392 | cm_0392 | <code>**foo bar **</code> |
| 393 | cm_0393 | <code>**(**foo)</code> |
| 394 | cm_0394 | <code>*(**foo**)*</code> |
| 395 | cm_0395 | <code>**Gomphocarpus (*Gomphocarpus physocarpus*, syn.<br>*Asclepias physocarpa*)**</code> |
| 396 | cm_0396 | <code>**foo "*bar*" foo**</code> |
| 397 | cm_0397 | <code>**foo**bar</code> |
| 398 | cm_0398 | <code>__foo bar __</code> |
| 399 | cm_0399 | <code>__(__foo)</code> |
| 400 | cm_0400 | <code>_(__foo__)_</code> |
| 401 | cm_0401 | <code>__foo__bar</code> |
| 402 | cm_0402 | <code>__пристаням__стремятся</code> |
| 403 | cm_0403 | <code>__foo__bar__baz__</code> |
| 404 | cm_0404 | <code>__(bar)__.</code> |
| 405 | cm_0405 | <code>*foo [bar](/url)*</code> |
| 406 | cm_0406 | <code>*foo<br>bar*</code> |
| 407 | cm_0407 | <code>_foo __bar__ baz_</code> |
| 408 | cm_0408 | <code>_foo _bar_ baz_</code> |
| 409 | cm_0409 | <code>__foo_ bar_</code> |
| 410 | cm_0410 | <code>*foo *bar**</code> |
| 411 | cm_0411 | <code>*foo **bar** baz*</code> |
| 412 | cm_0412 | <code>*foo**bar**baz*</code> |
| 413 | cm_0413 | <code>*foo**bar*</code> |
| 414 | cm_0414 | <code>***foo** bar*</code> |
| 415 | cm_0415 | <code>*foo **bar***</code> |
| 416 | cm_0416 | <code>*foo**bar***</code> |
| 417 | cm_0417 | <code>foo***bar***baz</code> |
| 418 | cm_0418 | <code>foo******bar*********baz</code> |
| 419 | cm_0419 | <code>*foo **bar *baz* bim** bop*</code> |
| 420 | cm_0420 | <code>*foo [*bar*](/url)*</code> |
| 421 | cm_0421 | <code>** is not an empty emphasis</code> |
| 422 | cm_0422 | <code>**** is not an empty strong emphasis</code> |
| 423 | cm_0423 | <code>**foo [bar](/url)**</code> |
| 424 | cm_0424 | <code>**foo<br>bar**</code> |
| 425 | cm_0425 | <code>__foo _bar_ baz__</code> |
| 426 | cm_0426 | <code>__foo __bar__ baz__</code> |
| 427 | cm_0427 | <code>____foo__ bar__</code> |
| 428 | cm_0428 | <code>**foo **bar****</code> |
| 429 | cm_0429 | <code>**foo *bar* baz**</code> |
| 430 | cm_0430 | <code>**foo*bar*baz**</code> |
| 431 | cm_0431 | <code>***foo* bar**</code> |
| 432 | cm_0432 | <code>**foo *bar***</code> |
| 433 | cm_0433 | <code>**foo *bar **baz**<br>bim* bop**</code> |
| 434 | cm_0434 | <code>**foo [*bar*](/url)**</code> |
| 435 | cm_0435 | <code>__ is not an empty emphasis</code> |
| 436 | cm_0436 | <code>____ is not an empty strong emphasis</code> |
| 437 | cm_0437 | <code>foo ***</code> |
| 438 | cm_0438 | <code>foo *\**</code> |
| 439 | cm_0439 | <code>foo *_*</code> |
| 440 | cm_0440 | <code>foo *****</code> |
| 441 | cm_0441 | <code>foo **\***</code> |
| 442 | cm_0442 | <code>foo **_**</code> |
| 443 | cm_0443 | <code>**foo*</code> |
| 444 | cm_0444 | <code>*foo**</code> |
| 445 | cm_0445 | <code>***foo**</code> |
| 446 | cm_0446 | <code>****foo*</code> |
| 447 | cm_0447 | <code>**foo***</code> |
| 448 | cm_0448 | <code>*foo****</code> |
| 449 | cm_0449 | <code>foo ___</code> |
| 450 | cm_0450 | <code>foo _\__</code> |
| 451 | cm_0451 | <code>foo _*_</code> |
| 452 | cm_0452 | <code>foo _____</code> |
| 453 | cm_0453 | <code>foo __\___</code> |
| 454 | cm_0454 | <code>foo __*__</code> |
| 455 | cm_0455 | <code>__foo_</code> |
| 456 | cm_0456 | <code>_foo__</code> |
| 457 | cm_0457 | <code>___foo__</code> |
| 458 | cm_0458 | <code>____foo_</code> |
| 459 | cm_0459 | <code>__foo___</code> |
| 460 | cm_0460 | <code>_foo____</code> |
| 461 | cm_0461 | <code>**foo**</code> |
| 462 | cm_0462 | <code>*_foo_*</code> |
| 463 | cm_0463 | <code>__foo__</code> |
| 464 | cm_0464 | <code>_*foo*_</code> |
| 465 | cm_0465 | <code>****foo****</code> |
| 466 | cm_0466 | <code>____foo____</code> |
| 467 | cm_0467 | <code>******foo******</code> |
| 468 | cm_0468 | <code>***foo***</code> |
| 469 | cm_0469 | <code>_____foo_____</code> |
| 470 | cm_0470 | <code>*foo _bar* baz_</code> |
| 471 | cm_0471 | <code>*foo __bar *baz bim__ bam*</code> |
| 472 | cm_0472 | <code>**foo **bar baz**</code> |
| 473 | cm_0473 | <code>*foo *bar baz*</code> |
| 474 | cm_0474 | <code>*[bar*](/url)</code> |
| 475 | cm_0475 | <code>_foo [bar_](/url)</code> |
| 476 | cm_0476 | <code>*&lt;img src="foo" title="*"/&gt;</code> |
| 477 | cm_0477 | <code>**&lt;a href="**"&gt;</code> |
| 478 | cm_0478 | <code>__&lt;a href="__"&gt;</code> |
| 479 | cm_0479 | <code>*a `*`*</code> |
| 480 | cm_0480 | <code>_a `_`_</code> |
| 481 | cm_0481 | <code>**a&lt;https://foo.bar/?q=**&gt;</code> |
| 482 | cm_0482 | <code>__a&lt;https://foo.bar/?q=__&gt;</code> |
| 483 | cm_0483 | <code>[link](/uri "title")</code> |
| 484 | cm_0484 | <code>[link](/uri)</code> |
| 485 | cm_0485 | <code>[](./target.md)</code> |
| 486 | cm_0486 | <code>[link]()</code> |
| 487 | cm_0487 | <code>[link](&lt;&gt;)</code> |
| 488 | cm_0488 | <code>[]()</code> |
| 489 | cm_0489 | <code>[link](/my uri)</code> |
| 490 | cm_0490 | <code>[link](&lt;/my uri&gt;)</code> |
| 491 | cm_0491 | <code>[link](foo<br>bar)</code> |
| 492 | cm_0492 | <code>[link](&lt;foo<br>bar&gt;)</code> |
| 493 | cm_0493 | <code>[a](&lt;b)c&gt;)</code> |
| 494 | cm_0494 | <code>[link](&lt;foo\&gt;)</code> |
| 495 | cm_0495 | <code>[a](&lt;b)c<br>[a](&lt;b)c&gt;<br>[a](&lt;b&gt;c)</code> |
| 496 | cm_0496 | <code>[link](\(foo\))</code> |
| 497 | cm_0497 | <code>[link](foo(and(bar)))</code> |
| 498 | cm_0498 | <code>[link](foo(and(bar))</code> |
| 499 | cm_0499 | <code>[link](foo\(and\(bar\))</code> |
| 500 | cm_0500 | <code>[link](&lt;foo(and(bar)&gt;)</code> |
| 501 | cm_0501 | <code>[link](foo\)\:)</code> |
| 502 | cm_0502 | <code>[link](#fragment)<br><br>[link](https://example.com#fragment)<br><br>[link](https://example.com?foo=3#frag)</code> |
| 503 | cm_0503 | <code>[link](foo\bar)</code> |
| 504 | cm_0504 | <code>[link](foo%20b&amp;auml;)</code> |
| 505 | cm_0505 | <code>[link]("title")</code> |
| 506 | cm_0506 | <code>[link](/url "title")<br>[link](/url 'title')<br>[link](/url (title))</code> |
| 507 | cm_0507 | <code>[link](/url "title \"&amp;quot;")</code> |
| 508 | cm_0508 | <code>[link](/url "title")</code> |
| 509 | cm_0509 | <code>[link](/url "title "and" title")</code> |
| 510 | cm_0510 | <code>[link](/url 'title "and" title')</code> |
| 511 | cm_0511 | <code>[link](   /uri<br>  "title"  )</code> |
| 512 | cm_0512 | <code>[link] (/uri)</code> |
| 513 | cm_0513 | <code>[link [foo [bar]]](/uri)</code> |
| 514 | cm_0514 | <code>[link] bar](/uri)</code> |
| 515 | cm_0515 | <code>[link [bar](/uri)</code> |
| 516 | cm_0516 | <code>[link \[bar](/uri)</code> |
| 517 | cm_0517 | <code>[link *foo **bar** `#`*](/uri)</code> |
| 518 | cm_0518 | <code>[![moon](moon.jpg)](/uri)</code> |
| 519 | cm_0519 | <code>[foo [bar](/uri)](/uri)</code> |
| 520 | cm_0520 | <code>[foo *[bar [baz](/uri)](/uri)*](/uri)</code> |
| 521 | cm_0521 | <code>![[[foo](uri1)](uri2)](uri3)</code> |
| 522 | cm_0522 | <code>*[foo*](/uri)</code> |
| 523 | cm_0523 | <code>[foo *bar](baz*)</code> |
| 524 | cm_0524 | <code>*foo [bar* baz]</code> |
| 525 | cm_0525 | <code>[foo &lt;bar attr="](baz)"&gt;</code> |
| 526 | cm_0526 | <code>[foo`](/uri)`</code> |
| 527 | cm_0527 | <code>[foo&lt;https://example.com/?search=](uri)&gt;</code> |
| 528 | cm_0528 | <code>[foo][bar]<br><br>[bar]: /url "title"</code> |
| 529 | cm_0529 | <code>[link [foo [bar]]][ref]<br><br>[ref]: /uri</code> |
| 530 | cm_0530 | <code>[link \[bar][ref]<br><br>[ref]: /uri</code> |
| 531 | cm_0531 | <code>[link *foo **bar** `#`*][ref]<br><br>[ref]: /uri</code> |
| 532 | cm_0532 | <code>[![moon](moon.jpg)][ref]<br><br>[ref]: /uri</code> |
| 533 | cm_0533 | <code>[foo [bar](/uri)][ref]<br><br>[ref]: /uri</code> |
| 534 | cm_0534 | <code>[foo *bar [baz][ref]*][ref]<br><br>[ref]: /uri</code> |
| 535 | cm_0535 | <code>*[foo*][ref]<br><br>[ref]: /uri</code> |
| 536 | cm_0536 | <code>[foo *bar][ref]*<br><br>[ref]: /uri</code> |
| 537 | cm_0537 | <code>[foo &lt;bar attr="][ref]"&gt;<br><br>[ref]: /uri</code> |
| 538 | cm_0538 | <code>[foo`][ref]`<br><br>[ref]: /uri</code> |
| 539 | cm_0539 | <code>[foo&lt;https://example.com/?search=][ref]&gt;<br><br>[ref]: /uri</code> |
| 540 | cm_0540 | <code>[foo][BaR]<br><br>[bar]: /url "title"</code> |
| 541 | cm_0541 | <code>[ẞ]<br><br>[SS]: /url</code> |
| 542 | cm_0542 | <code>[Foo<br>  bar]: /url<br><br>[Baz][Foo bar]</code> |
| 543 | cm_0543 | <code>[foo] [bar]<br><br>[bar]: /url "title"</code> |
| 544 | cm_0544 | <code>[foo]<br>[bar]<br><br>[bar]: /url "title"</code> |
| 545 | cm_0545 | <code>[foo]: /url1<br><br>[foo]: /url2<br><br>[bar][foo]</code> |
| 546 | cm_0546 | <code>[bar][foo\!]<br><br>[foo!]: /url</code> |
| 547 | cm_0547 | <code>[foo][ref[]<br><br>[ref[]: /uri</code> |
| 548 | cm_0548 | <code>[foo][ref[bar]]<br><br>[ref[bar]]: /uri</code> |
| 549 | cm_0549 | <code>[[[foo]]]<br><br>[[[foo]]]: /url</code> |
| 550 | cm_0550 | <code>[foo][ref\[]<br><br>[ref\[]: /uri</code> |
| 551 | cm_0551 | <code>[bar\\]: /uri<br><br>[bar\\]</code> |
| 552 | cm_0552 | <code>[]<br><br>[]: /uri</code> |
| 553 | cm_0553 | <code>[<br> ]<br><br>[<br> ]: /uri</code> |
| 554 | cm_0554 | <code>[foo][]<br><br>[foo]: /url "title"</code> |
| 555 | cm_0555 | <code>[*foo* bar][]<br><br>[*foo* bar]: /url "title"</code> |
| 556 | cm_0556 | <code>[Foo][]<br><br>[foo]: /url "title"</code> |
| 557 | cm_0557 | <code>[foo] <br>[]<br><br>[foo]: /url "title"</code> |
| 558 | cm_0558 | <code>[foo]<br><br>[foo]: /url "title"</code> |
| 559 | cm_0559 | <code>[*foo* bar]<br><br>[*foo* bar]: /url "title"</code> |
| 560 | cm_0560 | <code>[[*foo* bar]]<br><br>[*foo* bar]: /url "title"</code> |
| 561 | cm_0561 | <code>[[bar [foo]<br><br>[foo]: /url</code> |
| 562 | cm_0562 | <code>[Foo]<br><br>[foo]: /url "title"</code> |
| 563 | cm_0563 | <code>[foo] bar<br><br>[foo]: /url</code> |
| 564 | cm_0564 | <code>\[foo]<br><br>[foo]: /url "title"</code> |
| 565 | cm_0565 | <code>[foo*]: /url<br><br>*[foo*]</code> |
| 566 | cm_0566 | <code>[foo][bar]<br><br>[foo]: /url1<br>[bar]: /url2</code> |
| 567 | cm_0567 | <code>[foo][]<br><br>[foo]: /url1</code> |
| 568 | cm_0568 | <code>[foo]()<br><br>[foo]: /url1</code> |
| 569 | cm_0569 | <code>[foo](not a link)<br><br>[foo]: /url1</code> |
| 570 | cm_0570 | <code>[foo][bar][baz]<br><br>[baz]: /url</code> |
| 571 | cm_0571 | <code>[foo][bar][baz]<br><br>[baz]: /url1<br>[bar]: /url2</code> |
| 572 | cm_0572 | <code>[foo][bar][baz]<br><br>[baz]: /url1<br>[foo]: /url2</code> |
| 573 | cm_0573 | <code>![foo](/url "title")</code> |
| 574 | cm_0574 | <code>![foo *bar*]<br><br>[foo *bar*]: train.jpg "train &amp; tracks"</code> |
| 575 | cm_0575 | <code>![foo ![bar](/url)](/url2)</code> |
| 576 | cm_0576 | <code>![foo [bar](/url)](/url2)</code> |
| 577 | cm_0577 | <code>![foo *bar*][]<br><br>[foo *bar*]: train.jpg "train &amp; tracks"</code> |
| 578 | cm_0578 | <code>![foo *bar*][foobar]<br><br>[FOOBAR]: train.jpg "train &amp; tracks"</code> |
| 579 | cm_0579 | <code>![foo](train.jpg)</code> |
| 580 | cm_0580 | <code>My ![foo bar](/path/to/train.jpg  "title"   )</code> |
| 581 | cm_0581 | <code>![foo](&lt;url&gt;)</code> |
| 582 | cm_0582 | <code>![](/url)</code> |
| 583 | cm_0583 | <code>![foo][bar]<br><br>[bar]: /url</code> |
| 584 | cm_0584 | <code>![foo][bar]<br><br>[BAR]: /url</code> |
| 585 | cm_0585 | <code>![foo][]<br><br>[foo]: /url "title"</code> |
| 586 | cm_0586 | <code>![*foo* bar][]<br><br>[*foo* bar]: /url "title"</code> |
| 587 | cm_0587 | <code>![Foo][]<br><br>[foo]: /url "title"</code> |
| 588 | cm_0588 | <code>![foo] <br>[]<br><br>[foo]: /url "title"</code> |
| 589 | cm_0589 | <code>![foo]<br><br>[foo]: /url "title"</code> |
| 590 | cm_0590 | <code>![*foo* bar]<br><br>[*foo* bar]: /url "title"</code> |
| 591 | cm_0591 | <code>![[foo]]<br><br>[[foo]]: /url "title"</code> |
| 592 | cm_0592 | <code>![Foo]<br><br>[foo]: /url "title"</code> |
| 593 | cm_0593 | <code>!\[foo]<br><br>[foo]: /url "title"</code> |
| 594 | cm_0594 | <code>\![foo]<br><br>[foo]: /url "title"</code> |
| 595 | cm_0595 | <code>&lt;http://foo.bar.baz&gt;</code> |
| 596 | cm_0596 | <code>&lt;https://foo.bar.baz/test?q=hello&amp;id=22&amp;boolean&gt;</code> |
| 597 | cm_0597 | <code>&lt;irc://foo.bar:2233/baz&gt;</code> |
| 598 | cm_0598 | <code>&lt;MAILTO:FOO@BAR.BAZ&gt;</code> |
| 599 | cm_0599 | <code>&lt;a+b+c:d&gt;</code> |
| 600 | cm_0600 | <code>&lt;made-up-scheme://foo,bar&gt;</code> |
| 601 | cm_0601 | <code>&lt;https://../&gt;</code> |
| 602 | cm_0602 | <code>&lt;localhost:5001/foo&gt;</code> |
| 603 | cm_0603 | <code>&lt;https://foo.bar/baz bim&gt;</code> |
| 604 | cm_0604 | <code>&lt;https://example.com/\[\&gt;</code> |
| 605 | cm_0605 | <code>&lt;foo@bar.example.com&gt;</code> |
| 606 | cm_0606 | <code>&lt;foo+special@Bar.baz-bar0.com&gt;</code> |
| 607 | cm_0607 | <code>&lt;foo\+@bar.example.com&gt;</code> |
| 608 | cm_0608 | <code>&lt;&gt;</code> |
| 609 | cm_0609 | <code>&lt; https://foo.bar &gt;</code> |
| 610 | cm_0610 | <code>&lt;m:abc&gt;</code> |
| 611 | cm_0611 | <code>&lt;foo.bar.baz&gt;</code> |
| 612 | cm_0612 | <code>https://example.com</code> |
| 613 | cm_0613 | <code>foo@bar.example.com</code> |
| 614 | cm_0614 | <code>&lt;a&gt;&lt;bab&gt;&lt;c2c&gt;</code> |
| 615 | cm_0615 | <code>&lt;a/&gt;&lt;b2/&gt;</code> |
| 616 | cm_0616 | <code>&lt;a  /&gt;&lt;b2<br>data="foo" &gt;</code> |
| 617 | cm_0617 | <code>&lt;a foo="bar" bam = 'baz &lt;em&gt;"&lt;/em&gt;'<br>_boolean zoop:33=zoop:33 /&gt;</code> |
| 618 | cm_0618 | <code>Foo &lt;responsive-image src="foo.jpg" /&gt;</code> |
| 619 | cm_0619 | <code>&lt;33&gt; &lt;__&gt;</code> |
| 620 | cm_0620 | <code>&lt;a h*#ref="hi"&gt;</code> |
| 621 | cm_0621 | <code>&lt;a href="hi'&gt; &lt;a href=hi'&gt;</code> |
| 622 | cm_0622 | <code>&lt; a&gt;&lt;<br>foo&gt;&lt;bar/ &gt;<br>&lt;foo bar=baz<br>bim!bop /&gt;</code> |
| 623 | cm_0623 | <code>&lt;a href='bar'title=title&gt;</code> |
| 624 | cm_0624 | <code>&lt;/a&gt;&lt;/foo &gt;</code> |
| 625 | cm_0625 | <code>&lt;/a href="foo"&gt;</code> |
| 626 | cm_0626 | <code>foo &lt;!-- this is a --<br>comment - with hyphens --&gt;</code> |
| 627 | cm_0627 | <code>foo &lt;!--&gt; foo --&gt;<br><br>foo &lt;!---&gt; foo --&gt;</code> |
| 628 | cm_0628 | <code>foo &lt;?php echo $a; ?&gt;</code> |
| 629 | cm_0629 | <code>foo &lt;!ELEMENT br EMPTY&gt;</code> |
| 630 | cm_0630 | <code>foo &lt;![CDATA[&gt;&amp;&lt;]]&gt;</code> |
| 631 | cm_0631 | <code>foo &lt;a href="&amp;ouml;"&gt;</code> |
| 632 | cm_0632 | <code>foo &lt;a href="\*"&gt;</code> |
| 633 | cm_0633 | <code>&lt;a href="\""&gt;</code> |
| 634 | cm_0634 | <code>&lt;a<br>&gt; quoted text</code> |
| 635 | cm_0635 | <code>foo  <br>baz</code> |
| 636 | cm_0636 | <code>foo\<br>baz</code> |
| 637 | cm_0637 | <code>foo       <br>baz</code> |
| 638 | cm_0638 | <code>foo  <br>     bar</code> |
| 639 | cm_0639 | <code>foo\<br>     bar</code> |
| 640 | cm_0640 | <code>*foo  <br>bar*</code> |
| 641 | cm_0641 | <code>*foo\<br>bar*</code> |
| 642 | cm_0642 | <code>`code  <br>span`</code> |
| 643 | cm_0643 | <code>`code\<br>span`</code> |
| 644 | cm_0644 | <code>&lt;a href="foo  <br>bar"&gt;</code> |
| 645 | cm_0645 | <code>&lt;a href="foo\<br>bar"&gt;</code> |
| 646 | cm_0646 | <code>foo\</code> |
| 647 | cm_0647 | <code>foo  </code> |
| 648 | cm_0648 | <code>### foo\</code> |
| 649 | cm_0649 | <code>### foo  </code> |
| 650 | cm_0650 | <code>foo<br>baz</code> |
| 651 | cm_0651 | <code>foo <br> baz</code> |
| 652 | cm_0652 | <code>hello $.;'there</code> |
| 653 | cm_0653 | <code>Foo χρῆν</code> |
| 654 | cm_0654 | <code>Multiple     spaces</code> |
