# Function: <code>break_deleg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81209b5c)
Location: include/linux/fs.h:2115
Inline: True
Inline callers:
  - fs/open.c:chmod_common
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff8121884a)
Location: include/linux/fs.h:2115
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
```
```
In fs/attr.c (ffffffff812296fe)
Location: include/linux/fs.h:2115
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81240d04)
Location: include/linux/fs.h:2115
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122fb18)
Location: include/linux/fs.h:2245
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff81245f5e)
Location: include/linux/fs.h:2245
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81251d69)
Location: include/linux/fs.h:2245
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8126901a)
Location: include/linux/fs.h:2245
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
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
In fs/open.c (ffffffff812420b8)
Location: include/linux/fs.h:2226
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff81258ebc)
Location: include/linux/fs.h:2226
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff8126500e)
Location: include/linux/fs.h:2226
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8127bffa)
Location: include/linux/fs.h:2226
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
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
In fs/open.c (ffffffff8124d5b0)
Location: include/linux/fs.h:2279
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff81265087)
Location: include/linux/fs.h:2279
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81272830)
Location: include/linux/fs.h:2279
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8128935c)
Location: include/linux/fs.h:2279
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
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
In fs/open.c (ffffffff8126f530)
Location: include/linux/fs.h:2324
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff81287917)
Location: include/linux/fs.h:2324
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81295150)
Location: include/linux/fs.h:2324
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff812abe7c)
Location: include/linux/fs.h:2324
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
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
In fs/open.c (ffffffff81294f80)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff812acaf8)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812bb2c5)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff812d2b3b)
Location: include/linux/fs.h:2340
Inline: True
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
In fs/open.c (ffffffff812a9c70)
Location: include/linux/fs.h:2426
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff812c1bf8)
Location: include/linux/fs.h:2426
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812d04ba)
Location: include/linux/fs.h:2426
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff812e7f1b)
Location: include/linux/fs.h:2426
Inline: True
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
In fs/open.c (ffffffff812c6415)
Location: include/linux/fs.h:2420
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff812de12b)
Location: include/linux/fs.h:2420
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812ed4e0)
Location: include/linux/fs.h:2420
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8130682b)
Location: include/linux/fs.h:2420
Inline: True
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
In fs/open.c (ffffffff812d7e25)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff812efc4b)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812fef3c)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81319891)
Location: include/linux/fs.h:2455
Inline: True
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
In fs/open.c (ffffffff8130deb3)
Location: include/linux/fs.h:2488
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff81327f2e)
Location: include/linux/fs.h:2488
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff8133803c)
Location: include/linux/fs.h:2488
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81343587)
Location: include/linux/fs.h:2488
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff8135383b)
Location: include/linux/fs.h:2488
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
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
In fs/open.c (ffffffff8131b613)
Location: include/linux/fs.h:2442
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff81334a55)
Location: include/linux/fs.h:2442
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff813439a6)
Location: include/linux/fs.h:2442
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8134f717)
Location: include/linux/fs.h:2442
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff81360167)
Location: include/linux/fs.h:2442
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
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
In fs/open.c (ffffffff81321752)
Location: include/linux/fs.h:2673
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff8133abe4)
Location: include/linux/fs.h:2673
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81349d20)
Location: include/linux/fs.h:2673
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8135621f)
Location: include/linux/fs.h:2673
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff81366bfd)
Location: include/linux/fs.h:2673
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
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
In fs/open.c (ffffffff8136ec32)
Location: include/linux/fs.h:2646
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff8138877f)
Location: include/linux/fs.h:2646
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81397c1c)
Location: include/linux/fs.h:2646
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff813a474f)
Location: include/linux/fs.h:2646
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff813b574d)
Location: include/linux/fs.h:2646
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
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
In fs/open.c (ffffffff813ed4bd)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff8140977d)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81419c10)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8142876e)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff8143aa2f)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
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
In fs/open.c (ffffffff81475b46)
Location: include/linux/fs.h:2642
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff81493e2d)
Location: include/linux/fs.h:2642
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff814a5c20)
Location: include/linux/fs.h:2642
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814b5c9e)
Location: include/linux/fs.h:2642
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff814c8ee6)
Location: include/linux/fs.h:2642
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/posix_acl.c (ffffffff81515f6b)
Location: include/linux/fs.h:2642
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
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
In fs/open.c (ffffffff814aa4a8)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff814c8e9b)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff814dac14)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814ea4ec)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff814ff120)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/posix_acl.c (ffffffff8154d8db)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
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
In fs/open.c (ffffffff814db948)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff814fb759)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff8150d1c6)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8151e38c)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff81533d50)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/posix_acl.c (ffffffff8158370b)
Location: include/linux/filelock.h:364
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
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
In fs/open.c (ffff80001037d1e0)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffff8000103993ac)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffff8000103b0408)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffff8000103d0854)
Location: include/linux/fs.h:2455
Inline: True
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
In fs/open.c (c05680b0)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (c057fa20)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (c058fcb8)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (c05abbec)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
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
In fs/open.c (c0000000004727ac)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (c000000000493bc0)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (c0000000004abc70)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (c0000000004d319c)
Location: include/linux/fs.h:2455
Inline: True
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
In fs/open.c (ffffffe0002536cc)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffe000266e66)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffe0002747ec)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffe00028ca8c)
Location: include/linux/fs.h:2455
Inline: True
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
In fs/open.c (ffffffff812d0405)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff812e822b)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812f751c)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81311e71)
Location: include/linux/fs.h:2455
Inline: True
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
In fs/open.c (ffffffff812c1085)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff812d8e6b)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812e813c)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81302a81)
Location: include/linux/fs.h:2455
Inline: True
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
In fs/open.c (ffffffff812ce215)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff812e603b)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812f532c)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8130fc61)
Location: include/linux/fs.h:2455
Inline: True
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
In fs/open.c (ffffffff812df025)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
```
```
In fs/namei.c (ffffffff812f6fbb)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff813064bc)
Location: include/linux/fs.h:2455
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81321461)
Location: include/linux/fs.h:2455
Inline: True
```
</details>
</li>
</ul>

## Differences
