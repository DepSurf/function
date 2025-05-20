# Function: <code>wake_up_var</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d9ab0)
Location: kernel/sched/wait_bit.c:189
Inline: False
```
**Symbols:**

```
ffffffff810d9ab0-ffffffff810d9ae6: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810e35b0)
Location: kernel/sched/wait_bit.c:189
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffff810e35b0-ffffffff810e35e6: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ea1c0)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffff810ea1c0-ffffffff810ea1f6: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f5b90)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffff810f5b90-ffffffff810f5bc6: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ff280)
Location: kernel/sched/wait_bit.c:191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - mm/memremap.c:free_devmap_managed_page
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffff810ff280-ffffffff810ff30c: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810fdd80)
Location: kernel/sched/wait_bit.c:191
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - mm/memremap.c:free_devmap_managed_page
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffff810fdd80-ffffffff810fde0c: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81100160)
Location: kernel/sched/wait_bit.c:191
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - mm/memremap.c:free_devmap_managed_page
  - fs/notify/mark.c:fsnotify_drop_object
  - security/landlock/fs.c:release_inode
```
**Symbols:**

```
ffffffff81100160-ffffffff811001ec: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff8111c200)
Location: kernel/sched/wait_bit.c:191
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_clear_sched
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - mm/memremap.c:free_devmap_managed_page
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - security/landlock/fs.c:release_inode
```
**Symbols:**

```
ffffffff8111c200-ffffffff8111c28c: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141c00)
Location: kernel/sched/wait_bit.c:191
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_clear_sched
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
  - security/landlock/fs.c:release_inode
```
**Symbols:**

```
ffffffff81141c00-ffffffff81141c9e: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116c8d0)
Location: kernel/sched/wait_bit.c:191
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_clear_sched
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
  - security/landlock/fs.c:release_inode
```
**Symbols:**

```
ffffffff8116c8d0-ffffffff8116c96e: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117cef0)
Location: kernel/sched/wait_bit.c:191
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_clear_sched
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
  - security/landlock/fs.c:release_inode
```
**Symbols:**

```
ffffffff8117cef0-ffffffff8117cf8e: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c580)
Location: kernel/sched/wait_bit.c:191
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_clear_sched
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:vfs_get_tree
  - fs/super.c:generic_shutdown_super
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
  - security/landlock/fs.c:release_inode
```
**Symbols:**

```
ffffffff8118c580-ffffffff8118c63e: wake_up_var (STB_GLOBAL)
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
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff8000101591c0)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffff8000101591c0-ffff800010159264: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c03a6528)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
c03a6528-c03a65cc: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0000000001ad6c0)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
c0000000001ad6c0-c0000000001ad708: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0000ff2a6)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffe0000ff2a6-ffffffe0000ff2f4: wake_up_var (STB_GLOBAL)
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
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810eef90)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffff810eef90-ffffffff810eefc6: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810df010)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
  - drivers/nvdimm/pmem.c:pmem_pagemap_page_free
```
**Symbols:**

```
ffffffff810df010-ffffffff810df046: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ec0c0)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffff810ec0c0-ffffffff810ec0f6: wake_up_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wake_up_var(void *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f7110)
Location: kernel/sched/wait_bit.c:190
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_release_kernel
  - mm/shmem.c:shmem_unuse
  - fs/notify/mark.c:fsnotify_drop_object
```
**Symbols:**

```
ffffffff810f7110-ffffffff810f7146: wake_up_var (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
