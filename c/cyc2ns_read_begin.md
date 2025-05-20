# Function: <code>cyc2ns_read_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cyc2ns_data *cyc2ns_read_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037d10)
Location: arch/x86/kernel/tsc.c:82
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81037d10-ffffffff81037d22: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cyc2ns_data *cyc2ns_read_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036f20)
Location: arch/x86/kernel/tsc.c:83
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81036f20-ffffffff81036f32: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cyc2ns_data *cyc2ns_read_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036c50)
Location: arch/x86/kernel/tsc.c:84
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81036c50-ffffffff81036c62: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034e23)
Location: arch/x86/kernel/tsc.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81034dc0-ffffffff81034e00: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037183)
Location: arch/x86/kernel/tsc.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81037120-ffffffff81037160: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103817f)
Location: arch/x86/kernel/tsc.c:63
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff81037b90-ffffffff81037bd0: cyc2ns_read_begin.part.2 (STB_LOCAL)
ffffffff81038140-ffffffff8103814b: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff82892dad)
Location: arch/x86/kernel/tsc.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81039860-ffffffff810398a0: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103be50)
Location: arch/x86/kernel/tsc.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103be00-ffffffff8103be3c: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c610)
Location: arch/x86/kernel/tsc.c:62
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
ffffffff8103c5c0-ffffffff8103c5fc: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f400)
Location: arch/x86/kernel/tsc.c:69
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
ffffffff8103f3b0-ffffffff8103f3ec: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f4c0)
Location: arch/x86/kernel/tsc.c:69
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
ffffffff8103f470-ffffffff8103f4ac: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81040e30)
Location: arch/x86/kernel/tsc.c:70
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
ffffffff81040de0-ffffffff81040e1c: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81046f51)
Location: arch/x86/kernel/tsc.c:70
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
ffffffff81046ed0-ffffffff81046f19: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8104fcf1)
Location: arch/x86/kernel/tsc.c:70
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
ffffffff8104fc50-ffffffff8104fcac: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105d071)
Location: arch/x86/kernel/tsc.c:70
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
ffffffff8105cfb0-ffffffff8105d00c: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105e520)
Location: arch/x86/kernel/tsc.c:87
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8105e520-ffffffff8105e57c: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810655e0)
Location: arch/x86/kernel/tsc.c:87
Inline: False
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff810655e0-ffffffff8106563c: cyc2ns_read_begin (STB_GLOBAL)
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
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c770)
Location: arch/x86/kernel/tsc.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103c720-ffffffff8103c75c: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102be60)
Location: arch/x86/kernel/tsc.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8102be10-ffffffff8102be4c: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c5d0)
Location: arch/x86/kernel/tsc.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103c580-ffffffff8103c5bc: cyc2ns_read_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103d640)
Location: arch/x86/kernel/tsc.c:62
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
ffffffff8103d5d0-ffffffff8103d613: cyc2ns_read_begin (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct cyc2ns_data *data</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct cyc2ns_data *</code> ➡️ <code>void</code>
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
