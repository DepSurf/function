# Function: <code>percpu_counter_sum</code>

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
In mm/shmem.c (ffffffff811a6f20)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/ext4/inode.c (ffffffff8129c68e)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/sysfs.c (ffffffff812e3a64)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/flex_proportions.c (ffffffff813e97e4)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In lib/percpu_counter.c (ffffffff81411cfa)
Location: include/linux/percpu_counter.h:62
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1de0)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
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
In mm/shmem.c (ffffffff811bd410)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/ext4/inode.c (ffffffff812ca04d)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/sysfs.c (ffffffff81313a34)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/flex_proportions.c (ffffffff8142fc40)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In lib/percpu_counter.c (ffffffff81459a56)
Location: include/linux/percpu_counter.h:62
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8180faa0)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
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
In mm/shmem.c (ffffffff811cdae9)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/ext4/inode.c (ffffffff812dfd1a)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/sysfs.c (ffffffff813299d4)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/flex_proportions.c (ffffffff8144be70)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In lib/percpu_counter.c (ffffffff814784f7)
Location: include/linux/percpu_counter.h:62
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81840ff0)
Location: include/linux/percpu_counter.h:62
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
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
In mm/shmem.c (ffffffff811d6d6a)
Location: include/linux/percpu_counter.h:63
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/ext4/inode.c (ffffffff813040f4)
Location: include/linux/percpu_counter.h:63
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/sysfs.c (ffffffff813395c4)
Location: include/linux/percpu_counter.h:63
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff81481837)
Location: include/linux/percpu_counter.h:63
Inline: True
```
```
In lib/flex_proportions.c (ffffffff818ec620)
Location: include/linux/percpu_counter.h:63
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff811ec28a)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/ext4/inode.c (ffffffff81328aef)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/sysfs.c (ffffffff8135d93a)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff814bd677)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff819725f0)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8120d8d0)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/ext4/inode.c (ffffffff81356737)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/sysfs.c (ffffffff8138c166)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff814efedc)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff819cea20)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81220480)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/ext4/inode.c (ffffffff8136ea5d)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/sysfs.c (ffffffff813a4d8c)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff81503dfc)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a07ee0)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8122fc40)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/ext4/inode.c (ffffffff81397528)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff813cf150)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff81531f6c)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a77830)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8123de30)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff81367165)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff813aff5b)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff813e8820)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff81552c9f)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81aaec20)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8126b210)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff813aeac5)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff813f5525)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
```
```
In fs/ext4/sysfs.c (ffffffff81435129)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff815dc082)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff815e8980)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81275bb0)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/io_uring.c (ffffffff81389ec3)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/io_uring.c:tctx_inflight
  - fs/io_uring.c:tctx_inflight
```
```
In fs/quota/dquot.c (ffffffff813c00b5)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff81407cc5)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
```
```
In fs/ext4/sysfs.c (ffffffff8144dac0)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff815f9d22)
Location: include/linux/percpu_counter.h:65
Inline: True
```
```
In lib/flex_proportions.c (ffffffff8160da30)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8127aeec)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/io_uring.c (ffffffff813a1dd4)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_uring_cancel_sqpoll
  - fs/io_uring.c:io_uring_cancel_sqpoll
```
```
In fs/quota/dquot.c (ffffffff813c6e95)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff81414852)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff81453582)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff815dc8ff)
Location: include/linux/percpu_counter.h:65
Inline: True
```
```
In lib/flex_proportions.c (ffffffff815f1170)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff812b8d9c)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/io_uring.c (ffffffff81cc5e1b)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_uring_cancel_generic
```
```
In fs/quota/dquot.c (ffffffff81417180)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff81467c08)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff814a7588)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff8164823f)
Location: include/linux/percpu_counter.h:65
Inline: True
```
```
In lib/flex_proportions.c (ffffffff8165e2d4)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81314b56)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff8148f1b2)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff814e78ce)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff8152edb7)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In io_uring/io_uring.c (ffffffff81e92a87)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
```
```
In lib/percpu_counter.c (ffffffff8175e55b)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
```
```
In lib/flex_proportions.c (ffffffff81777a02)
Location: include/linux/percpu_counter.h:65
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In kernel/fork.c (ffffffff810e56b3)
Location: include/linux/percpu_counter.h:84
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In mm/shmem.c (ffffffff81388a26)
Location: include/linux/percpu_counter.h:84
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff81522d42)
Location: include/linux/percpu_counter.h:84
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff81581c5e)
Location: include/linux/percpu_counter.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff815cd24e)
Location: include/linux/percpu_counter.h:84
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In ipc/msg.c (ffffffff8163e4b3)
Location: include/linux/percpu_counter.h:84
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81792692)
Location: include/linux/percpu_counter.h:84
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
```
```
In lib/percpu_counter.c (ffffffff8188bd2b)
Location: include/linux/percpu_counter.h:84
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
```
```
In lib/flex_proportions.c (ffffffff8202068d)
Location: include/linux/percpu_counter.h:84
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In kernel/fork.c (ffffffff810f0d66)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/bpf/hashtab.c (ffffffff81326afe)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_mem_usage
```
```
In mm/shmem.c (ffffffff813bac56)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff8155aeb6)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff815b884e)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff816049b8)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In ipc/msg.c (ffffffff81676a13)
Location: include/linux/percpu_counter.h:83
Inline: True
```
```
In io_uring/io_uring.c (ffffffff817d3348)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
```
```
In lib/percpu_counter.c (ffffffff818ce30b)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
```
```
In lib/flex_proportions.c (ffffffff820a06cd)
Location: include/linux/percpu_counter.h:83
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In kernel/fork.c (ffffffff810fa156)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/bpf/hashtab.c (ffffffff8134b14e)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_mem_usage
```
```
In mm/shmem.c (ffffffff813e543a)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff81591676)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff815f15db)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff8163d678)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In ipc/msg.c (ffffffff816b2dd3)
Location: include/linux/percpu_counter.h:103
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81817158)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
```
```
In lib/percpu_counter.c (ffffffff8191ff3b)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
```
```
In lib/flex_proportions.c (ffffffff821786ad)
Location: include/linux/percpu_counter.h:103
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffff8000102cf958)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffff80001042e7cc)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffff800010484a3c)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffff8000104c1490)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffff80001065eedc)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffff800010d88324)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (c04f9200)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (c05f8658)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (c06462f4)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (c0685000)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (c0808530)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (c0e83020)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (c00000000038d6ac)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (c000000000540958)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (c0000000005aa6ac)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/sysfs.c (c0000000005f7ee0)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (c0000000008116b8)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (c000000000ec87d0)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffe0001ed106)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffe0002cb1de)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffe00030cd9c)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffe00033c980)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffe00048c4ea)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffe0008b2320)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81236480)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff8135f745)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff813a853b)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff813e0e00)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff8154b27f)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a4da70)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff812294e0)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff813503e5)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff81398fcb)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff813d1880)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff8153b55f)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a0ab73)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81234220)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff8135d215)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff813a5d9b)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff813de180)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff81546fbf)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81ab9e60)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81243940)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_statfs
```
```
In fs/quota/dquot.c (ffffffff81370db5)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/inode.c (ffffffff813ba514)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/sysfs.c (ffffffff813f35a0)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In lib/percpu_counter.c (ffffffff81560eaf)
Location: include/linux/percpu_counter.h:64
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81ac62b0)
Location: include/linux/percpu_counter.h:64
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
</details>
</li>
</ul>

## Differences
