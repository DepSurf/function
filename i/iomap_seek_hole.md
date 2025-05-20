# Function: <code>iomap_seek_hole</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812bf1e0)
Location: fs/iomap.c:607
Inline: False
```
**Symbols:**

```
ffffffff812bf1e0-ffffffff812bf27a: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e2ca0)
Location: fs/iomap.c:608
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812e2ca0-ffffffff812e2d3a: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f640)
Location: fs/iomap.c:723
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8130f640-ffffffff8130f6da: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813265c0)
Location: fs/iomap.c:1357
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813265c0-ffffffff8132665a: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8134e050)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8134e050-ffffffff8134e0e0: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff81366340)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81366340-ffffffff813663d0: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813adea0)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813adea0-ffffffff813adf30: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813bf510)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813bf510-ffffffff813bf5a0: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813c6650)
Location: fs/iomap/seek.c:35
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813c6650-ffffffff813c66de: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff81416860)
Location: fs/iomap/seek.c:34
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81416860-ffffffff814169c5: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8148de50)
Location: fs/iomap/seek.c:34
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8148de50-ffffffff8148dfc4: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff81521660)
Location: fs/iomap/seek.c:34
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81521660-ffffffff815217d4: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff815596a0)
Location: fs/iomap/seek.c:34
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff815596a0-ffffffff81559814: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8158fe30)
Location: fs/iomap/seek.c:34
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8158fe30-ffffffff8158ffa4: iomap_seek_hole (STB_GLOBAL)
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
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffff80001042dab8)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffff80001042dab8-ffff80001042db74: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (c05f7048)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
c05f7048-c05f71b8: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (c00000000053ecb0)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
c00000000053ecb0-c00000000053eda8: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffe0002ca55c)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffe0002ca55c-ffffffe0002ca5f2: iomap_seek_hole (STB_GLOBAL)
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
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8135e920)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8135e920-ffffffff8135e9b0: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8134f5c0)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8134f5c0-ffffffff8134f650: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8135c3f0)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8135c3f0-ffffffff8135c480: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t iomap_seek_hole(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8136fb40)
Location: fs/iomap/seek.c:140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8136fb40-ffffffff8136fbd0: iomap_seek_hole (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>loff_t pos</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
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
