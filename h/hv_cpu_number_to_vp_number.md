# Function: <code>hv_cpu_number_to_vp_number</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102a89c)
Location: arch/x86/include/asm/mshyperv.h:308
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
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
In arch/x86/hyperv/mmu.c (ffffffff8102b488)
Location: arch/x86/include/asm/mshyperv.h:258
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bcd8)
Location: arch/x86/include/asm/mshyperv.h:258
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
In arch/x86/hyperv/mmu.c (ffffffff8102bda4)
Location: arch/x86/include/asm/mshyperv.h:304
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cc94)
Location: arch/x86/include/asm/mshyperv.h:304
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff8102de7b)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ebde)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
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
In arch/x86/hyperv/mmu.c (ffffffff8102e78b)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f4ee)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
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
In arch/x86/hyperv/mmu.c (ffffffff81030d59)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031d95)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff81031ac9)
Location: include/asm-generic/mshyperv.h:128
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032a79)
Location: include/asm-generic/mshyperv.h:128
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff810325e3)
Location: include/asm-generic/mshyperv.h:182
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81033520)
Location: include/asm-generic/mshyperv.h:182
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033ed9)
Location: include/asm-generic/mshyperv.h:182
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff81037773)
Location: include/asm-generic/mshyperv.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810386c8)
Location: include/asm-generic/mshyperv.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81039169)
Location: include/asm-generic/mshyperv.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff8103d97f)
Location: include/asm-generic/mshyperv.h:206
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e951)
Location: include/asm-generic/mshyperv.h:206
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103ff89)
Location: include/asm-generic/mshyperv.h:206
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff8104679b)
Location: include/asm-generic/mshyperv.h:212
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810476b3)
Location: include/asm-generic/mshyperv.h:212
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810491b9)
Location: include/asm-generic/mshyperv.h:212
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
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
In arch/x86/hyperv/mmu.c (ffffffff810469d9)
Location: include/asm-generic/mshyperv.h:215
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047bd8)
Location: include/asm-generic/mshyperv.h:215
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81049419)
Location: include/asm-generic/mshyperv.h:215
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
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
In arch/x86/hyperv/mmu.c (ffffffff8104d1e9)
Location: include/asm-generic/mshyperv.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e341)
Location: include/asm-generic/mshyperv.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81050399)
Location: include/asm-generic/mshyperv.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
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
In arch/x86/hyperv/mmu.c (ffffffff8102e8eb)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f64e)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
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
In arch/x86/hyperv/mmu.c (ffffffff8101e448)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ecd7)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In drivers/hv/connection.c (ffffffff81850268)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - drivers/hv/connection.c:vmbus_negotiate_version
```
```
In drivers/hv/channel_mgmt.c (ffffffff818529ea)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
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
In arch/x86/hyperv/mmu.c (ffffffff8102e74b)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f4ae)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
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
In arch/x86/hyperv/mmu.c (ffffffff8102f53b)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810302ee)
Location: include/asm-generic/mshyperv.h:126
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
</details>
</li>
</ul>

## Differences
