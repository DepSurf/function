# Function: <code>get_inode_acl</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct posix_acl *get_inode_acl(struct inode *inode, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81516dad)
Location: fs/posix_acl.c:182
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81516b90-ffffffff81516bd0: get_inode_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct posix_acl *get_inode_acl(struct inode *inode, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8154e6ed)
Location: fs/posix_acl.c:183
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff8154e4d0-ffffffff8154e510: get_inode_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct posix_acl *get_inode_acl(struct inode *inode, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8158453d)
Location: fs/posix_acl.c:183
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81584320-ffffffff81584360: get_inode_acl (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
