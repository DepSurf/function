# Function: <code>kernfs_iattrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81288ba0)
Location: fs/kernfs/inode.c:37
Inline: True
Direct callers:
  - fs/kernfs/inode.c:__kernfs_setattr
  - fs/kernfs/inode.c:kernfs_iop_setxattr
  - fs/kernfs/inode.c:kernfs_iop_setxattr
  - fs/kernfs/inode.c:kernfs_iop_removexattr
  - fs/kernfs/inode.c:kernfs_iop_getxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff81288ba0-ffffffff81288c64: kernfs_iattrs.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812b60a0)
Location: fs/kernfs/inode.c:37
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:kernfs_iop_getxattr
  - fs/kernfs/inode.c:kernfs_iop_removexattr
  - fs/kernfs/inode.c:kernfs_iop_setxattr
  - fs/kernfs/inode.c:kernfs_iop_setxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff812b60a0-ffffffff812b6160: kernfs_iattrs.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812cb930)
Location: fs/kernfs/inode.c:34
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff812cb930-ffffffff812cb9f0: kernfs_iattrs.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812d8d80)
Location: fs/kernfs/inode.c:34
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff812d8d80-ffffffff812d8e37: kernfs_iattrs.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812fd5e0)
Location: fs/kernfs/inode.c:34
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff812fd5e0-ffffffff812fd697: kernfs_iattrs.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8132b240)
Location: fs/kernfs/inode.c:34
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff8132b240-ffffffff8132b2f3: kernfs_iattrs.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81342410)
Location: fs/kernfs/inode.c:34
Inline: True
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_xattr_get
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
**Symbols:**

```
ffffffff81342410-ffffffff813424c3: kernfs_iattrs.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136ad75)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382f35)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd4d9)
Location: fs/kernfs/inode.c:64
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df109)
Location: fs/kernfs/inode.c:64
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5c8a)
Location: fs/kernfs/inode.c:64
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8143780a)
Location: fs/kernfs/inode.c:58
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b257a)
Location: fs/kernfs/inode.c:58
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815490fa)
Location: fs/kernfs/inode.c:58
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81580cda)
Location: fs/kernfs/inode.c:58
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b9757)
Location: fs/kernfs/inode.c:58
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffff8000104514b0)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c061443c)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c000000000569bac)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e4328)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137b515)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136bfe5)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81378fe5)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138ca95)
Location: fs/kernfs/inode.c:62
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_listxattr
  - fs/kernfs/inode.c:__kernfs_setattr
```
</details>
</li>
</ul>

## Differences
