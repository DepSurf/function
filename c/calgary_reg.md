# Function: <code>calgary_reg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff810673ea)
Location: arch/x86/kernel/pci-calgary_64.c:521
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9efcb)
Location: arch/x86/kernel/pci-calgary_64.c:521
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda52d)
Location: arch/x86/kernel/pci-calgary_64.c:521
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb3ac)
Location: arch/x86/kernel/pci-calgary_64.c:530
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c1d8e)
Location: arch/x86/kernel/pci-calgary_64.c:530
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ebf72)
Location: arch/x86/kernel/pci-calgary_64.c:529
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a2b74)
Location: arch/x86/kernel/pci-calgary_64.c:516
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bae76)
Location: arch/x86/kernel/pci-calgary_64.c:504
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c1338)
Location: arch/x86/kernel/pci-calgary_64.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ac30e)
Location: arch/x86/kernel/pci-calgary_64.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a45d5)
Location: arch/x86/kernel/pci-calgary_64.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bf20d)
Location: arch/x86/kernel/pci-calgary_64.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c235a)
Location: arch/x86/kernel/pci-calgary_64.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
</details>
</li>
</ul>

## Differences
