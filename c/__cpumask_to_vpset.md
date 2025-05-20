# Function: <code>__cpumask_to_vpset</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81037713)
Location: include/asm-generic/mshyperv.h:200
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103864f)
Location: include/asm-generic/mshyperv.h:200
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038c4f)
Location: include/asm-generic/mshyperv.h:200
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
In arch/x86/hyperv/mmu.c (ffffffff8103d923)
Location: include/asm-generic/mshyperv.h:211
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e8dc)
Location: include/asm-generic/mshyperv.h:211
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f9eb)
Location: include/asm-generic/mshyperv.h:211
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __cpumask_to_vpset(struct hv_vpset *vpset, const struct cpumask *cpus, bool exclude_self);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81046725)
Location: include/asm-generic/mshyperv.h:217
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: include/asm-generic/mshyperv.h:217
Inline: True
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/asm-generic/mshyperv.h:217
Inline: False
```
**Symbols:**

```
ffffffff81047620-ffffffff81047741: __cpumask_to_vpset.constprop.0 (STB_LOCAL)
ffffffff82051f16-ffffffff82051f34: __cpumask_to_vpset.constprop.0.cold (STB_LOCAL)
ffffffff810488d0-ffffffff81048a0c: __cpumask_to_vpset (STB_LOCAL)
ffffffff82051f49-ffffffff82051f67: __cpumask_to_vpset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __cpumask_to_vpset(struct hv_vpset *vpset, const struct cpumask *cpus, bool (*func)(int));
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81046982)
Location: include/asm-generic/mshyperv.h:220
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047b72)
Location: include/asm-generic/mshyperv.h:220
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/asm-generic/mshyperv.h:220
Inline: False
```
**Symbols:**

```
ffffffff81048b80-ffffffff81048c9e: __cpumask_to_vpset (STB_LOCAL)
ffffffff820d043f-ffffffff820d045d: __cpumask_to_vpset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __cpumask_to_vpset(struct hv_vpset *vpset, const struct cpumask *cpus, bool (*func)(int));
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8104d192)
Location: include/asm-generic/mshyperv.h:228
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e2d9)
Location: include/asm-generic/mshyperv.h:228
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/asm-generic/mshyperv.h:228
Inline: False
```
**Symbols:**

```
ffffffff8104fe40-ffffffff8104ff5e: __cpumask_to_vpset (STB_LOCAL)
ffffffff821aaf31-ffffffff821aaf4f: __cpumask_to_vpset.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool (*func)(int)</code>
</li>
<li>
<b>Param removed. </b>
<code>bool exclude_self</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
