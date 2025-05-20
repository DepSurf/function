# Function: <code>is_uncached_acl</code>

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
In fs/namei.c (0)
Location: include/linux/fs.h:586
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:586
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/fs.h:586
Inline: True
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
In fs/namei.c (0)
Location: include/linux/fs.h:537
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:537
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/fs.h:537
Inline: True
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
In fs/namei.c (0)
Location: include/linux/fs.h:548
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:548
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/fs.h:548
Inline: True
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
In fs/namei.c (0)
Location: include/linux/fs.h:552
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:552
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/fs.h:552
Inline: True
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
In fs/namei.c (ffffffff812a5836)
Location: include/linux/fs.h:554
Inline: True
```
```
In fs/inode.c (ffffffff812b910e)
Location: include/linux/fs.h:554
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8130b088)
Location: include/linux/fs.h:554
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff812ba996)
Location: include/linux/fs.h:591
Inline: True
```
```
In fs/inode.c (ffffffff812ce258)
Location: include/linux/fs.h:591
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81320868)
Location: include/linux/fs.h:591
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff812d7599)
Location: include/linux/fs.h:603
Inline: True
```
```
In fs/inode.c (ffffffff812eb11b)
Location: include/linux/fs.h:603
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81348118)
Location: include/linux/fs.h:603
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff812e90f9)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (ffffffff812fcc57)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813603b8)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff8132185a)
Location: include/linux/fs.h:628
Inline: True
```
```
In fs/inode.c (ffffffff813354cb)
Location: include/linux/fs.h:628
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813a5f28)
Location: include/linux/fs.h:628
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff8132cdfa)
Location: include/linux/fs.h:592
Inline: True
```
```
In fs/inode.c (ffffffff81340e40)
Location: include/linux/fs.h:592
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813b6f6a)
Location: include/linux/fs.h:592
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff81332a24)
Location: include/linux/fs.h:593
Inline: True
```
```
In fs/inode.c (ffffffff81347230)
Location: include/linux/fs.h:593
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff813be49a)
Location: include/linux/fs.h:593
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff813801b4)
Location: include/linux/fs.h:605
Inline: True
```
```
In fs/inode.c (ffffffff81394c90)
Location: include/linux/fs.h:605
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8140e2ca)
Location: include/linux/fs.h:605
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff81401629)
Location: include/linux/fs.h:560
Inline: True
```
```
In fs/inode.c (ffffffff81417038)
Location: include/linux/fs.h:560
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff814838e0)
Location: include/linux/fs.h:560
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff8148b6e0)
Location: include/linux/fs.h:575
Inline: True
```
```
In fs/inode.c (ffffffff814a2638)
Location: include/linux/fs.h:575
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81516b11)
Location: include/linux/fs.h:575
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff814bf7bc)
Location: include/linux/fs.h:590
Inline: True
```
```
In fs/inode.c (ffffffff814d7798)
Location: include/linux/fs.h:590
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff8154e451)
Location: include/linux/fs.h:590
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff814f1cac)
Location: include/linux/fs.h:623
Inline: True
```
```
In fs/inode.c (ffffffff81509aa8)
Location: include/linux/fs.h:623
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff815842a1)
Location: include/linux/fs.h:623
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffff8000103924a0)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (ffff8000103ace34)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffff800010426668)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (c0579acc)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (c058dd20)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (c05ef27c)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (c00000000048af60)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (c0000000004a8630)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (c000000000535b98)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffe000261714)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (ffffffe000271c48)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffe0002c4a14)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff812e16d9)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (ffffffff812f5237)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81358998)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff812d2319)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (ffffffff812e5e57)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81349648)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff812df4e9)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (ffffffff812f3047)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81356468)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/namei.c (ffffffff812f08d9)
Location: include/linux/fs.h:610
Inline: True
```
```
In fs/inode.c (ffffffff8130498f)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/posix_acl.c (ffffffff81369b48)
Location: include/linux/fs.h:610
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
```
</details>
</li>
</ul>

## Differences
