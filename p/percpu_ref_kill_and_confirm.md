# Function: <code>percpu_ref_kill_and_confirm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff813ff310)
Location: lib/percpu-refcount.c:299
Inline: False
Direct callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_release_root
  - mm/backing-dev.c:cgwb_kill
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff813ff310-ffffffff813ff399: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814469f0)
Location: lib/percpu-refcount.c:299
Inline: False
Direct callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_kill_sb
  - mm/backing-dev.c:cgwb_kill
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814469f0-ffffffff81446a71: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814651d0)
Location: lib/percpu-refcount.c:309
Inline: False
Direct callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_kill_sb
  - mm/backing-dev.c:cgwb_kill
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814651d0-ffffffff81465275: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8146a2d0)
Location: lib/percpu-refcount.c:326
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - mm/backing-dev.c:cgwb_kill
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff8146a2d0-ffffffff8146a369: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814965c0)
Location: lib/percpu-refcount.c:326
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - mm/backing-dev.c:cgwb_kill
  - mm/hmm.c:hmm_devmem_ref_kill
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814965c0-ffffffff81496661: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814cb820)
Location: lib/percpu-refcount.c:328
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - mm/backing-dev.c:cgwb_kill
  - mm/hmm.c:hmm_devmem_ref_kill
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814cb820-ffffffff814cb8c1: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814e0570)
Location: lib/percpu-refcount.c:328
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - mm/backing-dev.c:cgwb_kill
  - mm/hmm.c:hmm_devmem_ref_kill
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff814e0570-ffffffff814e0611: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8150c510)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff8150c510-ffffffff8150c5b9: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8152a360)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff8152a360-ffffffff8152a409: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8158db40)
Location: lib/percpu-refcount.c:339
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_sqe_files_unregister
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partitions/core.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff8158db40-ffffffff8158dbe8: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815aa820)
Location: lib/percpu-refcount.c:375
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_sqe_files_unregister
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff815aa820-ffffffff815aa8d5: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815b5440)
Location: lib/percpu-refcount.c:381
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_rsrc_node_switch
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff815b5440-ffffffff815b54f5: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/percpu-refcount.c (0)
Location: lib/percpu-refcount.c:381
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/swapfile.c:__do_sys_swapoff
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff81cdaa8b-ffffffff81cdaa9f: percpu_ref_kill_and_confirm.cold (STB_LOCAL)
ffffffff8161b860-ffffffff8161b925: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/percpu-refcount.c (0)
Location: lib/percpu-refcount.c:382
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/swapfile.c:__do_sys_swapoff
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/blk-cgroup.c:blkg_destroy
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81e9335a-ffffffff81e9336f: percpu_ref_kill_and_confirm.cold (STB_LOCAL)
ffffffff816e90f0-ffffffff816e91c6: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/percpu-refcount.c (0)
Location: lib/percpu-refcount.c:383
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/swapfile.c:__do_sys_swapoff
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/blk-cgroup.c:blkg_destroy
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff820784c6-ffffffff820784db: percpu_ref_kill_and_confirm.cold (STB_LOCAL)
ffffffff817d91f0-ffffffff817d92c6: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/percpu-refcount.c (0)
Location: lib/percpu-refcount.c:383
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/swapfile.c:__do_sys_swapoff
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/blk-cgroup.c:blkg_destroy
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff820f8a22-ffffffff820f8a37: percpu_ref_kill_and_confirm.cold (STB_LOCAL)
ffffffff81818400-ffffffff818184d2: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/percpu-refcount.c (0)
Location: lib/percpu-refcount.c:383
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/swapfile.c:__do_sys_swapoff
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - block/blk-cgroup.c:blkg_destroy
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - drivers/md/md.c:mddev_suspend
  - drivers/md/md.c:mddev_suspend
```
**Symbols:**

```
ffffffff821d6543-ffffffff821d6558: percpu_ref_kill_and_confirm.cold (STB_LOCAL)
ffffffff8185d700-ffffffff8185d7d2: percpu_ref_kill_and_confirm (STB_GLOBAL)
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
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffff800010635470)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffff800010635470-ffff8000106355d8: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c07db5c8)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
c07db5c8-c07db6dc: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c0000000007daeb0)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
c0000000007daeb0-c0000000007db00c: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffe000462ece)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffe000462ece-ffffffe000462fa2: percpu_ref_kill_and_confirm (STB_GLOBAL)
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
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81522940)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff81522940-ffffffff815229e9: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81512c20)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff81512c20-ffffffff81512cc9: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8151e9d0)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff8151e9d0-ffffffff8151ea79: percpu_ref_kill_and_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref *ref, percpu_ref_func_t *confirm_kill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81538290)
Location: lib/percpu-refcount.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
  - mm/backing-dev.c:cgwb_kill
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-mq.c:blk_freeze_queue_start
  - block/partition-generic.c:delete_partition
  - block/blk-cgroup.c:blkg_destroy
```
**Symbols:**

```
ffffffff81538290-ffffffff81538350: percpu_ref_kill_and_confirm (STB_GLOBAL)
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
