# Function: <code>default_vector_allocation_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void default_vector_allocation_domain(int cpu, struct cpumask *retmask, const struct cpumask *mask);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059250)
Location: arch/x86/include/asm/apic.h:582
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810596d0)
Location: arch/x86/include/asm/apic.h:582
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a4c0)
Location: arch/x86/include/asm/apic.h:582
Inline: False
```
**Symbols:**

```
ffffffff81059250-ffffffff8105928d: default_vector_allocation_domain (STB_LOCAL)
ffffffff810596d0-ffffffff8105970d: default_vector_allocation_domain (STB_LOCAL)
ffffffff8105a4c0-ffffffff8105a4fd: default_vector_allocation_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void default_vector_allocation_domain(int cpu, struct cpumask *retmask, const struct cpumask *mask);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810596b0)
Location: arch/x86/include/asm/apic.h:589
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059920)
Location: arch/x86/include/asm/apic.h:589
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a850)
Location: arch/x86/include/asm/apic.h:589
Inline: False
```
**Symbols:**

```
ffffffff810596b0-ffffffff810596f8: default_vector_allocation_domain (STB_LOCAL)
ffffffff81059920-ffffffff81059968: default_vector_allocation_domain (STB_LOCAL)
ffffffff8105a850-ffffffff8105a898: default_vector_allocation_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void default_vector_allocation_domain(int cpu, struct cpumask *retmask, const struct cpumask *mask);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c460)
Location: arch/x86/include/asm/apic.h:589
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c6d0)
Location: arch/x86/include/asm/apic.h:589
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d570)
Location: arch/x86/include/asm/apic.h:589
Inline: False
```
**Symbols:**

```
ffffffff8105c460-ffffffff8105c4a3: default_vector_allocation_domain (STB_LOCAL)
ffffffff8105c6d0-ffffffff8105c713: default_vector_allocation_domain (STB_LOCAL)
ffffffff8105d570-ffffffff8105d5b3: default_vector_allocation_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void default_vector_allocation_domain(int cpu, struct cpumask *retmask, const struct cpumask *mask);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105bb60)
Location: arch/x86/include/asm/apic.h:569
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105be00)
Location: arch/x86/include/asm/apic.h:569
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cc70)
Location: arch/x86/include/asm/apic.h:569
Inline: False
```
**Symbols:**

```
ffffffff8105bb60-ffffffff8105bba3: default_vector_allocation_domain (STB_LOCAL)
ffffffff8105be00-ffffffff8105be43: default_vector_allocation_domain (STB_LOCAL)
ffffffff8105cc70-ffffffff8105ccb3: default_vector_allocation_domain (STB_LOCAL)
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
