# Function: <code>arch_update_cpu_topology</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afc60)
Location: kernel/sched/core.c:7052
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810afc60-ffffffff810afc6d: arch_update_cpu_topology (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2460)
Location: kernel/sched/core.c:6987
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810b2460-ffffffff810b246d: arch_update_cpu_topology (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053a40)
Location: arch/x86/kernel/smpboot.c:113
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff81053a40-ffffffff81053a59: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810533a0)
Location: arch/x86/kernel/smpboot.c:116
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810533a0-ffffffff810533b9: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81057150)
Location: arch/x86/kernel/smpboot.c:114
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81057150-ffffffff81057169: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81059fc0)
Location: arch/x86/kernel/smpboot.c:110
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81059fc0-ffffffff81059fd9: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105fc40)
Location: arch/x86/kernel/smpboot.c:110
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff8105fc40-ffffffff8105fc59: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063470)
Location: arch/x86/kernel/smpboot.c:114
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81063470-ffffffff81063489: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063b20)
Location: arch/x86/kernel/smpboot.c:114
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81063b20-ffffffff81063b39: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106a530)
Location: arch/x86/kernel/smpboot.c:115
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff8106a530-ffffffff8106a549: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c200)
Location: arch/x86/kernel/smpboot.c:120
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff8106c200-ffffffff8106c219: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106ccd0)
Location: arch/x86/kernel/smpboot.c:120
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff8106ccd0-ffffffff8106cce9: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81120940)
Location: arch/x86/kernel/smpboot.c:120
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81c9d3ef-ffffffff81c9d416: arch_update_cpu_topology.cold (STB_LOCAL)
ffffffff81077cc0-ffffffff81077cdf: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8114ad00)
Location: arch/x86/kernel/smpboot.c:118
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
```
**Symbols:**

```
ffffffff81e4c876-ffffffff81e4c8a7: arch_update_cpu_topology.cold (STB_LOCAL)
ffffffff81086910-ffffffff81086939: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff811796c0)
Location: arch/x86/kernel/smpboot.c:116
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
```
**Symbols:**

```
ffffffff82053b63-ffffffff82053b94: arch_update_cpu_topology.cold (STB_LOCAL)
ffffffff81099ed0-ffffffff81099ef9: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8118a2b0)
Location: arch/x86/kernel/smpboot.c:139
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
```
**Symbols:**

```
ffffffff820d216f-ffffffff820d21a0: arch_update_cpu_topology.cold (STB_LOCAL)
ffffffff8109d350-ffffffff8109d379: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81198bb0)
Location: arch/x86/kernel/smpboot.c:153
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
```
**Symbols:**

```
ffffffff821acdd3-ffffffff821ace04: arch_update_cpu_topology.cold (STB_LOCAL)
ffffffff810a4890-ffffffff810a48b9: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/numa.c (c0000000000a3950)
Location: arch/powerpc/mm/numa.c:1441
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
c0000000000a3950-c0000000000a3968: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101a14)
Location: kernel/sched/topology.c:2106
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffe000101a14-ffffffe000101a30: arch_update_cpu_topology (STB_WEAK)
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
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063610)
Location: arch/x86/kernel/smpboot.c:114
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81063610-ffffffff81063629: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053920)
Location: arch/x86/kernel/smpboot.c:114
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81053920-ffffffff81053939: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063ac0)
Location: arch/x86/kernel/smpboot.c:114
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81063ac0-ffffffff81063ad9: arch_update_cpu_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_update_cpu_topology();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81065080)
Location: arch/x86/kernel/smpboot.c:114
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81065080-ffffffff81065099: arch_update_cpu_topology (STB_GLOBAL)
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
