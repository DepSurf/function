# Function: <code>HAS_UNMAPPED_ID</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81241165)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff8125176f)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff8125a2a5)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81254015)
Location: include/linux/fs.h:1860
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff8126486f)
Location: include/linux/fs.h:1860
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
```
```
In fs/xattr.c (ffffffff8126d9a5)
Location: include/linux/fs.h:1860
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812609f7)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff8127209f)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
```
```
In fs/xattr.c (ffffffff8127b1c5)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812830e7)
Location: include/linux/fs.h:1917
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff812949bf)
Location: include/linux/fs.h:1917
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
```
```
In fs/xattr.c (ffffffff8129dc55)
Location: include/linux/fs.h:1917
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9b51)
Location: include/linux/fs.h:1937
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffff812bab41)
Location: include/linux/fs.h:1937
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
```
```
In fs/xattr.c (ffffffff812c4305)
Location: include/linux/fs.h:1937
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bf3e1)
Location: include/linux/fs.h:2019
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffff812cfdff)
Location: include/linux/fs.h:2019
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff812d9505)
Location: include/linux/fs.h:2019
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dbfed)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffff812ecd5d)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff812f7a98)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812edafd)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffff812fe8ed)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff81309698)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813255c3)
Location: include/linux/fs.h:2075
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff8133798d)
Location: include/linux/fs.h:2075
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff81342ba8)
Location: include/linux/fs.h:2075
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81330d33)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff813432cd)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff8134eeb8)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133754e)
Location: include/linux/fs.h:2251
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff81349598)
Location: include/linux/fs.h:2251
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff81355aaf)
Location: include/linux/fs.h:2251
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81384fae)
Location: include/linux/fs.h:2305
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff813972e8)
Location: include/linux/fs.h:2305
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff813a3ecf)
Location: include/linux/fs.h:2305
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81403133)
Location: include/linux/fs.h:2195
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff81419414)
Location: include/linux/fs.h:2195
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff81427d45)
Location: include/linux/fs.h:2195
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148d553)
Location: include/linux/fs.h:2329
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff814a4e4d)
Location: include/linux/fs.h:2329
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff814b5480)
Location: include/linux/fs.h:2329
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c34d2)
Location: include/linux/fs.h:2018
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff814da124)
Location: include/linux/fs.h:2018
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff814ea00c)
Location: include/linux/fs.h:2018
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f59a2)
Location: include/linux/fs.h:2246
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
```
```
In fs/inode.c (ffffffff8150c754)
Location: include/linux/fs.h:2246
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff8151deac)
Location: include/linux/fs.h:2246
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010397318)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffff8000103af7b4)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffff8000103bd838)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057d884)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (c058f53c)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (c059ad58)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0000000004910bc)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (c0000000004ab31c)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (c0000000004bb494)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000265444)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffe00027423a)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffe00027eaa0)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e60dd)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffff812f6ecd)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff81301c78)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d6d1d)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffff812e7aed)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff812f2898)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3eed)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffff812f4cdd)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff812ffa68)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f3fbd)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffff81305e6d)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/xattr.c (ffffffff81310da8)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
</details>
</li>
</ul>

## Differences
