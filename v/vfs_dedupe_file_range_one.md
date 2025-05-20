# Function: <code>vfs_dedupe_file_range_one</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ac520)
Location: fs/read_write.c:2053
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812ac520-ffffffff812ac660: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c8c80)
Location: fs/read_write.c:2126
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812c8c80-ffffffff812c8dc2: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812da690)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812da690-ffffffff812da7d2: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81310e7a)
Location: fs/read_write.c:2208
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff81310b90-ffffffff81310ca6: vfs_dedupe_file_range_one.part.0 (STB_LOCAL)
ffffffff81310cb0-ffffffff81310d1c: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81366090)
Location: fs/remap_range.c:446
Inline: True
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff81366090-ffffffff813661f7: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8136ca30)
Location: fs/remap_range.c:449
Inline: True
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff8136ca30-ffffffff8136cbec: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff813bb6f0)
Location: fs/remap_range.c:437
Inline: True
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff813bb6f0-ffffffff813bb8ac: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff814418e0)
Location: fs/remap_range.c:427
Inline: True
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff814418e0-ffffffff81441b00: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff814d0b90)
Location: fs/remap_range.c:436
Inline: True
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff814d0b90-ffffffff814d0dc6: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff815076d0)
Location: fs/remap_range.c:439
Inline: True
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff815076d0-ffffffff815078f8: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8153be90)
Location: fs/remap_range.c:432
Inline: True
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff8153be90-ffffffff8153c087: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff80001037fcc8)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffff80001037fcc8-ffff80001037fe2c: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056a2fc)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
c056a2fc-c056a4cc: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000475c00)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
c000000000475c00-c000000000475de8: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe00025565a)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffe00025565a-ffffffe000255756: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2c70)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812d2c70-ffffffff812d2db2: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c38f0)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812c38f0-ffffffff812c3a32: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d0a80)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812d0a80-ffffffff812d0bc2: vfs_dedupe_file_range_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file *src_file, loff_t src_pos, struct file *dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e18b0)
Location: fs/read_write.c:2124
Inline: True
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812e18b0-ffffffff812e19f2: vfs_dedupe_file_range_one (STB_GLOBAL)
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
