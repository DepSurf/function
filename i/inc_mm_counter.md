# Function: <code>inc_mm_counter</code>

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
In kernel/events/uprobes.c (ffffffff8118781b)
Location: include/linux/mm.h:1375
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/rmap.c (ffffffff811cb522)
Location: include/linux/mm.h:1375
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811d458a)
Location: include/linux/mm.h:1375
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/userfaultfd.c (ffffffff81207afb)
Location: include/linux/mm.h:1375
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff81199fec)
Location: include/linux/mm.h:1469
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/rmap.c (ffffffff811e866d)
Location: include/linux/mm.h:1469
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811f2400)
Location: include/linux/mm.h:1469
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/userfaultfd.c (ffffffff8122d3e9)
Location: include/linux/mm.h:1469
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff811a9720)
Location: include/linux/mm.h:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/rmap.c (ffffffff811f9798)
Location: include/linux/mm.h:1443
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81202dfb)
Location: include/linux/mm.h:1443
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/userfaultfd.c (ffffffff8123f90c)
Location: include/linux/mm.h:1443
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff811b0c0c)
Location: include/linux/mm.h:1475
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811dcfb8)
Location: include/linux/mm.h:1475
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/rmap.c (ffffffff812046b4)
Location: include/linux/mm.h:1475
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8120de9e)
Location: include/linux/mm.h:1475
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/userfaultfd.c (ffffffff8124b463)
Location: include/linux/mm.h:1475
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff811c4792)
Location: include/linux/mm.h:1549
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811eef28)
Location: include/linux/mm.h:1549
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff8121d5f3)
Location: include/linux/mm.h:1549
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8122910e)
Location: include/linux/mm.h:1549
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/migrate.c (ffffffff8124a1e0)
Location: include/linux/mm.h:1549
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8126b74d)
Location: include/linux/mm.h:1549
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff811e4d45)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8120fa2d)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff8123f3e5)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8124a421)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/migrate.c (ffffffff8126f159)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81290002)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff811f53b0)
Location: include/linux/mm.h:1706
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81222801)
Location: include/linux/mm.h:1706
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff81253af6)
Location: include/linux/mm.h:1706
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8125ea62)
Location: include/linux/mm.h:1706
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/migrate.c (ffffffff81283809)
Location: include/linux/mm.h:1706
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812a5036)
Location: include/linux/mm.h:1706
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff8120d077)
Location: include/linux/mm.h:1701
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81231e08)
Location: include/linux/mm.h:1701
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff81265d5b)
Location: include/linux/mm.h:1701
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812797b0)
Location: include/linux/mm.h:1701
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c06f9)
Location: include/linux/mm.h:1701
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff8121a3e5)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8123fec8)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff81274688)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81289290)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/migrate.c (ffffffff812af2bc)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d2646)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff81246dad)
Location: include/linux/mm.h:1889
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8126e8ed)
Location: include/linux/mm.h:1889
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812a5981)
Location: include/linux/mm.h:1889
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812bbc5f)
Location: include/linux/mm.h:1889
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812e5357)
Location: include/linux/mm.h:1889
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81308207)
Location: include/linux/mm.h:1889
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In kernel/events/uprobes.c (ffffffff8125141a)
Location: include/linux/mm.h:1934
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812792e7)
Location: include/linux/mm.h:1934
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812b0dfb)
Location: include/linux/mm.h:1934
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812c770f)
Location: include/linux/mm.h:1934
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f0720)
Location: include/linux/mm.h:1934
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313fa9)
Location: include/linux/mm.h:1934
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In kernel/events/uprobes.c (ffffffff81255522)
Location: include/linux/mm.h:1942
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127e2d3)
Location: include/linux/mm.h:1942
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812b6448)
Location: include/linux/mm.h:1942
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812ce088)
Location: include/linux/mm.h:1942
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f6ae9)
Location: include/linux/mm.h:1942
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8131a168)
Location: include/linux/mm.h:1942
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In kernel/events/uprobes.c (ffffffff81290f63)
Location: include/linux/mm.h:1971
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812f7e74)
Location: include/linux/mm.h:1971
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81313508)
Location: include/linux/mm.h:1971
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff81341145)
Location: include/linux/mm.h:1971
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366e5f)
Location: include/linux/mm.h:1971
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In kernel/events/uprobes.c (ffffffff812e635e)
Location: include/linux/mm.h:2049
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8135dc19)
Location: include/linux/mm.h:2049
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8137e9de)
Location: include/linux/mm.h:2049
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff813b7f58)
Location: include/linux/mm.h:2049
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e4345)
Location: include/linux/mm.h:2049
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void inc_mm_counter(struct mm_struct *mm, int member);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134fe2c)
Location: include/linux/mm.h:2215
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813bb226)
Location: include/linux/mm.h:2215
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff813d8ab2)
Location: include/linux/mm.h:2215
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff813fd37d)
Location: include/linux/mm.h:2215
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff81439c3c)
Location: include/linux/mm.h:2215
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146bded)
Location: include/linux/mm.h:2215
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff813b5040-ffffffff813b50e3: inc_mm_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void inc_mm_counter(struct mm_struct *mm, int member);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81380fe5)
Location: include/linux/mm.h:2535
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813efd25)
Location: include/linux/mm.h:2535
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
Direct callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/rmap.c (ffffffff8140d1ba)
Location: include/linux/mm.h:2535
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8143065a)
Location: include/linux/mm.h:2535
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff8146e8d8)
Location: include/linux/mm.h:2535
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0bbe)
Location: include/linux/mm.h:2535
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff813e9de0-ffffffff813e9e83: inc_mm_counter (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff813aa3be)
Location: include/linux/mm.h:2584
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81420293)
Location: include/linux/mm.h:2584
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81439932)
Location: include/linux/mm.h:2584
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8146900e)
Location: include/linux/mm.h:2584
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff8149d342)
Location: include/linux/mm.h:2584
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/userfaultfd.c (ffffffff814d03c4)
Location: include/linux/mm.h:2584
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In kernel/events/uprobes.c (ffff8000102a57d0)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffff8000102d3214)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffff80001030a284)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffff8000103260dc)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/userfaultfd.c (ffff8000103781ac)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In kernel/events/uprobes.c (c04d4c4c)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (c04fb19c)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (c0526874)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (c053d924)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/userfaultfd.c (c0563b00)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (c0000000003585e4)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (c000000000391c70)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (c0000000003d9d04)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (c0000000003fc628)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/migrate.c (c000000000432aa0)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/userfaultfd.c (c00000000046a8fc)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In mm/shmem.c (ffffffe0001ee3cc)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffe000214030)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffe00022643c)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/userfaultfd.c (ffffffe00024feaa)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff81212a35)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81238518)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff8126ccd8)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81281870)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/migrate.c (ffffffff812a789c)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812cac26)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff812057af)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8122b519)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff8125ed14)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81274ff0)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/migrate.c (ffffffff812992a9)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812bbbb0)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff812107d5)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812362b8)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff8126aa78)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8127f680)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/migrate.c (ffffffff812a56ac)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c8a36)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff8121f6e6)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81246593)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff8127a3e1)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8128f353)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/migrate.c (ffffffff812b4dd9)
Location: include/linux/mm.h:1673
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d972e)
Location: include/linux/mm.h:1673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
