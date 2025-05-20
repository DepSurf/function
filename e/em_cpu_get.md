# Function: <code>em_cpu_get</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct em_perf_domain *em_cpu_get(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8111c800)
Location: kernel/power/energy_model.c:179
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
```
**Symbols:**

```
ffffffff8111c800-ffffffff8111c820: em_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_cpu_get(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8111788f)
Location: kernel/power/energy_model.c:246
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
```
**Symbols:**

```
ffffffff81117190-ffffffff811171b8: em_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_cpu_get(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff81117f57)
Location: kernel/power/energy_model.c:246
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline
  - drivers/powercap/dtpm_cpu.c:get_pd_power_uw
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
```
**Symbols:**

```
ffffffff811178c0-ffffffff811178e8: em_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_cpu_get(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811382b7)
Location: kernel/power/energy_model.c:241
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline
  - drivers/powercap/dtpm_cpu.c:get_pd_power_uw
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
```
**Symbols:**

```
ffffffff81137c20-ffffffff81137c48: em_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_cpu_get(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8115a93a)
Location: kernel/power/energy_model.c:305
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
**Symbols:**

```
ffffffff8115a280-ffffffff8115a2b4: em_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_cpu_get(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8118cfa4)
Location: kernel/power/energy_model.c:302
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
**Symbols:**

```
ffffffff8118c5a0-ffffffff8118c5d4: em_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_cpu_get(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff8119e743)
Location: kernel/power/energy_model.c:302
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
**Symbols:**

```
ffffffff8119dcc0-ffffffff8119dcf4: em_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct em_perf_domain *em_cpu_get(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/energy_model.c (ffffffff811ad903)
Location: kernel/power/energy_model.c:302
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
**Symbols:**

```
ffffffff811ace30-ffffffff811ace64: em_cpu_get (STB_GLOBAL)
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
