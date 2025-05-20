# Function: <code>mmap_read_trylock</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087970)
Location: include/linux/mmap_lock.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff810e99c8)
Location: include/linux/mmap_lock.h:54
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/oom_kill.c (ffffffff812571b5)
Location: include/linux/mmap_lock.h:54
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812955bc)
Location: include/linux/mmap_lock.h:54
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
```
```
In mm/mmap.c (ffffffff8129d465)
Location: include/linux/mmap_lock.h:54
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/khugepaged.c (ffffffff812f39db)
Location: include/linux/mmap_lock.h:54
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812f9f21)
Location: include/linux/mmap_lock.h:54
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2882)
Location: include/linux/mmap_lock.h:54
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
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
In arch/x86/mm/fault.c (ffffffff810880cc)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff810e77f7)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/bpf/stackmap.c (ffffffff81233521)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/oom_kill.c (ffffffff81261da0)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812a045c)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
```
```
In mm/mmap.c (ffffffff812a8865)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/khugepaged.c (ffffffff812ff1e1)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff813053cb)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b259a)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
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
In arch/x86/mm/fault.c (ffffffff81088b97)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff810e96c7)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/bpf/stackmap.c (ffffffff812372e1)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/oom_kill.c (ffffffff812668e4)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff812a5d9c)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
```
```
In mm/mmap.c (ffffffff812add15)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/khugepaged.c (ffffffff81305e61)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8130acab)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818958ba)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
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
In arch/x86/mm/fault.c (ffffffff81097fd0)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff81100f57)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/bpf/stackmap.c (ffffffff812718c1)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/oom_kill.c (ffffffff812a2eb4)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff812e722c)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mmap.c (ffffffff812ef485)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/khugepaged.c (ffffffff8134fcc1)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff813533cb)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192982a)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
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
In arch/x86/mm/fault.c (ffffffff810aac0d)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff8111c683)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/bpf/task_iter.c (ffffffff8129a52e)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/stackmap.c (ffffffff812c09fb)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/oom_kill.c (ffffffff812face9)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff813484bc)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/khugepaged.c (ffffffff813c7ee0)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff813cdefb)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f8c4)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
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
In arch/x86/mm/fault.c (ffffffff810c48fd)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff811441e5)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/bpf/task_iter.c (ffffffff812f66ae)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/stackmap.c (ffffffff8132429a)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/oom_kill.c (ffffffff8136381b)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81379720)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/memory.c (ffffffff813c096c)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/khugepaged.c (ffffffff8144c0e4)
Location: include/linux/mmap_lock.h:131
Inline: True
```
```
In mm/memcontrol.c (ffffffff81452fdb)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
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
In kernel/sched/fair.c (ffffffff8115482b)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/bpf/task_iter.c (ffffffff8132457e)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/stackmap.c (ffffffff813544da)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/oom_kill.c (ffffffff81395cee)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813ae116)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/memory.c (ffffffff813f56ec)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/khugepaged.c (ffffffff81481904)
Location: include/linux/mmap_lock.h:162
Inline: True
```
```
In mm/memcontrol.c (ffffffff81488c2b)
Location: include/linux/mmap_lock.h:162
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
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
In kernel/sched/fair.c (ffffffff8116967d)
Location: include/linux/mmap_lock.h:160
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/bpf/task_iter.c (ffffffff813497d9)
Location: include/linux/mmap_lock.h:160
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/stackmap.c (ffffffff8137ce4a)
Location: include/linux/mmap_lock.h:160
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/oom_kill.c (ffffffff813bfaae)
Location: include/linux/mmap_lock.h:160
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813d7746)
Location: include/linux/mmap_lock.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/memory.c (ffffffff8141f3cc)
Location: include/linux/mmap_lock.h:160
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/khugepaged.c (ffffffff814b0d00)
Location: include/linux/mmap_lock.h:160
Inline: True
```
```
In mm/memcontrol.c (ffffffff814b82ab)
Location: include/linux/mmap_lock.h:160
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
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
