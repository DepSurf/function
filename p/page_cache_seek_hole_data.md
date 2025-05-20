# Function: <code>page_cache_seek_hole_data</code>

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
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812902a0)
Location: fs/buffer.c:3538
Inline: False
Direct callers:
  - fs/iomap.c:iomap_seek_data_actor
  - fs/iomap.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff812902a0-ffffffff81290584: page_cache_seek_hole_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b2fb0)
Location: fs/buffer.c:3506
Inline: False
Direct callers:
  - fs/iomap.c:iomap_seek_data_actor
  - fs/iomap.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff812b2fb0-ffffffff812b3242: page_cache_seek_hole_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130daf0)
Location: fs/iomap.c:657
Inline: False
Direct callers:
  - fs/iomap.c:iomap_seek_data_actor
  - fs/iomap.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff8130daf0-ffffffff8130de70: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813249a0)
Location: fs/iomap.c:1291
Inline: False
Direct callers:
  - fs/iomap.c:iomap_seek_data_actor
  - fs/iomap.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff813249a0-ffffffff81324d26: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8134e180)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff8134e180-ffffffff8134e4c5: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff81366470)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff81366470-ffffffff813667b5: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813adfd0)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff813adfd0-ffffffff813ae310: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff813bf640)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff813bf640-ffffffff813bf980: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
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
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffff80001042dc40)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffff80001042dc40-ffff80001042df1c: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (c05f6b70)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
c05f6b70-c05f6f3c: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (c00000000053eed0)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
c00000000053eed0-c00000000053f2dc: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffe0002ca696)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffe0002ca696-ffffffe0002ca8dc: page_cache_seek_hole_data (STB_LOCAL)
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
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8135ea50)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff8135ea50-ffffffff8135ed95: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8134f6f0)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff8134f6f0-ffffffff8134fa35: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8135c520)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff8135c520-ffffffff8135c865: page_cache_seek_hole_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode *inode, loff_t offset, loff_t length, int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/seek.c (ffffffff8136fc70)
Location: fs/iomap/seek.c:74
Inline: False
Direct callers:
  - fs/iomap/seek.c:iomap_seek_data_actor
  - fs/iomap/seek.c:iomap_seek_hole_actor
```
**Symbols:**

```
ffffffff8136fc70-ffffffff8136ffdf: page_cache_seek_hole_data (STB_LOCAL)
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
