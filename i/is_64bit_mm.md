# Function: <code>is_64bit_mm</code>

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
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/include/asm/mmu_context.h:236
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/mmu_context.h:236
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
In arch/x86/kernel/uprobes.c (ffffffff810656a6)
Location: arch/x86/include/asm/mmu_context.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/mmu_context.h:156
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
In arch/x86/kernel/uprobes.c (ffffffff81068bd6)
Location: arch/x86/include/asm/mmu_context.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/mmu_context.h:166
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
In arch/x86/kernel/uprobes.c (ffffffff81067eb6)
Location: arch/x86/include/asm/mmu_context.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/mmu_context.h:188
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
In arch/x86/kernel/uprobes.c (ffffffff8106c156)
Location: arch/x86/include/asm/mmu_context.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/mmu_context.h:248
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
In arch/x86/kernel/uprobes.c (ffffffff8106ef8f)
Location: arch/x86/include/asm/mmu_context.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/mmu_context.h:249
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
In arch/x86/kernel/uprobes.c (ffffffff81074fff)
Location: arch/x86/include/asm/mmu_context.h:262
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (ffffffff81089739)
Location: arch/x86/include/asm/mmu_context.h:262
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
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
In arch/x86/kernel/uprobes.c (ffffffff81078bfd)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (ffffffff8108cdc3)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
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
In arch/x86/kernel/uprobes.c (ffffffff81079c4d)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (ffffffff8108da23)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81081216)
Location: arch/x86/include/asm/mmu_context.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81080cc2)
Location: arch/x86/include/asm/mmu_context.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8108195e)
Location: arch/x86/include/asm/mmu_context.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8109097a)
Location: arch/x86/include/asm/mmu_context.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810a19bd)
Location: arch/x86/include/asm/mmu_context.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810b9b87)
Location: arch/x86/include/asm/mmu_context.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810bcd48)
Location: arch/x86/include/asm/mmu_context.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810c3ec8)
Location: arch/x86/include/asm/mmu_context.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81078c4d)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (ffffffff8108c9e3)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
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
In arch/x86/kernel/uprobes.c (ffffffff810683fd)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (ffffffff8107b513)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
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
In arch/x86/kernel/uprobes.c (ffffffff81078bfd)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (ffffffff8108c993)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
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
In arch/x86/kernel/uprobes.c (ffffffff8107acfd)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
```
In arch/x86/mm/mpx.c (ffffffff8108ed03)
Location: arch/x86/include/asm/mmu_context.h:263
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
</details>
</li>
</ul>

## Differences
