# Function: <code>online_target_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *online_target_cpus();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81058fc0)
Location: arch/x86/include/asm/apic.h:486
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059610)
Location: arch/x86/include/asm/apic.h:486
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a260)
Location: arch/x86/include/asm/apic.h:486
Inline: False
```
**Symbols:**

```
ffffffff81058fc0-ffffffff81058fcd: online_target_cpus (STB_LOCAL)
ffffffff81059610-ffffffff8105961d: online_target_cpus (STB_LOCAL)
ffffffff8105a260-ffffffff8105a26d: online_target_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *online_target_cpus();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059320)
Location: arch/x86/include/asm/apic.h:493
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059860)
Location: arch/x86/include/asm/apic.h:493
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a4b0)
Location: arch/x86/include/asm/apic.h:493
Inline: False
```
**Symbols:**

```
ffffffff81059320-ffffffff8105932d: online_target_cpus (STB_LOCAL)
ffffffff81059860-ffffffff8105986d: online_target_cpus (STB_LOCAL)
ffffffff8105a4b0-ffffffff8105a4bd: online_target_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *online_target_cpus();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c0b0)
Location: arch/x86/include/asm/apic.h:493
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c610)
Location: arch/x86/include/asm/apic.h:493
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d2c0)
Location: arch/x86/include/asm/apic.h:493
Inline: False
```
**Symbols:**

```
ffffffff8105c0b0-ffffffff8105c0bd: online_target_cpus (STB_LOCAL)
ffffffff8105c610-ffffffff8105c61d: online_target_cpus (STB_LOCAL)
ffffffff8105d2c0-ffffffff8105d2cd: online_target_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *online_target_cpus();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105b7b0)
Location: arch/x86/include/asm/apic.h:489
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bd40)
Location: arch/x86/include/asm/apic.h:489
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105c9e0)
Location: arch/x86/include/asm/apic.h:489
Inline: False
```
**Symbols:**

```
ffffffff8105b7b0-ffffffff8105b7bd: online_target_cpus (STB_LOCAL)
ffffffff8105bd40-ffffffff8105bd4d: online_target_cpus (STB_LOCAL)
ffffffff8105c9e0-ffffffff8105c9ed: online_target_cpus (STB_LOCAL)
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
