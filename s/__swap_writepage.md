# Function: <code>__swap_writepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff811d2250)
Location: mm/page_io.c:252
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff811d2250-ffffffff811d24b8: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff811efdc0)
Location: mm/page_io.c:260
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff811efdc0-ffffffff811f009a: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81200760)
Location: mm/page_io.c:260
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81200760-ffffffff81200a68: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8120b3a0)
Location: mm/page_io.c:265
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8120b3a0-ffffffff8120b6e5: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81224860)
Location: mm/page_io.c:278
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81224860-ffffffff81224c0d: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81246df0)
Location: mm/page_io.c:278
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81246df0-ffffffff812471a8: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8125b210)
Location: mm/page_io.c:278
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8125b210-ffffffff8125b600: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81276a51-ffffffff81276a5b: __swap_writepage.cold (STB_LOCAL)
ffffffff81276350-ffffffff8127676a: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81286541-ffffffff8128654b: __swap_writepage.cold (STB_LOCAL)
ffffffff81285e40-ffffffff8128625a: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812b8160)
Location: mm/page_io.c:280
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff812b8160-ffffffff812b851a: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812c3810)
Location: mm/page_io.c:304
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff812c3810-ffffffff812c3be7: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812ca550)
Location: mm/page_io.c:285
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff812ca550-ffffffff812ca97f: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8130f550)
Location: mm/page_io.c:285
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8130f550-ffffffff8130f982: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:335
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81e709ef-ffffffff81e70a56: __swap_writepage.cold (STB_LOCAL)
ffffffff813799c0-ffffffff81379f30: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:336
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff820659e6-ffffffff82065a00: __swap_writepage.cold (STB_LOCAL)
ffffffff813f77a0-ffffffff813f79be: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __swap_writepage(struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:372
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff820e51e9-ffffffff820e5204: __swap_writepage.cold (STB_LOCAL)
ffffffff8142a9c0-ffffffff8142ab56: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __swap_writepage(struct folio *folio, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:374
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff821c2392-ffffffff821c23aa: __swap_writepage.cold (STB_LOCAL)
ffffffff81464140-ffffffff814642d8: __swap_writepage (STB_GLOBAL)
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
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffff8000103203e8)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffff8000103203e8-ffff800010320820: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0538e9c)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
c0538e9c-c053923c: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0000000003f5520)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
c0000000003f5520-c0000000003f5ab0: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffe000221b50)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffe000221b50-ffffffe000221eaa: __swap_writepage (STB_GLOBAL)
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
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8127eb91-ffffffff8127eb9b: __swap_writepage.cold (STB_LOCAL)
ffffffff8127e490-ffffffff8127e8aa: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff812709c1-ffffffff812709cb: __swap_writepage.cold (STB_LOCAL)
ffffffff812702c0-ffffffff812706da: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8127c931-ffffffff8127c93b: __swap_writepage.cold (STB_LOCAL)
ffffffff8127c230-ffffffff8127c64a: __swap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __swap_writepage(struct page *page, struct writeback_control *wbc, bio_end_io_t *end_write_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:277
Inline: False
Direct callers:
  - mm/page_io.c:swap_writepage
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8128c501-ffffffff8128c50b: __swap_writepage.cold (STB_LOCAL)
ffffffff8128be00-ffffffff8128c21a: __swap_writepage (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bio_end_io_t *end_write_func</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
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
