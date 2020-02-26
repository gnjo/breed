# breed
```
female father X--+
                 +----x
female mother Y--+    |
                      +-----s =base(xy)*gain
male father  A---+    |   //gain=range( (stable(XYABxy)+rmin(XYAB))/rate,rmax(XYAB)*rate)
                 +----y
male mother  B---+

わかりやすさを優先する。
能力値の最低は、XYABxyの中から最高のレベルを一つ抽出する。stable(XYABxy)
祖父母からランダムに値を取る。rmin(XYAB) rmax(XYAB)
直近の親のいずれかをベースとする。base(xy) //現実では祖父母だが。
継代を得ると振れ幅を大きくする。 rate=1+n*0.05
```
