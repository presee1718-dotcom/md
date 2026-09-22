# GFM 스펙 세트 (646개)

각 행 = 예제 한 개. 소스는 원본 마크다운(escape 표시). 렌더 대조는 quality_compare.xlsx 참조.

| 번호 | 파일명 | 소스 |
|---:|---|---|
| 1 | gfm_0001 | <code>&nbsp;&nbsp;&nbsp;&nbsp;foo&nbsp;&nbsp;&nbsp;&nbsp;baz&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bim</code> |
| 2 | gfm_0002 | <code>  &nbsp;&nbsp;&nbsp;&nbsp;foo&nbsp;&nbsp;&nbsp;&nbsp;baz&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bim</code> |
| 3 | gfm_0003 | <code>    a&nbsp;&nbsp;&nbsp;&nbsp;a<br>    ὐ&nbsp;&nbsp;&nbsp;&nbsp;a</code> |
| 4 | gfm_0004 | <code>  - foo<br><br>&nbsp;&nbsp;&nbsp;&nbsp;bar</code> |
| 5 | gfm_0005 | <code>- foo<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bar</code> |
| 6 | gfm_0006 | <code>&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;foo</code> |
| 7 | gfm_0007 | <code>-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;foo</code> |
| 8 | gfm_0008 | <code>    foo<br>&nbsp;&nbsp;&nbsp;&nbsp;bar</code> |
| 9 | gfm_0009 | <code> - foo<br>   - bar<br>&nbsp;&nbsp;&nbsp;&nbsp; - baz</code> |
| 10 | gfm_0010 | <code>#&nbsp;&nbsp;&nbsp;&nbsp;Foo</code> |
| 11 | gfm_0011 | <code>*&nbsp;&nbsp;&nbsp;&nbsp;*&nbsp;&nbsp;&nbsp;&nbsp;*&nbsp;&nbsp;&nbsp;&nbsp;</code> |
| 12 | gfm_0012 | <code>- `one<br>- two`</code> |
| 13 | gfm_0013 | <code>***<br>---<br>___</code> |
| 14 | gfm_0014 | <code>+++</code> |
| 15 | gfm_0015 | <code>===</code> |
| 16 | gfm_0016 | <code>--<br>**<br>__</code> |
| 17 | gfm_0017 | <code> ***<br>  ***<br>   ***</code> |
| 18 | gfm_0018 | <code>    ***</code> |
| 19 | gfm_0019 | <code>Foo<br>    ***</code> |
| 20 | gfm_0020 | <code>_____________________________________</code> |
| 21 | gfm_0021 | <code> - - -</code> |
| 22 | gfm_0022 | <code> **  * ** * ** * **</code> |
| 23 | gfm_0023 | <code>-     -      -      -</code> |
| 24 | gfm_0024 | <code>- - - -    </code> |
| 25 | gfm_0025 | <code>_ _ _ _ a<br><br>a------<br><br>---a---</code> |
| 26 | gfm_0026 | <code> *-*</code> |
| 27 | gfm_0027 | <code>- foo<br>***<br>- bar</code> |
| 28 | gfm_0028 | <code>Foo<br>***<br>bar</code> |
| 29 | gfm_0029 | <code>Foo<br>---<br>bar</code> |
| 30 | gfm_0030 | <code>* Foo<br>* * *<br>* Bar</code> |
| 31 | gfm_0031 | <code>- Foo<br>- * * *</code> |
| 32 | gfm_0032 | <code># foo<br>## foo<br>### foo<br>#### foo<br>##### foo<br>###### foo</code> |
| 33 | gfm_0033 | <code>####### foo</code> |
| 34 | gfm_0034 | <code>#5 bolt<br><br>#hashtag</code> |
| 35 | gfm_0035 | <code>\## foo</code> |
| 36 | gfm_0036 | <code># foo *bar* \*baz\*</code> |
| 37 | gfm_0037 | <code>#                  foo                     </code> |
| 38 | gfm_0038 | <code> ### foo<br>  ## foo<br>   # foo</code> |
| 39 | gfm_0039 | <code>    # foo</code> |
| 40 | gfm_0040 | <code>foo<br>    # bar</code> |
| 41 | gfm_0041 | <code>## foo ##<br>  ###   bar    ###</code> |
| 42 | gfm_0042 | <code># foo ##################################<br>##### foo ##</code> |
| 43 | gfm_0043 | <code>### foo ###     </code> |
| 44 | gfm_0044 | <code>### foo ### b</code> |
| 45 | gfm_0045 | <code># foo#</code> |
| 46 | gfm_0046 | <code>### foo \###<br>## foo #\##<br># foo \#</code> |
| 47 | gfm_0047 | <code>****<br>## foo<br>****</code> |
| 48 | gfm_0048 | <code>Foo bar<br># baz<br>Bar foo</code> |
| 49 | gfm_0049 | <code>## <br>#<br>### ###</code> |
| 50 | gfm_0050 | <code>Foo *bar*<br>=========<br><br>Foo *bar*<br>---------</code> |
| 51 | gfm_0051 | <code>Foo *bar<br>baz*<br>====</code> |
| 52 | gfm_0052 | <code>  Foo *bar<br>baz*&nbsp;&nbsp;&nbsp;&nbsp;<br>====</code> |
| 53 | gfm_0053 | <code>Foo<br>-------------------------<br><br>Foo<br>=</code> |
| 54 | gfm_0054 | <code>   Foo<br>---<br><br>  Foo<br>-----<br><br>  Foo<br>  ===</code> |
| 55 | gfm_0055 | <code>    Foo<br>    ---<br><br>    Foo<br>---</code> |
| 56 | gfm_0056 | <code>Foo<br>   ----      </code> |
| 57 | gfm_0057 | <code>Foo<br>    ---</code> |
| 58 | gfm_0058 | <code>Foo<br>= =<br><br>Foo<br>--- -</code> |
| 59 | gfm_0059 | <code>Foo  <br>-----</code> |
| 60 | gfm_0060 | <code>Foo\<br>----</code> |
| 61 | gfm_0061 | <code>`Foo<br>----<br>`<br><br>&lt;a title="a lot<br>---<br>of dashes"/&gt;</code> |
| 62 | gfm_0062 | <code>&gt; Foo<br>---</code> |
| 63 | gfm_0063 | <code>&gt; foo<br>bar<br>===</code> |
| 64 | gfm_0064 | <code>- Foo<br>---</code> |
| 65 | gfm_0065 | <code>Foo<br>Bar<br>---</code> |
| 66 | gfm_0066 | <code>---<br>Foo<br>---<br>Bar<br>---<br>Baz</code> |
| 67 | gfm_0067 | <code><br>====</code> |
| 68 | gfm_0068 | <code>---<br>---</code> |
| 69 | gfm_0069 | <code>- foo<br>-----</code> |
| 70 | gfm_0070 | <code>    foo<br>---</code> |
| 71 | gfm_0071 | <code>&gt; foo<br>-----</code> |
| 72 | gfm_0072 | <code>\&gt; foo<br>------</code> |
| 73 | gfm_0073 | <code>Foo<br><br>bar<br>---<br>baz</code> |
| 74 | gfm_0074 | <code>Foo<br>bar<br><br>---<br><br>baz</code> |
| 75 | gfm_0075 | <code>Foo<br>bar<br>* * *<br>baz</code> |
| 76 | gfm_0076 | <code>Foo<br>bar<br>\---<br>baz</code> |
| 77 | gfm_0077 | <code>    a simple<br>      indented code block</code> |
| 78 | gfm_0078 | <code>  - foo<br><br>    bar</code> |
| 79 | gfm_0079 | <code>1.  foo<br><br>    - bar</code> |
| 80 | gfm_0080 | <code>    &lt;a/&gt;<br>    *hi*<br><br>    - one</code> |
| 81 | gfm_0081 | <code>    chunk1<br><br>    chunk2<br>  <br> <br> <br>    chunk3</code> |
| 82 | gfm_0082 | <code>    chunk1<br>      <br>      chunk2</code> |
| 83 | gfm_0083 | <code>Foo<br>    bar</code> |
| 84 | gfm_0084 | <code>    foo<br>bar</code> |
| 85 | gfm_0085 | <code># Heading<br>    foo<br>Heading<br>------<br>    foo<br>----</code> |
| 86 | gfm_0086 | <code>        foo<br>    bar</code> |
| 87 | gfm_0087 | <code><br>    <br>    foo<br>    </code> |
| 88 | gfm_0088 | <code>    foo  </code> |
| 89 | gfm_0089 | <code>```<br>&lt;<br> &gt;<br>```</code> |
| 90 | gfm_0090 | <code>~~~<br>&lt;<br> &gt;<br>~~~</code> |
| 91 | gfm_0091 | <code>``<br>foo<br>``</code> |
| 92 | gfm_0092 | <code>```<br>aaa<br>~~~<br>```</code> |
| 93 | gfm_0093 | <code>~~~<br>aaa<br>```<br>~~~</code> |
| 94 | gfm_0094 | <code>````<br>aaa<br>```<br>``````</code> |
| 95 | gfm_0095 | <code>~~~~<br>aaa<br>~~~<br>~~~~</code> |
| 96 | gfm_0096 | <code>```</code> |
| 97 | gfm_0097 | <code>`````<br><br>```<br>aaa</code> |
| 98 | gfm_0098 | <code>&gt; ```<br>&gt; aaa<br><br>bbb</code> |
| 99 | gfm_0099 | <code>```<br><br>  <br>```</code> |
| 100 | gfm_0100 | <code>```<br>```</code> |
| 101 | gfm_0101 | <code> ```<br> aaa<br>aaa<br>```</code> |
| 102 | gfm_0102 | <code>  ```<br>aaa<br>  aaa<br>aaa<br>  ```</code> |
| 103 | gfm_0103 | <code>   ```<br>   aaa<br>    aaa<br>  aaa<br>   ```</code> |
| 104 | gfm_0104 | <code>    ```<br>    aaa<br>    ```</code> |
| 105 | gfm_0105 | <code>```<br>aaa<br>  ```</code> |
| 106 | gfm_0106 | <code>   ```<br>aaa<br>  ```</code> |
| 107 | gfm_0107 | <code>```<br>aaa<br>    ```</code> |
| 108 | gfm_0108 | <code>``` ```<br>aaa</code> |
| 109 | gfm_0109 | <code>~~~~~~<br>aaa<br>~~~ ~~</code> |
| 110 | gfm_0110 | <code>foo<br>```<br>bar<br>```<br>baz</code> |
| 111 | gfm_0111 | <code>foo<br>---<br>~~~<br>bar<br>~~~<br># baz</code> |
| 112 | gfm_0112 | <code>```ruby<br>def foo(x)<br>  return 3<br>end<br>```</code> |
| 113 | gfm_0113 | <code>~~~~    ruby startline=3 $%@#$<br>def foo(x)<br>  return 3<br>end<br>~~~~~~~</code> |
| 114 | gfm_0114 | <code>````;<br>````</code> |
| 115 | gfm_0115 | <code>``` aa ```<br>foo</code> |
| 116 | gfm_0116 | <code>~~~ aa ``` ~~~<br>foo<br>~~~</code> |
| 117 | gfm_0117 | <code>```<br>``` aaa<br>```</code> |
| 118 | gfm_0118 | <code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;<br>&lt;pre&gt;<br>**Hello**,<br><br>_world_.<br>&lt;/pre&gt;<br>&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt;</code> |
| 119 | gfm_0119 | <code>&lt;table&gt;<br>  &lt;tr&gt;<br>    &lt;td&gt;<br>           hi<br>    &lt;/td&gt;<br>  &lt;/tr&gt;<br>&lt;/table&gt;<br><br>okay.</code> |
| 120 | gfm_0120 | <code> &lt;div&gt;<br>  *hello*<br>         &lt;foo&gt;&lt;a&gt;</code> |
| 121 | gfm_0121 | <code>&lt;/div&gt;<br>*foo*</code> |
| 122 | gfm_0122 | <code>&lt;DIV CLASS="foo"&gt;<br><br>*Markdown*<br><br>&lt;/DIV&gt;</code> |
| 123 | gfm_0123 | <code>&lt;div id="foo"<br>  class="bar"&gt;<br>&lt;/div&gt;</code> |
| 124 | gfm_0124 | <code>&lt;div id="foo" class="bar<br>  baz"&gt;<br>&lt;/div&gt;</code> |
| 125 | gfm_0125 | <code>&lt;div&gt;<br>*foo*<br><br>*bar*</code> |
| 126 | gfm_0126 | <code>&lt;div id="foo"<br>*hi*</code> |
| 127 | gfm_0127 | <code>&lt;div class<br>foo</code> |
| 128 | gfm_0128 | <code>&lt;div *???-&amp;&amp;&amp;-&lt;---<br>*foo*</code> |
| 129 | gfm_0129 | <code>&lt;div&gt;&lt;a href="bar"&gt;*foo*&lt;/a&gt;&lt;/div&gt;</code> |
| 130 | gfm_0130 | <code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;<br>foo<br>&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt;</code> |
| 131 | gfm_0131 | <code>&lt;div&gt;&lt;/div&gt;<br>``` c<br>int x = 33;<br>```</code> |
| 132 | gfm_0132 | <code>&lt;a href="foo"&gt;<br>*bar*<br>&lt;/a&gt;</code> |
| 133 | gfm_0133 | <code>&lt;Warning&gt;<br>*bar*<br>&lt;/Warning&gt;</code> |
| 134 | gfm_0134 | <code>&lt;i class="foo"&gt;<br>*bar*<br>&lt;/i&gt;</code> |
| 135 | gfm_0135 | <code>&lt;/ins&gt;<br>*bar*</code> |
| 136 | gfm_0136 | <code>&lt;del&gt;<br>*foo*<br>&lt;/del&gt;</code> |
| 137 | gfm_0137 | <code>&lt;del&gt;<br><br>*foo*<br><br>&lt;/del&gt;</code> |
| 138 | gfm_0138 | <code>&lt;del&gt;*foo*&lt;/del&gt;</code> |
| 139 | gfm_0139 | <code>&lt;pre language="haskell"&gt;&lt;code&gt;<br>import Text.HTML.TagSoup<br><br>main :: IO ()<br>main = print $ parseTags tags<br>&lt;/code&gt;&lt;/pre&gt;<br>okay</code> |
| 140 | gfm_0140 | <code>&lt;script type="text/javascript"&gt;<br>// JavaScript example<br><br>document.getElementById("demo").innerHTML = "Hello JavaScript!";<br>&lt;/script&gt;<br>okay</code> |
| 141 | gfm_0141 | <code>&lt;style<br>  type="text/css"&gt;<br>h1 {color:red;}<br><br>p {color:blue;}<br>&lt;/style&gt;<br>okay</code> |
| 142 | gfm_0142 | <code>&lt;style<br>  type="text/css"&gt;<br><br>foo</code> |
| 143 | gfm_0143 | <code>&gt; &lt;div&gt;<br>&gt; foo<br><br>bar</code> |
| 144 | gfm_0144 | <code>- &lt;div&gt;<br>- foo</code> |
| 145 | gfm_0145 | <code>&lt;style&gt;p{color:red;}&lt;/style&gt;<br>*foo*</code> |
| 146 | gfm_0146 | <code>&lt;!-- foo --&gt;*bar*<br>*baz*</code> |
| 147 | gfm_0147 | <code>&lt;script&gt;<br>foo<br>&lt;/script&gt;1. *bar*</code> |
| 148 | gfm_0148 | <code>&lt;!-- Foo<br><br>bar<br>   baz --&gt;<br>okay</code> |
| 149 | gfm_0149 | <code>&lt;?php<br><br>  echo '&gt;';<br><br>?&gt;<br>okay</code> |
| 150 | gfm_0150 | <code>&lt;!DOCTYPE html&gt;</code> |
| 151 | gfm_0151 | <code>&lt;![CDATA[<br>function matchwo(a,b)<br>{<br>  if (a &lt; b &amp;&amp; a &lt; 0) then {<br>    return 1;<br><br>  } else {<br><br>    return 0;<br>  }<br>}<br>]]&gt;<br>okay</code> |
| 152 | gfm_0152 | <code>  &lt;!-- foo --&gt;<br><br>    &lt;!-- foo --&gt;</code> |
| 153 | gfm_0153 | <code>  &lt;div&gt;<br><br>    &lt;div&gt;</code> |
| 154 | gfm_0154 | <code>Foo<br>&lt;div&gt;<br>bar<br>&lt;/div&gt;</code> |
| 155 | gfm_0155 | <code>&lt;div&gt;<br>bar<br>&lt;/div&gt;<br>*foo*</code> |
| 156 | gfm_0156 | <code>Foo<br>&lt;a href="bar"&gt;<br>baz</code> |
| 157 | gfm_0157 | <code>&lt;div&gt;<br><br>*Emphasized* text.<br><br>&lt;/div&gt;</code> |
| 158 | gfm_0158 | <code>&lt;div&gt;<br>*Emphasized* text.<br>&lt;/div&gt;</code> |
| 159 | gfm_0159 | <code>&lt;table&gt;<br><br>&lt;tr&gt;<br><br>&lt;td&gt;<br>Hi<br>&lt;/td&gt;<br><br>&lt;/tr&gt;<br><br>&lt;/table&gt;</code> |
| 160 | gfm_0160 | <code>&lt;table&gt;<br><br>  &lt;tr&gt;<br><br>    &lt;td&gt;<br>      Hi<br>    &lt;/td&gt;<br><br>  &lt;/tr&gt;<br><br>&lt;/table&gt;</code> |
| 161 | gfm_0161 | <code>[foo]: /url "title"<br><br>[foo]</code> |
| 162 | gfm_0162 | <code>   [foo]: <br>      /url  <br>           'the title'  <br><br>[foo]</code> |
| 163 | gfm_0163 | <code>[Foo*bar\]]:my_(url) 'title (with parens)'<br><br>[Foo*bar\]]</code> |
| 164 | gfm_0164 | <code>[Foo bar]:<br>&lt;my url&gt;<br>'title'<br><br>[Foo bar]</code> |
| 165 | gfm_0165 | <code>[foo]: /url '<br>title<br>line1<br>line2<br>'<br><br>[foo]</code> |
| 166 | gfm_0166 | <code>[foo]: /url 'title<br><br>with blank line'<br><br>[foo]</code> |
| 167 | gfm_0167 | <code>[foo]:<br>/url<br><br>[foo]</code> |
| 168 | gfm_0168 | <code>[foo]:<br><br>[foo]</code> |
| 169 | gfm_0169 | <code>[foo]: &lt;&gt;<br><br>[foo]</code> |
| 170 | gfm_0170 | <code>[foo]: &lt;bar&gt;(baz)<br><br>[foo]</code> |
| 171 | gfm_0171 | <code>[foo]: /url\bar\*baz "foo\"bar\baz"<br><br>[foo]</code> |
| 172 | gfm_0172 | <code>[foo]<br><br>[foo]: url</code> |
| 173 | gfm_0173 | <code>[foo]<br><br>[foo]: first<br>[foo]: second</code> |
| 174 | gfm_0174 | <code>[FOO]: /url<br><br>[Foo]</code> |
| 175 | gfm_0175 | <code>[ΑΓΩ]: /φου<br><br>[αγω]</code> |
| 176 | gfm_0176 | <code>[foo]: /url</code> |
| 177 | gfm_0177 | <code>[foo]: /url "title" ok</code> |
| 178 | gfm_0178 | <code>[foo]: /url<br>"title" ok</code> |
| 179 | gfm_0179 | <code>    [foo]: /url "title"<br><br>[foo]</code> |
| 180 | gfm_0180 | <code>```<br>[foo]: /url<br>```<br><br>[foo]</code> |
| 181 | gfm_0181 | <code>Foo<br>[bar]: /baz<br><br>[bar]</code> |
| 182 | gfm_0182 | <code># [Foo]<br>[foo]: /url<br>&gt; bar</code> |
| 183 | gfm_0183 | <code>[foo]: /url<br>bar<br>===<br>[foo]</code> |
| 184 | gfm_0184 | <code>[foo]: /url<br>===<br>[foo]</code> |
| 185 | gfm_0185 | <code>[foo]: /foo-url "foo"<br>[bar]: /bar-url<br>  "bar"<br>[baz]: /baz-url<br><br>[foo],<br>[bar],<br>[baz]</code> |
| 186 | gfm_0186 | <code>[foo]<br><br>&gt; [foo]: /url</code> |
| 187 | gfm_0187 | <code>[foo]: /url</code> |
| 188 | gfm_0188 | <code>aaa<br>bbb<br><br>ccc<br>ddd</code> |
| 189 | gfm_0189 | <code>aaa<br><br><br>bbb</code> |
| 190 | gfm_0190 | <code>  aaa<br> bbb</code> |
| 191 | gfm_0191 | <code>aaa<br>             bbb<br>                                       ccc</code> |
| 192 | gfm_0192 | <code>   aaa<br>bbb</code> |
| 193 | gfm_0193 | <code>    aaa<br>bbb</code> |
| 194 | gfm_0194 | <code>aaa     <br>bbb     </code> |
| 195 | gfm_0195 | <code>  <br><br>aaa<br>  <br><br># aaa<br><br>  </code> |
| 196 | gfm_0196 | <code>&gt; # Foo<br>&gt; bar<br>&gt; baz</code> |
| 197 | gfm_0197 | <code>&gt;# Foo<br>&gt;bar<br>&gt; baz</code> |
| 198 | gfm_0198 | <code>   &gt; # Foo<br>   &gt; bar<br> &gt; baz</code> |
| 199 | gfm_0199 | <code>    &gt; # Foo<br>    &gt; bar<br>    &gt; baz</code> |
| 200 | gfm_0200 | <code>&gt; # Foo<br>&gt; bar<br>baz</code> |
| 201 | gfm_0201 | <code>&gt; bar<br>baz<br>&gt; foo</code> |
| 202 | gfm_0202 | <code>&gt; foo<br>---</code> |
| 203 | gfm_0203 | <code>&gt; - foo<br>- bar</code> |
| 204 | gfm_0204 | <code>&gt;     foo<br>    bar</code> |
| 205 | gfm_0205 | <code>&gt; ```<br>foo<br>```</code> |
| 206 | gfm_0206 | <code>&gt; foo<br>    - bar</code> |
| 207 | gfm_0207 | <code>&gt;</code> |
| 208 | gfm_0208 | <code>&gt;<br>&gt;  <br>&gt; </code> |
| 209 | gfm_0209 | <code>&gt;<br>&gt; foo<br>&gt;  </code> |
| 210 | gfm_0210 | <code>&gt; foo<br><br>&gt; bar</code> |
| 211 | gfm_0211 | <code>&gt; foo<br>&gt; bar</code> |
| 212 | gfm_0212 | <code>&gt; foo<br>&gt;<br>&gt; bar</code> |
| 213 | gfm_0213 | <code>foo<br>&gt; bar</code> |
| 214 | gfm_0214 | <code>&gt; aaa<br>***<br>&gt; bbb</code> |
| 215 | gfm_0215 | <code>&gt; bar<br>baz</code> |
| 216 | gfm_0216 | <code>&gt; bar<br><br>baz</code> |
| 217 | gfm_0217 | <code>&gt; bar<br>&gt;<br>baz</code> |
| 218 | gfm_0218 | <code>&gt; &gt; &gt; foo<br>bar</code> |
| 219 | gfm_0219 | <code>&gt;&gt;&gt; foo<br>&gt; bar<br>&gt;&gt;baz</code> |
| 220 | gfm_0220 | <code>&gt;     code<br><br>&gt;    not code</code> |
| 221 | gfm_0221 | <code>A paragraph<br>with two lines.<br><br>    indented code<br><br>&gt; A block quote.</code> |
| 222 | gfm_0222 | <code>1.  A paragraph<br>    with two lines.<br><br>        indented code<br><br>    &gt; A block quote.</code> |
| 223 | gfm_0223 | <code>- one<br><br> two</code> |
| 224 | gfm_0224 | <code>- one<br><br>  two</code> |
| 225 | gfm_0225 | <code> -    one<br><br>     two</code> |
| 226 | gfm_0226 | <code> -    one<br><br>      two</code> |
| 227 | gfm_0227 | <code>   &gt; &gt; 1.  one<br>&gt;&gt;<br>&gt;&gt;     two</code> |
| 228 | gfm_0228 | <code>&gt;&gt;- one<br>&gt;&gt;<br>  &gt;  &gt; two</code> |
| 229 | gfm_0229 | <code>-one<br><br>2.two</code> |
| 230 | gfm_0230 | <code>- foo<br><br><br>  bar</code> |
| 231 | gfm_0231 | <code>1.  foo<br><br>    ```<br>    bar<br>    ```<br><br>    baz<br><br>    &gt; bam</code> |
| 232 | gfm_0232 | <code>- Foo<br><br>      bar<br><br><br>      baz</code> |
| 233 | gfm_0233 | <code>123456789. ok</code> |
| 234 | gfm_0234 | <code>1234567890. not ok</code> |
| 235 | gfm_0235 | <code>0. ok</code> |
| 236 | gfm_0236 | <code>003. ok</code> |
| 237 | gfm_0237 | <code>-1. not ok</code> |
| 238 | gfm_0238 | <code>- foo<br><br>      bar</code> |
| 239 | gfm_0239 | <code>  10.  foo<br><br>           bar</code> |
| 240 | gfm_0240 | <code>    indented code<br><br>paragraph<br><br>    more code</code> |
| 241 | gfm_0241 | <code>1.     indented code<br><br>   paragraph<br><br>       more code</code> |
| 242 | gfm_0242 | <code>1.      indented code<br><br>   paragraph<br><br>       more code</code> |
| 243 | gfm_0243 | <code>   foo<br><br>bar</code> |
| 244 | gfm_0244 | <code>-    foo<br><br>  bar</code> |
| 245 | gfm_0245 | <code>-  foo<br><br>   bar</code> |
| 246 | gfm_0246 | <code>-<br>  foo<br>-<br>  ```<br>  bar<br>  ```<br>-<br>      baz</code> |
| 247 | gfm_0247 | <code>-   <br>  foo</code> |
| 248 | gfm_0248 | <code>-<br><br>  foo</code> |
| 249 | gfm_0249 | <code>- foo<br>-<br>- bar</code> |
| 250 | gfm_0250 | <code>- foo<br>-   <br>- bar</code> |
| 251 | gfm_0251 | <code>1. foo<br>2.<br>3. bar</code> |
| 252 | gfm_0252 | <code>*</code> |
| 253 | gfm_0253 | <code>foo<br>*<br><br>foo<br>1.</code> |
| 254 | gfm_0254 | <code> 1.  A paragraph<br>     with two lines.<br><br>         indented code<br><br>     &gt; A block quote.</code> |
| 255 | gfm_0255 | <code>  1.  A paragraph<br>      with two lines.<br><br>          indented code<br><br>      &gt; A block quote.</code> |
| 256 | gfm_0256 | <code>   1.  A paragraph<br>       with two lines.<br><br>           indented code<br><br>       &gt; A block quote.</code> |
| 257 | gfm_0257 | <code>    1.  A paragraph<br>        with two lines.<br><br>            indented code<br><br>        &gt; A block quote.</code> |
| 258 | gfm_0258 | <code>  1.  A paragraph<br>with two lines.<br><br>          indented code<br><br>      &gt; A block quote.</code> |
| 259 | gfm_0259 | <code>  1.  A paragraph<br>    with two lines.</code> |
| 260 | gfm_0260 | <code>&gt; 1. &gt; Blockquote<br>continued here.</code> |
| 261 | gfm_0261 | <code>&gt; 1. &gt; Blockquote<br>&gt; continued here.</code> |
| 262 | gfm_0262 | <code>- foo<br>  - bar<br>    - baz<br>      - boo</code> |
| 263 | gfm_0263 | <code>- foo<br> - bar<br>  - baz<br>   - boo</code> |
| 264 | gfm_0264 | <code>10) foo<br>    - bar</code> |
| 265 | gfm_0265 | <code>10) foo<br>   - bar</code> |
| 266 | gfm_0266 | <code>- - foo</code> |
| 267 | gfm_0267 | <code>1. - 2. foo</code> |
| 268 | gfm_0268 | <code>- # Foo<br>- Bar<br>  ---<br>  baz</code> |
| 269 | gfm_0269 | <code>- foo<br>- bar<br>+ baz</code> |
| 270 | gfm_0270 | <code>1. foo<br>2. bar<br>3) baz</code> |
| 271 | gfm_0271 | <code>Foo<br>- bar<br>- baz</code> |
| 272 | gfm_0272 | <code>The number of windows in my house is<br>14.  The number of doors is 6.</code> |
| 273 | gfm_0273 | <code>The number of windows in my house is<br>1.  The number of doors is 6.</code> |
| 274 | gfm_0274 | <code>- foo<br><br>- bar<br><br><br>- baz</code> |
| 275 | gfm_0275 | <code>- foo<br>  - bar<br>    - baz<br><br><br>      bim</code> |
| 276 | gfm_0276 | <code>- foo<br>- bar<br><br>&lt;!-- --&gt;<br><br>- baz<br>- bim</code> |
| 277 | gfm_0277 | <code>-   foo<br><br>    notcode<br><br>-   foo<br><br>&lt;!-- --&gt;<br><br>    code</code> |
| 278 | gfm_0278 | <code>- a<br> - b<br>  - c<br>   - d<br>  - e<br> - f<br>- g</code> |
| 279 | gfm_0279 | <code>1. a<br><br>  2. b<br><br>   3. c</code> |
| 280 | gfm_0280 | <code>- a<br> - b<br>  - c<br>   - d<br>    - e</code> |
| 281 | gfm_0281 | <code>1. a<br><br>  2. b<br><br>    3. c</code> |
| 282 | gfm_0282 | <code>- a<br>- b<br><br>- c</code> |
| 283 | gfm_0283 | <code>* a<br>*<br><br>* c</code> |
| 284 | gfm_0284 | <code>- a<br>- b<br><br>  c<br>- d</code> |
| 285 | gfm_0285 | <code>- a<br>- b<br><br>  [ref]: /url<br>- d</code> |
| 286 | gfm_0286 | <code>- a<br>- ```<br>  b<br><br><br>  ```<br>- c</code> |
| 287 | gfm_0287 | <code>- a<br>  - b<br><br>    c<br>- d</code> |
| 288 | gfm_0288 | <code>* a<br>  &gt; b<br>  &gt;<br>* c</code> |
| 289 | gfm_0289 | <code>- a<br>  &gt; b<br>  ```<br>  c<br>  ```<br>- d</code> |
| 290 | gfm_0290 | <code>- a</code> |
| 291 | gfm_0291 | <code>- a<br>  - b</code> |
| 292 | gfm_0292 | <code>1. ```<br>   foo<br>   ```<br><br>   bar</code> |
| 293 | gfm_0293 | <code>* foo<br>  * bar<br><br>  baz</code> |
| 294 | gfm_0294 | <code>- a<br>  - b<br>  - c<br><br>- d<br>  - e<br>  - f</code> |
| 295 | gfm_0295 | <code>`hi`lo`</code> |
| 296 | gfm_0296 | <code>\!\"\#\$\%\&amp;\'\(\)\*\+\,\-\.\/\:\;\&lt;\=\&gt;\?\@\[\\\]\^\_\`\{\&#124;\}\~</code> |
| 297 | gfm_0297 | <code>\&nbsp;&nbsp;&nbsp;&nbsp;\A\a\ \3\φ\«</code> |
| 298 | gfm_0298 | <code>\*not emphasized*<br>\&lt;br/&gt; not a tag<br>\[not a link](/foo)<br>\`not code`<br>1\. not a list<br>\* not a list<br>\# not a heading<br>\[foo]: /url "not a reference"<br>\&amp;ouml; not a character entity</code> |
| 299 | gfm_0299 | <code>\\*emphasis*</code> |
| 300 | gfm_0300 | <code>foo\<br>bar</code> |
| 301 | gfm_0301 | <code>`` \[\` ``</code> |
| 302 | gfm_0302 | <code>    \[\]</code> |
| 303 | gfm_0303 | <code>~~~<br>\[\]<br>~~~</code> |
| 304 | gfm_0304 | <code>&lt;http://example.com?find=\*&gt;</code> |
| 305 | gfm_0305 | <code>&lt;a href="/bar\/)"&gt;</code> |
| 306 | gfm_0306 | <code>[foo](/bar\* "ti\*tle")</code> |
| 307 | gfm_0307 | <code>[foo]<br><br>[foo]: /bar\* "ti\*tle"</code> |
| 308 | gfm_0308 | <code>``` foo\+bar<br>foo<br>```</code> |
| 309 | gfm_0309 | <code>&amp;nbsp; &amp;amp; &amp;copy; &amp;AElig; &amp;Dcaron;<br>&amp;frac34; &amp;HilbertSpace; &amp;DifferentialD;<br>&amp;ClockwiseContourIntegral; &amp;ngE;</code> |
| 310 | gfm_0310 | <code>&amp;#35; &amp;#1234; &amp;#992; &amp;#0;</code> |
| 311 | gfm_0311 | <code>&amp;#X22; &amp;#XD06; &amp;#xcab;</code> |
| 312 | gfm_0312 | <code>&amp;nbsp &amp;x; &amp;#; &amp;#x;<br>&amp;#987654321;<br>&amp;#abcdef0;<br>&amp;ThisIsNotDefined; &amp;hi?;</code> |
| 313 | gfm_0313 | <code>&amp;copy</code> |
| 314 | gfm_0314 | <code>&amp;MadeUpEntity;</code> |
| 315 | gfm_0315 | <code>&lt;a href="&amp;ouml;&amp;ouml;.html"&gt;</code> |
| 316 | gfm_0316 | <code>[foo](/f&amp;ouml;&amp;ouml; "f&amp;ouml;&amp;ouml;")</code> |
| 317 | gfm_0317 | <code>[foo]<br><br>[foo]: /f&amp;ouml;&amp;ouml; "f&amp;ouml;&amp;ouml;"</code> |
| 318 | gfm_0318 | <code>``` f&amp;ouml;&amp;ouml;<br>foo<br>```</code> |
| 319 | gfm_0319 | <code>`f&amp;ouml;&amp;ouml;`</code> |
| 320 | gfm_0320 | <code>    f&amp;ouml;f&amp;ouml;</code> |
| 321 | gfm_0321 | <code>&amp;#42;foo&amp;#42;<br>*foo*</code> |
| 322 | gfm_0322 | <code>&amp;#42; foo<br><br>* foo</code> |
| 323 | gfm_0323 | <code>foo&amp;#10;&amp;#10;bar</code> |
| 324 | gfm_0324 | <code>&amp;#9;foo</code> |
| 325 | gfm_0325 | <code>[a](url &amp;quot;tit&amp;quot;)</code> |
| 326 | gfm_0326 | <code>`foo`</code> |
| 327 | gfm_0327 | <code>`` foo ` bar ``</code> |
| 328 | gfm_0328 | <code>` `` `</code> |
| 329 | gfm_0329 | <code>`  ``  `</code> |
| 330 | gfm_0330 | <code>` a`</code> |
| 331 | gfm_0331 | <code>` b `</code> |
| 332 | gfm_0332 | <code>` `<br>`  `</code> |
| 333 | gfm_0333 | <code>``<br>foo<br>bar  <br>baz<br>``</code> |
| 334 | gfm_0334 | <code>``<br>foo <br>``</code> |
| 335 | gfm_0335 | <code>`foo   bar <br>baz`</code> |
| 336 | gfm_0336 | <code>`foo\`bar`</code> |
| 337 | gfm_0337 | <code>``foo`bar``</code> |
| 338 | gfm_0338 | <code>` foo `` bar `</code> |
| 339 | gfm_0339 | <code>*foo`*`</code> |
| 340 | gfm_0340 | <code>[not a `link](/foo`)</code> |
| 341 | gfm_0341 | <code>`&lt;a href="`"&gt;`</code> |
| 342 | gfm_0342 | <code>&lt;a href="`"&gt;`</code> |
| 343 | gfm_0343 | <code>`&lt;http://foo.bar.`baz&gt;`</code> |
| 344 | gfm_0344 | <code>&lt;http://foo.bar.`baz&gt;`</code> |
| 345 | gfm_0345 | <code>```foo``</code> |
| 346 | gfm_0346 | <code>`foo</code> |
| 347 | gfm_0347 | <code>`foo``bar``</code> |
| 348 | gfm_0348 | <code>*foo bar*</code> |
| 349 | gfm_0349 | <code>a * foo bar*</code> |
| 350 | gfm_0350 | <code>a*"foo"*</code> |
| 351 | gfm_0351 | <code>* a *</code> |
| 352 | gfm_0352 | <code>foo*bar*</code> |
| 353 | gfm_0353 | <code>5*6*78</code> |
| 354 | gfm_0354 | <code>_foo bar_</code> |
| 355 | gfm_0355 | <code>_ foo bar_</code> |
| 356 | gfm_0356 | <code>a_"foo"_</code> |
| 357 | gfm_0357 | <code>foo_bar_</code> |
| 358 | gfm_0358 | <code>5_6_78</code> |
| 359 | gfm_0359 | <code>пристаням_стремятся_</code> |
| 360 | gfm_0360 | <code>aa_"bb"_cc</code> |
| 361 | gfm_0361 | <code>foo-_(bar)_</code> |
| 362 | gfm_0362 | <code>_foo*</code> |
| 363 | gfm_0363 | <code>*foo bar *</code> |
| 364 | gfm_0364 | <code>*foo bar<br>*</code> |
| 365 | gfm_0365 | <code>*(*foo)</code> |
| 366 | gfm_0366 | <code>*(*foo*)*</code> |
| 367 | gfm_0367 | <code>*foo*bar</code> |
| 368 | gfm_0368 | <code>_foo bar _</code> |
| 369 | gfm_0369 | <code>_(_foo)</code> |
| 370 | gfm_0370 | <code>_(_foo_)_</code> |
| 371 | gfm_0371 | <code>_foo_bar</code> |
| 372 | gfm_0372 | <code>_пристаням_стремятся</code> |
| 373 | gfm_0373 | <code>_foo_bar_baz_</code> |
| 374 | gfm_0374 | <code>_(bar)_.</code> |
| 375 | gfm_0375 | <code>**foo bar**</code> |
| 376 | gfm_0376 | <code>** foo bar**</code> |
| 377 | gfm_0377 | <code>a**"foo"**</code> |
| 378 | gfm_0378 | <code>foo**bar**</code> |
| 379 | gfm_0379 | <code>__foo bar__</code> |
| 380 | gfm_0380 | <code>__ foo bar__</code> |
| 381 | gfm_0381 | <code>__<br>foo bar__</code> |
| 382 | gfm_0382 | <code>a__"foo"__</code> |
| 383 | gfm_0383 | <code>foo__bar__</code> |
| 384 | gfm_0384 | <code>5__6__78</code> |
| 385 | gfm_0385 | <code>пристаням__стремятся__</code> |
| 386 | gfm_0386 | <code>__foo, __bar__, baz__</code> |
| 387 | gfm_0387 | <code>foo-__(bar)__</code> |
| 388 | gfm_0388 | <code>**foo bar **</code> |
| 389 | gfm_0389 | <code>**(**foo)</code> |
| 390 | gfm_0390 | <code>*(**foo**)*</code> |
| 391 | gfm_0391 | <code>**Gomphocarpus (*Gomphocarpus physocarpus*, syn.<br>*Asclepias physocarpa*)**</code> |
| 392 | gfm_0392 | <code>**foo "*bar*" foo**</code> |
| 393 | gfm_0393 | <code>**foo**bar</code> |
| 394 | gfm_0394 | <code>__foo bar __</code> |
| 395 | gfm_0395 | <code>__(__foo)</code> |
| 396 | gfm_0396 | <code>_(__foo__)_</code> |
| 397 | gfm_0397 | <code>__foo__bar</code> |
| 398 | gfm_0398 | <code>__пристаням__стремятся</code> |
| 399 | gfm_0399 | <code>__foo__bar__baz__</code> |
| 400 | gfm_0400 | <code>__(bar)__.</code> |
| 401 | gfm_0401 | <code>*foo [bar](/url)*</code> |
| 402 | gfm_0402 | <code>*foo<br>bar*</code> |
| 403 | gfm_0403 | <code>_foo __bar__ baz_</code> |
| 404 | gfm_0404 | <code>_foo _bar_ baz_</code> |
| 405 | gfm_0405 | <code>__foo_ bar_</code> |
| 406 | gfm_0406 | <code>*foo *bar**</code> |
| 407 | gfm_0407 | <code>*foo **bar** baz*</code> |
| 408 | gfm_0408 | <code>*foo**bar**baz*</code> |
| 409 | gfm_0409 | <code>*foo**bar*</code> |
| 410 | gfm_0410 | <code>***foo** bar*</code> |
| 411 | gfm_0411 | <code>*foo **bar***</code> |
| 412 | gfm_0412 | <code>*foo**bar***</code> |
| 413 | gfm_0413 | <code>foo***bar***baz</code> |
| 414 | gfm_0414 | <code>foo******bar*********baz</code> |
| 415 | gfm_0415 | <code>*foo **bar *baz* bim** bop*</code> |
| 416 | gfm_0416 | <code>*foo [*bar*](/url)*</code> |
| 417 | gfm_0417 | <code>** is not an empty emphasis</code> |
| 418 | gfm_0418 | <code>**** is not an empty strong emphasis</code> |
| 419 | gfm_0419 | <code>**foo [bar](/url)**</code> |
| 420 | gfm_0420 | <code>**foo<br>bar**</code> |
| 421 | gfm_0421 | <code>__foo _bar_ baz__</code> |
| 422 | gfm_0422 | <code>__foo __bar__ baz__</code> |
| 423 | gfm_0423 | <code>____foo__ bar__</code> |
| 424 | gfm_0424 | <code>**foo **bar****</code> |
| 425 | gfm_0425 | <code>**foo *bar* baz**</code> |
| 426 | gfm_0426 | <code>**foo*bar*baz**</code> |
| 427 | gfm_0427 | <code>***foo* bar**</code> |
| 428 | gfm_0428 | <code>**foo *bar***</code> |
| 429 | gfm_0429 | <code>**foo *bar **baz**<br>bim* bop**</code> |
| 430 | gfm_0430 | <code>**foo [*bar*](/url)**</code> |
| 431 | gfm_0431 | <code>__ is not an empty emphasis</code> |
| 432 | gfm_0432 | <code>____ is not an empty strong emphasis</code> |
| 433 | gfm_0433 | <code>foo ***</code> |
| 434 | gfm_0434 | <code>foo *\**</code> |
| 435 | gfm_0435 | <code>foo *_*</code> |
| 436 | gfm_0436 | <code>foo *****</code> |
| 437 | gfm_0437 | <code>foo **\***</code> |
| 438 | gfm_0438 | <code>foo **_**</code> |
| 439 | gfm_0439 | <code>**foo*</code> |
| 440 | gfm_0440 | <code>*foo**</code> |
| 441 | gfm_0441 | <code>***foo**</code> |
| 442 | gfm_0442 | <code>****foo*</code> |
| 443 | gfm_0443 | <code>**foo***</code> |
| 444 | gfm_0444 | <code>*foo****</code> |
| 445 | gfm_0445 | <code>foo ___</code> |
| 446 | gfm_0446 | <code>foo _\__</code> |
| 447 | gfm_0447 | <code>foo _*_</code> |
| 448 | gfm_0448 | <code>foo _____</code> |
| 449 | gfm_0449 | <code>foo __\___</code> |
| 450 | gfm_0450 | <code>foo __*__</code> |
| 451 | gfm_0451 | <code>__foo_</code> |
| 452 | gfm_0452 | <code>_foo__</code> |
| 453 | gfm_0453 | <code>___foo__</code> |
| 454 | gfm_0454 | <code>____foo_</code> |
| 455 | gfm_0455 | <code>__foo___</code> |
| 456 | gfm_0456 | <code>_foo____</code> |
| 457 | gfm_0457 | <code>**foo**</code> |
| 458 | gfm_0458 | <code>*_foo_*</code> |
| 459 | gfm_0459 | <code>__foo__</code> |
| 460 | gfm_0460 | <code>_*foo*_</code> |
| 461 | gfm_0461 | <code>****foo****</code> |
| 462 | gfm_0462 | <code>____foo____</code> |
| 463 | gfm_0463 | <code>******foo******</code> |
| 464 | gfm_0464 | <code>***foo***</code> |
| 465 | gfm_0465 | <code>_____foo_____</code> |
| 466 | gfm_0466 | <code>*foo _bar* baz_</code> |
| 467 | gfm_0467 | <code>*foo __bar *baz bim__ bam*</code> |
| 468 | gfm_0468 | <code>**foo **bar baz**</code> |
| 469 | gfm_0469 | <code>*foo *bar baz*</code> |
| 470 | gfm_0470 | <code>*[bar*](/url)</code> |
| 471 | gfm_0471 | <code>_foo [bar_](/url)</code> |
| 472 | gfm_0472 | <code>*&lt;img src="foo" title="*"/&gt;</code> |
| 473 | gfm_0473 | <code>**&lt;a href="**"&gt;</code> |
| 474 | gfm_0474 | <code>__&lt;a href="__"&gt;</code> |
| 475 | gfm_0475 | <code>*a `*`*</code> |
| 476 | gfm_0476 | <code>_a `_`_</code> |
| 477 | gfm_0477 | <code>**a&lt;http://foo.bar/?q=**&gt;</code> |
| 478 | gfm_0478 | <code>__a&lt;http://foo.bar/?q=__&gt;</code> |
| 479 | gfm_0479 | <code>[link](/uri "title")</code> |
| 480 | gfm_0480 | <code>[link](/uri)</code> |
| 481 | gfm_0481 | <code>[link]()</code> |
| 482 | gfm_0482 | <code>[link](&lt;&gt;)</code> |
| 483 | gfm_0483 | <code>[link](/my uri)</code> |
| 484 | gfm_0484 | <code>[link](&lt;/my uri&gt;)</code> |
| 485 | gfm_0485 | <code>[link](foo<br>bar)</code> |
| 486 | gfm_0486 | <code>[link](&lt;foo<br>bar&gt;)</code> |
| 487 | gfm_0487 | <code>[a](&lt;b)c&gt;)</code> |
| 488 | gfm_0488 | <code>[link](&lt;foo\&gt;)</code> |
| 489 | gfm_0489 | <code>[a](&lt;b)c<br>[a](&lt;b)c&gt;<br>[a](&lt;b&gt;c)</code> |
| 490 | gfm_0490 | <code>[link](\(foo\))</code> |
| 491 | gfm_0491 | <code>[link](foo(and(bar)))</code> |
| 492 | gfm_0492 | <code>[link](foo\(and\(bar\))</code> |
| 493 | gfm_0493 | <code>[link](&lt;foo(and(bar)&gt;)</code> |
| 494 | gfm_0494 | <code>[link](foo\)\:)</code> |
| 495 | gfm_0495 | <code>[link](#fragment)<br><br>[link](http://example.com#fragment)<br><br>[link](http://example.com?foo=3#frag)</code> |
| 496 | gfm_0496 | <code>[link](foo\bar)</code> |
| 497 | gfm_0497 | <code>[link](foo%20b&amp;auml;)</code> |
| 498 | gfm_0498 | <code>[link]("title")</code> |
| 499 | gfm_0499 | <code>[link](/url "title")<br>[link](/url 'title')<br>[link](/url (title))</code> |
| 500 | gfm_0500 | <code>[link](/url "title \"&amp;quot;")</code> |
| 501 | gfm_0501 | <code>[link](/url "title")</code> |
| 502 | gfm_0502 | <code>[link](/url "title "and" title")</code> |
| 503 | gfm_0503 | <code>[link](/url 'title "and" title')</code> |
| 504 | gfm_0504 | <code>[link](   /uri<br>  "title"  )</code> |
| 505 | gfm_0505 | <code>[link] (/uri)</code> |
| 506 | gfm_0506 | <code>[link [foo [bar]]](/uri)</code> |
| 507 | gfm_0507 | <code>[link] bar](/uri)</code> |
| 508 | gfm_0508 | <code>[link [bar](/uri)</code> |
| 509 | gfm_0509 | <code>[link \[bar](/uri)</code> |
| 510 | gfm_0510 | <code>[link *foo **bar** `#`*](/uri)</code> |
| 511 | gfm_0511 | <code>[![moon](moon.jpg)](/uri)</code> |
| 512 | gfm_0512 | <code>[foo [bar](/uri)](/uri)</code> |
| 513 | gfm_0513 | <code>[foo *[bar [baz](/uri)](/uri)*](/uri)</code> |
| 514 | gfm_0514 | <code>![[[foo](uri1)](uri2)](uri3)</code> |
| 515 | gfm_0515 | <code>*[foo*](/uri)</code> |
| 516 | gfm_0516 | <code>[foo *bar](baz*)</code> |
| 517 | gfm_0517 | <code>*foo [bar* baz]</code> |
| 518 | gfm_0518 | <code>[foo &lt;bar attr="](baz)"&gt;</code> |
| 519 | gfm_0519 | <code>[foo`](/uri)`</code> |
| 520 | gfm_0520 | <code>[foo&lt;http://example.com/?search=](uri)&gt;</code> |
| 521 | gfm_0521 | <code>[foo][bar]<br><br>[bar]: /url "title"</code> |
| 522 | gfm_0522 | <code>[link [foo [bar]]][ref]<br><br>[ref]: /uri</code> |
| 523 | gfm_0523 | <code>[link \[bar][ref]<br><br>[ref]: /uri</code> |
| 524 | gfm_0524 | <code>[link *foo **bar** `#`*][ref]<br><br>[ref]: /uri</code> |
| 525 | gfm_0525 | <code>[![moon](moon.jpg)][ref]<br><br>[ref]: /uri</code> |
| 526 | gfm_0526 | <code>[foo [bar](/uri)][ref]<br><br>[ref]: /uri</code> |
| 527 | gfm_0527 | <code>[foo *bar [baz][ref]*][ref]<br><br>[ref]: /uri</code> |
| 528 | gfm_0528 | <code>*[foo*][ref]<br><br>[ref]: /uri</code> |
| 529 | gfm_0529 | <code>[foo *bar][ref]<br><br>[ref]: /uri</code> |
| 530 | gfm_0530 | <code>[foo &lt;bar attr="][ref]"&gt;<br><br>[ref]: /uri</code> |
| 531 | gfm_0531 | <code>[foo`][ref]`<br><br>[ref]: /uri</code> |
| 532 | gfm_0532 | <code>[foo&lt;http://example.com/?search=][ref]&gt;<br><br>[ref]: /uri</code> |
| 533 | gfm_0533 | <code>[foo][BaR]<br><br>[bar]: /url "title"</code> |
| 534 | gfm_0534 | <code>[Толпой][Толпой] is a Russian word.<br><br>[ТОЛПОЙ]: /url</code> |
| 535 | gfm_0535 | <code>[Foo<br>  bar]: /url<br><br>[Baz][Foo bar]</code> |
| 536 | gfm_0536 | <code>[foo] [bar]<br><br>[bar]: /url "title"</code> |
| 537 | gfm_0537 | <code>[foo]<br>[bar]<br><br>[bar]: /url "title"</code> |
| 538 | gfm_0538 | <code>[foo]: /url1<br><br>[foo]: /url2<br><br>[bar][foo]</code> |
| 539 | gfm_0539 | <code>[bar][foo\!]<br><br>[foo!]: /url</code> |
| 540 | gfm_0540 | <code>[foo][ref[]<br><br>[ref[]: /uri</code> |
| 541 | gfm_0541 | <code>[foo][ref[bar]]<br><br>[ref[bar]]: /uri</code> |
| 542 | gfm_0542 | <code>[[[foo]]]<br><br>[[[foo]]]: /url</code> |
| 543 | gfm_0543 | <code>[foo][ref\[]<br><br>[ref\[]: /uri</code> |
| 544 | gfm_0544 | <code>[bar\\]: /uri<br><br>[bar\\]</code> |
| 545 | gfm_0545 | <code>[]<br><br>[]: /uri</code> |
| 546 | gfm_0546 | <code>[<br> ]<br><br>[<br> ]: /uri</code> |
| 547 | gfm_0547 | <code>[foo][]<br><br>[foo]: /url "title"</code> |
| 548 | gfm_0548 | <code>[*foo* bar][]<br><br>[*foo* bar]: /url "title"</code> |
| 549 | gfm_0549 | <code>[Foo][]<br><br>[foo]: /url "title"</code> |
| 550 | gfm_0550 | <code>[foo] <br>[]<br><br>[foo]: /url "title"</code> |
| 551 | gfm_0551 | <code>[foo]<br><br>[foo]: /url "title"</code> |
| 552 | gfm_0552 | <code>[*foo* bar]<br><br>[*foo* bar]: /url "title"</code> |
| 553 | gfm_0553 | <code>[[*foo* bar]]<br><br>[*foo* bar]: /url "title"</code> |
| 554 | gfm_0554 | <code>[[bar [foo]<br><br>[foo]: /url</code> |
| 555 | gfm_0555 | <code>[Foo]<br><br>[foo]: /url "title"</code> |
| 556 | gfm_0556 | <code>[foo] bar<br><br>[foo]: /url</code> |
| 557 | gfm_0557 | <code>\[foo]<br><br>[foo]: /url "title"</code> |
| 558 | gfm_0558 | <code>[foo*]: /url<br><br>*[foo*]</code> |
| 559 | gfm_0559 | <code>[foo][bar]<br><br>[foo]: /url1<br>[bar]: /url2</code> |
| 560 | gfm_0560 | <code>[foo][]<br><br>[foo]: /url1</code> |
| 561 | gfm_0561 | <code>[foo]()<br><br>[foo]: /url1</code> |
| 562 | gfm_0562 | <code>[foo](not a link)<br><br>[foo]: /url1</code> |
| 563 | gfm_0563 | <code>[foo][bar][baz]<br><br>[baz]: /url</code> |
| 564 | gfm_0564 | <code>[foo][bar][baz]<br><br>[baz]: /url1<br>[bar]: /url2</code> |
| 565 | gfm_0565 | <code>[foo][bar][baz]<br><br>[baz]: /url1<br>[foo]: /url2</code> |
| 566 | gfm_0566 | <code>![foo](/url "title")</code> |
| 567 | gfm_0567 | <code>![foo *bar*]<br><br>[foo *bar*]: train.jpg "train &amp; tracks"</code> |
| 568 | gfm_0568 | <code>![foo ![bar](/url)](/url2)</code> |
| 569 | gfm_0569 | <code>![foo [bar](/url)](/url2)</code> |
| 570 | gfm_0570 | <code>![foo *bar*][]<br><br>[foo *bar*]: train.jpg "train &amp; tracks"</code> |
| 571 | gfm_0571 | <code>![foo *bar*][foobar]<br><br>[FOOBAR]: train.jpg "train &amp; tracks"</code> |
| 572 | gfm_0572 | <code>![foo](train.jpg)</code> |
| 573 | gfm_0573 | <code>My ![foo bar](/path/to/train.jpg  "title"   )</code> |
| 574 | gfm_0574 | <code>![foo](&lt;url&gt;)</code> |
| 575 | gfm_0575 | <code>![](/url)</code> |
| 576 | gfm_0576 | <code>![foo][bar]<br><br>[bar]: /url</code> |
| 577 | gfm_0577 | <code>![foo][bar]<br><br>[BAR]: /url</code> |
| 578 | gfm_0578 | <code>![foo][]<br><br>[foo]: /url "title"</code> |
| 579 | gfm_0579 | <code>![*foo* bar][]<br><br>[*foo* bar]: /url "title"</code> |
| 580 | gfm_0580 | <code>![Foo][]<br><br>[foo]: /url "title"</code> |
| 581 | gfm_0581 | <code>![foo] <br>[]<br><br>[foo]: /url "title"</code> |
| 582 | gfm_0582 | <code>![foo]<br><br>[foo]: /url "title"</code> |
| 583 | gfm_0583 | <code>![*foo* bar]<br><br>[*foo* bar]: /url "title"</code> |
| 584 | gfm_0584 | <code>![[foo]]<br><br>[[foo]]: /url "title"</code> |
| 585 | gfm_0585 | <code>![Foo]<br><br>[foo]: /url "title"</code> |
| 586 | gfm_0586 | <code>!\[foo]<br><br>[foo]: /url "title"</code> |
| 587 | gfm_0587 | <code>\![foo]<br><br>[foo]: /url "title"</code> |
| 588 | gfm_0588 | <code>&lt;http://foo.bar.baz&gt;</code> |
| 589 | gfm_0589 | <code>&lt;http://foo.bar.baz/test?q=hello&amp;id=22&amp;boolean&gt;</code> |
| 590 | gfm_0590 | <code>&lt;irc://foo.bar:2233/baz&gt;</code> |
| 591 | gfm_0591 | <code>&lt;MAILTO:FOO@BAR.BAZ&gt;</code> |
| 592 | gfm_0592 | <code>&lt;a+b+c:d&gt;</code> |
| 593 | gfm_0593 | <code>&lt;made-up-scheme://foo,bar&gt;</code> |
| 594 | gfm_0594 | <code>&lt;http://../&gt;</code> |
| 595 | gfm_0595 | <code>&lt;localhost:5001/foo&gt;</code> |
| 596 | gfm_0596 | <code>&lt;http://foo.bar/baz bim&gt;</code> |
| 597 | gfm_0597 | <code>&lt;http://example.com/\[\&gt;</code> |
| 598 | gfm_0598 | <code>&lt;foo@bar.example.com&gt;</code> |
| 599 | gfm_0599 | <code>&lt;foo+special@Bar.baz-bar0.com&gt;</code> |
| 600 | gfm_0600 | <code>&lt;foo\+@bar.example.com&gt;</code> |
| 601 | gfm_0601 | <code>&lt;&gt;</code> |
| 602 | gfm_0602 | <code>&lt; http://foo.bar &gt;</code> |
| 603 | gfm_0603 | <code>&lt;m:abc&gt;</code> |
| 604 | gfm_0604 | <code>&lt;foo.bar.baz&gt;</code> |
| 605 | gfm_0605 | <code>http://example.com</code> |
| 606 | gfm_0606 | <code>foo@bar.example.com</code> |
| 607 | gfm_0607 | <code>&lt;a&gt;&lt;bab&gt;&lt;c2c&gt;</code> |
| 608 | gfm_0608 | <code>&lt;a/&gt;&lt;b2/&gt;</code> |
| 609 | gfm_0609 | <code>&lt;a  /&gt;&lt;b2<br>data="foo" &gt;</code> |
| 610 | gfm_0610 | <code>&lt;a foo="bar" bam = 'baz &lt;em&gt;"&lt;/em&gt;'<br>_boolean zoop:33=zoop:33 /&gt;</code> |
| 611 | gfm_0611 | <code>Foo &lt;responsive-image src="foo.jpg" /&gt;</code> |
| 612 | gfm_0612 | <code>&lt;33&gt; &lt;__&gt;</code> |
| 613 | gfm_0613 | <code>&lt;a h*#ref="hi"&gt;</code> |
| 614 | gfm_0614 | <code>&lt;a href="hi'&gt; &lt;a href=hi'&gt;</code> |
| 615 | gfm_0615 | <code>&lt; a&gt;&lt;<br>foo&gt;&lt;bar/ &gt;<br>&lt;foo bar=baz<br>bim!bop /&gt;</code> |
| 616 | gfm_0616 | <code>&lt;a href='bar'title=title&gt;</code> |
| 617 | gfm_0617 | <code>&lt;/a&gt;&lt;/foo &gt;</code> |
| 618 | gfm_0618 | <code>&lt;/a href="foo"&gt;</code> |
| 619 | gfm_0619 | <code>foo &lt;!-- this is a --<br>comment - with hyphens --&gt;</code> |
| 620 | gfm_0620 | <code>foo &lt;!--&gt; foo --&gt;<br><br>foo &lt;!---&gt; foo --&gt;</code> |
| 621 | gfm_0621 | <code>foo &lt;?php echo $a; ?&gt;</code> |
| 622 | gfm_0622 | <code>foo &lt;!ELEMENT br EMPTY&gt;</code> |
| 623 | gfm_0623 | <code>foo &lt;![CDATA[&gt;&amp;&lt;]]&gt;</code> |
| 624 | gfm_0624 | <code>foo &lt;a href="&amp;ouml;"&gt;</code> |
| 625 | gfm_0625 | <code>foo &lt;a href="\*"&gt;</code> |
| 626 | gfm_0626 | <code>&lt;a href="\""&gt;</code> |
| 627 | gfm_0627 | <code>foo  <br>baz</code> |
| 628 | gfm_0628 | <code>foo\<br>baz</code> |
| 629 | gfm_0629 | <code>foo       <br>baz</code> |
| 630 | gfm_0630 | <code>foo  <br>     bar</code> |
| 631 | gfm_0631 | <code>foo\<br>     bar</code> |
| 632 | gfm_0632 | <code>*foo  <br>bar*</code> |
| 633 | gfm_0633 | <code>*foo\<br>bar*</code> |
| 634 | gfm_0634 | <code>`code  <br>span`</code> |
| 635 | gfm_0635 | <code>`code\<br>span`</code> |
| 636 | gfm_0636 | <code>&lt;a href="foo  <br>bar"&gt;</code> |
| 637 | gfm_0637 | <code>&lt;a href="foo\<br>bar"&gt;</code> |
| 638 | gfm_0638 | <code>foo\</code> |
| 639 | gfm_0639 | <code>foo  </code> |
| 640 | gfm_0640 | <code>### foo\</code> |
| 641 | gfm_0641 | <code>### foo  </code> |
| 642 | gfm_0642 | <code>foo<br>baz</code> |
| 643 | gfm_0643 | <code>foo <br> baz</code> |
| 644 | gfm_0644 | <code>hello $.;'there</code> |
| 645 | gfm_0645 | <code>Foo χρῆν</code> |
| 646 | gfm_0646 | <code>Multiple     spaces</code> |
