# Function: <code>hugetlb_unregister_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811da310)
Location: mm/hugetlb.c:2532
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_exit
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff81560871)
Location: drivers/base/node.c:237
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_one_node
```
**Symbols:**

```
ffffffff811da310-ffffffff811da3f2: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f8780)
Location: mm/hugetlb.c:2583
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff815b554c)
Location: drivers/base/node.c:248
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff811f8780-ffffffff811f886d: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81209130)
Location: mm/hugetlb.c:2689
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff815e482c)
Location: drivers/base/node.c:248
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81209130-ffffffff8120921d: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81214950)
Location: mm/hugetlb.c:2667
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff815f940c)
Location: drivers/base/node.c:248
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81214950-ffffffff81214a2d: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122f4e0)
Location: mm/hugetlb.c:2675
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff816614fc)
Location: drivers/base/node.c:265
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff8122f4e0-ffffffff8122f5bd: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81251a20)
Location: mm/hugetlb.c:2677
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff8169ccbc)
Location: drivers/base/node.c:265
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81251a20-ffffffff81251b0d: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81265e20)
Location: mm/hugetlb.c:2671
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff816bd46c)
Location: drivers/base/node.c:270
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81265e20-ffffffff81265f0d: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81280eb0)
Location: mm/hugetlb.c:2739
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff816f79c8)
Location: drivers/base/node.c:568
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff81280eb0-ffffffff81280f92: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812908c0)
Location: mm/hugetlb.c:2856
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff8171be28)
Location: drivers/base/node.c:574
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff812908c0-ffffffff812909a2: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c33f0)
Location: mm/hugetlb.c:3139
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff817d7fc8)
Location: drivers/base/node.c:577
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff812c33f0-ffffffff812c34d5: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cf1c0)
Location: mm/hugetlb.c:3095
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff817ec948)
Location: drivers/base/node.c:588
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff812cf1c0-ffffffff812cf2a5: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d5e50)
Location: mm/hugetlb.c:3260
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff817d1168)
Location: drivers/base/node.c:591
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff812d5e50-ffffffff812d5f35: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131bde0)
Location: mm/hugetlb.c:3545
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff8185bbf8)
Location: drivers/base/node.c:610
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff8131bde0-ffffffff8131bf1d: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81387e40)
Location: mm/hugetlb.c:3930
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff819a2c88)
Location: drivers/base/node.c:613
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff81387e40-ffffffff81387f87: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140bba0)
Location: mm/hugetlb.c:4087
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff8140bba0-ffffffff8140bd2e: hugetlb_unregister_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143f240)
Location: mm/hugetlb.c:4117
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff8143f240-ffffffff8143f403: hugetlb_unregister_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81478e60)
Location: mm/hugetlb.c:4375
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff81478e60-ffffffff81479023: hugetlb_unregister_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032ddb8)
Location: mm/hugetlb.c:2856
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffff80001090ea34)
Location: drivers/base/node.c:574
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffff80001032ddb8-ffff80001032de98: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c0000000004066c0)
Location: mm/hugetlb.c:2856
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (c0000000009af6ec)
Location: drivers/base/node.c:574
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
c0000000004066c0-c000000000406804: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288ea0)
Location: mm/hugetlb.c:2856
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff816e2158)
Location: drivers/base/node.c:574
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff81288ea0-ffffffff81288f82: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127ad40)
Location: mm/hugetlb.c:2856
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff816bc798)
Location: drivers/base/node.c:574
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff8127ad40-ffffffff8127ae22: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81286cb0)
Location: mm/hugetlb.c:2856
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff8170f688)
Location: drivers/base/node.c:574
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff81286cb0-ffffffff81286d92: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_unregister_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297180)
Location: mm/hugetlb.c:2856
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_register_node
```
```
In drivers/base/node.c (ffffffff8172a448)
Location: drivers/base/node.c:574
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_node
```
**Symbols:**

```
ffffffff81297180-ffffffff81297262: hugetlb_unregister_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
