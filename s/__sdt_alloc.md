# Function: <code>__sdt_alloc</code>

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
In kernel/sched/core.c (ffffffff810af15c)
Location: kernel/sched/core.c:6845
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
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
In kernel/sched/core.c (ffffffff810b195c)
Location: kernel/sched/core.c:6780
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
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
In kernel/sched/core.c (ffffffff810b7c5c)
Location: kernel/sched/core.c:6877
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cc57c)
Location: kernel/sched/topology.c:1493
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d3266)
Location: kernel/sched/topology.c:1508
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810daf54)
Location: kernel/sched/topology.c:1503
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e4b04)
Location: kernel/sched/topology.c:1704
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ebac3)
Location: kernel/sched/topology.c:1729
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f748a)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sdt_alloc(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101130)
Location: kernel/sched/topology.c:1735
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81101130-ffffffff81101327: __sdt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sdt_alloc(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ffc90)
Location: kernel/sched/topology.c:1794
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810ffc90-ffffffff810ffe87: __sdt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sdt_alloc(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101890)
Location: kernel/sched/topology.c:1822
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81101890-ffffffff81101a81: __sdt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sdt_alloc(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111db70)
Location: kernel/sched/topology.c:2016
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8111db70-ffffffff8111ded3: __sdt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sdt_alloc(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113fd20)
Location: kernel/sched/topology.c:2072
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8113fd20-ffffffff811400a4: __sdt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sdt_alloc(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116bd30)
Location: kernel/sched/topology.c:2072
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8116bd30-ffffffff8116c0bc: __sdt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sdt_alloc(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117c290)
Location: kernel/sched/topology.c:2172
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8117c290-ffffffff8117c61c: __sdt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sdt_alloc(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81189f70)
Location: kernel/sched/topology.c:2207
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81189f70-ffffffff8118a32d: __sdt_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015b7f0)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (c03a8234)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001afe98)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffe000100a64)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f088a)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e08fa)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ed9ba)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f89fa)
Location: kernel/sched/topology.c:1750
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
