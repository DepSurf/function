# Function: <code>sched_domains_numa_masks_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a6871)
Location: kernel/sched/core.c:6785
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_domains_numa_masks_update
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b28c1)
Location: kernel/sched/core.c:6751
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8eb4)
Location: kernel/sched/core.c:6848
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cc110)
Location: kernel/sched/topology.c:1468
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810cc110-ffffffff810cc1d5: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d49d0)
Location: kernel/sched/topology.c:1483
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810d49d0-ffffffff810d4a95: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dc5b0)
Location: kernel/sched/topology.c:1478
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810dc5b0-ffffffff810dc675: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e6210)
Location: kernel/sched/topology.c:1679
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810e6210-ffffffff810e62d5: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ece60)
Location: kernel/sched/topology.c:1704
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810ece60-ffffffff810ecf25: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8900)
Location: kernel/sched/topology.c:1705
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810f8900-ffffffff810f89c5: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811027b0)
Location: kernel/sched/topology.c:1690
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff811027b0-ffffffff81102875: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811013d0)
Location: kernel/sched/topology.c:1749
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff811013d0-ffffffff81101495: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103760)
Location: kernel/sched/topology.c:1777
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81103760-ffffffff81103825: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81120640)
Location: kernel/sched/topology.c:1965
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81120640-ffffffff8112081c: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114a9f0)
Location: kernel/sched/topology.c:2009
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8114a9f0-ffffffff8114aaf0: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179370)
Location: kernel/sched/topology.c:2009
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81179370-ffffffff81179470: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81189f60)
Location: kernel/sched/topology.c:2016
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81189f60-ffffffff8118a055: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81198860)
Location: kernel/sched/topology.c:2042
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81198860-ffffffff81198955: sched_domains_numa_masks_set (STB_GLOBAL)
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
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015ced8)
Location: kernel/sched/topology.c:1705
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffff80001015ced8-ffff80001015cff4: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1278
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b1940)
Location: kernel/sched/topology.c:1705
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
c0000000001b1940-c0000000001b1ab0: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1278
Inline: True
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
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f1d00)
Location: kernel/sched/topology.c:1705
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810f1d00-ffffffff810f1dc5: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e1d70)
Location: kernel/sched/topology.c:1705
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810e1d70-ffffffff810e1e35: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810eee30)
Location: kernel/sched/topology.c:1705
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810eee30-ffffffff810eeef5: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f9e70)
Location: kernel/sched/topology.c:1705
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810f9e70-ffffffff810f9f35: sched_domains_numa_masks_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
