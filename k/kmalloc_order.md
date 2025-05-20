# Function: <code>kmalloc_order</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b2750)
Location: mm/slab_common.c:1001
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff811b2750-ffffffff811b2795: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cc225)
Location: mm/slab_common.c:1009
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff811cc1d0-ffffffff811cc20f: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dc2d0)
Location: mm/slab_common.c:1038
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff811dc2d0-ffffffff811dc309: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e61f0)
Location: mm/slab_common.c:1107
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff811e61f0-ffffffff811e6229: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fc430)
Location: mm/slab_common.c:1116
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff811fc430-ffffffff811fc469: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121d590)
Location: mm/slab_common.c:1177
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff8121d590-ffffffff8121d5c9: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81230580)
Location: mm/slab_common.c:1223
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff81230580-ffffffff812305b5: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812405a0)
Location: mm/slab_common.c:1251
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff812405a0-ffffffff812405d5: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124eb10)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff8124eb10-ffffffff8124eb88: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127cdd0)
Location: mm/slab_common.c:1319
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff8127cdd0-ffffffff8127ce48: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:828
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff81be7375-ffffffff81be7381: kmalloc_order.cold (STB_LOCAL)
ffffffff81288c60-ffffffff81288cf5: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:914
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff81bd923b-ffffffff81bd9247: kmalloc_order.cold (STB_LOCAL)
ffffffff8128e310-ffffffff8128e3b1: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:948
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff81cbb4a7-ffffffff81cbb4cc: kmalloc_order.cold (STB_LOCAL)
ffffffff812ce230-ffffffff812ce2e6: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:936
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff81e6d04c-ffffffff81e6d079: kmalloc_order.cold (STB_LOCAL)
ffffffff8132c2f0-ffffffff8132c38c: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e4dd0)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffff8000102e4dd0-ffff8000102e4e60: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0509ca8)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
c0509ca8-c0509d04: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a6980)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
c0000000003a6980-c0000000003a6a50: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fb93a)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffe0001fb93a-ffffffe0001fb9a8: kmalloc_order (STB_GLOBAL)
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
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81247160)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff81247160-ffffffff812471d8: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123a110)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff8123a110-ffffffff8123a188: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81244f00)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff81244f00-ffffffff81244f78: kmalloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *kmalloc_order(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812548f0)
Location: mm/slab_common.c:1311
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order_trace
```
**Symbols:**

```
ffffffff812548f0-ffffffff81254968: kmalloc_order (STB_GLOBAL)
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
