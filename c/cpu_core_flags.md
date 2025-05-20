# Function: <code>cpu_core_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050e20)
Location: include/linux/sched.h:1003
Inline: False
```
```
In kernel/sched/core.c (ffffffff810a48e0)
Location: include/linux/sched.h:1003
Inline: False
```
**Symbols:**

```
ffffffff81050e20-ffffffff81050e2b: cpu_core_flags (STB_LOCAL)
ffffffff810a48e0-ffffffff810a48eb: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050fd0)
Location: include/linux/sched.h:1042
Inline: False
```
```
In kernel/sched/core.c (ffffffff810a8000)
Location: include/linux/sched.h:1042
Inline: False
```
**Symbols:**

```
ffffffff81050fd0-ffffffff81050fdb: cpu_core_flags (STB_LOCAL)
ffffffff810a8000-ffffffff810a800b: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched.h:1081
Inline: True
```
```
In kernel/sched/core.c (ffffffff810adfe0)
Location: include/linux/sched.h:1081
Inline: False
```
**Symbols:**

```
ffffffff810adfe0-ffffffff810adfeb: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:43
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810caf60)
Location: include/linux/sched/topology.h:43
Inline: False
```
**Symbols:**

```
ffffffff810caf60-ffffffff810caf6b: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:44
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810d26c0)
Location: include/linux/sched/topology.h:44
Inline: False
```
**Symbols:**

```
ffffffff810d26c0-ffffffff810d26cb: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:44
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810da7a0)
Location: include/linux/sched/topology.h:44
Inline: False
```
**Symbols:**

```
ffffffff810da7a0-ffffffff810da7a6: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:44
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810e42f0)
Location: include/linux/sched/topology.h:44
Inline: False
```
**Symbols:**

```
ffffffff810e42f0-ffffffff810e42f6: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:38
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810eaf00)
Location: include/linux/sched/topology.h:38
Inline: False
```
**Symbols:**

```
ffffffff810eaf00-ffffffff810eaf06: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:38
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810f68a0)
Location: include/linux/sched/topology.h:38
Inline: False
```
**Symbols:**

```
ffffffff810f68a0-ffffffff810f68a6: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:37
Inline: True
```
```
In kernel/sched/topology.c (ffffffff81100240)
Location: include/linux/sched/topology.h:37
Inline: False
```
**Symbols:**

```
ffffffff81100240-ffffffff81100246: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:46
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810feda0)
Location: include/linux/sched/topology.h:46
Inline: False
```
**Symbols:**

```
ffffffff810feda0-ffffffff810feda6: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:46
Inline: True
```
```
In kernel/sched/topology.c (ffffffff81101180)
Location: include/linux/sched/topology.h:46
Inline: False
```
**Symbols:**

```
ffffffff81101180-ffffffff81101186: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:46
Inline: True
```
```
In kernel/sched/topology.c (ffffffff8111d380)
Location: include/linux/sched/topology.h:46
Inline: False
```
**Symbols:**

```
ffffffff8111d380-ffffffff8111d386: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:53
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched/topology.h:53
Inline: False
```
**Symbols:**

```
ffffffff8113fbd0-ffffffff8113fbda: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:53
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched/topology.h:53
Inline: False
```
**Symbols:**

```
ffffffff8116a640-ffffffff8116a64a: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:53
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched/topology.h:53
Inline: False
```
**Symbols:**

```
ffffffff8117ad50-ffffffff8117ad5a: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:53
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff811846e0)
Location: include/linux/sched/topology.h:53
Inline: False
```
**Symbols:**

```
ffffffff811846e0-ffffffff811846ea: cpu_core_flags (STB_LOCAL)
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
int cpu_core_flags();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015aa28)
Location: include/linux/sched/topology.h:38
Inline: False
```
**Symbols:**

```
ffff80001015aa28-ffff80001015aa30: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/topology.c (c03199b8)
Location: include/linux/sched/topology.h:38
Inline: False
```
```
In kernel/sched/topology.c (c03a75c0)
Location: include/linux/sched/topology.h:38
Inline: False
```
**Symbols:**

```
c03199b8-c03199cc: cpu_core_flags (STB_LOCAL)
c03a75c0-c03a75d4: cpu_core_flags (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:38
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810efca0)
Location: include/linux/sched/topology.h:38
Inline: False
```
**Symbols:**

```
ffffffff810efca0-ffffffff810efca6: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:38
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810dfd10)
Location: include/linux/sched/topology.h:38
Inline: False
```
**Symbols:**

```
ffffffff810dfd10-ffffffff810dfd16: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:38
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810ecdd0)
Location: include/linux/sched/topology.h:38
Inline: False
```
**Symbols:**

```
ffffffff810ecdd0-ffffffff810ecdd6: cpu_core_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_core_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:38
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810f7e10)
Location: include/linux/sched/topology.h:38
Inline: False
```
**Symbols:**

```
ffffffff810f7e10-ffffffff810f7e16: cpu_core_flags (STB_LOCAL)
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
