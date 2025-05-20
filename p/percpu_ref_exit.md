# Function: <code>percpu_ref_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff813fef40)
Location: lib/percpu-refcount.c:99
Inline: False
Direct callers:
  - kernel/cgroup.c:create_css
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_get_create
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:disk_release
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:part_release
```
**Symbols:**

```
ffffffff813fef40-ffffffff813fef66: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81446630)
Location: lib/percpu-refcount.c:99
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
```
**Symbols:**

```
ffffffff81446630-ffffffff81446656: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81464e30)
Location: lib/percpu-refcount.c:101
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
```
**Symbols:**

```
ffffffff81464e30-ffffffff81464e83: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81469e70)
Location: lib/percpu-refcount.c:101
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff81469e70-ffffffff81469ea2: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81496140)
Location: lib/percpu-refcount.c:101
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/hmm.c:hmm_devmem_ref_exit
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff81496140-ffffffff81496172: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814cb3c0)
Location: lib/percpu-refcount.c:101
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/hmm.c:hmm_devmem_ref_exit
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff814cb3c0-ffffffff814cb3f1: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814e00f0)
Location: lib/percpu-refcount.c:101
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/hmm.c:hmm_devmem_ref_exit
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff814e00f0-ffffffff814e0121: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8150c050)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
  - mm/memremap.c:dev_pagemap_cleanup
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff8150c050-ffffffff8150c07d: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81529ea0)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - mm/memremap.c:dev_pagemap_cleanup
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff81529ea0-ffffffff81529ecd: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8158dccb)
Location: lib/percpu-refcount.c:106
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - mm/memremap.c:dev_pagemap_cleanup
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_file_put_work
  - fs/io_uring.c:io_sqe_files_unregister
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partitions/core.c:part_release
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff8158d790-ffffffff8158d7c0: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815aa130)
Location: lib/percpu-refcount.c:128
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/memcontrol.c:obj_cgroup_release
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_put_work
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_sqe_files_unregister
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff815aa130-ffffffff815aa186: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815b4d30)
Location: lib/percpu-refcount.c:129
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/memcontrol.c:obj_cgroup_release
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_rsrc_put_work
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff815b4d30-ffffffff815b4d86: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8161b7e0)
Location: lib/percpu-refcount.c:129
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:obj_cgroup_release
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_rsrc_put_work
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff8161b7e0-ffffffff8161b855: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff816e9020)
Location: lib/percpu-refcount.c:130
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:obj_cgroup_release
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-cgroup.c:blkg_free_workfn
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_rsrc_put_work
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff816e9020-ffffffff816e90e2: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff817d9110)
Location: lib/percpu-refcount.c:130
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:obj_cgroup_release
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_free_queue_rcu
  - block/blk-cgroup.c:blkg_free_workfn
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/rsrc.c:io_rsrc_put_work
  - drivers/md/md.c:md_free_disk
```
**Symbols:**

```
ffffffff817d9110-ffffffff817d91d2: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81818320)
Location: lib/percpu-refcount.c:130
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_free_rcu
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:obj_cgroup_release
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_free_queue_rcu
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_free_workfn
  - io_uring/io_uring.c:io_ring_ctx_free
  - drivers/md/md.c:md_free_disk
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81818320-ffffffff818183e2: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8185d620)
Location: lib/percpu-refcount.c:130
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_free_rcu
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:obj_cgroup_release
  - mm/memremap.c:memunmap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - block/blk-core.c:blk_free_queue_rcu
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_free_workfn
  - io_uring/io_uring.c:io_ring_ctx_free
  - drivers/md/md.c:md_free_disk
  - drivers/md/md.c:md_free_disk
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:mddev_alloc
  - drivers/md/md.c:mddev_alloc
  - drivers/md/md.c:mddev_init
```
**Symbols:**

```
ffffffff8185d620-ffffffff8185d6e2: percpu_ref_exit (STB_GLOBAL)
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
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffff800010634e18)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffff800010634e18-ffff800010634e5c: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c07daea8)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
c07daea8-c07daf18: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c0000000007da5a0)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - mm/memremap.c:dev_pagemap_cleanup
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
c0000000007da5a0-c0000000007da608: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffe00046296e)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffe00046296e-ffffffe00046299e: percpu_ref_exit (STB_GLOBAL)
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
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81522480)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - mm/memremap.c:dev_pagemap_cleanup
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff81522480-ffffffff815224ad: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81512770)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - mm/memremap.c:dev_pagemap_cleanup
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff81512770-ffffffff8151279d: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8151e510)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - mm/memremap.c:dev_pagemap_cleanup
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff8151e510-ffffffff8151e53d: percpu_ref_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81537d80)
Location: lib/percpu-refcount.c:105
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:destroy_memcg_params
  - mm/memremap.c:dev_pagemap_cleanup
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/aio.c:free_ioctx
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - drivers/md/md.c:md_free
```
**Symbols:**

```
ffffffff81537d80-ffffffff81537dad: percpu_ref_exit (STB_GLOBAL)
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
