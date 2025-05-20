# Function: <code>flat_cpu_mask_to_apicid_and</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int flat_cpu_mask_to_apicid_and(const struct cpumask *cpumask, const struct cpumask *andmask, unsigned int *apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff810259f0)
Location: arch/x86/include/asm/apic.h:543
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054960)
Location: arch/x86/include/asm/apic.h:543
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a3c0)
Location: arch/x86/include/asm/apic.h:543
Inline: False
```
**Symbols:**

```
ffffffff810259f0-ffffffff81025a14: flat_cpu_mask_to_apicid_and (STB_LOCAL)
ffffffff81054960-ffffffff81054984: flat_cpu_mask_to_apicid_and (STB_LOCAL)
ffffffff8105a3c0-ffffffff8105a3e4: flat_cpu_mask_to_apicid_and (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int flat_cpu_mask_to_apicid_and(const struct cpumask *cpumask, const struct cpumask *andmask, unsigned int *apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81024e00)
Location: arch/x86/include/asm/apic.h:550
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054af0)
Location: arch/x86/include/asm/apic.h:550
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a7c0)
Location: arch/x86/include/asm/apic.h:550
Inline: False
```
**Symbols:**

```
ffffffff81024e00-ffffffff81024e1e: flat_cpu_mask_to_apicid_and (STB_LOCAL)
ffffffff81054af0-ffffffff81054b0e: flat_cpu_mask_to_apicid_and (STB_LOCAL)
ffffffff8105a7c0-ffffffff8105a7de: flat_cpu_mask_to_apicid_and (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
int flat_cpu_mask_to_apicid_and(const struct cpumask *cpumask, const struct cpumask *andmask, unsigned int *apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81025520)
Location: arch/x86/include/asm/apic.h:550
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810578d0)
Location: arch/x86/include/asm/apic.h:550
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d4e0)
Location: arch/x86/include/asm/apic.h:550
Inline: False
```
**Symbols:**

```
ffffffff81025520-ffffffff8102553e: flat_cpu_mask_to_apicid_and (STB_LOCAL)
ffffffff810578d0-ffffffff810578ee: flat_cpu_mask_to_apicid_and (STB_LOCAL)
ffffffff8105d4e0-ffffffff8105d4fe: flat_cpu_mask_to_apicid_and (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
