# Function: <code>cpu_clustergroup_mask</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct cpumask *cpu_clustergroup_mask(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810857b0)
Location: arch/x86/kernel/smpboot.c:693
Inline: False
Direct callers:
  - drivers/base/topology.c:cluster_cpus_list_read
  - drivers/base/topology.c:cluster_cpus_read
```
**Symbols:**

```
ffffffff810857b0-ffffffff810857f9: cpu_clustergroup_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct cpumask *cpu_clustergroup_mask(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81098b40)
Location: arch/x86/kernel/smpboot.c:691
Inline: False
Direct callers:
  - drivers/base/topology.c:cluster_cpus_list_read
  - drivers/base/topology.c:cluster_cpus_read
```
**Symbols:**

```
ffffffff81098b40-ffffffff81098b89: cpu_clustergroup_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct cpumask *cpu_clustergroup_mask(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109bce0)
Location: arch/x86/kernel/smpboot.c:753
Inline: False
Direct callers:
  - drivers/base/topology.c:cluster_cpus_list_read
  - drivers/base/topology.c:cluster_cpus_read
```
**Symbols:**

```
ffffffff8109bce0-ffffffff8109bd29: cpu_clustergroup_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct cpumask *cpu_clustergroup_mask(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a32e0)
Location: arch/x86/kernel/smpboot.c:756
Inline: False
Direct callers:
  - drivers/base/topology.c:cluster_cpus_list_read
  - drivers/base/topology.c:cluster_cpus_read
```
**Symbols:**

```
ffffffff810a32e0-ffffffff810a3329: cpu_clustergroup_mask (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
