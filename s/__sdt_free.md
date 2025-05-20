# Function: <code>__sdt_free</code>

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
In kernel/sched/core.c (ffffffff810af3f0)
Location: kernel/sched/core.c:6898
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
In kernel/sched/core.c (ffffffff810b1bfd)
Location: kernel/sched/core.c:6833
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
In kernel/sched/core.c (ffffffff810b7f7b)
Location: kernel/sched/core.c:6942
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
In kernel/sched/topology.c (ffffffff810cc899)
Location: kernel/sched/topology.c:1562
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
In kernel/sched/topology.c (ffffffff810d373d)
Location: kernel/sched/topology.c:1577
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
In kernel/sched/topology.c (ffffffff810db3ff)
Location: kernel/sched/topology.c:1572
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
In kernel/sched/topology.c (ffffffff810e5008)
Location: kernel/sched/topology.c:1773
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
In kernel/sched/topology.c (ffffffff810ebfb8)
Location: kernel/sched/topology.c:1798
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
In kernel/sched/topology.c (ffffffff810f77de)
Location: kernel/sched/topology.c:1819
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
void __sdt_free(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81100b20)
Location: kernel/sched/topology.c:1804
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81100b20-ffffffff81100c99: __sdt_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sdt_free(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ff670)
Location: kernel/sched/topology.c:1863
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810ff670-ffffffff810ff7e9: __sdt_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sdt_free(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101710)
Location: kernel/sched/topology.c:1891
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81101710-ffffffff81101889: __sdt_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sdt_free(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111d7c0)
Location: kernel/sched/topology.c:2085
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8111d7c0-ffffffff8111d9fe: __sdt_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sdt_free(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141190)
Location: kernel/sched/topology.c:2141
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81141190-ffffffff811413cb: __sdt_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sdt_free(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116c470)
Location: kernel/sched/topology.c:2141
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8116c470-ffffffff8116c6ba: __sdt_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sdt_free(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117c8c0)
Location: kernel/sched/topology.c:2241
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8117c8c0-ffffffff8117cb0a: __sdt_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sdt_free(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a5f0)
Location: kernel/sched/topology.c:2276
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8118a5f0-ffffffff8118a83a: __sdt_free (STB_LOCAL)
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
In kernel/sched/topology.c (ffff80001015bb28)
Location: kernel/sched/topology.c:1819
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
In kernel/sched/topology.c (c03a85dc)
Location: kernel/sched/topology.c:1819
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
In kernel/sched/topology.c (c0000000001b0288)
Location: kernel/sched/topology.c:1819
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
In kernel/sched/topology.c (ffffffe000100d1e)
Location: kernel/sched/topology.c:1819
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
In kernel/sched/topology.c (ffffffff810f0bde)
Location: kernel/sched/topology.c:1819
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
In kernel/sched/topology.c (ffffffff810e0c4e)
Location: kernel/sched/topology.c:1819
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
In kernel/sched/topology.c (ffffffff810edd0e)
Location: kernel/sched/topology.c:1819
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
In kernel/sched/topology.c (ffffffff810f8d4e)
Location: kernel/sched/topology.c:1819
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
