# Function: <code>dirty_sched_domain_sysctl</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d84b0)
Location: kernel/sched/debug.c:396
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810d84b0-ffffffff810d84cf: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810df920)
Location: kernel/sched/debug.c:371
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810df920-ffffffff810df93e: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810ea0a0)
Location: kernel/sched/debug.c:372
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810ea0a0-ffffffff810ea0be: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f0e90)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f0e90-ffffffff810f0ead: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810fcb40)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810fcb40-ffffffff810fcb5d: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff811072d0)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff811072d0-ffffffff811072ed: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff81105ae0)
Location: kernel/sched/debug.c:413
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81105ae0-ffffffff81105afd: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff81107a30)
Location: kernel/sched/debug.c:424
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81107a30-ffffffff81107a4d: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff81125b20)
Location: kernel/sched/debug.c:437
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81125b20-ffffffff81125b3d: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811495a8)
Location: kernel/sched/debug.c:437
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81146250-ffffffff81146275: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177e75)
Location: kernel/sched/debug.c:438
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81173490-ffffffff811734b5: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81188b77)
Location: kernel/sched/debug.c:484
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff811840a0-ffffffff811840c5: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81197450)
Location: kernel/sched/debug.c:482
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81192750-ffffffff81192775: dirty_sched_domain_sysctl (STB_GLOBAL)
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
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010161f18)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffff800010161f18-ffff800010161f80: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03ae72c)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
c03ae72c-c03ae77c: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b8220)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
c0000000001b8220-c0000000001b8268: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe000105c8e)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffe000105c8e-ffffffe000105cda: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f5e70)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f5e70-ffffffff810f5e8d: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810e6030)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810e6030-ffffffff810e604d: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f3070)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f3070-ffffffff810f308d: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dirty_sched_domain_sysctl(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810fe070)
Location: kernel/sched/debug.c:359
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810fe070-ffffffff810fe08d: dirty_sched_domain_sysctl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
