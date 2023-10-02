# 1121 CP1

[TOC]

## 2023/09/19
### hw01 Rectangle Area
<div class="v-card v-theme--light v-card--density-default elevation-5 rounded-lg v-card--variant-elevated pa-2"><!----><!----><div class="pa-4"><h5 class="text-h5 font-weight-bold mb-2">Description</h5><div class="v-md-editor-preview pa-2" style="tab-size: 2;"><div class="vuepress-markdown-body"><h3 data-v-md-heading="objective" data-v-md-line="1">Objective</h3>
<p data-v-md-line="2">Practice how to write a C program that includes basic components such as main function, arithmetic expressions, and basic input and output.</p>
<h3 data-v-md-heading="description" data-v-md-line="4">Description</h3>
<p data-v-md-line="5">There is a rectangle in plane coordinates. Give you the coordinates of the upper-left and bottom-right points of the given rectangle. Please calculate the area of the rectangle.</p>
<p data-v-md-line="7"><img src="https://oj.ebg.tw/public/upload/aea7fe88aa.png" alt="Description"></p>
</div></div></div><div class="pa-4"><h5 class="text-h5 font-weight-bold mb-2">Input</h5><div class="v-md-editor-preview pa-2" style="tab-size: 2;"><div class="vuepress-markdown-body"><p data-v-md-line="1">Input contains two lines, and each line contains two numbers.</p>
<p data-v-md-line="3">The two numbers in the first line are the coordinate of the upper-left point <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mn>1</mn></msub><mtext>​</mtext><mo separator="true">,</mo><msub><mi>y</mi><mn>1</mn></msub><mtext>​</mtext><mo stretchy="false">)</mo></mrow><annotation encoding="application/x-tex">(x_1​,y_1​)</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord">​</span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord">​</span><span class="mclose">)</span></span></span></span><br>
The two numbers in the secend line are the coordinate of the bottom-right point <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mn>2</mn></msub><mtext>​</mtext><mo separator="true">,</mo><msub><mi>y</mi><mn>2</mn></msub><mtext>​</mtext><mo stretchy="false">)</mo></mrow><annotation encoding="application/x-tex">(x_2​,y_2​)</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord">​</span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord">​</span><span class="mclose">)</span></span></span></span></p>
<h3 data-v-md-heading="technical-specification" data-v-md-line="6">Technical Specification</h3>
<ul data-v-md-line="8">
<li>for <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mn>30</mn><mi mathvariant="normal">%</mi></mrow><annotation encoding="application/x-tex">30\%</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.8056em;vertical-align:-0.0556em;"></span><span class="mord">30%</span></span></span></span> of data, <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo>−</mo><mn>100</mn><mo>≤</mo><msub><mi>x</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>x</mi><mn>2</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>2</mn></msub><mo>≤</mo><mn>100</mn></mrow><annotation encoding="application/x-tex">-100 \le x_1, x_2, y_1, y_2 \le 100</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.7804em;vertical-align:-0.136em;"></span><span class="mord">−</span><span class="mord">100</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8304em;vertical-align:-0.1944em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.6444em;"></span><span class="mord">100</span></span></span></span>.</li>
<li>for <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mn>50</mn><mi mathvariant="normal">%</mi></mrow><annotation encoding="application/x-tex">50\%</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.8056em;vertical-align:-0.0556em;"></span><span class="mord">50%</span></span></span></span> of data, <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo>−</mo><mn>1000</mn><mo>≤</mo><msub><mi>x</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>x</mi><mn>2</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>2</mn></msub><mo>≤</mo><mn>1000</mn></mrow><annotation encoding="application/x-tex">-1000 \le x_1, x_2, y_1, y_2 \le 1000</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.7804em;vertical-align:-0.136em;"></span><span class="mord">−</span><span class="mord">1000</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8304em;vertical-align:-0.1944em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.6444em;"></span><span class="mord">1000</span></span></span></span>.</li>
<li>for <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mn>100</mn><mi mathvariant="normal">%</mi></mrow><annotation encoding="application/x-tex">100\%</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.8056em;vertical-align:-0.0556em;"></span><span class="mord">100%</span></span></span></span> of data, <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo>−</mo><msup><mn>2</mn><mn>31</mn></msup><mo>≤</mo><msub><mi>x</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>x</mi><mn>2</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>2</mn></msub><mo>≤</mo><msup><mn>2</mn><mn>31</mn></msup><mo>−</mo><mn>1</mn></mrow><annotation encoding="application/x-tex">-2^{31} \le x_1, x_2, y_1, y_2 \le 2^{31}-1</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.9501em;vertical-align:-0.136em;"></span><span class="mord">−</span><span class="mord"><span class="mord">2</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height:0.8141em;"><span style="top:-3.063em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">31</span></span></span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8304em;vertical-align:-0.1944em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8974em;vertical-align:-0.0833em;"></span><span class="mord"><span class="mord">2</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height:0.8141em;"><span style="top:-3.063em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">31</span></span></span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">−</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6444em;"></span><span class="mord">1</span></span></span></span>.</li>
</ul>
</div></div></div><div class="pa-4"><h5 class="text-h5 font-weight-bold mb-2">Output</h5><div class="v-md-editor-preview pa-2" style="tab-size: 2;"><div class="vuepress-markdown-body"><p data-v-md-line="1">The area of the rectangle.</p>
</div></div></div><div class="v-row pa-4"><div class="v-col-sm-6 v-col-12 d-flex flex-column"><h5 class="text-h5 font-weight-bold mb-2">Sample Input 1</h5><div class="position-relative flex-grow-1"><pre class="v-code pa-2 overflow-auto h-100">4 5
10 1</pre></div></div><div class="v-col-sm-6 v-col-12 d-flex flex-column"><h5 class="text-h5 font-weight-bold mb-2">Sample Output 1</h5><div class="position-relative flex-grow-1"><pre class="v-code pa-2 overflow-auto h-100">24</pre></div></div></div><!----><!----><!----><span class="v-card__underlay"></span></div>

**code**
```c=
#include <stdio.h>
#define ll long long
#define abs(x) ((x)>0?(x):(-x))
int main(void){
    ll x1, x2, y1, y2;
    scanf("%lld %lld %lld %lld", &x1, &y1, &x2, &y2);
    printf("%lld\n", abs(x1-x2)*abs(y1-y2));
    return 0;
}
```

---

## 2023/09/26
### hw02 Citizen ID Validator
[https://oj.ebg.tw/contest/115/problem/hw02](https://oj.ebg.tw/contest/115/problem/hw02)
```c=
#include <stdio.h>
int main(void){
    char s[11];
    // int list[] = {1, 0, 9, 8, 7, 6, 5, 4, 9, 3, 2, 2, 1, 0, 8, 9, 8, 7, 6, 5, 4, 3, 1, 3, 2, 0};
    int convert[] = {10, 11, 12, 13, 14, 15, 16, 17, 34, 18, 19, 20, 21, 22, 35, 23, 24, 25, 26, 27, 28, 29, 32, 30, 31, 33};
    int mu[] = {1,8,7,6,5,4,3,2,1,1};
    int T;
    scanf("%d", &T);
    while(T--){
        scanf("%s", s);
        int arr[10];
        // arr[0] = list[(int)(s[0]-'A')];
        arr[0] = convert[(int)(s[0]-'A')]/10 + (convert[(int)(s[0]-'A')]%10)*9;
        for(int i=1;i<10;i++)
            arr[i] = (int)(s[i])-(int)('0');
        if(arr[1]!=1 && arr[1]!=2){
            printf("Invalid\n");
            continue;
        }
        int sum = 0;
        for(int i=0;i<10;i++){
            sum += arr[i] * mu[i];
        }
        if(sum % 10 == 0)
            printf("Valid\n");
        else
            printf("Invalid\n");
    }
    return 0;
}
```
### ex02 Rectangle Area +
[https://oj.ebg.tw/contest/115/problem/ex02](https://oj.ebg.tw/contest/115/problem/ex02)
```c=
#include <stdio.h>
#define abs(x) ((x)>0?(x):(-(x)))
struct rec{
    double x[4];
    double y[4];
};
double getArea(struct rec R){
    //  |  | x0 x1 x2 x3 x0 |  |
    //  |  | y0 y1 y2 y3 y0 |  |  / 2
    return abs((R.x[0]*R.y[1] + R.x[1]*R.y[2] + R.x[2]*R.y[3] + R.x[3]*R.y[0])
              -(R.x[1]*R.y[0] + R.x[2]*R.y[1] + R.x[3]*R.y[2] + R.x[0]*R.y[3]))/2;
    // return sqrt(pow(R.x[1] - R.x[0],2) + pow(R.y[1] - R.y[0],2)) * sqrt(pow(R.x[2] - R.x[1],2) + pow(R.y[2] - R.y[1],2));
    // return = (R.x[0]-R.x[1])*(R.y[2]-R.y[1])-(R.y[0]-R.y[1])*(R.x[2]-R.x[1]);
}
void print_area(double area){
    if(area - (int)(area) == 0)
        printf("%d\n", (int)(area));
    else if(area*10 - (int)(area*10) == 0)
        printf("%.1lf\n", area);
    else
        printf("%.2lf\n", area);
}
int main(void){
    struct rec A, B;

    scanf("(%lf, %lf), (%lf, %lf), (%lf, %lf), (%lf, %lf)\n", &A.x[0], &A.y[0], &A.x[1], &A.y[1], &A.x[2], &A.y[2], &A.x[3], &A.y[3]);
    scanf("(%lf, %lf), (%lf, %lf), (%lf, %lf), (%lf, %lf)", &B.x[0], &B.y[0], &B.x[1], &B.y[1], &B.x[2], &B.y[2], &B.x[3], &B.y[3]);

    double A_area = getArea(A);
    double B_area = getArea(B);

    print_area(A_area);
    print_area(B_area);

    char c = ' ';
    if(A_area > B_area) c = '>';
    else if(A_area == B_area) c = '=';
    else if(A_area < B_area) c = '<';
    printf("A %c B\n", c);
    return 0;
}
```

---

## 2023/10/03
### hw03 Sudoku

---

[TOC]
