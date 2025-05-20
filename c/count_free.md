# Function: <code>count_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e70a0)
Location: mm/slub.c:2192
Inline: False
```
**Symbols:**

```
ffffffff811e70a0-ffffffff811e70ba: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81206170)
Location: mm/slub.c:2321
Inline: False
```
**Symbols:**

```
ffffffff81206170-ffffffff8120618a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81218190)
Location: mm/slub.c:2343
Inline: False
```
**Symbols:**

```
ffffffff81218190-ffffffff812181aa: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81223d10)
Location: mm/slub.c:2347
Inline: False
```
**Symbols:**

```
ffffffff81223d10-ffffffff81223d2a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123f360)
Location: mm/slub.c:2360
Inline: False
```
**Symbols:**

```
ffffffff8123f360-ffffffff8123f37a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81262c00)
Location: mm/slub.c:2341
Inline: False
```
**Symbols:**

```
ffffffff81262c00-ffffffff81262c1a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81277480)
Location: mm/slub.c:2391
Inline: False
```
**Symbols:**

```
ffffffff81277480-ffffffff8127749a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81292dc0)
Location: mm/slub.c:2398
Inline: False
```
**Symbols:**

```
ffffffff81292dc0-ffffffff81292dda: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2b40)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
ffffffff812a2b40-ffffffff812a2b5a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df4d8)
Location: mm/slub.c:2435
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
```
**Symbols:**

```
ffffffff812d72e0-ffffffff812d72fa: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eb148)
Location: mm/slub.c:2500
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
```
**Symbols:**

```
ffffffff812e2e00-ffffffff812e2e1a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f2c18)
Location: mm/slub.c:2517
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
```
**Symbols:**

```
ffffffff812ea580-ffffffff812ea59a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133b948)
Location: mm/slub.c:2740
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
```
**Symbols:**

```
ffffffff81332470-ffffffff8133248a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int count_free(struct slab *slab);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ae078)
Location: mm/slub.c:2782
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
```
**Symbols:**

```
ffffffff813a38c0-ffffffff813a38e2: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142e474)
Location: mm/slub.c:2878
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
  - mm/slub.c:slab_out_of_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81463bc0)
Location: mm/slub.c:2888
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
  - mm/slub.c:slab_out_of_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145fe10)
Location: mm/slub.c:3162
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
  - mm/slub.c:slab_out_of_memory
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010342c40)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
ffff800010342c40-ffff800010342c74: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c05482f0)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
c05482f0-c0548318: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000420150)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
c000000000420150-c000000000420170: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000236884)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
ffffffe000236884-ffffffe0002368b2: count_free (STB_LOCAL)
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
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b120)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
ffffffff8129b120-ffffffff8129b13a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128cce0)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
ffffffff8128cce0-ffffffff8128ccfa: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81298f30)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
ffffffff81298f30-ffffffff81298f4a: count_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int count_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a8d50)
Location: mm/slub.c:2377
Inline: False
```
**Symbols:**

```
ffffffff812a8d50-ffffffff812a8d6a: count_free (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct slab *slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
