# Function: <code>iomap_truncate_page</code>

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
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129c0c0)
Location: fs/iomap.c:337
Inline: False
```
**Symbols:**

```
ffffffff8129c0c0-ffffffff8129c0f7: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1c40)
Location: fs/iomap.c:420
Inline: False
```
**Symbols:**

```
ffffffff812b1c40-ffffffff812b1c77: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812bef70)
Location: fs/iomap.c:416
Inline: False
```
**Symbols:**

```
ffffffff812bef70-ffffffff812befa7: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e29e0)
Location: fs/iomap.c:416
Inline: False
```
**Symbols:**

```
ffffffff812e29e0-ffffffff812e2a17: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f380)
Location: fs/iomap.c:423
Inline: False
```
**Symbols:**

```
ffffffff8130f380-ffffffff8130f3b7: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813262f0)
Location: fs/iomap.c:1052
Inline: False
```
**Symbols:**

```
ffffffff813262f0-ffffffff81326328: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b030)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
ffffffff8134b030-ffffffff8134b063: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813632d0)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
ffffffff813632d0-ffffffff81363303: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa610)
Location: fs/iomap/buffered-io.c:1004
Inline: False
```
**Symbols:**

```
ffffffff813aa610-ffffffff813aa68c: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bbe40)
Location: fs/iomap/buffered-io.c:973
Inline: False
```
**Symbols:**

```
ffffffff813bbe40-ffffffff813bbebc: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3b30)
Location: fs/iomap/buffered-io.c:973
Inline: False
```
**Symbols:**

```
ffffffff813c3b30-ffffffff813c3bac: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:948
Inline: False
```
**Symbols:**

```
ffffffff81cc79bc-ffffffff81cc79e5: iomap_truncate_page.cold (STB_LOCAL)
ffffffff81414920-ffffffff8141497c: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:946
Inline: False
```
**Symbols:**

```
ffffffff81e7a513-ffffffff81e7a53d: iomap_truncate_page.cold (STB_LOCAL)
ffffffff8148bd60-ffffffff8148bdc8: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1207
Inline: False
```
**Symbols:**

```
ffffffff8206b594-ffffffff8206b5be: iomap_truncate_page.cold (STB_LOCAL)
ffffffff8151fcf0-ffffffff8151fd58: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1227
Inline: False
```
**Symbols:**

```
ffffffff820eb500-ffffffff820eb52a: iomap_truncate_page.cold (STB_LOCAL)
ffffffff81557da0-ffffffff81557e08: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1395
Inline: False
```
**Symbols:**

```
ffffffff821c8747-ffffffff821c8771: iomap_truncate_page.cold (STB_LOCAL)
ffffffff8158e3d0-ffffffff8158e438: iomap_truncate_page (STB_GLOBAL)
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
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a1d0)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
ffff80001042a1d0-ffff80001042a24c: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f29d8)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
c05f29d8-c05f2a34: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053a550)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
c00000000053a550-c00000000053a5a4: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c7b60)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
ffffffe0002c7b60-ffffffe0002c7bc4: iomap_truncate_page (STB_GLOBAL)
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
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135b8b0)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
ffffffff8135b8b0-ffffffff8135b8e3: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c550)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
ffffffff8134c550-ffffffff8134c583: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359380)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
ffffffff81359380-ffffffff813593b3: iomap_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136ca80)
Location: fs/iomap/buffered-io.c:999
Inline: False
```
**Symbols:**

```
ffffffff8136ca80-ffffffff8136cab3: iomap_truncate_page (STB_GLOBAL)
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
