# Function: <code>fuse_fill_super_submount</code>

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
int fuse_fill_super_submount(struct super_block *sb, struct fuse_inode *parent_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81499b00)
Location: fs/fuse/inode.c:1276
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff81499b00-ffffffff81499d78: fuse_fill_super_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_fill_super_submount(struct super_block *sb, struct fuse_inode *parent_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149ed30)
Location: fs/fuse/inode.c:1318
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff8149ed30-ffffffff8149efa4: fuse_fill_super_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fuse_fill_super_submount(struct super_block *sb, struct fuse_inode *parent_fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/inode.c (0)
Location: fs/fuse/inode.c:1370
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff814f6400-ffffffff814f66c3: fuse_fill_super_submount (STB_LOCAL)
ffffffff81cd22c9-ffffffff81cd233c: fuse_fill_super_submount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fuse_fill_super_submount(struct super_block *sb, struct fuse_inode *parent_fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/inode.c (0)
Location: fs/fuse/inode.c:1426
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff81586210-ffffffff815864fd: fuse_fill_super_submount (STB_LOCAL)
ffffffff81e853ff-ffffffff81e85472: fuse_fill_super_submount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fuse_fill_super_submount(struct super_block *sb, struct fuse_inode *parent_fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/inode.c (0)
Location: fs/fuse/inode.c:1431
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff8162c490-ffffffff8162c76b: fuse_fill_super_submount (STB_LOCAL)
ffffffff820728b5-ffffffff82072928: fuse_fill_super_submount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fuse_fill_super_submount(struct super_block *sb, struct fuse_inode *parent_fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/inode.c (0)
Location: fs/fuse/inode.c:1437
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff816646d0-ffffffff81664993: fuse_fill_super_submount (STB_LOCAL)
ffffffff820f2519-ffffffff820f258c: fuse_fill_super_submount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fuse_fill_super_submount(struct super_block *sb, struct fuse_inode *parent_fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/inode.c (0)
Location: fs/fuse/inode.c:1520
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff8169e960-ffffffff8169ec84: fuse_fill_super_submount (STB_LOCAL)
ffffffff821cf7b4-ffffffff821cf827: fuse_fill_super_submount.cold (STB_LOCAL)
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
