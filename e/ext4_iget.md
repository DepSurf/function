# Function: <code>ext4_iget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *ext4_iget(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299cb0)
Location: fs/ext4/inode.c:4107
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_iget_normal
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff81299cb0-ffffffff8129a7cf: ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *ext4_iget(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c7b40)
Location: fs/ext4/inode.c:4423
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_iget_normal
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff812c7b40-ffffffff812c86b9: ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *ext4_iget(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dd6a0)
Location: fs/ext4/inode.c:4556
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_iget_normal
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff812dd6a0-ffffffff812de289: ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *ext4_iget(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81301760)
Location: fs/ext4/inode.c:4655
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_iget_normal
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81301760-ffffffff81302319: ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *ext4_iget(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81326120)
Location: fs/ext4/inode.c:4720
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_iget_normal
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff81326120-ffffffff81326cad: ext4_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *ext4_iget(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813544d0)
Location: fs/ext4/inode.c:4791
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_iget_normal
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813544d0-ffffffff813550e1: ext4_iget (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
