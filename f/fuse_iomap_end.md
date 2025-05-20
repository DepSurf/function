# Function: <code>fuse_iomap_end</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fuse_iomap_end(struct inode *inode, loff_t pos, loff_t length, ssize_t written, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149cba0)
Location: fs/fuse/dax.c:634
Inline: True
```
**Symbols:**

```
ffffffff8149cba0-ffffffff8149cbdf: fuse_iomap_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fuse_iomap_end(struct inode *inode, loff_t pos, loff_t length, ssize_t written, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a2bd0)
Location: fs/fuse/dax.c:634
Inline: True
```
**Symbols:**

```
ffffffff814a2bd0-ffffffff814a2c0f: fuse_iomap_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_iomap_end(struct inode *inode, loff_t pos, loff_t length, ssize_t written, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fac60)
Location: fs/fuse/dax.c:635
Inline: False
```
**Symbols:**

```
ffffffff814fac60-ffffffff814fac9f: fuse_iomap_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_iomap_end(struct inode *inode, loff_t pos, loff_t length, ssize_t written, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158b370)
Location: fs/fuse/dax.c:635
Inline: False
```
**Symbols:**

```
ffffffff8158b370-ffffffff8158b3d6: fuse_iomap_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_iomap_end(struct inode *inode, loff_t pos, loff_t length, ssize_t written, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81631b90)
Location: fs/fuse/dax.c:635
Inline: False
```
**Symbols:**

```
ffffffff81631b90-ffffffff81631bf6: fuse_iomap_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_iomap_end(struct inode *inode, loff_t pos, loff_t length, ssize_t written, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81669dd0)
Location: fs/fuse/dax.c:635
Inline: False
```
**Symbols:**

```
ffffffff81669dd0-ffffffff81669e36: fuse_iomap_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_iomap_end(struct inode *inode, loff_t pos, loff_t length, ssize_t written, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a4110)
Location: fs/fuse/dax.c:635
Inline: False
```
**Symbols:**

```
ffffffff816a4110-ffffffff816a4176: fuse_iomap_end (STB_LOCAL)
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
