# Function: <code>virt_to_folio</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132bccb)
Location: include/linux/mm.h:851
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff813a7ccb)
Location: include/linux/mm.h:851
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff813aec83)
Location: include/linux/mm.h:851
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
```
In mm/memcontrol.c (ffffffff813d344d)
Location: include/linux/mm.h:851
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff813e6c47)
Location: include/linux/mm.h:851
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
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
In mm/slab_common.c (ffffffff813a23ae)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff8142c3bb)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff8142f1d4)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
```
In mm/memcontrol.c (ffffffff81458e32)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff8146e821)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
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
In mm/slab_common.c (ffffffff813d5898)
Location: include/linux/mm.h:1207
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff8146196b)
Location: include/linux/mm.h:1207
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff81464edf)
Location: include/linux/mm.h:1207
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/memcontrol.c (ffffffff8148eac2)
Location: include/linux/mm.h:1207
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff814a2fb6)
Location: include/linux/mm.h:1207
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
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
In mm/slab_common.c (ffffffff813ff54e)
Location: include/linux/mm.h:1290
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff8145dc98)
Location: include/linux/mm.h:1290
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff81493b26)
Location: include/linux/mm.h:1290
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/memcontrol.c (ffffffff814be472)
Location: include/linux/mm.h:1290
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff814d3e4a)
Location: include/linux/mm.h:1290
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/jbd2/journal.c (ffffffff8165c990)
Location: include/linux/mm.h:1290
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In io_uring/io_uring.c (0)
Location: include/linux/mm.h:1290
Inline: False
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
