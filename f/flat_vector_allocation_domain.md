# Function: <code>flat_vector_allocation_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void flat_vector_allocation_domain(int cpu, struct cpumask *retmask, const struct cpumask *mask);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81025b10)
Location: arch/x86/include/asm/apic.h:566
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a430)
Location: arch/x86/include/asm/apic.h:566
Inline: False
```
**Symbols:**

```
ffffffff81025b10-ffffffff81025b35: flat_vector_allocation_domain (STB_LOCAL)
ffffffff8105a430-ffffffff8105a455: flat_vector_allocation_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void flat_vector_allocation_domain(int cpu, struct cpumask *retmask, const struct cpumask *mask);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81024f10)
Location: arch/x86/include/asm/apic.h:573
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a7e0)
Location: arch/x86/include/asm/apic.h:573
Inline: False
```
**Symbols:**

```
ffffffff81024f10-ffffffff81024f35: flat_vector_allocation_domain (STB_LOCAL)
ffffffff8105a7e0-ffffffff8105a805: flat_vector_allocation_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void flat_vector_allocation_domain(int cpu, struct cpumask *retmask, const struct cpumask *mask);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff810255f0)
Location: arch/x86/include/asm/apic.h:573
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d500)
Location: arch/x86/include/asm/apic.h:573
Inline: False
```
**Symbols:**

```
ffffffff810255f0-ffffffff8102561e: flat_vector_allocation_domain (STB_LOCAL)
ffffffff8105d500-ffffffff8105d52e: flat_vector_allocation_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void flat_vector_allocation_domain(int cpu, struct cpumask *retmask, const struct cpumask *mask);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101bfa0)
Location: arch/x86/include/asm/apic.h:553
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cc00)
Location: arch/x86/include/asm/apic.h:553
Inline: False
```
**Symbols:**

```
ffffffff8101bfa0-ffffffff8101bfcc: flat_vector_allocation_domain (STB_LOCAL)
ffffffff8105cc00-ffffffff8105cc2c: flat_vector_allocation_domain (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
