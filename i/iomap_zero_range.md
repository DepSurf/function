# Function: <code>iomap_zero_range</code>

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
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129c030)
Location: fs/iomap.c:317
Inline: False
Direct callers:
  - fs/iomap.c:iomap_truncate_page
```
**Symbols:**

```
ffffffff8129c030-ffffffff8129c0b2: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1bb0)
Location: fs/iomap.c:400
Inline: False
Direct callers:
  - fs/iomap.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff812b1bb0-ffffffff812b1c32: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812beee0)
Location: fs/iomap.c:396
Inline: False
Direct callers:
  - fs/iomap.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff812beee0-ffffffff812bef61: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e2950)
Location: fs/iomap.c:396
Inline: False
Direct callers:
  - fs/iomap.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff812e2950-ffffffff812e29d1: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f2f0)
Location: fs/iomap.c:403
Inline: False
Direct callers:
  - fs/iomap.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8130f2f0-ffffffff8130f371: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81326260)
Location: fs/iomap.c:1032
Inline: False
Direct callers:
  - fs/iomap.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81326260-ffffffff813262e1: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134afb0)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8134afb0-ffffffff8134b02a: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363250)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81363250-ffffffff813632ca: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa656)
Location: fs/iomap/buffered-io.c:984
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813a9e10-ffffffff813a9e8a: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bbe86)
Location: fs/iomap/buffered-io.c:953
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813bb460-ffffffff813bb4da: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3b76)
Location: fs/iomap/buffered-io.c:953
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813c2580-ffffffff813c25fa: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81414710)
Location: fs/iomap/buffered-io.c:930
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81414710-ffffffff81414918: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:928
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
```
**Symbols:**

```
ffffffff81e7a4a9-ffffffff81e7a513: iomap_zero_range.cold (STB_LOCAL)
ffffffff8148ba00-ffffffff8148bd53: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1189
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
```
**Symbols:**

```
ffffffff8206b52a-ffffffff8206b594: iomap_zero_range.cold (STB_LOCAL)
ffffffff8151fa60-ffffffff8151fcdf: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1209
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
```
**Symbols:**

```
ffffffff820eb496-ffffffff820eb500: iomap_zero_range.cold (STB_LOCAL)
ffffffff81557b10-ffffffff81557d8f: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1377
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
```
**Symbols:**

```
ffffffff821c86e0-ffffffff821c8747: iomap_zero_range.cold (STB_LOCAL)
ffffffff8158e130-ffffffff8158e3b1: iomap_zero_range (STB_GLOBAL)
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
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a128)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffff80001042a128-ffff80001042a1d0: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f2920)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
```
**Symbols:**

```
c05f2920-c05f29d8: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053a450)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
c00000000053a450-c00000000053a54c: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c7aee)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffe0002c7aee-ffffffe0002c7b60: iomap_zero_range (STB_GLOBAL)
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
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135b830)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8135b830-ffffffff8135b8aa: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c4d0)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8134c4d0-ffffffff8134c54a: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359300)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81359300-ffffffff8135937a: iomap_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136ca00)
Location: fs/iomap/buffered-io.c:979
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8136ca00-ffffffff8136ca7a: iomap_zero_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops *ops</code> ➡️ <code>const struct iomap_ops *ops</code>
</li>
</ul>
</details>
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
