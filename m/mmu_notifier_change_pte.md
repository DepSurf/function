# Function: <code>mmu_notifier_change_pte</code>

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
In kernel/events/uprobes.c (ffffffff8118788a)
Location: include/linux/mmu_notifier.h:264
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bc6d4)
Location: include/linux/mmu_notifier.h:264
Inline: True
```
```
In mm/ksm.c (ffffffff811e559a)
Location: include/linux/mmu_notifier.h:264
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In kernel/events/uprobes.c (ffffffff81199ea2)
Location: include/linux/mmu_notifier.h:264
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811d7343)
Location: include/linux/mmu_notifier.h:264
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81204263)
Location: include/linux/mmu_notifier.h:264
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In kernel/events/uprobes.c (ffffffff811a960c)
Location: include/linux/mmu_notifier.h:264
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811e6ffd)
Location: include/linux/mmu_notifier.h:264
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81216410)
Location: include/linux/mmu_notifier.h:264
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
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
In kernel/events/uprobes.c (ffffffff811b0b08)
Location: include/linux/mmu_notifier.h:251
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811f21c6)
Location: include/linux/mmu_notifier.h:251
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81221a3b)
Location: include/linux/mmu_notifier.h:251
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
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
In kernel/events/uprobes.c (ffffffff811c4668)
Location: include/linux/mmu_notifier.h:254
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81209060)
Location: include/linux/mmu_notifier.h:254
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8123cd38)
Location: include/linux/mmu_notifier.h:254
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124a43d)
Location: include/linux/mmu_notifier.h:254
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
In kernel/events/uprobes.c (ffffffff811e4bcc)
Location: include/linux/mmu_notifier.h:273
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81229fbd)
Location: include/linux/mmu_notifier.h:273
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81260778)
Location: include/linux/mmu_notifier.h:273
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126f438)
Location: include/linux/mmu_notifier.h:273
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
In kernel/events/uprobes.c (ffffffff811f5262)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8123d599)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81274ebe)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81283ac8)
Location: include/linux/mmu_notifier.h:261
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
In kernel/events/uprobes.c (ffffffff8120cf5a)
Location: include/linux/mmu_notifier.h:303
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8124f233)
Location: include/linux/mmu_notifier.h:303
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8128f7ea)
Location: include/linux/mmu_notifier.h:303
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
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
In kernel/events/uprobes.c (ffffffff8121a24b)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8125d7ef)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8129f572)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812af529)
Location: include/linux/mmu_notifier.h:336
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
In kernel/events/uprobes.c (ffffffff81246bc4)
Location: include/linux/mmu_notifier.h:432
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8128d0eb)
Location: include/linux/mmu_notifier.h:432
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812d3bc0)
Location: include/linux/mmu_notifier.h:432
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e5409)
Location: include/linux/mmu_notifier.h:432
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
In kernel/events/uprobes.c (ffffffff81251227)
Location: include/linux/mmu_notifier.h:438
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812980af)
Location: include/linux/mmu_notifier.h:438
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812df5c0)
Location: include/linux/mmu_notifier.h:438
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f07cc)
Location: include/linux/mmu_notifier.h:438
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
In kernel/events/uprobes.c (ffffffff81255321)
Location: include/linux/mmu_notifier.h:438
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8129d732)
Location: include/linux/mmu_notifier.h:438
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812e7efc)
Location: include/linux/mmu_notifier.h:438
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f6b99)
Location: include/linux/mmu_notifier.h:438
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
In kernel/events/uprobes.c (ffffffff81290d63)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812dde16)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8132fe0d)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813411f5)
Location: include/linux/mmu_notifier.h:444
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
In kernel/events/uprobes.c (ffffffff812e6062)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8133de71)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff813a01d9)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff813b8003)
Location: include/linux/mmu_notifier.h:444
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
In kernel/events/uprobes.c (ffffffff8134fcb9)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813b6f6c)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8141f0c0)
Location: include/linux/mmu_notifier.h:444
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff81439d0e)
Location: include/linux/mmu_notifier.h:444
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
In kernel/events/uprobes.c (ffffffff81380e52)
Location: include/linux/mmu_notifier.h:443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813eb8ba)
Location: include/linux/mmu_notifier.h:443
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81453d45)
Location: include/linux/mmu_notifier.h:443
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146e993)
Location: include/linux/mmu_notifier.h:443
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
In kernel/events/uprobes.c (ffffffff813aa207)
Location: include/linux/mmu_notifier.h:442
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81416504)
Location: include/linux/mmu_notifier.h:442
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8148e4c4)
Location: include/linux/mmu_notifier.h:442
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149d3e7)
Location: include/linux/mmu_notifier.h:442
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
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
In kernel/events/uprobes.c (ffff8000102a561c)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffff8000102f4dcc)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffff80001033edb4)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In kernel/events/uprobes.c (c04d4a84)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (c0516f68)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (c0544fdc)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
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
In kernel/events/uprobes.c (c000000000358390)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (c0000000003bbacc)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (c00000000041ad60)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c000000000432b50)
Location: include/linux/mmu_notifier.h:336
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
In mm/memory.c (ffffffe00020621c)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffe0002349a8)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In kernel/events/uprobes.c (ffffffff8121289b)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81255e3f)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81297b52)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a7b09)
Location: include/linux/mmu_notifier.h:336
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
In kernel/events/uprobes.c (ffffffff81205605)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812484d6)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812896e6)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812994c3)
Location: include/linux/mmu_notifier.h:336
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
In kernel/events/uprobes.c (ffffffff8121063b)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81253bdf)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81295962)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a5919)
Location: include/linux/mmu_notifier.h:336
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
In kernel/events/uprobes.c (ffffffff8121f57e)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812635fd)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812a5779)
Location: include/linux/mmu_notifier.h:336
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b5047)
Location: include/linux/mmu_notifier.h:336
Inline: True
```
</details>
</li>
</ul>

## Differences
