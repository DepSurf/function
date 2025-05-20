# Function: <code>iomap_file_dirty</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1b30)
Location: fs/iomap.c:320
Inline: False
```
**Symbols:**

```
ffffffff812b1b30-ffffffff812b1bad: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812bee60)
Location: fs/iomap.c:315
Inline: False
```
**Symbols:**

```
ffffffff812bee60-ffffffff812beed8: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e28d0)
Location: fs/iomap.c:315
Inline: False
```
**Symbols:**

```
ffffffff812e28d0-ffffffff812e2948: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f270)
Location: fs/iomap.c:325
Inline: False
```
**Symbols:**

```
ffffffff8130f270-ffffffff8130f2e8: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813261e0)
Location: fs/iomap.c:954
Inline: False
```
**Symbols:**

```
ffffffff813261e0-ffffffff81326258: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134af40)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
ffffffff8134af40-ffffffff8134afae: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813631e0)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
ffffffff813631e0-ffffffff8136324e: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a088)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
ffff80001042a088-ffff80001042a124: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f286c)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
c05f286c-c05f2920: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053a360)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
c00000000053a360-c00000000053a448: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c7a86)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
ffffffe0002c7a86-ffffffe0002c7aee: iomap_file_dirty (STB_GLOBAL)
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
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135b7c0)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
ffffffff8135b7c0-ffffffff8135b82e: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c460)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
ffffffff8134c460-ffffffff8134c4ce: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359290)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
ffffffff81359290-ffffffff813592fe: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_file_dirty(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136c990)
Location: fs/iomap/buffered-io.c:901
Inline: False
```
**Symbols:**

```
ffffffff8136c990-ffffffff8136c9fe: iomap_file_dirty (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
