# Function: <code>__break_lease</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812617b0)
Location: fs/locks.c:1390
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:chmod_common
  - fs/open.c:chown_common
  - fs/open.c:do_dentry_open
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/attr.c:notify_change
  - fs/utimes.c:utimes_common
```
**Symbols:**

```
ffffffff812617b0-ffffffff81261c3b: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128d9a0)
Location: fs/locks.c:1418
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/utimes.c:utimes_common
```
**Symbols:**

```
ffffffff8128d9a0-ffffffff8128de0d: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a3110)
Location: fs/locks.c:1442
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/utimes.c:utimes_common
```
**Symbols:**

```
ffffffff812a3110-ffffffff812a3629: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b10a0)
Location: fs/locks.c:1442
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/utimes.c:utimes_common
```
**Symbols:**

```
ffffffff812b10a0-ffffffff812b159b: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d4b80)
Location: fs/locks.c:1452
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/utimes.c:utimes_common
```
**Symbols:**

```
ffffffff812d4b80-ffffffff812d508a: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ff5d0)
Location: fs/locks.c:1452
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff812ff5d0-ffffffff812fface: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81314c80)
Location: fs/locks.c:1571
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81314c80-ffffffff81315185: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c570)
Location: fs/locks.c:1577
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff8133c570-ffffffff8133ca8b: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81354b00)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81354b00-ffffffff81355033: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139b780)
Location: fs/locks.c:1606
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/utimes.c:utimes_common
```
**Symbols:**

```
ffffffff8139b780-ffffffff8139bdf2: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ad1b0)
Location: fs/locks.c:1607
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/utimes.c:vfs_utimes
```
**Symbols:**

```
ffffffff813ad1b0-ffffffff813ad7ee: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b43b0)
Location: fs/locks.c:1607
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/utimes.c:vfs_utimes
```
**Symbols:**

```
ffffffff813b43b0-ffffffff813b49ef: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814040b0)
Location: fs/locks.c:1510
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/utimes.c:vfs_utimes
```
**Symbols:**

```
ffffffff814040b0-ffffffff814046ec: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81478140)
Location: fs/locks.c:1485
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/utimes.c:vfs_utimes
```
**Symbols:**

```
ffffffff81478140-ffffffff814788d9: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150aa60)
Location: fs/locks.c:1471
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/utimes.c:vfs_utimes
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
```
**Symbols:**

```
ffffffff8150aa60-ffffffff8150b1f7: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815421c0)
Location: fs/locks.c:1472
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/utimes.c:vfs_utimes
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
```
**Symbols:**

```
ffffffff815421c0-ffffffff81542957: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815776e0)
Location: fs/locks.c:1486
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/utimes.c:vfs_utimes
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
```
**Symbols:**

```
ffffffff815776e0-ffffffff81577e77: __break_lease (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010416be8)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffff800010416be8-ffff800010417288: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e48d4)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/utimes.c:utimes_common
```
**Symbols:**

```
c05e48d4-c05e4f38: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005280e0)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
c0000000005280e0-c000000000528880: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002be1ee)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffe0002be1ee-ffffffe0002be796: __break_lease (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134d0e0)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff8134d0e0-ffffffff8134d613: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133ddc0)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff8133ddc0-ffffffff8133e2f3: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134abb0)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff8134abb0-ffffffff8134b0e3: __break_lease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __break_lease(struct inode *inode, unsigned int mode, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135f4b0)
Location: fs/locks.c:1603
Inline: False
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff8135f4b0-ffffffff8135fa91: __break_lease (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
