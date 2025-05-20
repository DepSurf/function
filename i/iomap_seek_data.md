# Function: <code>iomap_seek_data</code>

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
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812bf280)
Location: fs/iomap.c:653
Inline: False
```
**Symbols:**

```
ffffffff812bf280-ffffffff812bf325: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e2d40)
Location: fs/iomap.c:654
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812e2d40-ffffffff812e2de5: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f6e0)
Location: fs/iomap.c:769
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8130f6e0-ffffffff8130f785: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81326660)
Location: fs/iomap.c:1403
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81326660-ffffffff81326705: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8134e0e0)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8134e0e0-ffffffff8134e179: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813663d0)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813663d0-ffffffff81366469: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813adf30)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813adf30-ffffffff813adfc9: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813bf5a0)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813bf5a0-ffffffff813bf639: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813c66e0)
Location: fs/iomap/seek.c:80
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff813c66e0-ffffffff813c676f: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff814169d0)
Location: fs/iomap/seek.c:80
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff814169d0-ffffffff81416b25: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8148dfd0)
Location: fs/iomap/seek.c:80
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8148dfd0-ffffffff8148e134: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff815217f0)
Location: fs/iomap/seek.c:80
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff815217f0-ffffffff81521954: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff81559830)
Location: fs/iomap/seek.c:80
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81559830-ffffffff81559994: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t pos, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8158ffc0)
Location: fs/iomap/seek.c:80
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8158ffc0-ffffffff81590124: iomap_seek_data (STB_GLOBAL)
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
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffff80001042db78)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffff80001042db78-ffff80001042dc40: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (c05f6a0c)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
c05f6a0c-c05f6b70: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (c00000000053edb0)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
c00000000053edb0-c00000000053eec8: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffe0002ca5f2)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffe0002ca5f2-ffffffe0002ca696: iomap_seek_data (STB_GLOBAL)
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
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8135e9b0)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8135e9b0-ffffffff8135ea49: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8134f650)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8134f650-ffffffff8134f6e9: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8135c480)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8135c480-ffffffff8135c519: iomap_seek_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode *inode, loff_t offset, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8136fbd0)
Location: fs/iomap/seek.c:186
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff8136fbd0-ffffffff8136fc69: iomap_seek_data (STB_GLOBAL)
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
