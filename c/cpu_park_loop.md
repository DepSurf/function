# Function: <code>cpu_park_loop</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff800010095a48)
Location: arch/arm64/include/asm/smp.h:115
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:arm64_serror_panic
  - arch/arm64/kernel/traps.c:handle_bad_stack
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009af04)
Location: arch/arm64/include/asm/smp.h:115
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities
```
```
In arch/arm64/kernel/smp.c (ffff80001009cd28)
Location: arch/arm64/include/asm/smp.h:115
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:local_cpu_stop
  - arch/arm64/kernel/smp.c:cpu_die_early
```
```
In arch/arm64/mm/context.c (ffff8000100afa28)
Location: arch/arm64/include/asm/smp.h:115
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:verify_cpu_asid_bits
```
</details>
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
