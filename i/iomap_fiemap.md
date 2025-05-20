# Function: <code>iomap_fiemap</code>

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
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129c2c0)
Location: fs/iomap.c:462
Inline: False
```
**Symbols:**

```
ffffffff8129c2c0-ffffffff8129c3db: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1d80)
Location: fs/iomap.c:547
Inline: False
```
**Symbols:**

```
ffffffff812b1d80-ffffffff812b1e9e: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812bf0b0)
Location: fs/iomap.c:542
Inline: False
```
**Symbols:**

```
ffffffff812bf0b0-ffffffff812bf1d3: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e2b70)
Location: fs/iomap.c:543
Inline: False
```
**Symbols:**

```
ffffffff812e2b70-ffffffff812e2c93: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f510)
Location: fs/iomap.c:551
Inline: False
```
**Symbols:**

```
ffffffff8130f510-ffffffff8130f639: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81326480)
Location: fs/iomap.c:1185
Inline: False
```
**Symbols:**

```
ffffffff81326480-ffffffff813265bf: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8134de50)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
ffffffff8134de50-ffffffff8134df5e: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff81366140)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
ffffffff81366140-ffffffff8136624e: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, u64 start, u64 len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff813adc10)
Location: fs/iomap/fiemap.c:68
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff813adc10-ffffffff813add14: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, u64 start, u64 len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff813bf280)
Location: fs/iomap/fiemap.c:68
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff813bf280-ffffffff813bf384: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, u64 start, u64 len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff813c63c0)
Location: fs/iomap/fiemap.c:68
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff813c63c0-ffffffff813c64c2: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, u64 start, u64 len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff81416360)
Location: fs/iomap/fiemap.c:61
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff81416360-ffffffff81416560: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, u64 start, u64 len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8148dc30)
Location: fs/iomap/fiemap.c:62
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff8148dc30-ffffffff8148de48: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, u64 start, u64 len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff81521420)
Location: fs/iomap/fiemap.c:62
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff81521420-ffffffff81521646: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, u64 start, u64 len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff81559460)
Location: fs/iomap/fiemap.c:62
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff81559460-ffffffff81559686: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, u64 start, u64 len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8158fbf0)
Location: fs/iomap/fiemap.c:62
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff8158fbf0-ffffffff8158fe16: iomap_fiemap (STB_GLOBAL)
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
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffff80001042d838)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
ffff80001042d838-ffff80001042d980: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (c05f6768)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
c05f6768-c05f68dc: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (c00000000053e980)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
c00000000053e980-c00000000053eb24: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffe0002ca34c)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
ffffffe0002ca34c-ffffffe0002ca44e: iomap_fiemap (STB_GLOBAL)
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
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8135e720)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
ffffffff8135e720-ffffffff8135e82e: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8134f3c0)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
ffffffff8134f3c0-ffffffff8134f4ce: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8135c1f0)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
ffffffff8135c1f0-ffffffff8135c2fe: iomap_fiemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_fiemap(struct inode *inode, struct fiemap_extent_info *fi, loff_t start, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8136f940)
Location: fs/iomap/fiemap.c:67
Inline: False
```
**Symbols:**

```
ffffffff8136f940-ffffffff8136fa4e: iomap_fiemap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>loff_t start</code> ➡️ <code>u64 start</code>
</li>
<li>
<b>Param type changed. </b>
<code>loff_t len</code> ➡️ <code>u64 len</code>
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
