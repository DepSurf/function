# Function: <code>fuse_mount_destroy</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_mount_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f4f1b)
Location: fs/fuse/inode.c:1742
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff814f4e70-ffffffff814f4e94: fuse_mount_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_mount_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81584e3b)
Location: fs/fuse/inode.c:1798
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff81584ae0-ffffffff81584b09: fuse_mount_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_mount_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162afcb)
Location: fs/fuse/inode.c:1803
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff8162ac40-ffffffff8162ac69: fuse_mount_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_mount_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff816631eb)
Location: fs/fuse/inode.c:1809
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff81662e60-ffffffff81662e89: fuse_mount_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_mount_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169d35b)
Location: fs/fuse/inode.c:1909
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff8169d140-ffffffff8169d174: fuse_mount_destroy (STB_GLOBAL)
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
