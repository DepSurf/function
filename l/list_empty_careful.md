# Function: <code>list_empty_careful</code>

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
In kernel/sched/wait.c (ffffffff810c3542)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In fs/open.c (ffffffff81209928)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:chmod_common
  - fs/open.c:chown_common
  - fs/open.c:do_dentry_open
```
```
In fs/namei.c (ffffffff8121885d)
Location: include/linux/list.h:205
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
In fs/attr.c (ffffffff81229715)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81240d17)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/userfaultfd.c (ffffffff8125ae84)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/locks.c (ffffffff8125fc26)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:fcntl_getlease
```
```
In security/selinux/hooks.c (ffffffff8134695a)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff813c482d)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
```
```
In drivers/leds/led-triggers.c (ffffffff816ce8d2)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810c6ec2)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810c7512)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In fs/open.c (ffffffff8122fe89)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81245f75)
Location: include/linux/list.h:205
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
In fs/attr.c (ffffffff81251d80)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8126907f)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/userfaultfd.c (ffffffff81283a52)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/locks.c (ffffffff8128e8eb)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff8137c11a)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff8140903a)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/leds/led-triggers.c (ffffffff81731932)
Location: include/linux/list.h:205
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810cced3)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810cd3e3)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In fs/open.c (ffffffff81242431)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81258ed3)
Location: include/linux/list.h:218
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
In fs/attr.c (ffffffff81265025)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8127c05f)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/userfaultfd.c (ffffffff81297641)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/locks.c (ffffffff812a3813)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff81392bea)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff814239f5)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_process_rq_list
```
```
In drivers/leds/led-triggers.c (ffffffff81764902)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810c97a3)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810c9de3)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff811d9fc8)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In fs/open.c (ffffffff8124d7ef)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8126509a)
Location: include/linux/list.h:218
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
In fs/attr.c (ffffffff81272847)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8128936f)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/userfaultfd.c (ffffffff812a4f2a)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/locks.c (ffffffff812b24bd)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff813a35af)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff81430b86)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_has_pending
```
```
In block/blk-mq-sched.c (ffffffff814356e9)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In drivers/leds/led-triggers.c (ffffffff81782fc2)
Location: include/linux/list.h:218
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810d0fe3)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810d1603)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff811efcf7)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In fs/open.c (ffffffff8126f852)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8128792d)
Location: include/linux/list.h:219
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
In fs/attr.c (ffffffff8129516a)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff812abe92)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/userfaultfd.c (ffffffff812c8336)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/locks.c (ffffffff812d601d)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff813c93af)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff8145b305)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814614b0)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In drivers/leds/led-triggers.c (ffffffff817f9382)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810d9683)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810d9c13)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff81210f3d)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In fs/open.c (ffffffff8129520f)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812acb0a)
Location: include/linux/list.h:219
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
In fs/attr.c (ffffffff812bb2db)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff812d2b4d)
Location: include/linux/list.h:219
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812f169a)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff812f41d5)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff81300dd0)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff813fd8f1)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff8148e70f)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff81495068)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In drivers/leds/led-triggers.c (ffffffff81842982)
Location: include/linux/list.h:219
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810e3183)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810e37a3)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff8122343b)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In fs/open.c (ffffffff812a9e83)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812c1c0a)
Location: include/linux/list.h:242
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
In fs/attr.c (ffffffff812d04d0)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff812e7f2d)
Location: include/linux/list.h:242
Inline: True
```
```
In fs/eventpoll.c (ffffffff8130067d)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff8130605a)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81308e75)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8131682c)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff814194f2)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff814a809c)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814af13b)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffffffff814c76e8)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff8186e992)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810e9c39)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810ea2d9)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff81233f5f)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In mm/hmm.c (ffffffff812c4022)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (ffffffff812c6633)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812de13d)
Location: include/linux/list.h:284
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
In fs/attr.c (ffffffff812ed4f6)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8130683d)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (ffffffff8132194d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff813275f5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813296d5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8133e07d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff814470e2)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff814d6c12)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814dd3ad)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffffffff814f5f6e)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff818b2c45)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810f5609)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810f5ca9)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff8124215f)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In mm/hmm.c (ffffffff812d5025)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (ffffffff812d8043)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812efc5d)
Location: include/linux/list.h:284
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
In fs/attr.c (ffffffff812fef52)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff813198a3)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (ffffffff81333ead)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff8133a3d5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8133d605)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8135666d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff81460c72)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff814eff92)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814f681d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffffffff81513dfe)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff818e5565)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810fed49)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810ff489)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff8126f12e)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In fs/open.c (ffffffff8130e0e1)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81327f40)
Location: include/linux/list.h:298
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
In fs/attr.c (ffffffff81338052)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81343599)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff8135384d)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/eventpoll.c (ffffffff8136e69c)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff813744c3)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81377365)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff813890a8)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_cqring_overflow_flush
```
```
In fs/locks.c (ffffffff8139d7d1)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In fs/ext4/inode.c (ffffffff813fe44f)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In security/selinux/hooks.c (ffffffff814b5912)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff815502a2)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-sched.c (ffffffff815572ca)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
```
In block/mq-deadline.c (ffffffff81574e1e)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff819b8835)
Location: include/linux/list.h:298
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810fd649)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810fdf89)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff8127a278)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In fs/open.c (ffffffff8131a1f6)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81334a67)
Location: include/linux/list.h:316
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
In fs/attr.c (ffffffff813439bc)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8134f729)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff8136017d)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/eventpoll.c (ffffffff8137b8ed)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff81382445)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81385655)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff813971a3)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
```
```
In fs/locks.c (ffffffff813af192)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In fs/ext4/inode.c (ffffffff81410b86)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In security/selinux/hooks.c (ffffffff814d35f2)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff8156c734)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-sched.c (ffffffff81573956)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In block/mq-deadline.c (ffffffff81591bf4)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff819bac95)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810ffa29)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff81100369)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff8127f3cc)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In fs/open.c (ffffffff813202d6)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8133abf6)
Location: include/linux/list.h:316
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
In fs/attr.c (ffffffff81349d36)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81356231)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff81366c0f)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/eventpoll.c (ffffffff8138206d)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff813894cb)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8138c8c5)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8139a4f9)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
```
```
In fs/locks.c (ffffffff813b6452)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:posix_test_lock
```
```
In fs/ext4/inode.c (ffffffff81416f46)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In security/selinux/hooks.c (ffffffff814d9c2d)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff81574114)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-sched.c (ffffffff8157b9da)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In block/mq-deadline.c (ffffffff81598a38)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff8199f4b5)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff8111baf8)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff8111c3e8)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff812bd739)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In fs/open.c (ffffffff8136d889)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81388791)
Location: include/linux/list.h:316
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
In fs/attr.c (ffffffff81397c2e)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff813a4761)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff813b575f)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/eventpoll.c (ffffffff813cf2dd)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff813d6784)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813d9f15)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff813e9c44)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_drain_req
```
```
In fs/locks.c (ffffffff81406152)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:posix_test_lock
```
```
In fs/ext4/inode.c (ffffffff8146a308)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In security/selinux/hooks.c (ffffffff81532b2d)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff815d8624)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-sched.c (ffffffff815e0d68)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In block/mq-deadline.c (ffffffff816002a4)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff81a4c155)
Location: include/linux/list.h:316
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/build_utility.c (ffffffff8113beb8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:finish_wait
  - kernel/sched/build_utility.c:finish_swait
```
```
In mm/shmem.c (ffffffff81319142)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In fs/open.c (ffffffff813eb995)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8140978f)
Location: include/linux/list.h:326
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
In fs/attr.c (ffffffff81419c22)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81428780)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff8143aa41)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/eventpoll.c (ffffffff814580b0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff81460121)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81464405)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8147ab10)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:posix_test_lock
```
```
In fs/ext4/inode.c (ffffffff814ea271)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In security/selinux/hooks.c (ffffffff815c61ed)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff81684d59)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_hctx_has_pending
```
```
In block/blk-mq-sched.c (ffffffff8168f90d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In block/mq-deadline.c (ffffffff816b29d4)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In io_uring/io_uring.c (ffffffff81e917c5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_add_buffers
```
```
In drivers/leds/led-triggers.c (ffffffff81bba8a5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/build_utility.c (ffffffff811669d8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:finish_wait
  - kernel/sched/build_utility.c:finish_swait
```
```
In mm/shmem.c (ffffffff8138d3b1)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In fs/open.c (ffffffff81473d55)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81493e3f)
Location: include/linux/list.h:326
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
In fs/attr.c (ffffffff814a5c32)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814b5cb0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff814c8ef8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/eventpoll.c (ffffffff814e79e0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff814eff88)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff814f4745)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8150d640)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:posix_test_lock
```
```
In fs/posix_acl.c (ffffffff81515f81)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/ext4/inode.c (ffffffff81583c5a)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In security/selinux/hooks.c (ffffffff81672e6d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff81742839)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_hctx_has_pending
```
```
In block/blk-mq-sched.c (ffffffff8174e45d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In block/mq-deadline.c (ffffffff81771f54)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_finish_request
```
```
In io_uring/io_uring.c (ffffffff817905c3)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_drain_req
```
```
In io_uring/kbuf.c (ffffffff8179ec67)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In drivers/leds/led-triggers.c (ffffffff81d5fe45)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/build_utility.c (ffffffff81176e48)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:finish_wait
  - kernel/sched/build_utility.c:finish_swait
```
```
In mm/shmem.c (ffffffff813bfb94)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In fs/open.c (ffffffff814a8554)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814c8ead)
Location: include/linux/list.h:326
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
In fs/attr.c (ffffffff814dac26)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814ea4fe)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff814ff132)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/eventpoll.c (ffffffff8151dc93)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff81526d65)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8152b515)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff81544e13)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:posix_test_lock
```
```
In fs/posix_acl.c (ffffffff8154d8f1)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/ext4/inode.c (ffffffff815ba5f3)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In security/selinux/hooks.c (ffffffff816ab30d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff8177df8c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_hctx_has_pending
```
```
In block/blk-mq-sched.c (ffffffff8178a99d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In block/mq-deadline.c (ffffffff817b1224)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_finish_request
```
```
In io_uring/io_uring.c (ffffffff817cf9b3)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_drain_req
```
```
In io_uring/kbuf.c (ffffffff817dfe57)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In drivers/leds/led-triggers.c (ffffffff81dcaf45)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/build_utility.c (ffffffff81184e08)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:finish_wait
  - kernel/sched/build_utility.c:finish_swait
```
```
In mm/shmem.c (ffffffff813eac14)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In fs/open.c (ffffffff814d9634)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814fb76b)
Location: include/linux/list.h:407
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
In fs/attr.c (ffffffff8150d1d8)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8151e39e)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:__vfs_setxattr_locked
```
```
In fs/utimes.c (ffffffff81533d62)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/eventpoll.c (ffffffff81552273)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff8155bad0)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff815603e5)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8157a303)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:posix_test_lock
```
```
In fs/posix_acl.c (ffffffff81583721)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/ext4/inode.c (ffffffff815f3363)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In security/selinux/hooks.c (ffffffff816e839d)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff817c05f9)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_hctx_has_pending
```
```
In block/blk-mq-sched.c (ffffffff817cd0ed)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In block/mq-deadline.c (ffffffff817f5034)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_finish_request
```
```
In io_uring/io_uring.c (ffffffff81812ae3)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_drain_req
```
```
In io_uring/kbuf.c (ffffffff818242a2)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_refill_buffer_cache
```
```
In drivers/leds/led-triggers.c (ffffffff81e83ab5)
Location: include/linux/list.h:407
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffff800010158c7c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffff80001015980c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffff8000102d45fc)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In mm/hmm.c (ffff80001037a3ac)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (ffff80001037db90)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffff8000103993b8)
Location: include/linux/list.h:284
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
In fs/attr.c (ffff8000103b0414)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffff8000103d0860)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (ffff8000103f2668)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffff8000103f955c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffff8000103fd324)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffff80001041913c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffff80001054e79c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffff8000105eeea0)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffff8000105f6e2c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffff80001061876c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffff800010b4ab40)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (c03a5d54)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (c03a66f4)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (0)
Location: include/linux/list.h:284
Inline: True
```
```
In mm/hmm.c (c05657c4)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (c0567628)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (c057fa30)
Location: include/linux/list.h:284
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
In fs/attr.c (c058fcc8)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (c05abbfc)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/eventpoll.c (c05c64f4)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (c05cd408)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c05cfe64)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (c05e5114)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (c06fe334)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (c079b7d8)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (c07a25d4)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (c07c33fc)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (c0c33718)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (c0000000001acdd0)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (c0000000001ad840)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (c000000000393afc)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In mm/hmm.c (c00000000046eb78)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (c000000000472ad8)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (c000000000493bd0)
Location: include/linux/list.h:284
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
In fs/attr.c (c0000000004abc80)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (c0000000004d31ac)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (c0000000004f8204)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (c000000000501768)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c00000000050616c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (c000000000528b0c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (c0000000006ae860)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (c000000000785910)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (c00000000078f2f8)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (c0000000007b7a84)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (c000000000c3efd4)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffe0000febf4)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffe0000ff3ac)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (0)
Location: include/linux/list.h:284
Inline: True
```
```
In mm/hmm.c (ffffffe0002517fa)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (ffffffe00025381c)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffe000266e70)
Location: include/linux/list.h:284
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
In fs/attr.c (ffffffe0002747f8)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffe00028ca96)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (ffffffe0002a32bc)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffe0002a88b6)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffe0002aad14)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffe0002bf8e6)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffe0003a8298)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffe00042e2d8)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffe0004345ec)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffffffe00044e708)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffe00071d80e)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810eea09)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810ef0a9)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff8123a7af)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In mm/hmm.c (ffffffff812cd605)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (ffffffff812d0623)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812e823d)
Location: include/linux/list.h:284
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
In fs/attr.c (ffffffff812f7532)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81311e83)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (ffffffff8132c48d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff813329b5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81335be5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8134ec4d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff81459252)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff814e8572)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814eedfd)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffffffff8150c3de)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff818886f5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810dea99)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810df129)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff8122d7ad)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In mm/hmm.c (ffffffff812be475)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (ffffffff812c12a3)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812d8e7d)
Location: include/linux/list.h:284
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
In fs/attr.c (ffffffff812e8152)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81302a93)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (ffffffff8131bd7d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff8132362b)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81326575)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8133f92d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff81449c82)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff814d8ae2)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814df33d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffffffff814fc80e)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff81840075)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810ebb39)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810ec1d9)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff8123854f)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In mm/hmm.c (ffffffff812cb415)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (ffffffff812ce433)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812e604d)
Location: include/linux/list.h:284
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
In fs/attr.c (ffffffff812f5342)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff8130fc73)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (ffffffff81329f5d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff81330485)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813336b5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8134c71d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff814552f2)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff814e4602)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814eae8d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffffffff8150846e)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff818da3c5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
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
In kernel/sched/wait.c (ffffffff810f6b99)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810f7229)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
```
```
In mm/shmem.c (ffffffff81247b92)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
```
```
In mm/hmm.c (ffffffff812dc175)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_release
```
```
In fs/open.c (ffffffff812df243)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812f6fcd)
Location: include/linux/list.h:284
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
In fs/attr.c (ffffffff813064d2)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/utimes.c (ffffffff81321473)
Location: include/linux/list.h:284
Inline: True
```
```
In fs/eventpoll.c (ffffffff8133aa3d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In fs/userfaultfd.c (ffffffff81342ddc)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813479c5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8135fc1d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In security/selinux/hooks.c (ffffffff81467882)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In block/blk-mq.c (ffffffff814fca59)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff81503e6d)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/mq-deadline.c (ffffffff81521b0e)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
  - block/mq-deadline.c:dd_has_work
```
```
In drivers/leds/led-triggers.c (ffffffff818f6ee5)
Location: include/linux/list.h:284
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
</details>
</li>
</ul>

## Differences
