# Function: <code>cpu_cpu_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a48a0)
Location: include/linux/topology.h:208
Inline: False
```
**Symbols:**

```
ffffffff810a48a0-ffffffff810a48c6: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a7fc0)
Location: include/linux/topology.h:204
Inline: False
```
**Symbols:**

```
ffffffff810a7fc0-ffffffff810a7fe6: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053870)
Location: include/linux/topology.h:204
Inline: False
```
```
In kernel/sched/core.c (ffffffff810adfa0)
Location: include/linux/topology.h:204
Inline: False
```
**Symbols:**

```
ffffffff81053870-ffffffff81053894: cpu_cpu_mask (STB_LOCAL)
ffffffff810adfa0-ffffffff810adfc4: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810531d0)
Location: include/linux/topology.h:204
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810caf20)
Location: include/linux/topology.h:204
Inline: False
```
**Symbols:**

```
ffffffff810531d0-ffffffff810531f4: cpu_cpu_mask (STB_LOCAL)
ffffffff810caf20-ffffffff810caf44: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81056f40)
Location: include/linux/topology.h:204
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810d2680)
Location: include/linux/topology.h:204
Inline: False
```
**Symbols:**

```
ffffffff81056f40-ffffffff81056f64: cpu_cpu_mask (STB_LOCAL)
ffffffff810d2680-ffffffff810d26a4: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81059db0)
Location: include/linux/topology.h:204
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810da760)
Location: include/linux/topology.h:204
Inline: False
```
**Symbols:**

```
ffffffff81059db0-ffffffff81059dd4: cpu_cpu_mask (STB_LOCAL)
ffffffff810da760-ffffffff810da784: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105fa30)
Location: include/linux/topology.h:204
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810e42b0)
Location: include/linux/topology.h:204
Inline: False
```
**Symbols:**

```
ffffffff8105fa30-ffffffff8105fa54: cpu_cpu_mask (STB_LOCAL)
ffffffff810e42b0-ffffffff810e42d4: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81062e80)
Location: include/linux/topology.h:210
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810eaed0)
Location: include/linux/topology.h:210
Inline: False
```
**Symbols:**

```
ffffffff81062e80-ffffffff81062e9f: cpu_cpu_mask (STB_LOCAL)
ffffffff810eaed0-ffffffff810eaeef: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063530)
Location: include/linux/topology.h:225
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810f6870)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
ffffffff81063530-ffffffff8106354f: cpu_cpu_mask (STB_LOCAL)
ffffffff810f6870-ffffffff810f688f: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810696f0)
Location: include/linux/topology.h:208
Inline: False
```
```
In kernel/sched/topology.c (ffffffff81100210)
Location: include/linux/topology.h:208
Inline: False
```
**Symbols:**

```
ffffffff810696f0-ffffffff8106970f: cpu_cpu_mask (STB_LOCAL)
ffffffff81100210-ffffffff8110022f: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b2d0)
Location: include/linux/topology.h:208
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810fed70)
Location: include/linux/topology.h:208
Inline: False
```
**Symbols:**

```
ffffffff8106b2d0-ffffffff8106b2ef: cpu_cpu_mask (STB_LOCAL)
ffffffff810fed70-ffffffff810fed8f: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106bd50)
Location: include/linux/topology.h:209
Inline: False
```
```
In kernel/sched/topology.c (ffffffff81101150)
Location: include/linux/topology.h:209
Inline: False
```
**Symbols:**

```
ffffffff8106bd50-ffffffff8106bd6f: cpu_cpu_mask (STB_LOCAL)
ffffffff81101150-ffffffff8110116f: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81076850)
Location: include/linux/topology.h:209
Inline: False
```
```
In kernel/sched/topology.c (ffffffff8111d310)
Location: include/linux/topology.h:209
Inline: False
```
**Symbols:**

```
ffffffff81076850-ffffffff810768ae: cpu_cpu_mask (STB_LOCAL)
ffffffff8111d310-ffffffff8111d36e: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81085690)
Location: include/linux/topology.h:243
Inline: False
```
```
In kernel/sched/build_utility.c (ffffffff8113b5d0)
Location: include/linux/topology.h:243
Inline: False
```
**Symbols:**

```
ffffffff81085690-ffffffff810856f6: cpu_cpu_mask (STB_LOCAL)
ffffffff8113b5d0-ffffffff8113b636: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810989e0)
Location: include/linux/topology.h:243
Inline: False
```
```
In kernel/sched/build_utility.c (ffffffff81165f50)
Location: include/linux/topology.h:243
Inline: False
```
**Symbols:**

```
ffffffff810989e0-ffffffff81098a46: cpu_cpu_mask (STB_LOCAL)
ffffffff81165f50-ffffffff81165fb6: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109bb90)
Location: include/linux/topology.h:243
Inline: False
```
```
In kernel/sched/build_utility.c (ffffffff811763c0)
Location: include/linux/topology.h:243
Inline: False
```
**Symbols:**

```
ffffffff8109bb90-ffffffff8109bbf6: cpu_cpu_mask (STB_LOCAL)
ffffffff811763c0-ffffffff81176426: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a3110)
Location: include/linux/topology.h:243
Inline: False
```
```
In kernel/sched/build_utility.c (ffffffff81184620)
Location: include/linux/topology.h:243
Inline: False
```
**Symbols:**

```
ffffffff810a3110-ffffffff810a3176: cpu_cpu_mask (STB_LOCAL)
ffffffff81184620-ffffffff81184686: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015a9f8)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
ffff80001015a9f8-ffff80001015aa20: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/topology.c (c03199a0)
Location: include/linux/topology.h:225
Inline: False
```
```
In kernel/sched/topology.c (c03a75a8)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
c03199a0-c03199b8: cpu_cpu_mask (STB_LOCAL)
c03a75a8-c03a75c0: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/smp.c (c000000000053de0)
Location: include/linux/topology.h:225
Inline: False
```
```
In kernel/sched/topology.c (c0000000001aec70)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
c000000000053de0-c000000000053e3c: cpu_cpu_mask (STB_LOCAL)
c0000000001aec70-c0000000001aeccc: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe00010019e)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
ffffffe00010019e-ffffffe0001001b2: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063020)
Location: include/linux/topology.h:225
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810efc70)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
ffffffff81063020-ffffffff8106303f: cpu_cpu_mask (STB_LOCAL)
ffffffff810efc70-ffffffff810efc8f: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053330)
Location: include/linux/topology.h:225
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810dfce0)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
ffffffff81053330-ffffffff8105334f: cpu_cpu_mask (STB_LOCAL)
ffffffff810dfce0-ffffffff810dfcff: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810634d0)
Location: include/linux/topology.h:225
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810ecda0)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
ffffffff810634d0-ffffffff810634ef: cpu_cpu_mask (STB_LOCAL)
ffffffff810ecda0-ffffffff810ecdbf: cpu_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_cpu_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064a90)
Location: include/linux/topology.h:225
Inline: False
```
```
In kernel/sched/topology.c (ffffffff810f7de0)
Location: include/linux/topology.h:225
Inline: False
```
**Symbols:**

```
ffffffff81064a90-ffffffff81064aaf: cpu_cpu_mask (STB_LOCAL)
ffffffff810f7de0-ffffffff810f7dff: cpu_cpu_mask (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
