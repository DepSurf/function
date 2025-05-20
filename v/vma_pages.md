# Function: <code>vma_pages</code>

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
In kernel/fork.c (ffffffff8107f9f2)
Location: include/linux/mm.h:2062
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2062
Inline: True
```
```
In mm/mmap.c (ffffffff811c6724)
Location: include/linux/mm.h:2062
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
```
In mm/mempolicy.c (ffffffff811e2e0f)
Location: include/linux/mm.h:2062
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143c730)
Location: include/linux/mm.h:2062
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
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
In kernel/fork.c (ffffffff81080e51)
Location: include/linux/mm.h:2184
Inline: True
```
```
In mm/memory.c (ffffffff811db6b2)
Location: include/linux/mm.h:2184
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_mapping_range
```
```
In mm/mmap.c (ffffffff811e2632)
Location: include/linux/mm.h:2184
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8120184f)
Location: include/linux/mm.h:2184
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In drivers/pci/pci-sysfs.c (ffffffff814886a5)
Location: include/linux/mm.h:2184
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815f9bc7)
Location: include/linux/mm.h:2184
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff81085858)
Location: include/linux/mm.h:2170
Inline: True
```
```
In mm/memory.c (ffffffff811eb1b2)
Location: include/linux/mm.h:2170
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_mapping_range
```
```
In mm/mmap.c (ffffffff811f2602)
Location: include/linux/mm.h:2170
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8121333f)
Location: include/linux/mm.h:2170
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a9e85)
Location: include/linux/mm.h:2170
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/base/dma-mapping.c (ffffffff815e0e12)
Location: include/linux/mm.h:2170
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81627d37)
Location: include/linux/mm.h:2170
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff81082eb8)
Location: include/linux/mm.h:2273
Inline: True
```
```
In mm/memory.c (ffffffff811f628b)
Location: include/linux/mm.h:2273
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_mapping_range
```
```
In mm/mmap.c (ffffffff811fd5a2)
Location: include/linux/mm.h:2273
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8121e65f)
Location: include/linux/mm.h:2273
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b4232)
Location: include/linux/mm.h:2273
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff814b9031)
Location: include/linux/mm.h:2273
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/base/dma-mapping.c (ffffffff815f5c82)
Location: include/linux/mm.h:2273
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163d867)
Location: include/linux/mm.h:2273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff81088f9b)
Location: include/linux/mm.h:2382
Inline: True
```
```
In mm/memory.c (ffffffff8120de8a)
Location: include/linux/mm.h:2382
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:unmap_mapping_range
```
```
In mm/mmap.c (ffffffff81215b42)
Location: include/linux/mm.h:2382
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8123987f)
Location: include/linux/mm.h:2382
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f3a42)
Location: include/linux/mm.h:2382
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff814f9481)
Location: include/linux/mm.h:2382
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/base/dma-mapping.c (ffffffff8165dba2)
Location: include/linux/mm.h:2382
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a65c4)
Location: include/linux/mm.h:2382
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff8108b91b)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:copy_mm
```
```
In kernel/dma/mapping.c (ffffffff8110c5db)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff81224564)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff8122ea0d)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:unmap_mapping_pages
```
```
In mm/mmap.c (ffffffff812369ac)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8125ce15)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In drivers/pci/pci-sysfs.c (ffffffff81523c72)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff81529f56)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e28c2)
Location: include/linux/mm.h:2471
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff8109540e)
Location: include/linux/mm.h:2544
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff811183db)
Location: include/linux/mm.h:2544
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff812375b4)
Location: include/linux/mm.h:2544
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff81242953)
Location: include/linux/mm.h:2544
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_mapping_pages
```
```
In mm/mmap.c (ffffffff8124a25c)
Location: include/linux/mm.h:2544
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff812716f5)
Location: include/linux/mm.h:2544
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff812b6c36)
Location: include/linux/mm.h:2544
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff81539ad2)
Location: include/linux/mm.h:2544
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8153fe08)
Location: include/linux/mm.h:2544
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81705d72)
Location: include/linux/mm.h:2544
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff8109790f)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff81122790)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/coherent.c (ffffffff811234dd)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
```
```
In mm/interval_tree.c (ffffffff81248b64)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff81253bc5)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff8125c5a6)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8128cd15)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff812d390f)
Location: include/linux/mm.h:2538
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff815693f3)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8156f6f1)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81740b87)
Location: include/linux/mm.h:2538
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff8109dfcf)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff8112ec8b)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff81256fb4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff81262128)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff8126ad06)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8129c945)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff812e549f)
Location: include/linux/mm.h:2512
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff8158a444)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8159072a)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81764e57)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810a54ab)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff8113d6c5)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/direct.c (ffffffff8113e395)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_mmap
```
```
In mm/interval_tree.c (ffffffff81285687)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff8128c5f4)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/memory.c:do_fault_around
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff8129cf26)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/pagewalk.c (ffffffff812a32b7)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_mapping
```
```
In mm/mempolicy.c (ffffffff812d0605)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff8131bc5a)
Location: include/linux/mm.h:2722
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff816315c6)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff81638273)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (ffffffff81791e6e)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81824ae7)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810a0c27)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/direct.c (ffffffff8113972b)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_mmap
```
```
In kernel/dma/ops_helpers.c (ffffffff81139ad5)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff8128f967)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff81297884)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/memory.c:do_fault_around
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff812a8326)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/pagewalk.c (ffffffff812aebd7)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_mapping
```
```
In mm/mempolicy.c (ffffffff812dc125)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff81326d8a)
Location: include/linux/mm.h:2722
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff81656c66)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8165cb13)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be09e)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81835543)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810a19b6)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff811388df)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_mmap_pages
```
```
In kernel/dma/direct.c (ffffffff8113a7e5)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_mmap
```
```
In kernel/dma/ops_helpers.c (ffffffff8113abf5)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff81294fca)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff812a1e59)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - mm/memory.c:do_read_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff812abd36)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/pagewalk.c (ffffffff812b4057)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_mapping
```
```
In mm/mempolicy.c (ffffffff812e39c5)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff8132ce2a)
Location: include/linux/mm.h:2718
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff816396d6)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8163f0b3)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a129e)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818189a3)
Location: include/linux/mm.h:2718
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810b3575)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff8115b7bf)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_mmap_pages
```
```
In kernel/dma/direct.c (ffffffff8115d705)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_mmap
```
```
In kernel/dma/ops_helpers.c (ffffffff8115db25)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff812d562a)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff812e2d6e)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - mm/memory.c:do_read_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff812ed436)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/pagewalk.c (ffffffff812f5c37)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_mapping
```
```
In mm/mempolicy.c (ffffffff8132aca5)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff8137a942)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a9d32)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff816afdb5)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (ffffffff81829ece)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818a2ca3)
Location: include/linux/mm.h:2776
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810c97b4)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff811852af)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_mmap_pages
```
```
In kernel/dma/direct.c (ffffffff81187640)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_mmap
```
```
In kernel/dma/ops_helpers.c (ffffffff81187ad5)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
```
```
In mm/shmem.c (ffffffff8131c3d2)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/interval_tree.c (ffffffff81334893)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff81343698)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - mm/memory.c:do_read_fault
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff813507c8)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/pagewalk.c (ffffffff81359b58)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_mapping
```
```
In mm/mempolicy.c (ffffffff8139a675)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff813faabe)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In drivers/pci/pci-sysfs.c (ffffffff817ccbca)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff817d32f7)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196a3b1)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ec693)
Location: include/linux/mm.h:2851
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810e6dac)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff811c0abc)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_mmap_pages
```
```
In kernel/dma/direct.c (ffffffff811c3230)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_mmap
```
```
In kernel/dma/ops_helpers.c (ffffffff811c3735)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
```
```
In mm/shmem.c (ffffffff8138ffbc)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/interval_tree.c (ffffffff813ab580)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff813bb715)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - mm/memory.c:do_read_fault
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff813ca16b)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:can_vma_merge_after
```
```
In mm/pagewalk.c (ffffffff813d4515)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_mapping
```
```
In mm/mempolicy.c (ffffffff8141a6b5)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff8148523a)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In drivers/pci/pci-sysfs.c (ffffffff818ebf9a)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff818f3ca7)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad43de)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b695ff)
Location: include/linux/mm.h:3002
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810f27cc)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff811d35af)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_mmap_pages
```
```
In kernel/dma/direct.c (ffffffff811d5d70)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_mmap
```
```
In kernel/dma/ops_helpers.c (ffffffff811d6285)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
```
```
In mm/shmem.c (ffffffff813c2915)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/interval_tree.c (ffffffff813df923)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff813f016b)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - mm/memory.c:do_read_fault
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff813fe6df)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:can_vma_merge_after
```
```
In mm/pagewalk.c (ffffffff81408fb8)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_mapping
```
```
In mm/mempolicy.c (ffffffff8144dc25)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff814ba225)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192f4aa)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff819370f7)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b22bb1)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbca3f)
Location: include/linux/mm.h:3308
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810fb490)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff811e822f)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_mmap_pages
```
```
In kernel/dma/direct.c (ffffffff811ead00)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_mmap
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb2b5)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
```
```
In mm/shmem.c (ffffffff813ed5b5)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/interval_tree.c (ffffffff8140a033)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff8141b7ed)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/memory.c:do_read_fault
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:__vm_map_pages
```
```
In mm/mlock.c (ffffffff81425448)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff8142ab4f)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:vma_merge_extend
  - mm/mmap.c:can_vma_merge_after
```
```
In mm/pagewalk.c (ffffffff814356d8)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_mapping
```
```
In mm/rmap.c (ffffffff81437824)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/mempolicy.c (ffffffff81487a55)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff814ec7a5)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In drivers/pci/pci-sysfs.c (ffffffff81977e1c)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8197ff57)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b797f1)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c11183)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9d209)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
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
In kernel/fork.c (ffff8000100f2aa4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffff800010194304)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/coherent.c (ffff80001019570c)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
```
```
In mm/interval_tree.c (ffff8000102ee914)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffff8000102f93d8)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffff800010302414)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffff80001033b934)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffff80001038d840)
Location: include/linux/mm.h:2512
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffff8000106eeefc)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffff8000106f587c)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/dma-buf/dma-buf.c (ffff8000109656b4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In arch/arm/mm/dma-mapping.c (c031c1f0)
Location: include/linux/mm.h:2512
Inline: True
```
```
In kernel/fork.c (c03514d4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (c03e1570)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/coherent.c (c03e2284)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
```
```
In mm/interval_tree.c (c0512704)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (c051b8a4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (c0520b24)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In fs/exec.c (c0574ae0)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
```
```
In drivers/pci/pci-sysfs.c (c0889f14)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (c08902c4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (c0a3bbd0)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (c000000000138800)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (c0000000001f457c)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/coherent.c (c0000000001f583c)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
```
```
In mm/interval_tree.c (c0000000003b2b20)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (c0000000003c2ffc)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (c0000000003ce890)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (c000000000416764)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (c000000000484f9c)
Location: include/linux/mm.h:2512
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c00000000086bdec)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (c000000000874500)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1bf34)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abdedc)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_mmap
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
In kernel/fork.c (ffffffe0000bf7ce)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffe0001264be)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/coherent.c (ffffffe000127444)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
```
```
In mm/interval_tree.c (ffffffe000202928)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffe0002093b4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffe00020f380)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In fs/exec.c (ffffffe00025dcba)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d1f8e)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff810978ef)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff8112726b)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff8124f604)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff8125a778)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff81263356)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81294f25)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff812dda7f)
Location: include/linux/mm.h:2512
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e2d4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff815845b1)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81719547)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff8108636f)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff81119ccb)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff812425a4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff8124cb98)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff81255776)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81286b35)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff812ce6ff)
Location: include/linux/mm.h:2512
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156d0a4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8157338a)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f29b7)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff8109789f)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff8112515b)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff8124d3a4)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff81258518)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff812610f6)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81292d35)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff812db88f)
Location: include/linux/mm.h:2512
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e194)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8158447a)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81758317)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In kernel/fork.c (ffffffff8109f49f)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/dma/mapping.c (ffffffff8113179b)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In mm/interval_tree.c (ffffffff8125cd64)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:__anon_vma_interval_tree_subtree_search
  - mm/interval_tree.c:__anon_vma_interval_tree_augment_rotate
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_subtree_search
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_augment_rotate
```
```
In mm/memory.c (ffffffff81267ef8)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:__vm_map_pages
```
```
In mm/mmap.c (ffffffff81270ac6)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff812a2b25)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In fs/exec.c (ffffffff812ec842)
Location: include/linux/mm.h:2512
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff81598644)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/mmap.c (ffffffff8159e92a)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817737f7)
Location: include/linux/mm.h:2512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
```
</details>
</li>
</ul>

## Differences
