## **まとめノート**

書いた記事やノートをまとめてあります。
### 位相空間論
<lo>
<li>
<strong><a href="/pdf/ultrafilter.pdf">超フィルターによる位相空間論</a>
</strong>
</li>
</lo>
  <p>超フィルターという概念はモデル理論や束論や位相空間論など様々なところで現れる。そこで、今回は位相空間論に視点を絞り、超フィルターによる位相空間論についてまとめる。
  
  超フィルターを用いて議論することは位相空間論に新しい視点を与えるだけでなく、議論が完結になったりと利点も多い。
  そのため、今回は位相空間論の基本的な概念を超フィルターを用いて特徴付けし、距離空間における点列の収束と超フィルターの類似点を述べる。
  また、様々な位相空間の定理を超フィルターを用いて証明し、最後に超フィルターを用いることで簡潔に証明できるTychonovの定理を示す。
  </p>
<lo>
  <li>
  <strong>
  <a href="/pdf/CWcomplex.pdf">CW複体</a>
  </strong>
  </li>
</lo>
  <p>CW複体は代数的位相幾何学で重要な対象である。そこで、今回はCW複体の定義や例を紹介し、push outによる定義とWhiteheadによる定義の同値性を示し、最後にCW複体が正規空間であることを示す。
  
  このノートはHatcherのAlgebraic TopologyのAppendixのまとめでもある。</p>

### 代数的位相幾何学
<lo>
<li>
<strong><a href="/pdf/Brown Rep Thm.pdf">Brown Representability Theorem</a>
</strong>
</li>
</lo>
  <p>任意のΩ-spectrumが基点付きCW複体の圏上の簡約コホモロジー論を定める。ここで逆に基点付きCW複体の圏上の任意の簡約コホモロジー論はある Ω-spectrumにより表現されるかという自然な疑問がある。
  この疑問に肯定的な解答を与えるのがBrown representability theoremである。また、特異コホモロジー群がEilenberg-MacLane空間により表現されるということが具体的な計算により得られるが、Brown representability theoremはその別証明を与える。
  今回は、簡約懸垂をとる関手とループ空間をとる関手が互いに随伴関手となることの説明から始め、Brown representability theoremの証明を与える。</p>

### 多様体論
<lo>
<li>
<strong>
<a href="/pdf/vector analysis.pdf">微分形式とベクトル解析</a></strong>
</li>
</lo>
  <p>今回は微分形式などを簡単に説明し、ベクトル解析で扱うgradient(勾配)やrotation(回転)やdivergence(発散)がR^3のde Rham複体と外微分を用いる事で理解できることを述べる.そして,最後にその性質が外微分の性質と一致していることをみる。</p>

### 微分空間論

<lo>
<li>
<strong><a href="https://arxiv.org/abs/2309.07379">A closed manifold is a fat CW complex</a></strong>
</li>
<p>
1980年頃に幾つかの同値でない可微分構造の概念が様々な研究者により独立に与えられた．
中でもK. T. Chenによるdifferentiable space(以下，Chen空間)は例えばT. Kohnoによりiterated integralへ応用される一方で，J. M. Souriauによるdiffeological space(以下，微分空間)はP. Iglesias-Zemmourをはじめとする研究者によって理論的な整備が進み，Zemmourにより滑らかな多様体の圏には類似物の存在しない微分空間の特徴的な例となるirrational torusが発見されるなど精力的に研究が進められている．

微分空間は滑らかな多様体の一般化である．
滑らかな多様体のなす圏は極限と余極限に関して閉じておらず，Cartesian閉圏でない．
しかし，微分空間のなす圏は極限と余極限に閉じており，Cartesian閉圏である．
そのため，ファイバー積や接着空間などの構成で微分構造が失われず，微分空間との積をとる関手が左随伴関手となる．

位相空間はユークリッド空間の開集合からの連続写像を考えることで微分空間とみなすことができるのだが逆に，Zemmourは微分空間に対し，D-topologyと呼ばれる位相を定めた．
微分空間に対し，D-topologyによる位相空間を対応させることで微分空間の圏から位相空間の圏への左随伴関手を得る．
また，微分空間の圏からR. SikorskiによるSikorski空間のなす圏への左随伴関手も存在する．
微分空間を上記の左随伴関手とその右随伴関手の合成関手でうつしたものが元の微分空間と一致するとき，その微分空間はreflexiveであると呼ぶ.

微分空間は滑らかな多様体だけでなく単なる位相空間など様々な種類の空間を含むため，「良い」微分空間とは何かということが問題となる．
そこで，滑らかな多様体やI. Satake によるV-manifoldやstratified spaceがもつ性質としてreflexivityに注目した．

N. IwaseとN. IzumidaやH. Kiharaはsmooth CW complexを定義した．
しかし，球面などの位相的なCW complexかつ滑らかな多様体である空間がsmooth CW complexにならないという問題がある．
また，smooth CW complexは滑らかな1の分割をもつなど滑らかな多様体と似た性質をもつが，一般にreflexiveであることは証明されていない．

本論文は，まず，微分空間の定義と基本的なことを述べる．
そして，fat CW complexを導入するためのsmooth handleを導入し，fat CW complexを定義する．
その後，fat CW complexのD-Topologyがパラコンパクトハウスドルフであることを示し，fat CW complexは滑らかな1の分割をもち，de Rhamの定理が成り立つことを示す．
さらに，主定理としてfat CW complexがregularかつ有限次元のときreflexiveであることを示し，閉多様体がfat CW complexであることを示す．
</p>
<lo>
<li>
<strong><a href="/pdf/Diff and Set adjoint.pdf">左右の随伴をもつ忘却関手</a></strong>
</li>
</lo>
  <p>忘却関手が左随伴をもつことは多いが右随伴をもつことは少ない。そこで今回は位相空間と微分空間(diffeological space)を用いて左右の随伴をもつ忘却関手の例をあげる。また、本稿はほとんど前提知識なしで読めるように心がけた。
</p>

### 力学系
<lo>
<li>
<strong><a href="/pdf/The stable manifold theorem.pdf">安定多様体定理</a></strong>
</li>
</lo>
  <p>安定多様体定理とは非線形系が安定多様体と不安定多様体をもち、それぞれが線形化された系の安定部分空間と不安定部分空間に双曲型平衡点で接するというものであり、常微分方程式における定性的な理論の重要な結果の1つである。
  今回は例をあげて安定多様体定理を説明した後に証明を与え、安定多様体定理を用いて安定多様体と不安定多様体を構成する。</p>

### 関数解析
<lo>
<li>
<strong><a href="/pdf/PaNor and PreHill.pdf">中線定理が成立するノルム空間と内積空間</a></strong>
</li>
</lo>
  <p>中線定理が成立するノルム空間から自然に内積空間を定義できる. 逆に, 内積空間から自然にノルム空間を定義することができる. これを証明し, 最後にこの事実を圏論を用いて述べる.
  このノートはノルム空間や内積空間の定義から始め、ほとんど前提知識なしで読めるように心がけた。
  </p>

### アーベル圏論
<lo>
<li>
<strong><a href="/pdf/longcohomology.pdf">蛇の補題とコホモロジー長完全列</a></strong>
</li>
</lo>
  <p>アーベル圏では埋め込み定理を用いて元を取って議論することができるが本稿ではそうではなく普遍性の議論で蛇の補題とコホモロジー長完全列の存在を示す。
  <a href="https://twitter.com/@cosmos8128">@cosmos8128</a>が1章と2章でアーベル圏の基本的な性質をまとめ、蛇の補題を示す。
  その後<a href="https://twitter.com/kyo_math1729">@kyo_math1729</a>が3章でコホモロジー長完全列の存在を示す。</p>

### モナド
<lo>
<li>
<strong><a href="/pdf/Eilenberg and Kleisli.pdf">アイレンベルグムーア圏とクライスリ圏</a></strong>
</li>
</lo>
  <p>任意の随伴からモナドを得ることができる。
  では、任意のモナドから随伴を得ることができるだろうか？
  この問の答えは肯定的であり、アイレンベルグムーア圏を用いたものとクライスリ圏を用いたものの2つの方法がある。
  本稿では、随伴からモナドを得る方法とモナドから随伴を得る2つの方法をまとめ、最後にアイレンベルグムーア圏とクライスリ圏を用いた随伴と代数の比較定理を証明する。</p>

---

**[ホームに戻る](/index)**