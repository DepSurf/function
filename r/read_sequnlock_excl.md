# Function: <code>read_sequnlock_excl</code>

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
In fs/namei.c (ffffffff8121711f)
Location: include/linux/seqlock.h:508
Inline: True
```
```
In fs/dcache.c (ffffffff812230aa)
Location: include/linux/seqlock.h:508
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff8122fe31)
Location: include/linux/seqlock.h:508
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
```
```
In fs/pnode.c (ffffffff8123cd3f)
Location: include/linux/seqlock.h:508
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
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
In fs/namei.c (ffffffff8123e2fb)
Location: include/linux/seqlock.h:511
Inline: True
```
```
In fs/dcache.c (ffffffff8124b645)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812584c1)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
```
```
In fs/pnode.c (ffffffff81265248)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
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
In fs/namei.c (ffffffff812510db)
Location: include/linux/seqlock.h:511
Inline: True
```
```
In fs/dcache.c (ffffffff8125e625)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8126b951)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81278678)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
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
In fs/namei.c (ffffffff8125d028)
Location: include/linux/seqlock.h:511
Inline: True
```
```
In fs/dcache.c (ffffffff8126be9d)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81279121)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812859a8)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
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
In fs/namei.c (ffffffff8127e5c8)
Location: include/linux/seqlock.h:512
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8128f78d)
Location: include/linux/seqlock.h:512
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8129bb61)
Location: include/linux/seqlock.h:512
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812a8428)
Location: include/linux/seqlock.h:512
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
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
In fs/namei.c (ffffffff812a6ea4)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812b653e)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812c1caa)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812cefc8)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff812d3806)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffff812bc0c4)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812cb17e)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812d6f4a)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812e4338)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff812e91b6)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffff812d8c84)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812e817e)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f53ab)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81302b28)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81307a8c)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffff812ea794)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812f9d0e)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81306f2b)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81315ba8)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff8131ab0c)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffff81322468)
Location: include/linux/seqlock.h:554
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff813326ac)
Location: include/linux/seqlock.h:554
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8133b130)
Location: include/linux/seqlock.h:554
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8134f552)
Location: include/linux/seqlock.h:554
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff813546da)
Location: include/linux/seqlock.h:554
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (ffffffff8132da38)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8133e87c)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81346ee0)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8135c40b)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81360fa2)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (ffffffff81333f08)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff81344c6c)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8134d6fc)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81362ecb)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81367a81)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (ffffffff81381858)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8139275c)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8139b65c)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff813b16cb)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff813b6971)
Location: include/linux/seqlock.h:1023
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (ffffffff813ffb6b)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff814123ed)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814255d1)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8143663b)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff8143bf74)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (ffffffff81489b5b)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8149d1ed)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814b1d51)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff814c466b)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff814ca5d4)
Location: include/linux/seqlock.h:1019
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (ffffffff814beb4b)
Location: include/linux/seqlock.h:1020
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff814d260d)
Location: include/linux/seqlock.h:1020
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814e6da1)
Location: include/linux/seqlock.h:1020
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff814f9a63)
Location: include/linux/seqlock.h:1020
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81500812)
Location: include/linux/seqlock.h:1020
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (ffffffff814f0fcb)
Location: include/linux/seqlock.h:955
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8150500d)
Location: include/linux/seqlock.h:955
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8151abe1)
Location: include/linux/seqlock.h:955
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8152e2c3)
Location: include/linux/seqlock.h:955
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81535432)
Location: include/linux/seqlock.h:955
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (ffff8000103938f8)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffff8000103a77e0)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffff8000103ba6bc)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffff8000103cc5b8)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffff8000103d1c88)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (c057a0ec)
Location: include/linux/seqlock.h:511
Inline: True
```
```
In fs/dcache.c (c058838c)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (c05984a8)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (c05a8164)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (c05aca20)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
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
In fs/namei.c (c00000000048d528)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (c0000000004a2868)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (c0000000004b7eb4)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (c0000000004cdcec)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (c0000000004d4a60)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffe000262850)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffe00026eb0a)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffe00027cba2)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffe000289ac2)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffe00028d2cc)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffff812e2d74)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812f22ee)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812ff50b)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8130e188)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff813130ec)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffff812d39b4)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812e2f1e)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f012b)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812fed98)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81303cfc)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffff812e0b84)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812f00fe)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812fd2fb)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8130bf78)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81310edc)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
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
In fs/namei.c (ffffffff812eff4f)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812ffc7e)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8130e65b)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8131d7a8)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff813226e2)
Location: include/linux/seqlock.h:511
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
</details>
</li>
</ul>

## Differences
