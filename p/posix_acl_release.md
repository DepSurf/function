# Function: <code>posix_acl_release</code>

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
In fs/namei.c (ffffffff81216e20)
Location: include/linux/posix_acl.h:73
Inline: True
```
```
In fs/inode.c (ffffffff81227b98)
Location: include/linux/posix_acl.h:73
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8126dec2)
Location: include/linux/posix_acl.h:73
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
```
```
In fs/ext4/acl.c (ffffffff812e43dc)
Location: include/linux/posix_acl.h:73
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
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
In fs/namei.c (ffffffff8123dcb2)
Location: include/linux/posix_acl.h:71
Inline: True
```
```
In fs/inode.c (ffffffff81250303)
Location: include/linux/posix_acl.h:71
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8129a1d8)
Location: include/linux/posix_acl.h:71
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/acl.c (ffffffff813144c6)
Location: include/linux/posix_acl.h:71
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff81250a92)
Location: include/linux/posix_acl.h:51
Inline: True
```
```
In fs/inode.c (ffffffff812633a3)
Location: include/linux/posix_acl.h:51
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff812aed08)
Location: include/linux/posix_acl.h:51
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/acl.c (ffffffff8132a4a6)
Location: include/linux/posix_acl.h:51
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff8125cc13)
Location: include/linux/posix_acl.h:51
Inline: True
```
```
In fs/inode.c (ffffffff81270bce)
Location: include/linux/posix_acl.h:51
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff812bc128)
Location: include/linux/posix_acl.h:51
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff812f5549)
Location: include/linux/posix_acl.h:51
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff8133f6fc)
Location: include/linux/posix_acl.h:51
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff8127ef83)
Location: include/linux/posix_acl.h:52
Inline: True
```
```
In fs/inode.c (ffffffff812934fe)
Location: include/linux/posix_acl.h:52
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff812dfa28)
Location: include/linux/posix_acl.h:52
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff81319caf)
Location: include/linux/posix_acl.h:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff81363d0c)
Location: include/linux/posix_acl.h:52
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff812a5911)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff812b912e)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8130bc5a)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff81347bfa)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff8139249c)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff812baa71)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff812ce278)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813214ba)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff8135fdaa)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff813ab0dc)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff812d7675)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff812eb13b)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81348d5e)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff81388f1e)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff813d530d)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff812e91d5)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff812fcc77)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81360ffe)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff813a1924)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff813ee9dd)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff813218c8)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff813354ee)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813a6da5)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff813edadf)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff8143ba5d)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/ext4/acl.c:ext4_acl_from_disk
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
In fs/namei.c (ffffffff8132ce68)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff81340e63)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813b7b65)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff813fe444)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_xattr_credits_for_new_inode
```
```
In fs/ext4/acl.c (ffffffff81457d8d)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/ext4/acl.c:ext4_acl_from_disk
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
In fs/namei.c (ffffffff81332aa5)
Location: include/linux/posix_acl.h:55
Inline: True
```
```
In fs/inode.c (ffffffff81347253)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813bebfc)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff814065fc)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff8145d73d)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/ext4/acl.c:ext4_acl_from_disk
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
In fs/namei.c (ffffffff81380235)
Location: include/linux/posix_acl.h:55
Inline: True
```
```
In fs/inode.c (ffffffff81394cb3)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8140ea2c)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff81458e71)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff814b2bfd)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In security/integrity/evm/evm_main.c (ffffffff815a2a73)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_xattr_change
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
In fs/namei.c (ffffffff814016fc)
Location: include/linux/posix_acl.h:55
Inline: True
```
```
In fs/inode.c (ffffffff81417066)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff814841c4)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff814d6a6e)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff8153b870)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In security/integrity/evm/evm_main.c (ffffffff816491a3)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_xattr_change
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
In fs/namei.c (ffffffff8148b7ef)
Location: include/linux/posix_acl.h:55
Inline: True
```
```
In fs/inode.c (ffffffff814a2666)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8151762f)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff8156f813)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff815d9ea0)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/ext4/acl.c:ext4_acl_from_disk
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
In fs/namei.c (ffffffff814bf830)
Location: include/linux/posix_acl.h:55
Inline: True
```
```
In fs/inode.c (ffffffff814d77c6)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8154ef05)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff815a766c)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff81611a80)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/ext4/acl.c:ext4_acl_from_disk
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
In fs/namei.c (ffffffff814f1d20)
Location: include/linux/posix_acl.h:55
Inline: True
```
```
In fs/inode.c (ffffffff81509ad6)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81584d45)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff815e049b)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff8164a830)
Location: include/linux/posix_acl.h:55
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/ext4/acl.c:ext4_acl_from_disk
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
In fs/namei.c (ffff8000103925a0)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffff8000103ace74)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffff80001042751c)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffff800010474ffc)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffff8000104c7e04)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (c0579bc0)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (c058dd64)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (c05f00b0)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (c0636730)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (c068ba88)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (c00000000048b044)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (c0000000004a8690)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (c0000000005371b0)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (c000000000596968)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (c0000000006004c4)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffe0002617d2)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffe000271c58)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffe0002c5b00)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffe0003007f2)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffe000341b56)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff812e17b5)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff812f5257)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813595de)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff81399f04)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff813e6fbd)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff812d23f5)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff812e5e77)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8134a28e)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff8138a994)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff813d7a3d)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff812df5c5)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff812f3067)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813570ae)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff81397764)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff813e433d)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
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
In fs/namei.c (ffffffff812f09b5)
Location: include/linux/posix_acl.h:53
Inline: True
```
```
In fs/inode.c (ffffffff813049af)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8136a78e)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/ialloc.c (ffffffff813abfad)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff813f974d)
Location: include/linux/posix_acl.h:53
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
</ul>

## Differences
