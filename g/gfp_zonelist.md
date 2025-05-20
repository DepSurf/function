# Function: <code>gfp_zonelist</code>

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
In arch/x86/events/intel/pt.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In drivers/iommu/dmar.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/gfp.h:385
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/gfp.h:385
Inline: True
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
In arch/x86/events/intel/pt.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034051)
Location: include/linux/gfp.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/fork.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ab3d4)
Location: include/linux/gfp.h:395
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ec2cd)
Location: include/linux/gfp.h:395
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f906f)
Location: include/linux/gfp.h:395
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff811fe4b6)
Location: include/linux/gfp.h:395
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:policy_zonelist
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In mm/slub.c (ffffffff81206aaf)
Location: include/linux/gfp.h:395
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In mm/khugepaged.c (ffffffff812194e5)
Location: include/linux/gfp.h:395
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In mm/memory-failure.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In drivers/iommu/dmar.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/gfp.h:395
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/gfp.h:395
Inline: True
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
In arch/x86/events/intel/pt.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81033c81)
Location: include/linux/gfp.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/profile.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bb9ae)
Location: include/linux/gfp.h:388
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fd56d)
Location: include/linux/gfp.h:388
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/hugetlb.c (ffffffff81209c5f)
Location: include/linux/gfp.h:388
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff8120f156)
Location: include/linux/gfp.h:388
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:policy_zonelist
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In mm/slub.c (ffffffff8121887f)
Location: include/linux/gfp.h:388
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In mm/khugepaged.c (ffffffff8122ba65)
Location: include/linux/gfp.h:388
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In mm/memory-failure.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In drivers/iommu/dmar.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/gfp.h:388
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/gfp.h:388
Inline: True
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
In mm/page_alloc.c (ffffffff811c39ea)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (0)
Location: include/linux/gfp.h:434
Inline: True
```
```
In mm/hugetlb.c (ffffffff81214416)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:434
Inline: True
```
```
In mm/slub.c (ffffffff812279be)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (0)
Location: include/linux/gfp.h:434
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:434
Inline: True
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
In mm/page_alloc.c (ffffffff811d8785)
Location: include/linux/gfp.h:419
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (0)
Location: include/linux/gfp.h:419
Inline: True
```
```
In mm/hugetlb.c (ffffffff8122efd6)
Location: include/linux/gfp.h:419
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:419
Inline: True
```
```
In mm/slub.c (ffffffff81243b11)
Location: include/linux/gfp.h:419
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:419
Inline: True
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
In mm/page_alloc.c (ffffffff811f9965)
Location: include/linux/gfp.h:419
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (0)
Location: include/linux/gfp.h:419
Inline: True
```
```
In mm/hugetlb.c (ffffffff8125252c)
Location: include/linux/gfp.h:419
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:419
Inline: True
```
```
In mm/slub.c (ffffffff81266381)
Location: include/linux/gfp.h:419
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:419
Inline: True
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
In mm/page_alloc.c (ffffffff8120bfb7)
Location: include/linux/gfp.h:436
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (0)
Location: include/linux/gfp.h:436
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126678c)
Location: include/linux/gfp.h:436
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:436
Inline: True
```
```
In mm/slub.c (ffffffff8127b0bc)
Location: include/linux/gfp.h:436
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:436
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:436
Inline: True
```
```
In mm/page_alloc.c (ffffffff812721d9)
Location: include/linux/gfp.h:436
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81281a70)
Location: include/linux/gfp.h:436
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:436
Inline: True
```
```
In mm/slub.c (ffffffff81296aff)
Location: include/linux/gfp.h:436
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:436
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/page_alloc.c (ffffffff81281039)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81291483)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/slub.c (ffffffff812a68c2)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:466
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b4145)
Location: include/linux/gfp.h:466
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff812c35b5)
Location: include/linux/gfp.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:466
Inline: True
```
```
In mm/slub.c (ffffffff812daff5)
Location: include/linux/gfp.h:466
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:466
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:468
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bfbc5)
Location: include/linux/gfp.h:468
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff812cf535)
Location: include/linux/gfp.h:468
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:468
Inline: True
```
```
In mm/slub.c (ffffffff812e78e5)
Location: include/linux/gfp.h:468
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:468
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:482
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c5325)
Location: include/linux/gfp.h:482
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff812d6715)
Location: include/linux/gfp.h:482
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:482
Inline: True
```
```
In mm/slub.c (ffffffff812ef055)
Location: include/linux/gfp.h:482
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:482
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:494
Inline: True
```
```
In mm/page_alloc.c (ffffffff81309885)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff8131c4a5)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:494
Inline: True
```
```
In mm/slub.c (ffffffff81337365)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:494
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:511
Inline: True
```
```
In mm/page_alloc.c (ffffffff813720e5)
Location: include/linux/gfp.h:511
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff81387625)
Location: include/linux/gfp.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:511
Inline: True
```
```
In mm/slub.c (ffffffff813a8c65)
Location: include/linux/gfp.h:511
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:511
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:147
Inline: True
```
```
In mm/page_alloc.c (ffffffff813ef915)
Location: include/linux/gfp.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff81405a55)
Location: include/linux/gfp.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:147
Inline: True
```
```
In mm/slub.c (ffffffff81429d35)
Location: include/linux/gfp.h:147
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:147
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:147
Inline: True
```
```
In mm/page_alloc.c (ffffffff81423485)
Location: include/linux/gfp.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff81438f95)
Location: include/linux/gfp.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:147
Inline: True
```
```
In mm/slub.c (ffffffff8145f115)
Location: include/linux/gfp.h:147
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:147
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:148
Inline: True
```
```
In mm/page_alloc.c (ffffffff814503b5)
Location: include/linux/gfp.h:148
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/slub.c (ffffffff8145a283)
Location: include/linux/gfp.h:148
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472ac5)
Location: include/linux/gfp.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:148
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:148
Inline: True
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
In mm/page_alloc.c (ffff800010318cf4)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffff80001032e5ec)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/slub.c (ffff800010347bcc)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
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
In mm/page_alloc.c (c0000000003eb678)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (c000000000407610)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/slub.c (c000000000425ed4)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
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
In mm/page_alloc.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/page_alloc.c (ffffffff81279689)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81289a63)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/slub.c (ffffffff8129eea2)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126b579)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff8127b893)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/slub.c (ffffffff812909e2)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/page_alloc.c (ffffffff81277429)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81287873)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/slub.c (ffffffff8129ccb2)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/page_alloc.c (ffffffff81287019)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81297e14)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
```
In mm/slub.c (ffffffff812acd19)
Location: include/linux/gfp.h:459
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:459
Inline: True
```
</details>
</li>
</ul>

## Differences
