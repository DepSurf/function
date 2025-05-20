# Function: <code>fuse_iomap_begin</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_iomap_begin(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149d8b0)
Location: fs/fuse/dax.c:560
Inline: False
```
**Symbols:**

```
ffffffff8149d8b0-ffffffff8149dad9: fuse_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_iomap_begin(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a3ae0)
Location: fs/fuse/dax.c:560
Inline: False
```
**Symbols:**

```
ffffffff814a3ae0-ffffffff814a3ddf: fuse_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fuse_iomap_begin(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:561
Inline: False
```
**Symbols:**

```
ffffffff814fbb50-ffffffff814fbe5e: fuse_iomap_begin (STB_LOCAL)
ffffffff81cd23c1-ffffffff81cd2407: fuse_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fuse_iomap_begin(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:561
Inline: False
```
**Symbols:**

```
ffffffff8158c070-ffffffff8158c3a8: fuse_iomap_begin (STB_LOCAL)
ffffffff81e854f4-ffffffff81e8553a: fuse_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fuse_iomap_begin(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:561
Inline: False
```
**Symbols:**

```
ffffffff816328c0-ffffffff81632bf8: fuse_iomap_begin (STB_LOCAL)
ffffffff8207296c-ffffffff820729b2: fuse_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fuse_iomap_begin(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:561
Inline: False
```
**Symbols:**

```
ffffffff8166a810-ffffffff8166ab48: fuse_iomap_begin (STB_LOCAL)
ffffffff820f25d0-ffffffff820f2616: fuse_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fuse_iomap_begin(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:561
Inline: False
```
**Symbols:**

```
ffffffff816a4b50-ffffffff816a4e88: fuse_iomap_begin (STB_LOCAL)
ffffffff821cf86b-ffffffff821cf8b1: fuse_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
