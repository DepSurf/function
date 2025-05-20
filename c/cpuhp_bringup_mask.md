# Function: <code>cpuhp_bringup_mask</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpuhp_bringup_mask(const struct cpumask *mask, unsigned int ncpus, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff836c9ba0)
Location: kernel/cpu.c:1787
Inline: False
Direct callers:
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
```
**Symbols:**

```
ffffffff836c9ba0-ffffffff836c9c69: cpuhp_bringup_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpuhp_bringup_mask(const struct cpumask *mask, unsigned int ncpus, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff838fa810)
Location: kernel/cpu.c:1822
Inline: False
Direct callers:
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
```
**Symbols:**

```
ffffffff838fa810-ffffffff838fa8d9: cpuhp_bringup_mask (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
