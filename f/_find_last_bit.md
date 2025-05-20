# Function: <code>_find_last_bit</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int _find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815b3e60)
Location: lib/find_bit.c:111
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/page_alloc.c:setup_nr_node_ids
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
**Symbols:**

```
ffffffff815b3e60-ffffffff815b3ea8: _find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int _find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8161a060)
Location: lib/find_bit.c:111
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/page_alloc.c:setup_nr_node_ids
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
**Symbols:**

```
ffffffff8161a060-ffffffff8161a0ad: _find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int _find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff816e7600)
Location: lib/find_bit.c:132
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/page_alloc.c:setup_nr_node_ids
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
**Symbols:**

```
ffffffff816e7600-ffffffff816e7665: _find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int _find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff817d71a0)
Location: lib/find_bit.c:186
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/page_alloc.c:free_area_init
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
```
**Symbols:**

```
ffffffff817d71a0-ffffffff817d7205: _find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int _find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81816270)
Location: lib/find_bit.c:204
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/mm_init.c:free_area_init
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
```
**Symbols:**

```
ffffffff81816270-ffffffff818162d2: _find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int _find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8185b3b0)
Location: lib/find_bit.c:204
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/mm_init.c:free_area_init
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
```
**Symbols:**

```
ffffffff8185b3b0-ffffffff8185b412: _find_last_bit (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
