# Function: <code>percpu_ref_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff813feec0)
Location: lib/percpu-refcount.c:58
Inline: False
Direct callers:
  - kernel/cgroup.c:create_css
  - kernel/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
**Symbols:**

```
ffffffff813feec0-ffffffff813fef40: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814465b0)
Location: lib/percpu-refcount.c:58
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
**Symbols:**

```
ffffffff814465b0-ffffffff81446630: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81464da0)
Location: lib/percpu-refcount.c:59
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
**Symbols:**

```
ffffffff81464da0-ffffffff81464e28: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81469de0)
Location: lib/percpu-refcount.c:59
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
**Symbols:**

```
ffffffff81469de0-ffffffff81469e68: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814960b0)
Location: lib/percpu-refcount.c:59
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/hmm.c:hmm_devmem_add
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
**Symbols:**

```
ffffffff814960b0-ffffffff81496138: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814cb330)
Location: lib/percpu-refcount.c:59
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/hmm.c:hmm_devmem_add
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
**Symbols:**

```
ffffffff814cb330-ffffffff814cb3b8: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814e0060)
Location: lib/percpu-refcount.c:59
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - mm/backing-dev.c:wb_get_create
  - mm/hmm.c:hmm_devmem_add
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff814e0060-ffffffff814e00e8: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8150bfa0)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - mm/memremap.c:devm_memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8150bfa0-ffffffff8150c047: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81529df0)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81529df0-ffffffff81529e97: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8158d6e0)
Location: lib/percpu-refcount.c:61
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:cgwb_create
  - mm/slab_common.c:create_cache
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:alloc_fixed_file_ref_node
  - fs/io_uring.c:io_ring_ctx_alloc
  - block/blk-core.c:__blk_alloc_queue
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8158d6e0-ffffffff8158d78a: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815aa1e0)
Location: lib/percpu-refcount.c:62
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:cgwb_create
  - mm/memcontrol.c:memcg_online_kmem
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:alloc_fixed_file_ref_node
  - fs/io_uring.c:io_ring_ctx_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff815aa1e0-ffffffff815aa2d7: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815b4de0)
Location: lib/percpu-refcount.c:63
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:cgwb_create
  - mm/memcontrol.c:memcg_online_kmem
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff815b4de0-ffffffff815b4ed7: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8161b0a0)
Location: lib/percpu-refcount.c:63
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:cgwb_create
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:memcg_online_kmem
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8161b0a0-ffffffff8161b1e5: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff816e8850)
Location: lib/percpu-refcount.c:63
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:cgwb_create
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-cgroup.c:blkg_alloc
  - io_uring/io_uring.c:io_register_rsrc_update
  - io_uring/io_uring.c:io_sqe_buffers_register
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/md/md.c:mddev_init_writes_pending
```
**Symbols:**

```
ffffffff816e8850-ffffffff816e89a0: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff817d8870)
Location: lib/percpu-refcount.c:63
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:cgwb_create
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-cgroup.c:blkg_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/rsrc.c:io_register_rsrc_update
  - drivers/md/md.c:mddev_init_writes_pending
```
**Symbols:**

```
ffffffff817d8870-ffffffff817d89c3: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81817a70)
Location: lib/percpu-refcount.c:63
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:cgwb_create
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-cgroup.c:blkg_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_init_writes_pending
```
**Symbols:**

```
ffffffff81817a70-ffffffff81817bcb: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8185cd50)
Location: lib/percpu-refcount.c:63
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:cgwb_create
  - mm/swapfile.c:alloc_swap_info
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-cgroup.c:blkg_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
```
**Symbols:**

```
ffffffff8185cd50-ffffffff8185cec7: percpu_ref_init (STB_GLOBAL)
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
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffff800010634d68)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffff800010634d68-ffff800010634e14: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c07dae04)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
c07dae04-c07daea8: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c0000000007da4a0)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
c0000000007da4a0-c0000000007da598: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffe0004628da)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffe0004628da-ffffffe00046296e: percpu_ref_init (STB_GLOBAL)
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
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815223d0)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff815223d0-ffffffff81522477: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815126c0)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff815126c0-ffffffff81512767: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8151e460)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8151e460-ffffffff8151e507: percpu_ref_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref *ref, percpu_ref_func_t *release, unsigned int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81537cd0)
Location: lib/percpu-refcount.c:60
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - mm/backing-dev.c:wb_get_create
  - mm/slab_common.c:create_cache
  - mm/memremap.c:memremap_pages
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81537cd0-ffffffff81537d77: percpu_ref_init (STB_GLOBAL)
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
