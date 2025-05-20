# Function: <code>__dump_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff811d4470)
Location: mm/debug.c:43
Inline: False
Direct callers:
  - mm/page_alloc.c:bad_page
  - mm/debug.c:dump_page
```
**Symbols:**

```
ffffffff811d4470-ffffffff811d45f4: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff811e44c0)
Location: mm/debug.c:43
Inline: False
Direct callers:
  - mm/page_alloc.c:bad_page
  - mm/debug.c:dump_page
```
**Symbols:**

```
ffffffff811e44c0-ffffffff811e4683: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff811ee920)
Location: mm/debug.c:43
Inline: False
Direct callers:
  - mm/page_alloc.c:bad_page
  - mm/debug.c:dump_page
```
**Symbols:**

```
ffffffff811ee920-ffffffff811eeae4: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81204d90)
Location: mm/debug.c:44
Inline: False
Direct callers:
  - mm/page_alloc.c:bad_page
  - mm/debug.c:dump_page
```
**Symbols:**

```
ffffffff81204d90-ffffffff81204f54: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:44
Inline: False
Direct callers:
  - mm/page_alloc.c:bad_page
  - mm/debug.c:dump_page
```
**Symbols:**

```
ffffffff81225cc0-ffffffff81225e56: __dump_page.cold.3 (STB_LOCAL)
ffffffff81225c30-ffffffff81225ca4: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/page_alloc.c:bad_page
  - mm/debug.c:dump_page
```
**Symbols:**

```
ffffffff81239380-ffffffff812395c7: __dump_page.cold.3 (STB_LOCAL)
ffffffff812392f0-ffffffff81239370: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff8124a3e0-ffffffff8124a627: __dump_page.cold (STB_LOCAL)
ffffffff8124a350-ffffffff8124a3d0: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff81258860-ffffffff81258ae0: __dump_page.cold (STB_LOCAL)
ffffffff81258790-ffffffff8125884c: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff81287340-ffffffff812875cc: __dump_page.cold (STB_LOCAL)
ffffffff81287010-ffffffff8128732b: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff81be7462-ffffffff81be787e: __dump_page.cold (STB_LOCAL)
ffffffff812912c0-ffffffff812913f5: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff81bd9328-ffffffff81bd96d8: __dump_page.cold (STB_LOCAL)
ffffffff812967f0-ffffffff81296945: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:47
Inline: False
Direct callers:
  - mm/debug.c:dump_page
```
**Symbols:**

```
ffffffff812d7040-ffffffff812d71ae: __dump_page (STB_LOCAL)
ffffffff81cbbd55-ffffffff81cbc0c5: __dump_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:49
Inline: False
```
**Symbols:**

```
ffffffff813368c0-ffffffff81336b0d: __dump_page (STB_LOCAL)
ffffffff81e6d9ee-ffffffff81e6dc3d: __dump_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dump_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff813adb50)
Location: mm/debug.c:49
Inline: False
```
**Symbols:**

```
ffffffff813adb50-ffffffff813ae023: __dump_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dump_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff813e1ee0)
Location: mm/debug.c:54
Inline: False
```
**Symbols:**

```
ffffffff813e1ee0-ffffffff813e2380: __dump_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __dump_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8140c710)
Location: mm/debug.c:54
Inline: False
```
**Symbols:**

```
ffffffff8140c710-ffffffff8140cb74: __dump_page (STB_LOCAL)
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
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffff8000102f0750)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffff8000102f0750-ffff8000102f0ab0: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (c0513cac)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
c0513cac-c0513f38: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (c0000000003b50b0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
c0000000003b50b0-c0000000003b552c: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffe000203f70)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffe000203f70-ffffffe000204202: __dump_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff81250eb0-ffffffff81251130: __dump_page.cold (STB_LOCAL)
ffffffff81250de0-ffffffff81250e9c: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff81243df0-ffffffff81244070: __dump_page.cold (STB_LOCAL)
ffffffff81243d20-ffffffff81243ddc: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff8124ec50-ffffffff8124eed0: __dump_page.cold (STB_LOCAL)
ffffffff8124eb80-ffffffff8124ec3c: __dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:45
Inline: False
Direct callers:
  - mm/debug.c:dump_page
  - mm/page_alloc.c:bad_page
```
**Symbols:**

```
ffffffff8125e5d0-ffffffff8125e850: __dump_page.cold (STB_LOCAL)
ffffffff8125e500-ffffffff8125e5bc: __dump_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const char *reason</code>
</li>
</ul>
</details>
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
