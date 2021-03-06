第十章

# 二元空间，二元性

## 10.1双空间E和线性形式

在第3.8节中，我们定义了向量空间e的对偶空间e=hom（e，k），并证明了有限维向量空间的对偶基的存在性。

在本章中，我们更深入地研究了空间E与其双空间E之间的联系。正如我们即将看到的，每一个线性映射f:e→f都会产生一个线性映射f>：f→e，结果表明，在适当的基础上，f>的矩阵是f的矩阵的转置。因此，对偶空间的概念提供了与tra相关的现象的概念解释。n位置。

但是它做得更多，因为它允许我们把一个线性方程看作双空间E的一个元素，从而把E的子空间看作一组线性方程的解，反之亦然。子空间与线性形式集之间的关系是对偶性的本质，一个经常被松散使用的术语，但可以精确地作为给定向量空间e的子空间集与其对偶e的子空间集之间的双射。在这种对应关系中，e的子空间v产生e的子空间v 0，由在v上消失的所有线性形式组成（即，v中所有输入的值为零）。考虑下一组r3中的两个“线性方程”，

*x*              −Y+Z=0 x−Y−Z=0，

让我们找出它们的公共解（x，y，z）的集合v∈r3。通过从第一个方程中减去第二个方程，我们得到2z=0，并且通过添加这两个方程，我们发现2（x-y）=0，因此解的集合v由下式给出：

*y*              =x z=0。

这是r3的一维子空间。几何上，这是平面z=0中方程y=x的直线。

三百一十九

现在，为什么我们说上面的方程是线性的？这是因为，作为（x，y，z）的函数，两个映射f1:（x，y，z）→7 x−y+z和f2:（x，y，z）7→x−y−z都是线性的。从r3到r的所有这些线性函数的集合是一个向量空间；我们利用这个事实来形成“方程式”f1和f2的线性组合。观察子空间V的尺寸为1。环境空间的尺寸为n=3，有两个“独立”方程f1、f2，因此由m独立方程定义的子空间v的尺寸dim（v）似乎是

尺寸（V）=N−m，

这确实是一个普遍的事实。

一般来说，在RN中，线性方程是由一个n-元组（a1，…，an）∈RN决定的，该线性方程的解是由n-元组（x1，…，xn）∈RN给出的，这样a1x1+·····+anxn=0；

这些解构成了线性映射（x1，…，xn）7→a1x1+·····+anxn的核心。上述考虑假设我们在RN的规范基（e1，…，en）中工作，但是我们可以通过将“线性方程”视为从E到K场的线性映射的向量空间hom（e，k）的元素，来定义独立于基和任何维的“线性方程”。

定义10.1.对于向量空间e，从e到场k的线性映射的向量空间hom（e，k）称为e的对偶空间（或对偶空间）。空间hom（e，k）也用e表示，e中的线性映射称为线性形式，或covector。空间e的双空间e称为e的双空间。

记法上，线性形式f:e→k也用星号表示，如u、x等。

给定一个向量空间e和任意基（u i）i∈i for e，我们可以将一个线性形式u i∈e与每个ui关联，并且u i具有一些显著的性质。

定义10.2.给定一个向量空间e和任意基（ui）i∈i for e，通过命题3.13，对于每一个i∈i，都有一个唯一的线性形式，这样

，

对于每个j∈i，线性形式称为索引i w.r.t的坐标形式。基础

（ui）i∈i。

第3.8节解释了术语坐标表的原因。

我们在定理3.18中证明，如果（u1，…，un）是e的基，那么（）是e的基，称为对偶基。

10.1。双空间E和线性形式

如果（u1，…，un）是rn的基（更一般地说是kn），则可以显式地找到对偶基（），其中每个u i由行向量表示。例如，考虑b'ezier矩阵的列

.

由于条件定义的公式=0，因此它由行向量（λ1λ2λ3λ4）表示，以便

.

这意味着这是B4的倒数第1行。自从

，

线性形式（）对应于B4-1的行。特别地，用（1 1 1 1 1）表示。

上述方法适用于任意n。给定rn的任何基（u1，…，un），如果p是n×n矩阵，其jth列为uj，则对偶形式由矩阵p-1的第i行给出。

当e是有限维n且（u1，…，un）是e的基础时，我们注意到该族

）是双空间e（称为（u1，…，un）的双基）的基础。让我们看看双基上的线性形式_的坐标是如何随基的变化而变化的。

设（u1，…，un）和（v1，…，vn）为e的两个基，设p=（aij）为基矩阵从（u1，…，un）变为（v1，…，vn），使

，

设p−1=（bij）为p的倒数，因此

.

由于u i（uj）=δij和vi（vj）=δij，我们得到

，

因此

，

和

.

这意味着基础从双重基础（）转变为双重基础。自从

，

我们得到

，

因此，使用矩阵p>将新坐标j表示为旧坐标_i。如果我们使用行向量（_，…，n）和（），我们有

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.gif)

与基础变化比较

，

我们注意到，这一次，线性形式_的坐标（_i）与基础变化方向相同。因此，我们说线性形式的坐标是协变的。由于语言的滥用，人们常说线性形式是协变的，这就解释了为什么covector这个术语也用于线性形式。

如果（e1，…，e n）是向量空间e的基础，那么，作为从e到k的线性映射，每一个线性形式f∈e都由1×n矩阵表示，也就是说，由一个行向量表示。

（λ1，…，λn）

关于e的基（e1，…，e n）和k的基（1），其中f（ei）=λi。向量u=由n×1矩阵表示，即由列向量表示。

，

10.1。双空间E和线性形式

f对u的作用，即f（u），用矩阵积表示。

.

另一方面，对于对偶基（，线性形式f是

由列向量表示

.

备注：在许多使用张量的文本中，向量通常用较低的索引索引。如果是这样，则更方便的是使用上面的索引将向量X的坐标写在基（U1，…，Un）上，这样，

，

在基础的变化中，我们

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image004.gif)

和

.

同时，线性形式被索引为高索引。然后，在双基（u 1，…，u n）上使用较低的索引将covector的坐标_写为（_i），以便

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image006.gif)

在基础的变化中，我们

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image008.gif)

和

.

有了这些约定，求和的指标在上下两个位置分别出现一次，求和符号可以被安全地省略，这是爱因斯坦的一个技巧。例如，我们可以写

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image010.gif)

作为的缩写

.

对于爱因斯坦符号的另一个例子，如果向量（v1，…，vn）是向量（u1，…，un）的线性组合，则

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image012.gif)

那么上述方程是：

vi=Ajiuj，1≤i≤n。

因此，在爱因斯坦的表示法中，n×n矩阵（aij）用（aji）表示，这是一个（1，1）张量。

注意，有些作者认为矩阵是坐标之间的映射，在这种情况下，矩阵（aij）用（aij）表示。

## 10.2 E与E_的配对与对偶性

给定线性形式u∈e和向量v∈e，应用u to v的结果u（v）也用hu，v i表示。这定义了一个满足以下性质的二元运算h−，−i:e×e→k：

hu 1+u 2，vi=hu 1，vi+hu 2，vi

胡，v1+v2i=hu，v1i+hu，v2i hλu，vi=λhu，vi hu，λvi=λhu，vi.

上面的恒等式意味着h−、−i是双线性映射，因为它在每个参数中都是线性的。通常称为e和e之间的正则对，鉴于上述恒等式，给定任何固定向量v e，映射evalv:e→k（v处的评价）定义如下：

evalv（u）=hu，vi=u（v）对于每个u∈e

是从e到k的线性映射，也就是说，evalv是e中的线性形式。同样，根据上述身份，地图evale:e→e，定义如下：

evale（v）=evalv，对于每个v∈e，

是一个线性映射。注意

evale（v）（u）=hu，vi=u（v），对于所有v∈e和所有u∈e。

10.2。E与E的配对与对偶性

我们将看到映射evale是内射的，当e有有限维时它是同构的。

我们现在将线性方程组v 0的概念形式化，在给定子空间v e中的所有向量上消失，并将线性方程组u e的公共解集u0的概念形式化。对偶定理（定理10.1）表明，v和v 0的维数，以及u和u0的维数，都以一种关键的方式联系在一起。在有限维上，图V 7→V 0和U 7→U0是从E的子空间到E的子空间的逆双射。

定义10.3.在给定向量空间e及其对偶e的情况下，如果hu，vi=0，则向量v e和线性形式u e是正交的。给定e的子空间v和e的子空间u，我们认为对于每个u∈u和每个v∈v，v和u是正交的，如果hu，vi=0。给出e（resp.e的一个子集u），v的正交v 0是e的子空间v 0，定义如下：

v 0=u∈e hu，vi=0，对于每个v∈v

（响应u的正交u0是e的子空间u0，定义如下：

u0=v∈e hu，vi=0，对于每个u∈u）。

子空间v 0 e也被称为v的湮灭子。被u e_歼灭的子空间u0 e没有特殊名称。把它称为线性子空间（或线性变化）似乎是合理的。

非正式地说，v 0是在v上消失的线性方程组，u0是在u中所有线性方程的公共零点组。我们也可以用

V 0=U∈E V Keru

和U0

.

观察e0=0=（0）和0 0=e。此外，如果v1 v2 e，则

，如果U1 U2 E，那么。

实际上，如果v1 v2 e，那么对于任何一个，对于所有v∈v2，我们都有f（v）=0，因此对于所有v∈v2，f（v）=0。同样地，如果u1 u2 e，那么对于任何一个，对于所有的f（v）=0，对于所有的f∈u2，那么f（v）=0，对于所有的f∈u1，这意味着。

下面是一些例子。设e=m2（r），实2×2矩阵的空间，设v为矩阵所跨越的m2（r）的子空间。

.

我们会立即检查子空间v是否由该形式的所有矩阵组成。

，

也就是说，所有的对称矩阵。矩阵

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image014.gif)

在v中满足方程

A12−A21=0，

所有这些方程的标量倍数，所以v 0是e的子空间，用u（a11，a12，a21，a22）给出的线性形式表示。根据对偶定理（定理10.1），我们有

尺寸（V 0）=Dim（E）−Dim（V）=4−3=1。

上面的例子推广到e=mn（r）对于任何n≥1，但这次，考虑线性形式的空间u，断言矩阵a是对称的；这些是由n（n−1）/2方程所跨越的线性形式。

aij−aji=0，1≤i<j≤n；

注意，对角项和半个方程没有限制。

aij−aji=0，1≤i=6 j≤n

是冗余的。很容易验证i<j的方程（线性形式）是线性独立的。更精确地说，假设u是E中线性形式的空间，由线性形式u i j（a11，…，a1n，a21，…，a2n，…，an1，…，ann）=aij−aji，1≤i<j≤n所跨越。

然后，这些方程的公共解的集合u0是对称矩阵的空间s（n）。根据对偶定理（定理10.1），这个空间有维

.

我们把它作为一个练习来寻找s（n）的基础。

如果e=mn（r），考虑e中由线性形式所跨越的线性形式的子空间u。

u i j（a11，…，a1n，a21，…，a2n，…，an1，…，ann）=aij+aji，1≤i<j≤n u ii（a11，…，a1n，a21，…，a2n，…，an1，…，ann）=aii，1≤i≤n。

10.2。E与E的配对与对偶性

很容易看出这些线性形式是线性独立的，所以dim（u）=n（n+1）/2。满足上述方程的矩阵a∈mn（r）的空间u0显然是斜对称矩阵的空间斜交（n）。根据对偶定理（定理10.1），u0的维数为

.

我们把它作为一个练习来寻找歪斜（n）的基础。

对于另一个例子，e=mn（r），对于任何a∈mn（r），考虑由tr（a）=a11+a22+·········+ann给出的e中的线性形式，

称为a的迹线。e的子空间u0由所有矩阵a组成，这样tr（a）=0是尺寸n2-1的空间。我们把它作为一个练习来寻找这个空间的基础。尺寸方程

尺寸（V）+尺寸（V 0）=Dim（E）Dim（U）+Dim（U0）=Dim（E）

总是正确的（如果e是有限维的话）。这是对偶定理（定理）的一部分

10.1）。

在前面的例子中，给定矩阵a∈mn（r），断言a>a=i的方程不是线性约束。例如，对于n=2，我们有

A211+A221=1 A221+A222=1 A11A12+A21A22=0。

评论：

(1)    符号v 0（分别为u0）表示e（resp）的子空间v的正交。e）的子空间u不是通用的。其他作者使用符号v（resp.u）。然而，符号v也用于表示子空间v相对于空间e上内积的正交补码，在这种情况下，v是e的子空间，而不是e的子空间（见第11章）。为了避免混淆，我们更喜欢使用表示法v 0。

(2)    由于线性形式可以看作线性方程（至少在有限维中），给定e的一个子空间（甚至一个子空间）u，我们可以用

z（u）=v∈e u（v）=0，对于所有u∈u。

当然z（u）=u0，但概念z（u）可以推广到更一般的方程，即多项式方程。在这个更一般的设置中，u是一组n个变量的多项式，系数为k（其中n=dim（e））。形式z（u）的集合称为代数变种。线性形式对应于一阶齐次多项式被考虑的特殊情况。

如果v是e的子集，那么很自然地将k[x1，…，xn]中消失在v上的多项式集与v联系起来。这个集合，通常表示为i（v），有一些特殊的属性使它成为理想。如果v是e的一个线性子空间，我们自然会把注意力限制在v上消失的线性形式的空间v 0上，在这种情况下，我们识别i（v）和v 0（尽管从技术上讲，i（v）不再是理想的）。

对于任意一组多项式u k[x1，…，xn]（resp v e），i（z（u））和u（resp）之间的关系。z（i（v））和v）通常不简单，即使我们总是

u i（z（u））（分别为v z（i（v）））。

然而，当场k是代数闭的，那么i（z（u））等于理想u的根式，这是希尔伯特的著名结果，被称为nullstellensatz（见lang[106]或dummit和foote[55]）。代数变种的研究是代数几何学的主要课题，是一门美丽而又令人生畏的学科。要了解代数几何，请参见lang[106]或dummit和foote[55]。

对偶定理（定理10.1）表明，如果我们把注意力局限于线性子空间，情况会简单得多；在这种情况下

u=i（z（u））和v=z（i（v））。

我们声称e的每个子空间v v 00，e的每个子空间u的u u00。

实际上，对于任何v∈v，为了证明v∈v 00，我们需要证明u（v）=0对于所有u∈v 0。然而，v 0由所有线性形式u组成，因此u（y）=0表示所有y∈v；特别是，因为v v，u（v）=0表示所有u∈v 0，根据需要。

同样，对于任何u∈u，为了证明u∈u00，我们需要证明u（v）=0对于所有v∈u0。但是，u0由所有向量v组成，因此f（v）=0表示所有f∈u；特别是，由于u∈u，u（v）=0表示所有v∈u0，根据需要。

我们很快就会看到，在有限维中，我们有v=v 00和u=u00。

然而，即使v=v 00总是真的，当e是无限维时，u=u00也不总是真的。

在给定向量空间e和e的子空间u的情况下，根据定理3.5，u的每一个基（u i）i∈i都可以推广到e的基（u j）j∈i j，其中i j为∅。


 

## 10.3对偶定理

我们有以下重要的定理改编自E.Artin[6]（第1章）。

定理10.1。（对偶定理）让e是一个向量空间。以下属性保留：

*(a)*    对于e的每一个基（ui）i∈i，坐标形式族是线性独立的。

*(b)*    对于e的每个子空间v，我们有v 00=v。

*(c)*     对于e的有限余维m的每个子空间v，对于e的每个子空间w，使e=v_w（其中w是有限维m），对于e的每个基（ui）i∈i，使（u1，…，um）是w的基，该族是正交的基。

e中v的0，因此dim（v 0）=codim（v）。

此外，我们有v 00=v。

*(d)*    对于e的有限维m的每个子空间u，e中u的正交u0是有限余维m，因此

codim（u0）=dim（u）。

此外，u00=u。

证据。（a）假设

xλiu i=0，

我爱我

对于一个家族（λi）i∈i（k中的标量）。因为（λi）i∈i有有限的支持，所以i有一个有限的子集j，因此，对于所有i∈i−j，λi=0，我们有

xλju j=0.

J·J·J

将线性形式pj∈jλj u j应用于每一个uj（j∈j），根据定义10.2，因为u i（uj）=1，如果i=j，否则为0，我们得到所有j∈j的λj=0，即所有i∈i的λi=0（根据j的定义作为支持）。因此，（是线性无关的。

V

（因此，ui）（i∈b）显然，我们有ij0是∈/i的基础。从0开始（其中v∈00v，i00u。如果j0jis与=v∅=6）中的每种线性形式正交。从00开始，那么让（v=6 Vu00i，）i∈uij 0 j∈作为0的一个00的基础。现在，我们有vj000，这样∈j（和

UJ V

）=0表示所有i∈i，因此。然而，）=1，这与uj0与v 0中的所有线性形式都是正交的这一事实相矛盾。因此，v=v 00。

(c)       设j=i−1，…，m。每一个线性形式f∈v 0与每一个uj正交，对于j j，因此，f（uj）=0，对于所有j j。对于这样一个线性形式f∈v 0，让

.

我们有g（ui）=f（ui），对于每个i，1≤i≤m。此外，根据定义，g在所有uj上消失，其中j∈j。因此，f和g在（ui）i∈i of e，and so，g=f。

这表明（）产生了v 0，由于它也是一个线性独立的族，

）是V 0的基础。很明显，dim（v 0）=codim（v），根据（b）部分，我们得到v 00=v。

(d)      让（）作为u的基础。注意地图h:e→km的定义如下：

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image016.gif)

对于每一个v∈e，都是一个线性映射，其核kerh精确地为u0。

提案5.11，e≈ker（h）imh=u0 imh，

由于dim（imh）≤m，我们推断u0至多是有限余维e的一个子空间，通过（c），我们得到dim（u00）=codim（u0）≤m=dim（u）。然而，很明显u u00，这意味着dim（u）≤dim（u00），所以dim（u00）=dim（u）=m，我们必须有u=u00。

定理10.1的（a）部分表明

尺寸（e）≤尺寸（e）。

当e是有限维n且（u1，…，un）是e的基础时，通过（c）部分，族

）是双空间e的基础，称为（u1，…，un）的双基础。定理3.18也直接证明了这一事实。

定义从e的子空间到e的子空间的函数e（e表示方程）和从e的子空间到e的子空间的函数z（z表示零），方法是

| 网络错误   网络错误   网络错误 | 网络错误   网络错误 |
| ------------------------------ | ------------------- |
|                                |                     |

（z_e）（v）=v 00=v

（e_z）（u）=u00=u，

其中v是e的有限余维的子空间，u是e的有限维的子空间，因此映射e和z是这些子空间之间的反向双射。这些映射在e的有限余维子空间和e的有限维子空间之间建立了对偶性。特别是，如果e是有限维，那么维m的每个子空间v e是线性形式空间（方程）v 0的公共零点集，它的维数为n−m。这证实了我们对由一组线性方程定义的子空间的维数所作的声明。

注意这个双射不延伸到无限维的e的子空间。

当e是无限维时，对于e的每一个基（u i）i∈i，坐标形式的族（u i）i∈i绝不是e的基。它是线性独立的，但它“太小”不能产生e。例如，如果e=r（n），其中n=0,1,2，…，则表示e中向量的非零坐标和的映射f:e→r是线性形式，但很容易看出它不能表示为坐标形式的线性组合。因此，当e是无限维时，e和e不是同构的。

假设v是维m的rn的子空间，而（v1，…，vm）是v的基础。为了找到v 0的基，我们首先将（v1，…，vm）扩展到rn的基（v1，…，vn），然后通过定理10.1的（c）部分，我们知道（）是v0的基。例如，假设v是两个线性无关向量所跨越的r4的子空间。

，

r4中haar基的前两个向量。haar矩阵的四列

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)

构成r4的基础，w的倒数由

.

因为双基（）由w-1的行给出，w-1的最后两行，

，

构成V 0的基础。我们还通过因子1/2重新缩放获得了一个基，因此行向量给出的线性形式

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image020.gif)

形成V 0的基础，即线性形式（线性方程）在子空间V上消失的空间。

我们描述的求v 0的方法需要先扩展v的基，然后求逆矩阵，但还有一种更直接的方法。实际上，假设a是n×m矩阵，其列是v的基向量（v1，…，vm）。那么，由行向量表示的线性形式u属于v 0 iff u v i=0，i=1，…，m iff。

UA＝0

敌我识别

A>U>=0。

因此，我们需要做的就是找到>的空空间的基础。这可以通过将矩阵约简为约简行梯队形式（RREF）来非常有效地实现；参见第节

7.10。

现在让我们考虑一个问题，找到由方程定义的Rn中超平面h的基。

c1x1+·····+cnxn=0.

更准确地说，如果u（x1，…，xn）是u（x1，…，xn）=c1x1+······+cnxn给出的（rn）中的线性形式，那么超平面h是u的核心。当然，我们假设一些Cj是非零的，在这种情况下，线性形式u跨越（rn）的一维子空间u，并且u0=h具有尺寸n-1。

| 网络错误                                                     |                                           |
| ------------------------------------------------------------ | ----------------------------------------- |
| 网络错误                                                     | 网络错误                                  |
| 1           网络错误   2           网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误 |

| 网络错误   网络错误   网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误   网络错误   网络错误 |
| ------------------------------------------------------------ | ----------------------------------------- | ------------------------------ | ----------------------------------------- | ---------------------------------------------------- | ----------------------------------------- | ----------------------------------------- | ------------------------------------------------------------ |
|                                                              |                                           |                                |                                           |                                                      |                                           |                                           |                                                              |

由于u不是一个相同为零的线性形式，所以有一个最小的正指数j≤n，使得cj=06，所以我们的线性形式实际上是u（x1，…，xn）=cjxj+······+cnxn。我们

j1 0 0…1 0 0…0

J 0 0…0 C/C C/C…C/C_

观察删除j行得到的（n-1）×n-1）矩阵是单位矩阵，因此上述矩阵的列是线性无关的。一个简单的计算也表明，线性形式u（x1，…，xn）=cjxj+·····+cnxn在上述矩阵的每一列上都消失了。对于R6中的一个具体例子，如果u（x1，…，x6）=x3+2x4+3x5+4x6，我们得到方程的超平面h的基础。

x3+2x4+3x5+4x6=0

由以下矩阵给出：

| 网络错误   网络错误   网络错误   网络错误   网络错误   网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误   网络错误   网络错误 | 网络错误   网络错误   网络错误 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------------- | ---------------------------------------------------- | ------------------------------ |
|                                                              |                                                              |                                                      |                                                      |                                |

相反，给定一个超平面h，在rn中，作为n-1线性向量的跨度。

（u1，…

和

是两个线性无关的向量，那么

，

u和v的叉积u×v由

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image022.gif)

是一个解决方案。

下面是另一个例子，说明定理10.1的幂。设e=mn（r），并考虑断言矩阵a∈mn（r）每一行中的项之和等于同一个数的方程。我们有n-1方程

，

很容易看出它们是线性独立的。因此，由上述线性形式（方程）所跨越的e中线性形式的空间u的维数为n−1，而将所有这些方程化的矩阵的空间u0的维数为n2−n+1。找到这个空间的基础并不那么明显。

现在我们将确定向量空间e与其双e之间的关系。

提案10.2.设e为向量空间。以下属性保留：

*(a)*     线性映射evale:e→e定义如下：

evale（v）=evalv，对于所有v∈e，

也就是说，evale（v）（u）=hu，vi=u（v）对于每个u∈e，都是内射的。

*(b)*     当e为有限维n时，线性映射evale:e→e是同构（称为规范同构）。

证据。（a）设（ui）i∈i为e的基，设v=pi∈i viui。如果evale（v）=0，那么特别是eval）=0表示全部，并且自

埃瓦

对于所有i∈i，我们有vi=0，也就是说，v=0，表明evale:e→e是内射的。

如果e是有限维n，根据定理10.1，对于每个基（u1，…，un），族

）是双空间e的基础，因此族（）是双空间e的基础。这表明dim（e）=dim（e）=n，由于（a）部分，我们知道evale:e→e是内射的，实际上evale:e→e是双射的（因为一个内射映射将一个线性独立的族传递给一个线性独立的族，在一个维数为n的向量空间中，一个li几乎独立的n向量族是一个基础，见命题

3.6）。

当一个向量空间E有无限维时，E及其双e永远不同构。

当e是有限维且（u1，…，un）是e的基础时，考虑到正则同构evale:e→e，双元的基础（）用

（U1，…，联合国）。

命题10.2可以用配对的方式非常有效地重新表述，这是庞特贾金在1931年发现的一个非常有用的概念（改编自E.Artin[6]，第1章）。在一个k域上给定两个向量空间e和f，我们认为，如果对于每一个v∈v，映射u 7（u，v）（从e到k）是线性的，对于每一个u∈e，映射v 7→（u，v）（从f到k）是线性的，那么函数_：e×f→k是双线性的。

定义10.4.在两个向量空间e和f超过k的情况下，e和f之间的配对是双线性映射，即：e×f→k。这种配对是非退化的iff。

(1)    对于每一个u∈e，如果所有v∈f的（u，v）=0，则u=0，并且

(2)    对于每一个v∈f，如果所有u∈e的（u，v）=0，则v=0。

一个配对：e×f→k通常用h−、−i:e×f→k表示。例如，前面定义的映射h−、−i:e×e→k是一个非退化配对（使用命题10.2中（a）的证明）。如果e=f和k=r，e上的任何内积都是非退化配对（因为内积是肯定的）；见第11章。


 

10.4。超平面和线性形式

给出了一个配对，我们可以定义两个映射，l_：e→f和r_：f→e如下：对于每个u∈e，我们在f_中定义线性形式l_（u），这样

l_（u）（y）=_（u，y），对于每个y∈f，

对于每一个v∈f，我们定义e中的线性形式r_（v），这样

每x∈e，r（v）（x）=（x，v）。

我们有以下有用的建议。

提案10.3.给定两个向量空间e和f over k，对于e和f之间的每一个非退化配对，映射l_：e→f和r_：f→e_是线性的和内射的。此外，如果e和f有有限的尺寸，那么这个尺寸是相同的，l_：e→f和r_：f→e是双射。

证据。因为配对是双线性的，所以图l_：e→f和r_：f→e_是线性的。如果l_（u）=0（零形式），则

对于每一个v∈f，

既然_是非退化的，u=0。因此，l_：e→f是注射的。同样，R_：F→E是注射剂。当f有有限维数n时，我们已经看到f和f有相同的维数。因为l_：e→f是内射的，我们有m=dim（e）≤dim（f）=n。同样的论点也适用于e，因此n=dim（f）≤dim（e）=m。但是，dim（e）=dim（f），l_：e→f和r_：f→e是双射。

当e有有限维时，非简并配对h−，−i:e×e→k给出了e与e之间存在自然同构的另一个证明。当e=f时，由e上的内积引起的非退化配对产生e和e之间的自然同构（见第11.2节）。

有趣的非退化配对出现在外代数中。我们现在展示超平面和线性形式之间的关系。

## 10.4超平面和线性形式

实际上，下面的命题10.4是从定理10.1的（c）和（d）部分得出的，但我们认为给出一个更直接的证明也是有趣的。

提案10.4.设e为向量空间。以下属性保留：

*(a)*     给定任意非零线性形式f∈e，其核h=kerf是超平面。

*(b)*     对于e中的任何超平面h，都有一个（非空）线性形式f∈e，这样h=kerf。

*(c)*     给定e中的任意超平面h和任意（非空）线性形式f∈e，使得h=kerf，对于每个线性形式g∈e，h=kerg iff g=λf，对于k中的某些λ=06。

证据。（a）如果f∈e为非空，则存在一些向量v0∈e，使得f（v0）=06。让

H=切口。对于每一个v∈e，我们有

.

因此，

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image024.gif)

和

，

也就是说，e=h+kv0。另外，由于f（v0）=06，我们得到v0∈/h，即h kv0=0。因此，e=h kv0，h是超平面。

(b)      如果h是一个超平面，对于某些v0∈/h，e=h kv0，那么每个v∈e都可以用一种独特的方式写成v=h+λv0。因此，有一个定义明确的函数f：e→k，因此，对于每个v=h+λv0，f（v）=λ。作为一个简单的练习，我们将验证f是一个线性形式。由于f（v0）=1，线性形式f为非空。而且，根据定义，很明显，λ=0 iff v∈h，即切口=h。

(c)       设h为e中的超平面，设f∈e为任意（非空）线性形式，使得h=kerf。显然，如果g=λf对于某些λ=06，则h=kerg。相反，假设对于某些非空线性形式g，h=kerg。从（a），我们得到e=h kv0，对于一些v0，这样f（v0）=06和g（v0）=06。然后，观察

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image026.gif)

是一个在h上消失的线性形式，因为f和g都在h上消失，但也在kv0上消失。因此，g=λf，与

.

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image027.gif)

作为练习，我们将向量空间e的每个子空间v=6e，都是包含v的所有超平面的交集。我们现在考虑线性映射和矩阵转置的概念。

## 10.5线性映射和矩阵的转置

给定一个线性映射f:e→f，可以定义一个具有一些有趣特性的映射f>：f→e。

定义10.5.给定线性映射f:e→f，f的转置f>：f→e是定义如下的线性映射：

f>（v）=v f，对于每个v∈f，

如下图所示：

f

fe>（bb bbbb/f v_

五）

K

等效地，线性映射f>：f→e的定义如下：

hv，f（u）i=hf>（v），ui，

对于所有u e和所有v f。

很容易验证以下属性是否有效：

(f    +g）>=f>+g>

(g   _f）>=f>g>id.

注意（g f）>=f>g>右侧的成分倒转。

方程式（g f）>=f>g>包含以下有用的命题。

提案10.5.如果f:e→f是任何线性映射，则以下属性保持不变：

*(1)*    如果F是注射剂，那么F>是注射剂。

*(2)*    如果F是Surjective，则F>是Injective。

证据。如果f:e→f是注射剂，那么它有一个收缩r:f→e，这样r f=ide，如果f:e→f是注射剂，那么它有一个s:f→e部分，这样f s=idf。现在，如果f:e→f是内射的，那么我们有

（r f）>=f>r>=ide，

这意味着f>是主观的，如果f是主观的，那么我们有

（f s）>=s>f>=idf，

这意味着f>是内射的。

我们还拥有以下显示Eval地图自然性的属性。提案10.6.对于任何线性图f:e→f，我们有

f>>evale=evalf f，

或者等价地，下图是通勤路线：

F>

EO_/O_

逃逸

/

证据。对于每一个u e和每一个_ f，我们有

（f>>evale）（u）（）=hf>>（evale（u）），_i

=混合气（u），f>（）i

=hf>（），用户界面

=h_，f（u）i

=hevalf（f（u）），i

=h（evalf f）（u），i=（evalf f）（u）（）

证明F>>evale=evalf f，如权利要求所述。

如果e和f是有限维的，那么evale和evalf是同构的，所以命题10.6表明，如果我们用e的双e_，和f的双f__，那么（f>）>=f来标识e。

作为命题10.6的推论，如果dim（e）是有限的，那么我们得到ker（f>>）=evale（ker（f））。

实际上，如果e是有限维的，那么map evale:e→e_是同构的，因此，对于某些u∈e，每个_ e_的形式都是_=evale（u），map evalf:f→f_是内射的，

| 网络错误 |          |          |          |
| -------- | -------- | -------- | -------- |
|          | 网络错误 | 网络错误 | 网络错误 |
|          |          | 网络错误 | 网络错误 |
|          |          | 网络错误 | 网络错误 |
|          |          | 网络错误 | 网络错误 |
|          |          | 网络错误 | 网络错误 |

这证明了ker（f>>）=evale（ker（f））。

下面的命题说明了正交性和换位之间的关系。

提案10.7.给定一个线性映射f:e→f，对于e的任何子空间v，我们有

f（v）0=（f>）−1（v 0）=w∈f f>（w）∈v 0。

因此，

kerf>=（imf）0和kerf=（imf>）0。

证据。我们有

hw，f（v）i=hf>（w），vi，

对于所有的V ，f（v）i=0，对于每个V，f（v）0，iff（v）0，iff（w）。

由于我们已经观察到e0=（0），在上面的恒等式中取v=e，我们得到

切口>=（imf）0.

从方程式

hw，f（v）i=hf>（w），vi，

我们推导出，v∈（imf>）0 i f f hf>（w），v i=0表示所有w∈f iff hw，f（v）i=0表示所有w∈f。假设v∈（imf>）0。如果我们选取f的基（wi）i∈i，那么我们有这样的线性形式，并且因为我们必须对所有i∈i和（wi）i∈i都有=0，我们得出f（v）=0，因此v∈kerf（这是因为hwi，f（v）i是与基向量wi关联的f（v）的系数）。相反，如果v∈kerf，那么hw，f（v）i=0代表所有w∈f，那么我们得出v∈（imf>）0。因此，v∈（imf>）0 iff v∈kerf，即：

切口=（imf>）0，

如要求。

下面的命题给出了商空间e/u的对偶（e/u）的自然解释。

提案10.8.对于向量空间e的任何子空间u，如果p:e→e/u是e/u上的标准投影，则p>是内射的，并且

im（p>）=u0=（ker（p））0.

因此，p>是（e/u）和u0之间的线性同构。

证据。由于p是主观的，根据命题10.5，映射p>是内射的。显然，u=ker（p）。观察到im（p>）由所有线性形式ψe组成，因此，对于某些_（e/u）来说，ψ=_p，由于ker（p）=u，我们得到u ker（ψ）。相反，对于任何线性

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image028.gif)

式ψ∈e，如果u ker（ψ），则通过e/u的ψ因子为ψ=ψp，如下图所示。

磷

E/E/U

CCCψCCCCC！γ

K

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image029.gif)

式中，ψ：e/u→k由下式给出

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image030.gif)

ψ（v）=ψ（v），v∈e，

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image031.gif)

式中，v∈e/u表示v∈e的等价类，图ψ不依赖于

在V类当量中选择的代表，因为如果v0=v，即v0−v=u∈u，则ψ（v0）=ψ（v+u）=ψ（v）+ψ（u）=ψ（v）+0=ψ（v）。因此，我们有

im（p>）=p∈（e/u）

克（ψ）

这证明了我们的结果。

命题10.8给出了对偶定理（定理10.1）第（b）部分的另一个证明，它不涉及基的存在（在无限维中）。

提案10.9.对于任何向量空间e和e的任何子空间v，我们有v 00=v。

证据。我们首先观察到v 0=v 000。这是因为，对于e的任何子空间u，我们都有u u00，所以v 0 v 000。此外，V V 00保持，任何两个子空间

m，n，e，如果m n，那么n0 n0，我们得到v 000 v 0。写v1=v 00，这样。我们想证明v1=v。

由于v v1=v 00，规范投影p1:e→e/v1因子为p1=f p，如下图所示，

磷

E/E/V型

CCPC1CCCCC！f

E/V1

式中，p:e→e/v是e/v上的正则投影，f:e/v→e/v1是p1诱导的商映射，其中f（ue/v）=p1（u）=ue/v1，对于所有u∈e（既然v v1，如果u−u0=v∈v，那么u−u0=v∈v1，那么p1（u）=p1（u0））。既然p1是主观性的，f也是主观性的，我们想证明f实际上是同构的，因此，就足以证明f是内射的。通过变换所有的映射，我们得到了交换图。

P>

e dho hhhhhhh（he/vo f>）

（e/v1），

但是根据命题10.8，映射p>：（e/v）→v 0和是同构的，因此，我们有下面的图，其中p>和都是同构的：

v 0 hdo hhph>hhhhh（he/vo f>）

（E/V1）。

因此，是同构的。我们声称这意味着f是内射的。

如果f不是内射的，那么有一些x∈e/v，这样x=06和f（x）=0，所以对于每一个θ∈（e/v1），我们有f>（）（x）=（f（x））=0。然而，存在线性形式ψ∈（e/v）使得ψ（x）=1，因此ψ=6 f>（）对于所有的ω∈（e/v1），与f>是主观的这一事实相矛盾。为了找到这样一个线性形式ψ，选取e/v中kx的任何补充w，使e/v=kx w（w是e/v中不含x的超平面），并将ψ定义为w的零和x的1。因此，f是内射的，既然我们已经知道它是外射的，它是双射的。这意味着带有v v1的正则映射f:e/v→e/v1是同构的，这意味着v=v1=v 00（否则，如果v∈v1−v，那么p1（v）=0，那么f（p（v））=p1（v）=0，但是p（v）6=0，因为v/∈v，而f不是内射的）。

下面的定理说明了f的秩与f>的秩之间的关系。

定理10.10。对于线性映射f:e→f，以下属性保持不变。（a）国际货币基金组织的双重（国际货币基金组织）与国际货币基金组织同构，即，

（国际货币基金组织）≈国际货币基金组织>。

（b）Rk（f）≤Rk（f>）。如果Rk（f）是有限的，我们得到Rk（f）=Rk（f>）。证据。（a）考虑线性图

P J E−→IMF−→F，

P.J

式中，e−→imf是e−→f诱导的推测图，imf−→f是imf的注入包含图，根据定义。为了简化符号，让i=imf。根据命题10.5，由于e−→p i是主观性的，i−p→e是内射的，并且

因为imf−→f是注射剂，所以是推测性的。既然f=j_p，我们也有

f>=（j_p）>=p>j>，

既然是主观的，是内射的，我们在（imf）和（f）之间有同构。

（b）我们已经注意到，定理10.1的（a）部分表明，对于每个向量空间e，dim（e）≤dim（e）。因此，dim（imf）≤dim（imf），由（a）表示，rk（f）≤rk（f>）。当dim（imf）是有限的，我们已经观察到作为定理10.1的推论，dim（imf）=dim（（imf）），因此，通过（a）部分，我们得到了rk（f）=rk（f>。

如果dim（f）是有限的，那么还有一个简单的证明（b）不使用（a）部分的结果。根据定理10.1（c）

dim（imf）+dim（imf）0）=dim（f），

根据定理5.11，dim（kerf>）+dim（imf>）=dim（f）。

此外，根据10.7号提案，我们

切口>=（imf）0，

因为f是有限维dim（f）=dim（f），所以我们推导

dim（imf）+dim（（imf）0）=dim（（imf）0）+dim（imf>），

得出dim（imf）=dim（imf>）；也就是说，rk（f）=rk（f>）。

评论：

\1.    如果dim（e）是有限的，根据dan guralnik的论点，我们也可以证明rk（f）=rk（f>）如下。

我们从适用于f>：f→e的10.7号提案得知

ker（f>>）=（imf>）0，

我们从10.6号提案中得出结论：

ker（f>>）=evale（ker（f））。

因此（因为evale是同构的），dim（（im f>）0）=dim（ker（f>））=dim（ker（f））=dim（e）−dim（im f），

因为dim（imf>）+dim（（imf>）0）=dim（e），

我们得到dim（im f>）=dim（imf）。

\2.    如Dan Guralnik所述，如果dim（e）是有限的，则上述结果可用于证明

imf>=（ker（f））0.

从

h f>（），u i=h_，f（u）i

对于所有的_ f和所有的u e，我们看到如果u ker（f），那么hf>（），ui=h_，0i=0，这意味着f>（_）（ker（f））0，因此，imf>（ker（f））0。反之，因为dim（e）是有限的，我们有

dim（（ker（f））0）=dim（e）−dim（ker（f））=dim（imf），

但我们刚刚证明了dim（im f>）=dim（imf），所以我们得到

dim（（ker（f））0）=dim（imf>），

由于imf>（ker（f））0，我们得到

imf>=（ker（f））0，

如要求。现在，由于（ker（f））00=ker（f），上述方程得出了另一个事实证明：

ker（f）=（imf>）0，

当e是有限维时。

三。方程式

imf>=（ker（f））0

实际上是有效的，即使当e是无限维时，如我们现在所证明的。

提案10.11.如果f:e→f是任何线性映射，则以下恒等式成立：

imf>=（ker（f））0

ker（f>）=（imf）0

imf=（ker（f>）0 ker（f）=（imf>）0.

证据。等式ker（f>）=（imf）0已经在命题10.7中得到证明。

根据对偶定理（ker（f））00=ker（f），所以从imf>=（ker（f））0我们得到ker（f）=（imf>）0。同样，（imf）00=imf，所以从ker（f>）=（imf）0我们得到imf=（ker（f>）0。因此，有待证明的是，imf>=（ker（f））0。

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image032.gif)

设P:E→E/Ker（f）为规范化假设，F:E/Ker（f）→imf为f诱导的同构，J:imf→f为包含图。那么，我们有了

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image032.gif)

F=J_F_P，

这意味着

F>=P>F>J>。

因为P是射血的，P>是射血的，因为J是射血的，是射血的，因为F是射血的。

双射，f>也是双射。由此得出（e/ker（f））=im（f_j>），我们有imf>=imp>。

因为p:e→e/ker（f）是标准的投注，所以命题10.8适用于u=

克尔（F），我们得到

imf>=imp>=（ker（f））0，

如要求。

总之，方程式

imf>=（ker（f））0

适用于任何维度，它意味着

ker（f）=（imf>）0.

下面的命题显示了表示线性映射f:e→f的矩阵与表示其转置f>：f→e的矩阵之间的关系。

提案10.12。设e和f为两个向量空间，设（u1，…，un）为e的基，（v1，…，vm）为f的基。给定任意线性映射f:e→f，如果m（f）是表示f w.r.t的m×n-矩阵。基（u1，…，un）和（v1，…，vm），n×m-矩阵

m（f>）表示f>：f→e w.r.t.双碱基，是m（f）的转置m（f>。

证据。回想一下，m（f）的第i行和第j列中的条目aij是f（uj）在基（v1，…，vm）上的第i个坐标。根据vi的定义，我们得到hvi，f（uj）i=aij。m（f>）第j行和第i列中的条目是

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image034.gif)

基于（），这是公正的。自从

hvi，f（uj）i=hf>（vi），uji，

我们有a i j=a>j i，证明m（f>）=m（f>。


 

10.6。四个基本子空间

现在我们可以给出一个非常简短的证明，证明矩阵的秩等于其转置的秩。

提案10.13。给定一个M×N矩阵A在一个K域上，我们得到了Rk（a）=Rk（a>）。

证据。矩阵A对应于线性映射f:kn→km，根据定理10.10，Rk（f）=Rk（f>）。根据命题10.12，线性映射f>对应于a>。由于Rk（a）=Rk（f），Rk（a>）=Rk（f>，我们得出Rk（a）=Rk（a>）。

因此，给定m×n矩阵a，线性无关列的最大数目等于线性无关行的最大数目。还有其他方法可以证明这个事实，不涉及对偶空间，而是行和列上的一些基本转换。

命题10.13立即给出了确定矩阵秩的下列标准：

提案10.14.给定一个K域上的任意m×n矩阵a（通常k=r或k=c），a的秩是最大自然数r，这样，通过选择a的r行和r列，可以得到a的可逆r×r子矩阵。

例如，3×2矩阵

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image036.gif)

具有三个2×2矩阵之一的秩2 iff

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image038.gif)

是可逆的。我们在第6章中看到，这相当于上面一个矩阵的行列式非零的事实。这不是一个非常有效的方法来寻找矩阵的秩。我们将看到有更好的方法可以使用各种分解，如LU、QR或SVD。

## 10.6四个基本子空间

给出了一个线性映射f:e→f（其中e和f是有限维），命题10.7揭示了这四个空间

国际货币基金组织，国际货币基金组织>，切口，切口>

扮演一个特殊的角色。它们通常被称为与f相关的基本子空间。这些空间以一种亲密的方式相关，因为命题10.7表明

切口=（imf>）0切口>=（imf）0，

定理10.10表明Rk（f）=Rk（f>）。

用矩阵来翻译这些关系是有指导意义的（事实上，某些线性代数书籍对此做了很大的讨论！）如果dim（e）=n和dim（f）=m，给定e的任何基（u1，…，un）和f的基（v1，…，vm），我们知道f由m×n矩阵a=（aij）表示，其中a的jth列等于f（uj）除以基（v1，…，vm）。此外，转置映射f>由n×m矩阵a>表示（相对于双碱基）。因此，四个基本空间

国际货币基金组织，国际货币基金组织>，切口，切口>

对应于

(1)    a的列空间，用ima或r（a）表示；这是由a的列所跨越的rm的子空间，与f的图像imf相对应。

(2)    a的核或空空间，用kera或n（a）表示；这是由所有向量x∈rn组成的rn的子空间，这样ax=0。

(3)    a的行空间，用ima>或r（a>）表示；这是用a>的行或相当于a>的列跨越的rn的子空间，它对应于f>的图像imf>。

(4)    由kera>或n（a>）表示的a的左核或左零空间；这是a>的核（零空间），rm的子空间由所有向量y∈rm组成，使得a>y=0，或等价地，y>a=0。

回想一下，imf的维数r，也等于列空间的维数ima=r（a），是a（和f）的秩。然后，我们以前的一些结果可以重新表述如下：

\1.    a的列空间r（a）具有维度r。

\2.    a的空空间n（a）具有尺寸n−r。

\3.    行空间r（a>）具有维度r。

\4.    a的左侧空空间n（a>）具有尺寸m−r。

10.6。四个基本子空间

以上陈述构成了Strang所称的线性代数基本定理，第一部分（见Strang[165]）。

这两个陈述

切口=（imf>）0

切口>=（imf）0

翻译为

(1)    a的空空间是a的行空间的正交。

(2)    a的左空空间是a的列空间的正交。

以上陈述构成了Strang所称的线性代数基本定理，第二部分（见Strang[165]）。

由于向量由列向量和线性形式由行向量表示（在e或f的基上），如果

yx=0.

然后，向量x∈rn与iff的行空间正交，x与a的每一行正交，即ax=0，相当于x属于a的空空间，同样，列向量y∈rm（表示f的对偶基上的线性形式）属于空。a>iff a>y=0，iff y>a=0，这意味着y>给出的线性形式（在f的基上）与a的列空间正交。

由于（2）等于a的列空间等于a的左零空间的正交，我们得到了形式为ax=b的方程的可解性的下列准则：

方程ax=b对所有y∈rm有一个解iff，如果a>y=0，则y>b=0。

实际上，右边的条件是b与a的左边空空间是正交的，即b属于a的列空间。

如果直接检查B是否由A列跨越，这个标准会更便宜。例如，如果我们考虑系统

x1−x2=b1 x2−x3=b2 x3−x1=b3

其矩阵形式为ax=b，如下所示：

，

我们看到矩阵A的行加起来是0。事实上，很容易让我们相信，a的左零空间的范围是y=（1,1,1），因此系统是可解的，如果y>b=0，即

b1+b2+b3=0。

请注意，上述标准也可作如下负面说明：

方程ax=b没有解，如果有y∈rm，则a>y=0，y>b=0.6。

由于a>y=0，当y>a=0时，我们可以将y>视为表示线性形式的行向量，y>a=0断言线性形式y>在a1列上消失，…，a的a列上消失，但不在b上消失。由于线性形式y>定义了方程y>z=0的超平面h（用z∈rm），几何上方程ax=b没有解，如果有一个超平面h，包含a1，…，a，不包含b。

## 10.7总结

本章的主要概念和结果如下：

•     双空间E和线性形式（covector）。招标人E。

•     双线性配对H−、−I:E×E→K（规范配对）。

•     在v:evalv:e→k时的评估。

•     地图评估：E→E。

•     e的子空间v与e的子空间u之间的正交性；正交v 0和正交u0。

•     坐标形式。

•     对偶定理（定理10.1）。

•     基础的双重基础。

•     当dim（e）有限时，同构evale:e→e。

•     两个向量空间之间的配对；非退化配对；命题10.3。

•     超平面和线性形式。

•     线性映射f:e→f的转置f>：f→e。

•     基本特征：

kerf>=（imf）0和kerf=（imf>）0

（提案10.7）。

10.7。总结

•     如果f是有限维，那么

Rk（f）=Rk（f>）。

（定理10.10）。

•     转置映射f>的矩阵等于映射f的矩阵的转置（命题10.12）。

•     对于任何M×N矩阵A，Rk（a）=Rk（a>）。•根据最大可逆子矩阵描述矩阵的秩（命题10.14）。

•     四个基本子空间：

国际货币基金组织，国际货币基金组织>，切口，切口>。

•     （矩阵的）列空间、空空间、行空间和左空空间。

•     形式为ax=b的方程的左零空间可解性准则。


 