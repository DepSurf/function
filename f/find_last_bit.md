# Function: <code>find_last_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff813fe010)
Location: lib/find_bit.c:115
Inline: True
Direct callers:
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff813fe010-ffffffff813fe05b: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81445670)
Location: lib/find_bit.c:115
Inline: True
Direct callers:
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff81445670-ffffffff814456bb: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81463e60)
Location: lib/find_bit.c:115
Inline: True
Direct callers:
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff81463e60-ffffffff81463eab: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81468ef0)
Location: lib/find_bit.c:115
Inline: True
Direct callers:
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff81468ef0-ffffffff81468f3b: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814951c0)
Location: lib/find_bit.c:115
Inline: True
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/page_alloc.c:setup_nr_node_ids
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff814951c0-ffffffff8149520f: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814ca4c0)
Location: lib/find_bit.c:135
Inline: True
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/page_alloc.c:setup_nr_node_ids
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff814ca4c0-ffffffff814ca50d: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814df1e0)
Location: lib/find_bit.c:135
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/page_alloc.c:setup_nr_node_ids
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff814df1e0-ffffffff814df22d: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8150b050)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff8150b050-ffffffff8150b097: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81528e70)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff81528e70-ffffffff81528eb7: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8158c6d0)
Location: lib/find_bit.c:139
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff8158c6d0-ffffffff8158c717: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815a9140)
Location: lib/find_bit.c:141
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/page_alloc.c:setup_nr_node_ids
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
```
**Symbols:**

```
ffffffff815a9140-ffffffff815a9187: find_last_bit (STB_GLOBAL)
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
In arch/x86/hyperv/mmu.c (ffffffff81032ae4)
Location: include/asm-generic/bitops/find.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033b70)
Location: include/asm-generic/bitops/find.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff831e639c)
Location: include/asm-generic/bitops/find.h:159
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff831e972f)
Location: include/asm-generic/bitops/find.h:159
Inline: True
Inline callers:
  - kernel/smp.c:setup_nr_cpu_ids
```
```
In mm/percpu.c (ffffffff8128a153)
Location: include/asm-generic/bitops/find.h:159
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
```
```
In mm/page_alloc.c (ffffffff831f290b)
Location: include/asm-generic/bitops/find.h:159
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_nr_node_ids
```
```
In lib/pldmfw/pldmfw.c (ffffffff815ee91f)
Location: include/asm-generic/bitops/find.h:159
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
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
In arch/x86/hyperv/mmu.c (ffffffff81037b4e)
Location: include/asm-generic/bitops/find.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038f31)
Location: include/asm-generic/bitops/find.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/smp.c (ffffffff832cdd32)
Location: include/asm-generic/bitops/find.h:164
Inline: True
Inline callers:
  - kernel/smp.c:setup_nr_cpu_ids
```
```
In mm/percpu.c (ffffffff812c9c33)
Location: include/asm-generic/bitops/find.h:164
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
```
```
In mm/page_alloc.c (ffffffff832d87bb)
Location: include/asm-generic/bitops/find.h:164
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_nr_node_ids
```
```
In lib/pldmfw/pldmfw.c (ffffffff8165b9cf)
Location: include/asm-generic/bitops/find.h:164
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
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
In arch/x86/hyperv/mmu.c (ffffffff8103de6a)
Location: include/linux/find.h:184
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fd12)
Location: include/linux/find.h:184
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/smp.c (ffffffff834819d6)
Location: include/linux/find.h:184
Inline: True
Inline callers:
  - kernel/smp.c:setup_nr_cpu_ids
```
```
In mm/percpu.c (ffffffff813281af)
Location: include/linux/find.h:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
```
```
In mm/page_alloc.c (ffffffff8348cd21)
Location: include/linux/find.h:184
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_nr_node_ids
```
```
In lib/pldmfw/pldmfw.c (ffffffff81774864)
Location: include/linux/find.h:184
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
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
In arch/x86/hyperv/mmu.c (ffffffff81046cdf)
Location: include/linux/find.h:314
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048c62)
Location: include/linux/find.h:314
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/smp.c (ffffffff83eaec15)
Location: include/linux/find.h:314
Inline: True
Inline callers:
  - kernel/smp.c:setup_nr_cpu_ids
```
```
In mm/percpu.c (ffffffff8139c44a)
Location: include/linux/find.h:314
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
```
```
In mm/page_alloc.c (ffffffff83ec074d)
Location: include/linux/find.h:314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
```
```
In lib/pldmfw/pldmfw.c (ffffffff818a46ca)
Location: include/linux/find.h:314
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
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
In arch/x86/hyperv/mmu.c (ffffffff81046ef4)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048ec2)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/smp.c (ffffffff836d3c45)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - kernel/smp.c:setup_nr_cpu_ids
```
```
In mm/mm_init.c (ffffffff836e24bc)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
```
```
In mm/percpu.c (ffffffff813cf53d)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
```
```
In lib/pldmfw/pldmfw.c (ffffffff818e750a)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
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
In arch/x86/hyperv/mmu.c (ffffffff8104d613)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81050132)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/smp.c (ffffffff83905c25)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - kernel/smp.c:setup_nr_cpu_ids
```
```
In mm/mm_init.c (ffffffff83914dcc)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
```
```
In mm/percpu.c (ffffffff813fa02f)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
```
```
In lib/pldmfw/pldmfw.c (ffffffff8192e54a)
Location: include/linux/find.h:379
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_send_component_tables
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffff800010633770)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - arch/arm64/kernel/fpsimd.c:sve_verify_vq_map
  - arch/arm64/kernel/fpsimd.c:sve_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/page_alloc.c:setup_nr_node_ids
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
```
**Symbols:**

```
ffff800010633770-ffff8000106337c4: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (c07d9b34)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
**Symbols:**

```
c07d9b34-c07d9b94: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (c0000000007d8af0)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
c0000000007d8af0-c0000000007d8b60: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffe000461772)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
**Symbols:**

```
ffffffe000461772-ffffffe0004617f0: find_last_bit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81521450)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff81521450-ffffffff81521497: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81511740)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff81511740-ffffffff81511787: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8151d4e0)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff8151d4e0-ffffffff8151d527: find_last_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_last_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81536d50)
Location: lib/find_bit.c:131
Inline: True
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/smp.c:setup_nr_cpu_ids
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/page_alloc.c:setup_nr_node_ids
```
**Symbols:**

```
ffffffff81536d50-ffffffff81536d97: find_last_bit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
