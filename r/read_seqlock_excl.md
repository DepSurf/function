# Function: <code>read_seqlock_excl</code>

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
In fs/namei.c (ffffffff812170e4)
Location: include/linux/seqlock.h:503
Inline: True
```
```
In fs/dcache.c (ffffffff812230fa)
Location: include/linux/seqlock.h:503
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff8122fe0f)
Location: include/linux/seqlock.h:503
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
```
```
In fs/pnode.c (ffffffff8123cd2c)
Location: include/linux/seqlock.h:503
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
In fs/namei.c (ffffffff8123e2c4)
Location: include/linux/seqlock.h:506
Inline: True
```
```
In fs/dcache.c (ffffffff8124b655)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8125849f)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
```
```
In fs/pnode.c (ffffffff8126520f)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff812510a4)
Location: include/linux/seqlock.h:506
Inline: True
```
```
In fs/dcache.c (ffffffff8125e635)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8126b92f)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8127863f)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff8125cfe6)
Location: include/linux/seqlock.h:506
Inline: True
```
```
In fs/dcache.c (ffffffff8126be7b)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812790ff)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8128596f)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff8127e586)
Location: include/linux/seqlock.h:507
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8128f76b)
Location: include/linux/seqlock.h:507
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8129bb3f)
Location: include/linux/seqlock.h:507
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812a83ef)
Location: include/linux/seqlock.h:507
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
In fs/namei.c (ffffffff812a6e6a)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812b6521)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812c1c75)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812cef8f)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff812d385a)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff812bc08a)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812cb161)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812d6f15)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812e42ff)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff812e920a)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff812d8c4a)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812e8161)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f5375)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81302af0)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81307a9c)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff812ea75a)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812f9cf1)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81306ef5)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81315b70)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff8131ab1c)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff813223fa)
Location: include/linux/seqlock.h:549
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8133268f)
Location: include/linux/seqlock.h:549
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8133b0e5)
Location: include/linux/seqlock.h:549
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8134f519)
Location: include/linux/seqlock.h:549
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff813546f4)
Location: include/linux/seqlock.h:549
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
In fs/namei.c (ffffffff8132d9ca)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8133e85f)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81346e95)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8135c3d2)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81361009)
Location: include/linux/seqlock.h:1014
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
In fs/namei.c (ffffffff81333e9a)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff81344c4f)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8134d6b5)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81362e92)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81367ae8)
Location: include/linux/seqlock.h:1014
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
In fs/namei.c (ffffffff813817ea)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8139273f)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8139b615)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff813b1692)
Location: include/linux/seqlock.h:1014
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff813b69f6)
Location: include/linux/seqlock.h:1014
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
In fs/namei.c (ffffffff813ffb31)
Location: include/linux/seqlock.h:1010
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff814123d0)
Location: include/linux/seqlock.h:1010
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814255b6)
Location: include/linux/seqlock.h:1010
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
In fs/pnode.c (ffffffff81436602)
Location: include/linux/seqlock.h:1010
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff8143c006)
Location: include/linux/seqlock.h:1010
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
In fs/namei.c (ffffffff81489b21)
Location: include/linux/seqlock.h:1010
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8149d1d0)
Location: include/linux/seqlock.h:1010
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814b1d36)
Location: include/linux/seqlock.h:1010
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
In fs/pnode.c (ffffffff814c4632)
Location: include/linux/seqlock.h:1010
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff814ca666)
Location: include/linux/seqlock.h:1010
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
In fs/namei.c (ffffffff814beb11)
Location: include/linux/seqlock.h:1011
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff814d25f0)
Location: include/linux/seqlock.h:1011
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814e6d87)
Location: include/linux/seqlock.h:1011
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
In fs/pnode.c (ffffffff814f9a25)
Location: include/linux/seqlock.h:1011
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff815008a4)
Location: include/linux/seqlock.h:1011
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
In fs/namei.c (ffffffff814f0f91)
Location: include/linux/seqlock.h:946
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff81504ff0)
Location: include/linux/seqlock.h:946
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8151abc7)
Location: include/linux/seqlock.h:946
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
In fs/pnode.c (ffffffff8152e285)
Location: include/linux/seqlock.h:946
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff815354c4)
Location: include/linux/seqlock.h:946
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
In fs/namei.c (ffff80001039389c)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffff8000103a7790)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffff8000103ba680)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffff8000103cc554)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffff8000103d1cd0)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (c057a0b4)
Location: include/linux/seqlock.h:506
Inline: True
```
```
In fs/dcache.c (c0588370)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (c059847c)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (c05a8128)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (c05aca3c)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (c00000000048d4e8)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (c0000000004a2848)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (c0000000004b7e80)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (c0000000004cdca0)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (c0000000004d4a90)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffe000262812)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffe00026eadc)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffe00027cb82)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffe000289a90)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffe00028d30a)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff812e2d3a)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812f22d1)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812ff4d5)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8130e150)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff813130fc)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff812d397a)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812e2f01)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f00f5)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812fed60)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81303d0c)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff812e0b4a)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812f00e1)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812fd2c5)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8130bf40)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81310eec)
Location: include/linux/seqlock.h:506
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
In fs/namei.c (ffffffff812eff11)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff812ffc61)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8130e625)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8131d770)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffff81322736)
Location: include/linux/seqlock.h:506
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
</details>
</li>
</ul>

## Differences
