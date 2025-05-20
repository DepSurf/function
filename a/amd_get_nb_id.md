# Function: <code>amd_get_nb_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81042550)
Location: arch/x86/kernel/cpu/amd.c:380
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
```
**Symbols:**

```
ffffffff81042550-ffffffff81042571: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81042460)
Location: arch/x86/kernel/cpu/amd.c:375
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff81042460-ffffffff81042481: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81041f50)
Location: arch/x86/kernel/cpu/amd.c:389
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff81041f50-ffffffff81041f71: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81040090)
Location: arch/x86/kernel/cpu/amd.c:391
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff81040090-ffffffff810400b1: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81043450)
Location: arch/x86/kernel/cpu/amd.c:401
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff81043450-ffffffff81043471: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81045540)
Location: arch/x86/kernel/cpu/amd.c:399
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff81045540-ffffffff81045561: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81046f90)
Location: arch/x86/kernel/cpu/amd.c:398
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff81046f90-ffffffff81046fb1: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81049be0)
Location: arch/x86/kernel/cpu/amd.c:402
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff81049be0-ffffffff81049c01: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a570)
Location: arch/x86/kernel/cpu/amd.c:404
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff8104a570-ffffffff8104a591: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104eb80)
Location: arch/x86/kernel/cpu/amd.c:427
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff8104eb80-ffffffff8104eba1: amd_get_nb_id (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a6e0)
Location: arch/x86/kernel/cpu/amd.c:404
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff8104a6e0-ffffffff8104a701: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81039be0)
Location: arch/x86/kernel/cpu/amd.c:404
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - drivers/edac/mce_amd.c:amd_decode_mce
```
**Symbols:**

```
ffffffff81039be0-ffffffff81039c01: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a520)
Location: arch/x86/kernel/cpu/amd.c:404
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff8104a520-ffffffff8104a541: amd_get_nb_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u16 amd_get_nb_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b930)
Location: arch/x86/kernel/cpu/amd.c:404
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
**Symbols:**

```
ffffffff8104b930-ffffffff8104b951: amd_get_nb_id (STB_GLOBAL)
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
