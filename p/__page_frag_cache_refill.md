# Function: <code>__page_frag_cache_refill</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bb9ae)
Location: mm/page_alloc.c:3925
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c3c86)
Location: mm/page_alloc.c:4212
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d8a26)
Location: mm/page_alloc.c:4331
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f9bb6)
Location: mm/page_alloc.c:4463
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120c256)
Location: mm/page_alloc.c:4640
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812724b9)
Location: mm/page_alloc.c:4807
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281319)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b37e9)
Location: mm/page_alloc.c:4928
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bf2ca)
Location: mm/page_alloc.c:5102
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c4371)
Location: mm/page_alloc.c:5303
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8130822d)
Location: mm/page_alloc.c:5484
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8137052f)
Location: mm/page_alloc.c:5539
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
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
In mm/page_alloc.c (ffffffff813ed49e)
Location: mm/page_alloc.c:5666
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *__page_frag_cache_refill(struct page_frag_cache *nc, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81422290)
Location: mm/page_alloc.c:4594
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
**Symbols:**

```
ffffffff81422290-ffffffff814223e5: __page_frag_cache_refill (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff8144f17f)
Location: mm/page_alloc.c:4683
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010318fd4)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0533abc)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003eba10)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ee2a)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81279969)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126b859)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277709)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812872f9)
Location: mm/page_alloc.c:4825
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
