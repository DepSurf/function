# Function: <code>get_cache_id</code>

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
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e9dc)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:931
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81042fe0)
Location: arch/x86/kernel/cpu/intel_rdt.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
**Symbols:**

```
ffffffff81042fe0-ffffffff8104303d: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c9a0)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:932
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041160)
Location: arch/x86/kernel/cpu/intel_rdt.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
**Symbols:**

```
ffffffff81041160-ffffffff810411bd: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f5a5)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:936
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044550)
Location: arch/x86/kernel/cpu/intel_rdt.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
**Symbols:**

```
ffffffff81044550-ffffffff810445ad: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040ba2)
Location: arch/x86/kernel/cpu/cacheinfo.c:978
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046770)
Location: arch/x86/kernel/cpu/intel_rdt.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
**Symbols:**

```
ffffffff81046770-ffffffff810467cd: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810421c2)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055700)
Location: arch/x86/kernel/cpu/resctrl/core.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff81055700-ffffffff8105575d: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044635)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058940)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff81058940-ffffffff8105898c: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044d85)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059210)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff81059210-ffffffff8105925c: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048eb4)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e4fa)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048374)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049b3d)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81051404)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105c9d2)
Location: arch/x86/kernel/cpu/cacheinfo.c:1007
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a9f2)
Location: arch/x86/kernel/cpu/cacheinfo.c:1020
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c362)
Location: arch/x86/kernel/cpu/cacheinfo.c:1019
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810735b2)
Location: arch/x86/kernel/cpu/cacheinfo.c:1013
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
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
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044f05)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058d90)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff81058d90-ffffffff81058ddc: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034415)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81048f80)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff81048f80-ffffffff81048fcc: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044d45)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810591c0)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff810591c0-ffffffff8105920c: get_cache_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs *id4_regs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046145)
Location: arch/x86/kernel/cpu/cacheinfo.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a660)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff8105a660-ffffffff8105a6ac: get_cache_id (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
