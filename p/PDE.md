# Function: <code>PDE</code>

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
In fs/proc/inode.c (ffffffff81279266)
Location: fs/proc/internal.h:80
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_follow_link
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
```
```
In fs/proc/generic.c (ffffffff8127ece2)
Location: fs/proc/internal.h:80
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:80
Inline: True
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
In fs/proc/inode.c (ffffffff812a5fc6)
Location: fs/proc/internal.h:80
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff812ac946)
Location: fs/proc/internal.h:80
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:80
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
In fs/proc/inode.c (ffffffff812bb8e6)
Location: fs/proc/internal.h:80
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff812c2236)
Location: fs/proc/internal.h:80
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:80
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
In fs/proc/inode.c (ffffffff812c8e26)
Location: fs/proc/internal.h:84
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff812cf4f6)
Location: fs/proc/internal.h:84
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:84
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
In fs/proc/inode.c (ffffffff812ed696)
Location: fs/proc/internal.h:84
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff812f3c76)
Location: fs/proc/internal.h:84
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:84
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
In fs/proc/inode.c (ffffffff8131a575)
Location: fs/proc/internal.h:109
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff81321035)
Location: fs/proc/internal.h:109
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff813282f5)
Location: fs/proc/internal.h:109
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff81331ab5)
Location: fs/proc/internal.h:108
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff81338145)
Location: fs/proc/internal.h:108
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff8133f4d5)
Location: fs/proc/internal.h:108
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff81359895)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff813602c5)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff813677f5)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff81371ae5)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff81378525)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff8137fa75)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff813b95e5)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/generic.c (ffffffff813c1615)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff813c9e15)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:get_proc_net
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
In fs/proc/inode.c (ffffffff813caff5)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/generic.c (ffffffff813d3505)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff813dba95)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff813d2035)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/generic.c (ffffffff813da335)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff813e29b5)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff81423565)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/generic.c (ffffffff8142ba65)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff814344c5)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff8149c185)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/generic.c (ffffffff814a5225)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff814ae5e5)
Location: fs/proc/internal.h:113
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff81530aa5)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/generic.c (ffffffff8153a7a5)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff81544c25)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff81568c25)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/generic.c (ffffffff81572a85)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff8157c815)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff815a1245)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/generic.c (ffffffff815ab435)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff815b5135)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffff80001043b7e4)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffff800010444744)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffff80001044d3a8)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (c0601ccc)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (c0609740)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (c0611984)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (c00000000054f480)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (c000000000559eec)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (c000000000564c80)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffe0002d3bb6)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffe0002da998)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffe0002e1caa)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff8136a0c5)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff81370b05)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff81378055)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff8135ab55)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff81361595)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff81368b25)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff81367b95)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff8136e5d5)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff81375b25)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
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
In fs/proc/inode.c (ffffffff8137b1e5)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_evict_inode
```
```
In fs/proc/generic.c (ffffffff81381f25)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_simple_write
  - fs/proc/generic.c:PDE_DATA
  - fs/proc/generic.c:proc_get_parent_data
  - fs/proc/generic.c:proc_single_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/generic.c:proc_readdir
  - fs/proc/generic.c:proc_lookup
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_net.c (ffffffff813895d5)
Location: fs/proc/internal.h:104
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
  - fs/proc/proc_net.c:seq_open_net
```
</details>
</li>
</ul>

## Differences
