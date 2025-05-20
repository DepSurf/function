# Function: <code>init_cpu_ftr_reg</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void init_cpu_ftr_reg(u32 sys_reg, u64 new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/cpufeature.c (ffff800011434ebc)
Location: arch/arm64/kernel/cpufeature.c:512
Inline: False
Direct callers:
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
```
**Symbols:**

```
ffff800011434ebc-ffff800011434fd8: init_cpu_ftr_reg (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
