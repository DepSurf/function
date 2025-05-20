# Function: <code>hugetlb_register_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811da740)
Location: mm/hugetlb.c:2576
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff81560845)
Location: drivers/base/node.c:227
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:register_one_node
```
**Symbols:**

```
ffffffff811da740-ffffffff811da827: hugetlb_register_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f8870)
Location: mm/hugetlb.c:2608
Inline: False
```
```
In drivers/base/node.c (ffffffff815b54e8)
Location: drivers/base/node.c:238
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff811f8870-ffffffff811f8951: hugetlb_register_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81209220)
Location: mm/hugetlb.c:2714
Inline: False
```
```
In drivers/base/node.c (ffffffff815e47d4)
Location: drivers/base/node.c:238
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81209220-ffffffff81209301: hugetlb_register_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81214a30)
Location: mm/hugetlb.c:2692
Inline: False
```
```
In drivers/base/node.c (ffffffff815f93b7)
Location: drivers/base/node.c:238
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81214a30-ffffffff81214b11: hugetlb_register_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122f5c0)
Location: mm/hugetlb.c:2700
Inline: False
```
```
In drivers/base/node.c (ffffffff81661498)
Location: drivers/base/node.c:255
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff8122f5c0-ffffffff8122f6a1: hugetlb_register_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2702
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff8169cbb9)
Location: drivers/base/node.c:255
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81251b10-ffffffff81251bd0: hugetlb_register_node (STB_LOCAL)
ffffffff81258890-ffffffff812588b7: hugetlb_register_node.cold.80 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2696
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff816bd3b5)
Location: drivers/base/node.c:260
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81265f10-ffffffff81265fd0: hugetlb_register_node (STB_LOCAL)
ffffffff8126cf64-ffffffff8126cf8b: hugetlb_register_node.cold.79 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2764
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff816f8128)
Location: drivers/base/node.c:558
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81280fa0-ffffffff81281061: hugetlb_register_node (STB_LOCAL)
ffffffff81288377-ffffffff8128839f: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2881
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff8171c528)
Location: drivers/base/node.c:564
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff812909b0-ffffffff81290a71: hugetlb_register_node (STB_LOCAL)
ffffffff81297f77-ffffffff81297f9f: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3164
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff817d86a2)
Location: drivers/base/node.c:567
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff812c3d70-ffffffff812c3e8a: hugetlb_register_node (STB_LOCAL)
ffffffff812cb6cf-ffffffff812cb6ff: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3120
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff817ed0e2)
Location: drivers/base/node.c:578
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff812cf2b0-ffffffff812cf371: hugetlb_register_node (STB_LOCAL)
ffffffff81be8a0b-ffffffff81be8a33: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3285
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff817d18b2)
Location: drivers/base/node.c:581
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff812d5f40-ffffffff812d6001: hugetlb_register_node (STB_LOCAL)
ffffffff81bdaa27-ffffffff81bdaa4f: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3570
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff8185c4fd)
Location: drivers/base/node.c:600
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff8131bf20-ffffffff8131c057: hugetlb_register_node (STB_LOCAL)
ffffffff81cbf1aa-ffffffff81cbf1d2: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3955
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff819a3676)
Location: drivers/base/node.c:603
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81387f90-ffffffff813880d9: hugetlb_register_node (STB_LOCAL)
ffffffff81e713f9-ffffffff81e71421: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4117
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - drivers/base/node.c:__register_one_node
```
**Symbols:**

```
ffffffff82066655-ffffffff8206666a: hugetlb_register_node.cold (STB_LOCAL)
ffffffff8140bd40-ffffffff8140bec2: hugetlb_register_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4147
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - drivers/base/node.c:__register_one_node
```
**Symbols:**

```
ffffffff820e5e6e-ffffffff820e5e83: hugetlb_register_node.cold (STB_LOCAL)
ffffffff8143f420-ffffffff8143f5a2: hugetlb_register_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4405
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - drivers/base/node.c:__register_one_node
```
**Symbols:**

```
ffffffff821c2f34-ffffffff821c2f49: hugetlb_register_node.cold (STB_LOCAL)
ffffffff81479040-ffffffff814791c2: hugetlb_register_node (STB_GLOBAL)
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
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032de98)
Location: mm/hugetlb.c:2881
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffff8000109101ac)
Location: drivers/base/node.c:564
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffff80001032de98-ffff80001032dfc0: hugetlb_register_node (STB_LOCAL)
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
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000406810)
Location: mm/hugetlb.c:2881
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (c0000000009b0dfc)
Location: drivers/base/node.c:564
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
c000000000406810-c0000000004069bc: hugetlb_register_node (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2881
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff816e2858)
Location: drivers/base/node.c:564
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81288f90-ffffffff81289051: hugetlb_register_node (STB_LOCAL)
ffffffff81290557-ffffffff8129057f: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2881
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff816bce98)
Location: drivers/base/node.c:564
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff8127ae30-ffffffff8127aef1: hugetlb_register_node (STB_LOCAL)
ffffffff812821e7-ffffffff8128220f: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2881
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff8170fa58)
Location: drivers/base/node.c:564
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81286da0-ffffffff81286e61: hugetlb_register_node (STB_LOCAL)
ffffffff8128e367-ffffffff8128e38f: hugetlb_register_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void hugetlb_register_node(struct node *node);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2881
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In drivers/base/node.c (ffffffff8172ab48)
Location: drivers/base/node.c:564
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:node_hugetlb_work
```
**Symbols:**

```
ffffffff81297270-ffffffff81297331: hugetlb_register_node (STB_LOCAL)
ffffffff8129e0f8-ffffffff8129e120: hugetlb_register_node.cold (STB_LOCAL)
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
