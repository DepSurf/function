# Function: <code>zone_watermark_ok_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81192e00)
Location: mm/page_alloc.c:2428
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81192e00-ffffffff81192eb6: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811aa300)
Location: mm/page_alloc.c:2814
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811aa300-ffffffff811aa3bf: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ba830)
Location: mm/page_alloc.c:2865
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811ba830-ffffffff811ba8f4: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c2870)
Location: mm/page_alloc.c:3048
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811c2870-ffffffff811c2929: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d7680)
Location: mm/page_alloc.c:3116
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811d7680-ffffffff811d772c: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f89d0)
Location: mm/page_alloc.c:3220
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811f89d0-ffffffff811f8a7e: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120af50)
Location: mm/page_alloc.c:3333
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8120af50-ffffffff8120affe: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812711e0)
Location: mm/page_alloc.c:3498
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812711e0-ffffffff8127128d: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81280020)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81280020-ffffffff812800cd: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b2880)
Location: mm/page_alloc.c:3601
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_zones
```
**Symbols:**

```
ffffffff812b2880-ffffffff812b2924: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812be3f0)
Location: mm/page_alloc.c:3737
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_zones
```
**Symbols:**

```
ffffffff812be3f0-ffffffff812be494: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c3480)
Location: mm/page_alloc.c:3787
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812c3480-ffffffff812c352e: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813071f0)
Location: mm/page_alloc.c:3958
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff813071f0-ffffffff813072d4: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136f500)
Location: mm/page_alloc.c:3998
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
```
**Symbols:**

```
ffffffff8136f500-ffffffff8136f5f1: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ebaa0)
Location: mm/page_alloc.c:4083
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
```
**Symbols:**

```
ffffffff813ebaa0-ffffffff813ebb9a: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81420ab0)
Location: mm/page_alloc.c:3016
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
```
**Symbols:**

```
ffffffff81420ab0-ffffffff81420baa: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144d870)
Location: mm/page_alloc.c:3087
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
```
**Symbols:**

```
ffffffff8144d870-ffffffff8144d96a: zone_watermark_ok_safe (STB_GLOBAL)
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
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317e88)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffff800010317e88-ffff800010317f5c: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05323f8)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
c05323f8-c05324b8: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ea400)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
c0000000003ea400-c0000000003ea53c: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021dd4c)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffe00021dd4c-ffffffe00021de0c: zone_watermark_ok_safe (STB_GLOBAL)
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
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81278670)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81278670-ffffffff8127871d: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126a560)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8126a560-ffffffff8126a60d: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276410)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81276410-ffffffff812764bd: zone_watermark_ok_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool zone_watermark_ok_safe(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285fd0)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81285fd0-ffffffff8128607d: zone_watermark_ok_safe (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
</li>
</ul>
</details>
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
