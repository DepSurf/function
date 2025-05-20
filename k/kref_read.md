# Function: <code>kref_read</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff814b9e06)
Location: include/linux/kref.h:36
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff814fa206)
Location: include/linux/kref.h:36
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
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
In block/blk-core.c (ffffffff8147fb8f)
Location: include/linux/kref.h:36
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
```
```
In block/blk-tag.c (ffffffff81485cbd)
Location: include/linux/kref.h:36
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff81486dad)
Location: include/linux/kref.h:36
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/blk-mq.c (ffffffff81492235)
Location: include/linux/kref.h:36
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In drivers/pci/slot.c (ffffffff8152acc6)
Location: include/linux/kref.h:36
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
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
In drivers/pci/slot.c (ffffffff81540b46)
Location: include/linux/kref.h:36
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/base/core.c (ffffffff8169d119)
Location: include/linux/kref.h:36
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
In drivers/pci/slot.c (ffffffff81570446)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/base/core.c (ffffffff816d5f5a)
Location: include/linux/kref.h:34
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
In drivers/pci/slot.c (ffffffff81591526)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81692872)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff816f9f9a)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767652)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In drivers/pci/slot.c (ffffffff8163f909)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8174518c)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
```
```
In drivers/base/core.c (ffffffff817b2ef1)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827a2a)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In drivers/pci/slot.c (ffffffff81665d59)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81761400)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
```
```
In drivers/base/core.c (ffffffff817c7951)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818384aa)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In drivers/pci/slot.c (ffffffff816482f9)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744ed8)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff817aadc1)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b787)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In drivers/pci/slot.c (ffffffff816b9d06)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c5d43)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff81833f61)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5c17)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In kernel/fork.c (ffffffff810c8ebf)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_dup
```
```
In mm/madvise.c (ffffffff813780ba)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In drivers/pci/slot.c (ffffffff817de5e7)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81902ca5)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff81975834)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efb67)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In kernel/fork.c (ffffffff810e636c)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_dup
```
```
In mm/madvise.c (ffffffff813f59c8)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In drivers/pci/slot.c (ffffffff819011d7)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5cc75)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff81ae13d4)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d1a7)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In kernel/fork.c (ffffffff810f1c3d)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_dup
```
```
In mm/madvise.c (ffffffff81428758)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In drivers/pci/slot.c (ffffffff81944797)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa73c7)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff81b2f639)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc08d7)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In kernel/fork.c (ffffffff810fafcd)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_dup
```
```
In mm/madvise.c (ffffffff81462002)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In drivers/pci/slot.c (ffffffff8198da97)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af9e57)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff81b86e39)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15057)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9b17a)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove
  - drivers/gpu/drm/drm_framebuffer.c:drm_fb_release
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9da93)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca38c1)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/gpu/drm/drm_debugfs.c (ffffffff81cb9d59)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs.c:drm_gem_one_name_info
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204d301)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:cpool_cleanup_work_cb
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
In drivers/pci/slot.c (ffff8000106f7088)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010866488)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffff8000108e4740)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff800010968754)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/of/dynamic.c (ffff800010b70998)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_changeset_destroy
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
In drivers/pci/slot.c (c08912dc)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (c096bbbc)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (c09d3168)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3e77c)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/of/dynamic.c (c0c52fec)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_changeset_destroy
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
In drivers/pci/slot.c (c000000000875df0)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905868)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (c000000000979aec)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1fe3c)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/of/dynamic.c (c000000000c4c16c)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_changeset_destroy
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
In drivers/pci/slot.c (ffffffe0004c9096)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053bea2)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffe000579638)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d4182)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/of/dynamic.c (ffffffe000724920)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_changeset_destroy
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
In drivers/pci/slot.c (ffffffff815853b6)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816582f2)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff816bf78a)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bd42)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In drivers/pci/slot.c (ffffffff81574186)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81638682)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff8169aa3a)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f51a2)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In drivers/pci/slot.c (ffffffff81585276)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816866b2)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff816edc5a)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175ab12)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
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
In drivers/pci/slot.c (ffffffff8159f726)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816a0cb2)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff8170849a)
Location: include/linux/kref.h:34
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817760f2)
Location: include/linux/kref.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
</details>
</li>
</ul>

## Differences
