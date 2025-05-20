# Function: <code>try_break_deleg</code>

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
In fs/namei.c (ffffffff8121884a)
Location: include/linux/fs.h:2129
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
```
```
In fs/attr.c (ffffffff812296fe)
Location: include/linux/fs.h:2129
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff81241b18)
Location: include/linux/fs.h:2259
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81251d69)
Location: include/linux/fs.h:2259
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812547f8)
Location: include/linux/fs.h:2240
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff8126500e)
Location: include/linux/fs.h:2240
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff81260303)
Location: include/linux/fs.h:2293
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81272830)
Location: include/linux/fs.h:2293
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812829e3)
Location: include/linux/fs.h:2338
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81295150)
Location: include/linux/fs.h:2338
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812ab4c6)
Location: include/linux/fs.h:2354
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812bb2c5)
Location: include/linux/fs.h:2354
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812be0d6)
Location: include/linux/fs.h:2440
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812d04ba)
Location: include/linux/fs.h:2440
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812dace4)
Location: include/linux/fs.h:2434
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812ed4e0)
Location: include/linux/fs.h:2434
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812ec7f4)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812fef3c)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff81326a26)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff8133803c)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff813434a6)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
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
In fs/namei.c (ffffffff81331e98)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff813439a6)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8134f636)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
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
In fs/namei.c (ffffffff81335f11)
Location: include/linux/fs.h:2687
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81349d20)
Location: include/linux/fs.h:2687
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81356130)
Location: include/linux/fs.h:2687
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
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
In fs/namei.c (ffffffff81383af7)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81397c1c)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff813a4660)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
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
In fs/namei.c (ffffffff814043a8)
Location: include/linux/fs.h:2521
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff81419c10)
Location: include/linux/fs.h:2521
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814285e6)
Location: include/linux/fs.h:2521
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
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
In fs/namei.c (ffffffff8148e828)
Location: include/linux/fs.h:2656
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff814a5c20)
Location: include/linux/fs.h:2656
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814b5b06)
Location: include/linux/fs.h:2656
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/posix_acl.c (ffffffff81515f6b)
Location: include/linux/fs.h:2656
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
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
In fs/namei.c (ffffffff814c400a)
Location: include/linux/filelock.h:378
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff814dac14)
Location: include/linux/filelock.h:378
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814ea356)
Location: include/linux/filelock.h:378
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/posix_acl.c (ffffffff8154d8db)
Location: include/linux/filelock.h:378
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
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
In fs/namei.c (ffffffff814f672d)
Location: include/linux/filelock.h:378
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff8150d1c6)
Location: include/linux/filelock.h:378
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8151e1f6)
Location: include/linux/filelock.h:378
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/posix_acl.c (ffffffff8158370b)
Location: include/linux/filelock.h:378
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
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
In fs/namei.c (ffff8000103963a4)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffff8000103b0408)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (c057b86c)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (c058fcb8)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (c00000000048e314)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (c0000000004abc70)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffe00026460a)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffe0002747ec)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812e4dd4)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812f751c)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812d5a14)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812e813c)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812e2be4)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff812f532c)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
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
In fs/namei.c (ffffffff812f2b24)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/attr.c (ffffffff813064bc)
Location: include/linux/fs.h:2469
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
</details>
</li>
</ul>

## Differences
