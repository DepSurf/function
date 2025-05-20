# Function: <code>cyc2ns_read_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cyc2ns_read_end(struct cyc2ns_data *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037d30)
Location: arch/x86/kernel/tsc.c:100
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81037d30-ffffffff81037d44: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cyc2ns_read_end(struct cyc2ns_data *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036f40)
Location: arch/x86/kernel/tsc.c:101
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81036f40-ffffffff81036f54: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cyc2ns_read_end(struct cyc2ns_data *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036c70)
Location: arch/x86/kernel/tsc.c:102
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81036c70-ffffffff81036c84: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034e47)
Location: arch/x86/kernel/tsc.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81034e00-ffffffff81034e06: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810371a7)
Location: arch/x86/kernel/tsc.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81037160-ffffffff81037166: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810381aa)
Location: arch/x86/kernel/tsc.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81038150-ffffffff81038156: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810398e8)
Location: arch/x86/kernel/tsc.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff810398a0-ffffffff810398a6: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103be84)
Location: arch/x86/kernel/tsc.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103be40-ffffffff8103be41: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c644)
Location: arch/x86/kernel/tsc.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
**Symbols:**

```
ffffffff8103c600-ffffffff8103c601: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f434)
Location: arch/x86/kernel/tsc.c:86
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
**Symbols:**

```
ffffffff8103f3f0-ffffffff8103f3f1: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f4f4)
Location: arch/x86/kernel/tsc.c:86
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103f4b0-ffffffff8103f4b1: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81040e64)
Location: arch/x86/kernel/tsc.c:87
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81040e20-ffffffff81040e21: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81046fa5)
Location: arch/x86/kernel/tsc.c:87
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81046f20-ffffffff81046f21: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8104fd5e)
Location: arch/x86/kernel/tsc.c:87
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8104fcb0-ffffffff8104fccd: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105d0de)
Location: arch/x86/kernel/tsc.c:87
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8105d020-ffffffff8105d03d: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105e590)
Location: arch/x86/kernel/tsc.c:93
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8105e590-ffffffff8105e5ad: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81065650)
Location: arch/x86/kernel/tsc.c:93
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81065650-ffffffff8106566d: cyc2ns_read_end (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c7a4)
Location: arch/x86/kernel/tsc.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103c760-ffffffff8103c761: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102be94)
Location: arch/x86/kernel/tsc.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8102be50-ffffffff8102be51: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c604)
Location: arch/x86/kernel/tsc.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103c5c0-ffffffff8103c5c1: cyc2ns_read_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103d691)
Location: arch/x86/kernel/tsc.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
**Symbols:**

```
ffffffff8103d620-ffffffff8103d635: cyc2ns_read_end (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct cyc2ns_data *head</code>
</li>
</ul>
</details>
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
