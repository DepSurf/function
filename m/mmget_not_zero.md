# Function: <code>mmget_not_zero</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a4a86)
Location: include/linux/sched.h:2835
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task
```
```
In fs/userfaultfd.c (ffffffff81282bd0)
Location: include/linux/sched.h:2835
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
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
In mm/oom_kill.c (ffffffff811b4c09)
Location: include/linux/sched.h:2949
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In fs/userfaultfd.c (ffffffff812966f0)
Location: include/linux/sched.h:2949
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
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
In kernel/events/uprobes.c (ffffffff811b1040)
Location: include/linux/sched/mm.h:80
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff811bc5ce)
Location: include/linux/sched/mm.h:80
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/swapfile.c (ffffffff8120fb10)
Location: include/linux/sched/mm.h:80
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff812a3e97)
Location: include/linux/sched/mm.h:80
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff812c6319)
Location: include/linux/sched/mm.h:80
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812cccb3)
Location: include/linux/sched/mm.h:80
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff815d3659)
Location: include/linux/sched/mm.h:80
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff811c4c20)
Location: include/linux/sched/mm.h:81
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff8122b3ef)
Location: include/linux/sched/mm.h:81
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff812c731a)
Location: include/linux/sched/mm.h:81
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff812ea1f9)
Location: include/linux/sched/mm.h:81
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812f1553)
Location: include/linux/sched/mm.h:81
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a354)
Location: include/linux/sched/mm.h:81
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff811e5179)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff8124c5fa)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff812f010b)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff813180a9)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8131d983)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff8167599d)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff811f5af6)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff81260b44)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff8130504b)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff8132efc9)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81334c73)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff81694c6f)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff8120d87d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff8127b729)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffffffff812c2e7d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (ffffffff81326d6e)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff81330cec)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81356a4b)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8135d46a)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff816cd61d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff8121aead)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff8128b209)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffffffff812d4d14)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (ffffffff81339afe)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff813446ed)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff8136f083)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81374eaa)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff816f145d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff81245827)
Location: include/linux/sched/mm.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/swapfile.c (ffffffff812be3df)
Location: include/linux/sched/mm.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff81373520)
Location: include/linux/sched/mm.h:100
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8137bf92)
Location: include/linux/sched/mm.h:100
Inline: True
```
```
In fs/io-wq.c (ffffffff8138a5d0)
Location: include/linux/sched/mm.h:100
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/proc/task_mmu.c (ffffffff813b6753)
Location: include/linux/sched/mm.h:100
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813bdb5a)
Location: include/linux/sched/mm.h:100
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel/svm.c (ffffffff817a974c)
Location: include/linux/sched/mm.h:100
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2841)
Location: include/linux/sched/mm.h:100
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068071)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/events/uprobes.c (ffffffff8124fe47)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/swapfile.c (ffffffff812c9ff9)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff813813d0)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8138cf23)
Location: include/linux/sched/mm.h:73
Inline: True
```
```
In fs/io-wq.c (ffffffff8139bd60)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/io-wq.c:io_impersonate_work
```
```
In fs/proc/task_mmu.c (ffffffff813c86b3)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813cf8aa)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5b22)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2561)
Location: include/linux/sched/mm.h:73
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685e1)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/events/uprobes.c (ffffffff81254727)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/swapfile.c (ffffffff812d0a70)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff81387d78)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff813cf6e9)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d6977)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel/svm.c (ffffffff81798e40)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895881)
Location: include/linux/sched/mm.h:73
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d77)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/events/uprobes.c (ffffffff81290157)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/oom_kill.c (ffffffff812a31ce)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/swapfile.c (ffffffff8131614b)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff813d5085)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff81420ac9)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814280a7)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff8182fb85)
Location: include/linux/sched/mm.h:73
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff819297f1)
Location: include/linux/sched/mm.h:73
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e7cd)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080fa5)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/events/uprobes.c (ffffffff812e5217)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/swapfile.c (ffffffff813812e0)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff8145d68b)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff814988fd)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8149df5a)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff81970d85)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f891)
Location: include/linux/sched/mm.h:103
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902ba)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a4a)
Location: include/linux/sched/mm.h:103
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8134ebc4)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813771ff)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
```
```
In mm/swapfile.c (ffffffff813ffb23)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff814ed1ab)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff8152cbbd)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81532c1a)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbe81)
Location: include/linux/sched/mm.h:103
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - drivers/iommu/iommu-sva.c:__mmget_not_zero
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931ce)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969ca)
Location: include/linux/sched/mm.h:135
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8137fd57)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813a9271)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
```
```
In mm/swapfile.c (ffffffff814329b3)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff815262ef)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff81564fed)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8156ae0a)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0a4)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a63e)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df3a)
Location: include/linux/sched/mm.h:135
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813a8fa2)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813dd0bc)
Location: include/linux/sched/mm.h:135
Inline: True
```
```
In mm/swapfile.c (ffffffff8146bdd3)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In fs/userfaultfd.c (ffffffff8155953a)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff8159c3ed)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815a37ea)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81274)
Location: include/linux/sched/mm.h:135
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
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
In kernel/events/uprobes.c (ffff8000102a6504)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffff8000103265dc)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffff80001037b0e4)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (ffff8000103f8904)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffff80001040630c)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffff80001043a5e8)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffff800010440550)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
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
In kernel/events/uprobes.c (c04d5670)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (c053dfb0)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (c0565c84)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (c05cc994)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (c05d5f00)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (c0600510)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (c0603bb4)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
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
In kernel/events/uprobes.c (c0000000003594a0)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (c0000000003fcc90)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (c00000000046e65c)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (c0000000004ffd44)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (c00000000050f1b0)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (c00000000054b5c4)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (c0000000005555d4)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
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
In mm/swapfile.c (ffffffe00022680c)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffffffe000251434)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (ffffffe0002a77c4)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffe0002afcda)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffe0002d2adc)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffe0002d7a8e)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
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
In kernel/events/uprobes.c (ffffffff812134fd)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff812837e9)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffffffff812cd2f4)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (ffffffff813320de)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8133cccd)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81367663)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8136d48a)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff816b6c4d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff8120626d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff812756a1)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffffffff812be164)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (ffffffff81322c9e)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8132d99d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81358303)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8135df1a)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff8169488d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff8121129d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff812815f9)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffffffff812cb104)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (ffffffff8132fbae)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8133a79d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81365133)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8136af5a)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff816e511d)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In kernel/events/uprobes.c (ffffffff812201ed)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/swapfile.c (ffffffff81291336)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (ffffffff812dbe64)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/userfaultfd.c (ffffffff8134252e)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8134d2f8)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/task_mmu.c (ffffffff81378813)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8137c5fa)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In drivers/iommu/intel-svm.c (ffffffff816ff7eb)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
</ul>

## Differences
