# Function: <code>cpu_smt_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050e10)
Location: include/linux/sched.h:996
Inline: False
```
```
In kernel/sched/core.c (ffffffff810a48d0)
Location: include/linux/sched.h:996
Inline: False
```
**Symbols:**

```
ffffffff81050e10-ffffffff81050e1b: cpu_smt_flags (STB_LOCAL)
ffffffff810a48d0-ffffffff810a48db: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050fc0)
Location: include/linux/sched.h:1035
Inline: False
```
```
In kernel/sched/core.c (ffffffff810a7ff0)
Location: include/linux/sched.h:1035
Inline: False
```
**Symbols:**

```
ffffffff81050fc0-ffffffff81050fcb: cpu_smt_flags (STB_LOCAL)
ffffffff810a7ff0-ffffffff810a7ffb: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched.h:1074
Inline: True
```
```
In kernel/sched/core.c (ffffffff810adfd0)
Location: include/linux/sched.h:1074
Inline: False
```
**Symbols:**

```
ffffffff810adfd0-ffffffff810adfdb: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:36
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810caf50)
Location: include/linux/sched/topology.h:36
Inline: False
```
**Symbols:**

```
ffffffff810caf50-ffffffff810caf5b: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
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
In kernel/sched/topology.c (ffffffff810d26b0)
Location: include/linux/sched/topology.h:37
Inline: False
```
**Symbols:**

```
ffffffff810d26b0-ffffffff810d26bb: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
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
In kernel/sched/topology.c (ffffffff810da790)
Location: include/linux/sched/topology.h:37
Inline: False
```
**Symbols:**

```
ffffffff810da790-ffffffff810da796: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
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
In kernel/sched/topology.c (ffffffff810e42e0)
Location: include/linux/sched/topology.h:37
Inline: False
```
**Symbols:**

```
ffffffff810e42e0-ffffffff810e42e6: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:31
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810eaef0)
Location: include/linux/sched/topology.h:31
Inline: False
```
**Symbols:**

```
ffffffff810eaef0-ffffffff810eaef6: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:31
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810f6890)
Location: include/linux/sched/topology.h:31
Inline: False
```
**Symbols:**

```
ffffffff810f6890-ffffffff810f6896: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:30
Inline: True
```
```
In kernel/sched/topology.c (ffffffff81100230)
Location: include/linux/sched/topology.h:30
Inline: False
```
**Symbols:**

```
ffffffff81100230-ffffffff81100236: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:39
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810fed90)
Location: include/linux/sched/topology.h:39
Inline: False
```
**Symbols:**

```
ffffffff810fed90-ffffffff810fed96: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:39
Inline: True
```
```
In kernel/sched/topology.c (ffffffff81101170)
Location: include/linux/sched/topology.h:39
Inline: False
```
**Symbols:**

```
ffffffff81101170-ffffffff81101176: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:39
Inline: True
```
```
In kernel/sched/topology.c (ffffffff8111d370)
Location: include/linux/sched/topology.h:39
Inline: False
```
**Symbols:**

```
ffffffff8111d370-ffffffff8111d376: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:39
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8113b640)
Location: include/linux/sched/topology.h:39
Inline: False
```
**Symbols:**

```
ffffffff8113b640-ffffffff8113b64a: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:39
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81165fd0)
Location: include/linux/sched/topology.h:39
Inline: False
```
**Symbols:**

```
ffffffff81165fd0-ffffffff81165fda: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:39
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81176440)
Location: include/linux/sched/topology.h:39
Inline: False
```
**Symbols:**

```
ffffffff81176440-ffffffff8117644a: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:39
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff811846a0)
Location: include/linux/sched/topology.h:39
Inline: False
```
**Symbols:**

```
ffffffff811846a0-ffffffff811846aa: cpu_smt_flags (STB_LOCAL)
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
int cpu_smt_flags();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015aa20)
Location: include/linux/sched/topology.h:31
Inline: False
```
**Symbols:**

```
ffff80001015aa20-ffff80001015aa28: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_smt_flags();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001aecd0)
Location: include/linux/sched/topology.h:31
Inline: False
```
**Symbols:**

```
c0000000001aecd0-c0000000001aecd8: cpu_smt_flags (STB_LOCAL)
```
</details>
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
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:31
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810efc90)
Location: include/linux/sched/topology.h:31
Inline: False
```
**Symbols:**

```
ffffffff810efc90-ffffffff810efc96: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:31
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810dfd00)
Location: include/linux/sched/topology.h:31
Inline: False
```
**Symbols:**

```
ffffffff810dfd00-ffffffff810dfd06: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:31
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810ecdc0)
Location: include/linux/sched/topology.h:31
Inline: False
```
**Symbols:**

```
ffffffff810ecdc0-ffffffff810ecdc6: cpu_smt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int cpu_smt_flags();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/topology.h:31
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810f7e00)
Location: include/linux/sched/topology.h:31
Inline: False
```
**Symbols:**

```
ffffffff810f7e00-ffffffff810f7e06: cpu_smt_flags (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
