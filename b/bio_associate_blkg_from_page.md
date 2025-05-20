# Function: <code>bio_associate_blkg_from_page</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81499e60)
Location: block/bio.c:2051
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff81499e60-ffffffff81499e94: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7f00)
Location: block/bio.c:2085
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff814c7f00-ffffffff814c7f38: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e1000)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff814e1000-ffffffff814e1038: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153fb50)
Location: block/bio.c:1706
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8153fb50-ffffffff8153fbc2: bio_associate_blkg_from_page (STB_GLOBAL)
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
In mm/page_io.c (ffffffff812c38c8)
Location: mm/page_io.c:286
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
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
In mm/page_io.c (ffffffff812ca679)
Location: mm/page_io.c:267
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
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
In mm/page_io.c (ffffffff8130f676)
Location: mm/page_io.c:267
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
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
In mm/page_io.c (ffffffff81379ab0)
Location: mm/page_io.c:220
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
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
In mm/page_io.c (ffffffff813f788a)
Location: mm/page_io.c:221
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81429c40)
Location: mm/page_io.c:221
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
```
**Symbols:**

```
ffffffff81429c40-ffffffff81429cce: bio_associate_blkg_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_io.c (ffffffff81463090)
Location: mm/page_io.c:225
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
```
**Symbols:**

```
ffffffff81463090-ffffffff814630e9: bio_associate_blkg_from_page.isra.0 (STB_LOCAL)
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
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105ddc58)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffff8000105ddc58-ffff8000105ddca8: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078afa4)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
c078afa4-c078afec: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076f5a0)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
c00000000076f5a0-c00000000076f608: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe000420bb8)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffe000420bb8-ffffffe000420c02: bio_associate_blkg_from_page (STB_GLOBAL)
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
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d95e0)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff814d95e0-ffffffff814d9618: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c9f90)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff814c9f90-ffffffff814c9fc8: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d5670)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff814d5670-ffffffff814d56a8: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio *bio, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ee280)
Location: block/bio.c:2127
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff814ee280-ffffffff814ee2c7: bio_associate_blkg_from_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
