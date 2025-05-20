# Function: <code>iomap_write_begin</code>

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
int iomap_write_begin(struct inode *inode, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129bd60)
Location: fs/iomap.c:110
Inline: False
Direct callers:
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8129bd60-ffffffff8129be6c: iomap_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iomap_write_begin(struct inode *inode, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b0920)
Location: fs/iomap.c:108
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff812b0920-ffffffff812b0a4c: iomap_write_begin (STB_LOCAL)
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
In fs/iomap.c (ffffffff812be5b0)
Location: fs/iomap.c:110
Inline: True
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff812be5b0-ffffffff812be6b2: iomap_write_begin.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap.c (ffffffff812e1f50)
Location: fs/iomap.c:110
Inline: True
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff812e1f50-ffffffff812e2090: iomap_write_begin.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap.c (ffffffff8130ea00)
Location: fs/iomap.c:120
Inline: True
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8130ea00-ffffffff8130eb53: iomap_write_begin.constprop.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap.c (ffffffff81325310)
Location: fs/iomap.c:664
Inline: True
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff81325310-ffffffff813255ae: iomap_write_begin.constprop.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134bfc0)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8134bfc0-ffffffff8134c342: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81364290)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff81364290-ffffffff81364612: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_write_begin(struct inode *inode, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813abcd0)
Location: fs/iomap/buffered-io.c:611
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff813abcd0-ffffffff813abf3b: iomap_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_write_begin(struct inode *inode, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bd1a0)
Location: fs/iomap/buffered-io.c:591
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff813bd1a0-ffffffff813bd408: iomap_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_write_begin(struct inode *inode, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c42f0)
Location: fs/iomap/buffered-io.c:591
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff813c42f0-ffffffff813c4558: iomap_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_write_begin(const struct iomap_iter *iter, loff_t pos, unsigned int len, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81413910)
Location: fs/iomap/buffered-io.c:601
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
```
**Symbols:**

```
ffffffff81413910-ffffffff81413ba8: iomap_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomap_write_begin(const struct iomap_iter *iter, loff_t pos, size_t len, struct folio **foliop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:597
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff8148b110-ffffffff8148b4ce: iomap_write_begin (STB_LOCAL)
ffffffff81e7a447-ffffffff81e7a4a9: iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iomap_write_begin(struct iomap_iter *iter, loff_t pos, size_t len, struct folio **foliop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:587
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff8151f130-ffffffff8151f4cf: iomap_write_begin (STB_LOCAL)
ffffffff8206b4ca-ffffffff8206b52a: iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iomap_write_begin(struct iomap_iter *iter, loff_t pos, size_t len, struct folio **foliop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:626
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff81557270-ffffffff81557589: iomap_write_begin (STB_LOCAL)
ffffffff820eb450-ffffffff820eb496: iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_write_begin(struct iomap_iter *iter, loff_t pos, size_t len, struct folio **foliop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:729
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff8158d7a0-ffffffff8158daae: iomap_write_begin (STB_LOCAL)
ffffffff821c8596-ffffffff821c85e2: iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042b590)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffff80001042b590-ffff80001042b8d4: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (c05f4000)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
c05f4000-c05f4424: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053c640)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
c00000000053c640-c00000000053cab4: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8e9e)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffe0002c8e9e-ffffffe0002c9120: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135c870)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8135c870-ffffffff8135cbf2: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134d510)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8134d510-ffffffff8134d892: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135a340)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8135a340-ffffffff8135a6c2: iomap_write_begin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136da90)
Location: fs/iomap/buffered-io.c:583
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8136da90-ffffffff8136de12: iomap_write_begin.constprop.0 (STB_LOCAL)
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
<b>Param added. </b>
<code>const struct iomap_iter *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap *iomap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap *srcmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, pos, len, flags, pagep, iomap, srcmap</code> ➡️ <code>iter, pos, len, pagep</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio **foliop</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page **pagep</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>size_t len</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct iomap_iter *iter</code> ➡️ <code>struct iomap_iter *iter</code>
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
