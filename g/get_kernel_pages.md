# Function: <code>get_kernel_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119d640)
Location: mm/swap.c:379
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff8119d640-ffffffff8119d73f: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b1bc0)
Location: mm/swap.c:138
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff811b1bc0-ffffffff811b1cf6: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c2220)
Location: mm/swap.c:139
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff811c2220-ffffffff811c2340: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811ca0b0)
Location: mm/swap.c:149
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff811ca0b0-ffffffff811ca15a: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811def70)
Location: mm/swap.c:149
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff811def70-ffffffff811df01a: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81200630)
Location: mm/swap.c:150
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff81200630-ffffffff812006ce: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81212fa0)
Location: mm/swap.c:149
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff81212fa0-ffffffff8121303e: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:150
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff812255ca-ffffffff812255dd: get_kernel_pages.cold (STB_LOCAL)
ffffffff81222da0-ffffffff81222e3c: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81230550)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff81230550-ffffffff812305e2: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125de40)
Location: mm/swap.c:167
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff8125de40-ffffffff8125decb: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81268240)
Location: mm/swap.c:165
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff81268240-ffffffff812682cb: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126cab0)
Location: mm/swap.c:165
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff8126cab0-ffffffff8126cb3b: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812a97d0)
Location: mm/swap.c:165
Inline: False
```
**Symbols:**

```
ffffffff812a97d0-ffffffff812a985b: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81303140)
Location: mm/swap.c:174
Inline: False
```
**Symbols:**

```
ffffffff81303140-ffffffff81303216: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136e930)
Location: mm/swap.c:174
Inline: False
```
**Symbols:**

```
ffffffff8136e930-ffffffff8136ea06: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c0280)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffff8000102c0280-ffff8000102c034c: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ebff8)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
c04ebff8-c04ec0a4: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c000000000378f80)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
c000000000378f80-c000000000379060: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e1d12)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffe0001e1d12-ffffffe0001e1d9a: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228ba0)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff81228ba0-ffffffff81228c32: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121bce0)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff8121bce0-ffffffff8121bd72: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81226940)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff81226940-ffffffff812269d2: get_kernel_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_kernel_pages(const struct kvec *kiov, int nr_segs, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81235c70)
Location: mm/swap.c:151
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_page
```
**Symbols:**

```
ffffffff81235c70-ffffffff81235d02: get_kernel_pages (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
