# Function: <code>fuse_dax_break_layouts</code>

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
int fuse_dax_break_layouts(struct inode *inode, u64 dmap_start, u64 dmap_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149d230)
Location: fs/fuse/dax.c:686
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/dax.c:inode_inline_reclaim_one_dmap
```
**Symbols:**

```
ffffffff8149d230-ffffffff8149d322: fuse_dax_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_dax_break_layouts(struct inode *inode, u64 dmap_start, u64 dmap_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a3150)
Location: fs/fuse/dax.c:686
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
**Symbols:**

```
ffffffff814a3150-ffffffff814a3242: fuse_dax_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_dax_break_layouts(struct inode *inode, u64 dmap_start, u64 dmap_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fb1c0)
Location: fs/fuse/dax.c:685
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
**Symbols:**

```
ffffffff814fb1c0-ffffffff814fb2b3: fuse_dax_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_dax_break_layouts(struct inode *inode, u64 dmap_start, u64 dmap_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158b6a0)
Location: fs/fuse/dax.c:685
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
**Symbols:**

```
ffffffff8158b6a0-ffffffff8158b7ab: fuse_dax_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_dax_break_layouts(struct inode *inode, u64 dmap_start, u64 dmap_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81631f00)
Location: fs/fuse/dax.c:685
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
**Symbols:**

```
ffffffff81631f00-ffffffff8163200b: fuse_dax_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_dax_break_layouts(struct inode *inode, u64 dmap_start, u64 dmap_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8166a140)
Location: fs/fuse/dax.c:685
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
**Symbols:**

```
ffffffff8166a140-ffffffff8166a24b: fuse_dax_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_dax_break_layouts(struct inode *inode, u64 dmap_start, u64 dmap_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a4480)
Location: fs/fuse/dax.c:685
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
**Symbols:**

```
ffffffff816a4480-ffffffff816a458b: fuse_dax_break_layouts (STB_GLOBAL)
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
