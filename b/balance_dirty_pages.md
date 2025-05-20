# Function: <code>balance_dirty_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff81199580)
Location: mm/page-writeback.c:1519
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff81199580-ffffffff8119a413: balance_dirty_pages.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff811adee0)
Location: mm/page-writeback.c:1562
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff811adee0-ffffffff811aed21: balance_dirty_pages.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff811be590)
Location: mm/page-writeback.c:1562
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff811be590-ffffffff811bf3db: balance_dirty_pages.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff811c6460)
Location: mm/page-writeback.c:1562
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff811c6460-ffffffff811c71e1: balance_dirty_pages.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811db280)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff811db280-ffffffff811dbff1: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fcb70)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff811fcb70-ffffffff811fd8f0: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8120f690)
Location: mm/page-writeback.c:1560
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff8120f690-ffffffff8121040d: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121ed20)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff8121ed20-ffffffff8121faaa: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122c7c0)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff8122c7c0-ffffffff8122d552: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8125a260)
Location: mm/page-writeback.c:1555
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff8125a260-ffffffff8125b080: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81264380)
Location: mm/page-writeback.c:1555
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff81264380-ffffffff812651aa: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81268590)
Location: mm/page-writeback.c:1555
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff81268590-ffffffff812693c0: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (0)
Location: mm/page-writeback.c:1560
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff812a5000-ffffffff812a5e33: balance_dirty_pages (STB_LOCAL)
ffffffff81cba524-ffffffff81cba56e: balance_dirty_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (0)
Location: mm/page-writeback.c:1557
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff812fdc90-ffffffff812feb07: balance_dirty_pages (STB_LOCAL)
ffffffff81e6bc32-ffffffff81e6bc98: balance_dirty_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (0)
Location: mm/page-writeback.c:1669
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
**Symbols:**

```
ffffffff81368430-ffffffff8136926b: balance_dirty_pages (STB_LOCAL)
ffffffff8206245d-ffffffff820624a7: balance_dirty_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (0)
Location: mm/page-writeback.c:1669
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
**Symbols:**

```
ffffffff8139a5d0-ffffffff8139b40b: balance_dirty_pages (STB_LOCAL)
ffffffff820e1c38-ffffffff820e1c82: balance_dirty_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (0)
Location: mm/page-writeback.c:1669
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
**Symbols:**

```
ffffffff813c4500-ffffffff813c5373: balance_dirty_pages (STB_LOCAL)
ffffffff821be65d-ffffffff821be6a7: balance_dirty_pages.cold (STB_LOCAL)
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
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bb2a8)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffff8000102bb2a8-ffff8000102bbde0: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e7d10)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
c04e7d10-c04e89fc: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000373a90)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
c000000000373a90-c0000000003747a8: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001de512)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffe0001de512-ffffffe0001df0e2: balance_dirty_pages (STB_LOCAL)
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
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81224e10)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff81224e10-ffffffff81225ba2: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81217fb0)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff81217fb0-ffffffff81218d42: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81222bb0)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff81222bb0-ffffffff81223942: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void balance_dirty_pages(struct bdi_writeback *wb, long unsigned int pages_dirtied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81231d90)
Location: mm/page-writeback.c:1561
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
**Symbols:**

```
ffffffff81231d90-ffffffff81232b4f: balance_dirty_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
