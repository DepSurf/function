# Function: <code>__iommu_flush_cache</code>

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
In drivers/iommu/dmar.c (ffffffff81534d18)
Location: include/linux/intel-iommu.h:446
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff8153837b)
Location: include/linux/intel-iommu.h:446
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153ce36)
Location: include/linux/intel-iommu.h:446
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:modify_irte
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
In drivers/iommu/intel-iommu.c (ffffffff8158cf88)
Location: include/linux/intel-iommu.h:446
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815919fe)
Location: include/linux/intel-iommu.h:446
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:modify_irte
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
In drivers/iommu/intel-iommu.c (ffffffff815ba608)
Location: include/linux/intel-iommu.h:447
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bf2be)
Location: include/linux/intel-iommu.h:447
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:modify_irte
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
In drivers/iommu/intel-iommu.c (ffffffff815d0579)
Location: include/linux/intel-iommu.h:434
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4dfa)
Location: include/linux/intel-iommu.h:434
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:modify_irte
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
In drivers/iommu/intel-iommu.c (ffffffff81637322)
Location: include/linux/intel-iommu.h:435
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163bb8a)
Location: include/linux/intel-iommu.h:435
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:modify_irte
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
In drivers/iommu/intel-iommu.c (ffffffff81672db2)
Location: include/linux/intel-iommu.h:440
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816774a1)
Location: include/linux/intel-iommu.h:440
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
In drivers/iommu/intel-iommu.c (ffffffff8169126d)
Location: include/linux/intel-iommu.h:581
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696561)
Location: include/linux/intel-iommu.h:581
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
In drivers/iommu/intel-iommu.c (ffffffff816c921c)
Location: include/linux/intel-iommu.h:580
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cee6c)
Location: include/linux/intel-iommu.h:580
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
In drivers/iommu/intel-iommu.c (ffffffff816ec1ec)
Location: include/linux/intel-iommu.h:586
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f2cac)
Location: include/linux/intel-iommu.h:586
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
In drivers/iommu/intel/iommu.c (ffffffff817a445f)
Location: include/linux/intel-iommu.h:633
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aafbc)
Location: include/linux/intel-iommu.h:633
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
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
In drivers/iommu/intel/iommu.c (ffffffff817b0e0f)
Location: include/linux/intel-iommu.h:645
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b741c)
Location: include/linux/intel-iommu.h:645
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
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
In drivers/iommu/intel/iommu.c (ffffffff81bfe226)
Location: include/linux/intel-iommu.h:657
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179ab95)
Location: include/linux/intel-iommu.h:657
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
In drivers/iommu/intel/iommu.c (ffffffff81cfff8c)
Location: include/linux/intel-iommu.h:659
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818236d2)
Location: include/linux/intel-iommu.h:659
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
In drivers/iommu/intel/iommu.c (ffffffff81ec86a6)
Location: include/linux/intel-iommu.h:632
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962fa8)
Location: include/linux/intel-iommu.h:632
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
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
In drivers/iommu/intel/iommu.c (ffffffff81ac5580)
Location: drivers/iommu/intel/iommu.h:626
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_context_addr
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbc1c)
Location: drivers/iommu/intel/iommu.h:626
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
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
In drivers/iommu/intel/iommu.c (ffffffff81b11fbc)
Location: drivers/iommu/intel/iommu.h:720
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_context_addr
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b1879a)
Location: drivers/iommu/intel/iommu.h:720
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
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
In drivers/iommu/intel/iommu.c (ffffffff81b65d0e)
Location: drivers/iommu/intel/iommu.h:772
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e0da)
Location: drivers/iommu/intel/iommu.h:772
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b1b1c)
Location: include/linux/intel-iommu.h:586
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b849c)
Location: include/linux/intel-iommu.h:586
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
In drivers/iommu/intel-iommu.c (ffffffff8168f61c)
Location: include/linux/intel-iommu.h:586
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816960dc)
Location: include/linux/intel-iommu.h:586
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
In drivers/iommu/intel-iommu.c (ffffffff816dfeac)
Location: include/linux/intel-iommu.h:586
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e696c)
Location: include/linux/intel-iommu.h:586
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
In drivers/iommu/intel-iommu.c (ffffffff816fa4bc)
Location: include/linux/intel-iommu.h:586
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8170106c)
Location: include/linux/intel-iommu.h:586
Inline: True
```
</details>
</li>
</ul>

## Differences
