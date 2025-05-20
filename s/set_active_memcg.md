# Function: <code>set_active_memcg</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fdbf6)
Location: include/linux/sched/mm.h:312
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In mm/memcontrol.c (ffffffff81c3b365)
Location: include/linux/sched/mm.h:312
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/buffer.c (ffffffff81367a5c)
Location: include/linux/sched/mm.h:312
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81376083)
Location: include/linux/sched/mm.h:312
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81377bf1)
Location: include/linux/sched/mm.h:312
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In kernel/bpf/syscall.c (ffffffff811fe7b4)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In mm/memcontrol.c (ffffffff81c2db25)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/buffer.c (ffffffff8136e661)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8137ca23)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e6ab)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In kernel/bpf/syscall.c (ffffffff812303f4)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In mm/memcontrol.c (ffffffff81d4c415)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/buffer.c (ffffffff813bd8f4)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813c9923)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb78b)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In drivers/block/loop.c (ffffffff81870022)
Location: include/linux/sched/mm.h:305
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e825)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/bpf/syscall.c (ffffffff81272d77)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In mm/memcontrol.c (ffffffff81f1bf55)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/buffer.c (ffffffff814444f4)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814513a4)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453e19)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In drivers/block/loop.c (ffffffff819b7615)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fe65)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/bpf/syscall.c (ffffffff812c9186)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/memalloc.c (ffffffff8131bd53)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/memcontrol.c (ffffffff820c3f05)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/buffer.c (ffffffff814d3764)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814dfe94)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2cc9)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In drivers/block/loop.c (ffffffff81b2c915)
Location: include/linux/sched/mm.h:378
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092d7b)
Location: include/linux/sched/mm.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/bpf/syscall.c (ffffffff812f08a6)
Location: include/linux/sched/mm.h:410
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/memalloc.c (ffffffff8134c447)
Location: include/linux/sched/mm.h:410
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/memcontrol.c (ffffffff82147cb5)
Location: include/linux/sched/mm.h:410
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/buffer.c (ffffffff81509d30)
Location: include/linux/sched/mm.h:410
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8151671e)
Location: include/linux/sched/mm.h:410
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519577)
Location: include/linux/sched/mm.h:410
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In drivers/block/loop.c (ffffffff81b7cb3c)
Location: include/linux/sched/mm.h:410
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a1bb)
Location: include/linux/sched/mm.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/bpf/syscall.c (ffffffff8130f686)
Location: include/linux/sched/mm.h:414
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/memalloc.c (ffffffff813739cd)
Location: include/linux/sched/mm.h:414
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/memcontrol.c (ffffffff8222a5b5)
Location: include/linux/sched/mm.h:414
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/buffer.c (ffffffff8153eb51)
Location: include/linux/sched/mm.h:414
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8154ab0e)
Location: include/linux/sched/mm.h:414
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154d957)
Location: include/linux/sched/mm.h:414
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In drivers/block/loop.c (ffffffff81bd0a74)
Location: include/linux/sched/mm.h:414
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
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
