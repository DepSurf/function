# Function: <code>hv_set_register</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff832259f1)
Location: arch/x86/include/asm/mshyperv.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
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
In drivers/clocksource/hyperv_timer.c (ffffffff8330fbcb)
Location: arch/x86/include/asm/mshyperv.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
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
In drivers/clocksource/hyperv_timer.c (ffffffff834c9a01)
Location: arch/x86/include/asm/mshyperv.h:212
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
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
In arch/x86/hyperv/hv_init.c (ffffffff81045709)
Location: arch/x86/include/asm/mshyperv.h:210
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83f0b0fb)
Location: arch/x86/include/asm/mshyperv.h:210
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hv_set_register(unsigned int reg, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: arch/x86/kernel/cpu/mshyperv.c:99
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
```
**Symbols:**

```
ffffffff820d1fdd-ffffffff820d1ff2: hv_set_register.cold (STB_LOCAL)
ffffffff81099090-ffffffff810990fd: hv_set_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hv_set_register(unsigned int reg, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: arch/x86/kernel/cpu/mshyperv.c:104
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
  - drivers/hv/hv_common.c:hv_kmsg_dump
```
**Symbols:**

```
ffffffff821acc41-ffffffff821acc56: hv_set_register.cold (STB_LOCAL)
ffffffff810a06f0-ffffffff810a075d: hv_set_register (STB_GLOBAL)
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
