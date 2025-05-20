# Function: <code>rdtsc_ordered</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff81009ce9)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_del
```
```
In arch/x86/kernel/tsc.c (ffffffff81037764)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810528d6)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105b7b4)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81065166)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_flags
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff813f642c)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff81009faa)
Location: arch/x86/include/asm/msr.h:178
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff81036974)
Location: arch/x86/include/asm/msr.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810529f6)
Location: arch/x86/include/asm/msr.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105b7c4)
Location: arch/x86/include/asm/msr.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81064f32)
Location: arch/x86/include/asm/msr.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff8143cffc)
Location: arch/x86/include/asm/msr.h:178
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff81009fea)
Location: arch/x86/include/asm/msr.h:192
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102bb00)
Location: arch/x86/include/asm/msr.h:192
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:read_hv_clock_tsc
```
```
In arch/x86/kernel/tsc.c (ffffffff81036694)
Location: arch/x86/include/asm/msr.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055306)
Location: arch/x86/include/asm/msr.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105e754)
Location: arch/x86/include/asm/msr.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81068462)
Location: arch/x86/include/asm/msr.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff81459f7c)
Location: arch/x86/include/asm/msr.h:192
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100a49a)
Location: arch/x86/include/asm/msr.h:203
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81029ecc)
Location: arch/x86/include/asm/msr.h:203
Inline: True
```
```
In arch/x86/kernel/tsc.c (ffffffff810346a4)
Location: arch/x86/include/asm/msr.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81054c26)
Location: arch/x86/include/asm/msr.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105dde4)
Location: arch/x86/include/asm/msr.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81067792)
Location: arch/x86/include/asm/msr.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff818fbe20)
Location: arch/x86/include/asm/msr.h:203
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100a97a)
Location: arch/x86/include/asm/msr.h:204
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a05c)
Location: arch/x86/include/asm/msr.h:204
Inline: True
```
```
In arch/x86/kernel/tsc.c (ffffffff81036a04)
Location: arch/x86/include/asm/msr.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810589e6)
Location: arch/x86/include/asm/msr.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81061aa4)
Location: arch/x86/include/asm/msr.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106b9f2)
Location: arch/x86/include/asm/msr.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff81982c80)
Location: arch/x86/include/asm/msr.h:204
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100b126)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102ab02)
Location: arch/x86/include/asm/msr.h:218
Inline: True
```
```
In arch/x86/kernel/tsc.c (ffffffff81037a40)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105b8f5)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81064ba0)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106e682)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff819df090)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100b086)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102b192)
Location: arch/x86/include/asm/msr.h:218
Inline: True
```
```
In arch/x86/kernel/tsc.c (ffffffff81038c60)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105ca34)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061575)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8106a810)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff810746a2)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff81a19fc0)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100b556)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8103b1f0)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fda4)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064c65)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8106e190)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81078202)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc992)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc
```
```
In arch/x86/lib/delay.c (ffffffff81a89d91)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100b966)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8103b9c0)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060654)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810652d5)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8106f740)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81079272)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef52c)
Location: arch/x86/include/asm/msr.h:218
Inline: True
```
```
In arch/x86/lib/delay.c (ffffffff81ac1051)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100cc4a)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8103e670)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066364)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bc35)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff810769d0)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080552)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff815fd4e4)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3378)
Location: arch/x86/include/asm/msr.h:218
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100bb9a)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8103e720)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064611)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d515)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81077000)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080162)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff81622214)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3768)
Location: arch/x86/include/asm/msr.h:216
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100c52a)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff810400f0)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064bb1)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106df85)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81077a60)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080ff5)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff81605af4)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7a78)
Location: arch/x86/include/asm/msr.h:216
Inline: True
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
In arch/x86/events/msr.c (ffffffff8100ca5a)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff81046110)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106ec61)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810797a5)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81085260)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff8108ff8a)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff816743e4)
Location: arch/x86/include/asm/msr.h:216
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81a55028)
Location: arch/x86/include/asm/msr.h:216
Inline: True
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
In arch/x86/events/msr.c (ffffffff8100d85a)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8104ed20)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c40f)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81088535)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81095460)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff810a0eda)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/lib/delay.c (ffffffff8178eadb)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4348)
Location: arch/x86/include/asm/msr.h:197
Inline: True
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
In arch/x86/events/msr.c (ffffffff81010a9a)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8105bc70)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108d709)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109bfe5)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff810aafe0)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff810b8d4a)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69ad1)
Location: arch/x86/include/asm/msr.h:197
Inline: True
```
```
In arch/x86/lib/delay.c (ffffffff8204c48b)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8101015a)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8105d1a0)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810905b9)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109ef45)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff810ae450)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff82141068)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82142a11)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
```
In arch/x86/lib/delay.c (ffffffff820cad9b)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8101593b)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff81064260)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097949)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a63c5)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff810b4fd0)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff82222f78)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82225101)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
```
```
In arch/x86/lib/delay.c (ffffffff821a55cb)
Location: arch/x86/include/asm/msr.h:197
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100b966)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bb20)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810601d4)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064dc5)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8106e6e0)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81078272)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff818908fc)
Location: arch/x86/include/asm/msr.h:218
Inline: True
```
```
In arch/x86/lib/delay.c (ffffffff81a5fea1)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100a27e)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_start
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8102b2a0)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810504ff)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055095)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105eb00)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81067b22)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81849ccc)
Location: arch/x86/include/asm/msr.h:218
Inline: True
```
```
In arch/x86/lib/delay.c (ffffffff81a1cf71)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100b926)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8103b980)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060604)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065275)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8106eb90)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff81078222)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff818e435c)
Location: arch/x86/include/asm/msr.h:218
Inline: True
```
```
In arch/x86/lib/delay.c (ffffffff81acc291)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/msr.c (ffffffff8100bb06)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff8103c9a0)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061b64)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066855)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81070e10)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/pvclock.c (ffffffff8107a322)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81900fbc)
Location: arch/x86/include/asm/msr.h:218
Inline: True
```
```
In arch/x86/lib/delay.c (ffffffff81ad8778)
Location: arch/x86/include/asm/msr.h:218
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
</ul>

## Differences
