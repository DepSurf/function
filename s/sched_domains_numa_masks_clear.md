# Function: <code>sched_domains_numa_masks_clear</code>

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
In kernel/sched/core.c (ffffffff810a6815)
Location: kernel/sched/core.c:6798
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
In kernel/sched/core.c (ffffffff810b2a03)
Location: kernel/sched/core.c:6764
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
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
In kernel/sched/core.c (ffffffff810b8ff3)
Location: kernel/sched/core.c:6861
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cc1e0)
Location: kernel/sched/topology.c:1481
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810cc1e0-ffffffff810cc23c: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d4aa0)
Location: kernel/sched/topology.c:1496
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810d4aa0-ffffffff810d4b24: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dc680)
Location: kernel/sched/topology.c:1491
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810dc680-ffffffff810dc703: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e62e0)
Location: kernel/sched/topology.c:1692
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810e62e0-ffffffff810e6363: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ecf30)
Location: kernel/sched/topology.c:1717
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810ecf30-ffffffff810ecf8c: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f89d0)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810f89d0-ffffffff810f8a2c: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81102880)
Location: kernel/sched/topology.c:1703
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff81102880-ffffffff811028dc: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811014a0)
Location: kernel/sched/topology.c:1762
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff811014a0-ffffffff811014fc: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103830)
Location: kernel/sched/topology.c:1790
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff81103830-ffffffff8110388c: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81120820)
Location: kernel/sched/topology.c:1984
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff81120820-ffffffff8112087c: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114aaf0)
Location: kernel/sched/topology.c:2026
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff8114aaf0-ffffffff8114ab62: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179480)
Location: kernel/sched/topology.c:2026
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff81179480-ffffffff811794f2: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a070)
Location: kernel/sched/topology.c:2033
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff8118a070-ffffffff8118a0e3: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81198970)
Location: kernel/sched/topology.c:2059
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff81198970-ffffffff811989e3: sched_domains_numa_masks_clear (STB_GLOBAL)
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
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015cff8)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffff80001015cff8-ffff80001015d0a4: sched_domains_numa_masks_clear (STB_GLOBAL)
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
Location: kernel/sched/sched.h:1279
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b1ab0)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
c0000000001b1ab0-c0000000001b1b80: sched_domains_numa_masks_clear (STB_GLOBAL)
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
Location: kernel/sched/sched.h:1279
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
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f1dd0)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810f1dd0-ffffffff810f1e2c: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e1e40)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810e1e40-ffffffff810e1e9c: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810eef00)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810eef00-ffffffff810eef5c: sched_domains_numa_masks_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f9f40)
Location: kernel/sched/topology.c:1718
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810f9f40-ffffffff810f9f9c: sched_domains_numa_masks_clear (STB_GLOBAL)
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
