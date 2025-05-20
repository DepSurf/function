# Function: <code>HYPERVISOR_mmu_update</code>

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
In arch/x86/xen/setup.c (ffffffff81f6128c)
Location: arch/x86/include/asm/xen/hypercall.h:231
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff81021e60)
Location: arch/x86/include/asm/xen/hypercall.h:231
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:do_remap_gfn
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
In arch/x86/xen/setup.c (ffffffff81f89460)
Location: arch/x86/include/asm/xen/hypercall.h:232
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8102247e)
Location: arch/x86/include/asm/xen/hypercall.h:232
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff81fc4854)
Location: arch/x86/include/asm/xen/hypercall.h:232
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff81022bce)
Location: arch/x86/include/asm/xen/hypercall.h:232
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff8101a611)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff820a46a4)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102392d)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff8101aee1)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff826aad84)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102449d)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff8101ba5c)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff826d3ef3)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d5db9)
Location: arch/x86/include/asm/xen/hypercall.h:237
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff82889f86)
Location: arch/x86/include/asm/xen/hypercall.h:239
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022729)
Location: arch/x86/include/asm/xen/hypercall.h:239
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff828a1337)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810236d8)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff828a43f7)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024198)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff82cc9fe2)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026b34)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff82fb5e50)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027344)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff831c0659)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810291e5)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff832a17d9)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102d93f)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff83450851)
Location: arch/x86/include/asm/xen/hypercall.h:259
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81032771)
Location: arch/x86/include/asm/xen/hypercall.h:259
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff83e6cd97)
Location: arch/x86/include/asm/xen/hypercall.h:259
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a181)
Location: arch/x86/include/asm/xen/hypercall.h:259
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff8368d8c7)
Location: arch/x86/include/asm/xen/hypercall.h:259
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a209)
Location: arch/x86/include/asm/xen/hypercall.h:259
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff838bd487)
Location: arch/x86/include/asm/xen/hypercall.h:259
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810406c9)
Location: arch/x86/include/asm/xen/hypercall.h:259
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff8289241d)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810242f8)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a53f7)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024158)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/setup.c (ffffffff828a53cb)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810246a6)
Location: arch/x86/include/asm/xen/hypercall.h:258
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
</details>
</li>
</ul>

## Differences
