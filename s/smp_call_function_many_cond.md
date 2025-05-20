# Function: <code>smp_call_function_many_cond</code>

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
void smp_call_function_many_cond(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait, smp_cond_func_t cond_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f630)
Location: kernel/smp.c:477
Inline: False
Direct callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
```
**Symbols:**

```
ffffffff8115f630-ffffffff8115f8e8: smp_call_function_many_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void smp_call_function_many_cond(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait, smp_cond_func_t cond_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b5d0)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
```
**Symbols:**

```
ffffffff8115b5d0-ffffffff8115b888: smp_call_function_many_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void smp_call_function_many_cond(const struct cpumask *mask, smp_call_func_t func, void *info, unsigned int scf_flags, smp_cond_func_t cond_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115c690)
Location: kernel/smp.c:862
Inline: False
Direct callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff8115c690-ffffffff8115c945: smp_call_function_many_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void smp_call_function_many_cond(const struct cpumask *mask, smp_call_func_t func, void *info, unsigned int scf_flags, smp_cond_func_t cond_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:864
Inline: False
Direct callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff811817b0-ffffffff81181aff: smp_call_function_many_cond (STB_LOCAL)
ffffffff81cb23b7-ffffffff81cb23cb: smp_call_function_many_cond.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void smp_call_function_many_cond(const struct cpumask *mask, smp_call_func_t func, void *info, unsigned int scf_flags, smp_cond_func_t cond_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:883
Inline: False
Direct callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff811b7dc0-ffffffff811b815f: smp_call_function_many_cond (STB_LOCAL)
ffffffff81e6395d-ffffffff81e63971: smp_call_function_many_cond.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void smp_call_function_many_cond(const struct cpumask *mask, smp_call_func_t func, void *info, unsigned int scf_flags, smp_cond_func_t cond_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:882
Inline: False
Direct callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff811f9070-ffffffff811f9411: smp_call_function_many_cond (STB_LOCAL)
ffffffff8205bf8f-ffffffff8205bfab: smp_call_function_many_cond.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void smp_call_function_many_cond(const struct cpumask *mask, smp_call_func_t func, void *info, unsigned int scf_flags, smp_cond_func_t cond_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:736
Inline: False
Direct callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff8120dd20-ffffffff8120e298: smp_call_function_many_cond (STB_LOCAL)
ffffffff820da759-ffffffff820da775: smp_call_function_many_cond.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void smp_call_function_many_cond(const struct cpumask *mask, smp_call_func_t func, void *info, unsigned int scf_flags, smp_cond_func_t cond_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:756
Inline: False
Direct callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff812254b0-ffffffff81225a28: smp_call_function_many_cond (STB_LOCAL)
ffffffff821b62c9-ffffffff821b62e5: smp_call_function_many_cond.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int scf_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wait</code>
</li>
</ul>
</details>
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
