# Function: <code>__kernfs_iattrs</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136a750)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff8136a750-ffffffff8136a803: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382930)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff81382930-ffffffff813829e3: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd612)
Location: fs/kernfs/inode.c:33
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff813cd050-ffffffff813cd120: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df242)
Location: fs/kernfs/inode.c:33
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff813dec80-ffffffff813ded50: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5e02)
Location: fs/kernfs/inode.c:33
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff813e59a0-ffffffff813e5a70: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81437a02)
Location: fs/kernfs/inode.c:27
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff81437570-ffffffff81437640: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b2722)
Location: fs/kernfs/inode.c:27
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff814b21e0-ffffffff814b22ba: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815492c2)
Location: fs/kernfs/inode.c:27
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff81548d60-ffffffff81548e2e: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81580ea2)
Location: fs/kernfs/inode.c:27
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff81580930-ffffffff815809fe: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b9952)
Location: fs/kernfs/inode.c:27
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff815b93c0-ffffffff815b948e: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffff800010450dc8)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffff800010450dc8-ffff800010450e9c: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_iattrs *__kernfs_iattrs(struct kernfs_node *kn, int alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c0613d8c)
Location: fs/kernfs/inode.c:33
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
c0613d8c-c0613e5c: __kernfs_iattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (c0000000005691d0)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
c0000000005691d0-c000000000569314: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e3cde)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffe0002e3cde-ffffffe0002e3d88: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137af10)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff8137af10-ffffffff8137afc3: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136b9e0)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff8136b9e0-ffffffff8136ba93: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813789e0)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff813789e0-ffffffff81378a93: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138c490)
Location: fs/kernfs/inode.c:33
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff8138c490-ffffffff8138c543: __kernfs_iattrs.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
