# Function: <code>hv_get_register</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8103162d)
Location: arch/x86/include/asm/mshyperv.h:23
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff832259d2)
Location: arch/x86/include/asm/mshyperv.h:23
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff8330fbac)
Location: arch/x86/include/asm/mshyperv.h:23
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
```
In drivers/hv/hv_common.c (ffffffff81a61095)
Location: arch/x86/include/asm/mshyperv.h:23
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:__hv_read_ref_counter
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff834c99e3)
Location: arch/x86/include/asm/mshyperv.h:201
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
```
In drivers/hv/hv_common.c (ffffffff81bd1735)
Location: arch/x86/include/asm/mshyperv.h:201
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:__hv_read_ref_counter
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff810456f9)
Location: arch/x86/include/asm/mshyperv.h:199
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83f0b091)
Location: arch/x86/include/asm/mshyperv.h:199
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
```
In drivers/hv/hv_common.c (ffffffff81d7d245)
Location: arch/x86/include/asm/mshyperv.h:199
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:__hv_read_ref_counter
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 hv_get_register(unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: arch/x86/kernel/cpu/mshyperv.c:90
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/hv/hv_common.c:__hv_read_ref_counter
  - drivers/hv/hv_common.c:hv_common_cpu_init
  - drivers/hv/hv_common.c:hv_common_init
```
**Symbols:**

```
ffffffff820d1fc8-ffffffff820d1fdd: hv_get_register.cold (STB_LOCAL)
ffffffff81098f50-ffffffff81098fc5: hv_get_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 hv_get_register(unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: arch/x86/kernel/cpu/mshyperv.c:95
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/hv/hv_common.c:__hv_read_ref_counter
  - drivers/hv/hv_common.c:hv_common_cpu_init
  - drivers/hv/hv_common.c:hv_common_init
```
**Symbols:**

```
ffffffff821acc2c-ffffffff821acc41: hv_get_register.cold (STB_LOCAL)
ffffffff810a0560-ffffffff810a0629: hv_get_register (STB_GLOBAL)
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
