# Function: <code>get_tb</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/irq.c (c00000000001b4e0)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:__check_irq_replay
```
```
In arch/powerpc/kernel/time.c (c00000000002b658)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:decrementer_shutdown
  - arch/powerpc/kernel/time.c:timebase_read
  - arch/powerpc/kernel/time.c:running_clock
  - arch/powerpc/kernel/time.c:timer_interrupt
  - arch/powerpc/kernel/time.c:udelay
  - arch/powerpc/kernel/time.c:udelay
  - arch/powerpc/kernel/time.c:time_init
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037538)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:arch_touch_nmi_watchdog
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:wd_lockup_ipi
```
```
In arch/powerpc/kernel/rtas.c (c00000000003f5a4)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_give_timebase
```
```
In arch/powerpc/kernel/rtas-rtc.c (c00000000003f9f4)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas-rtc.c:rtas_set_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_set_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_boot_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_boot_time
```
```
In arch/powerpc/kernel/trace/trace_clock.c (c0000000000740e0)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - arch/powerpc/kernel/trace/trace_clock.c:trace_clock_ppc_tb
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000121c98)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_xirr_x
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_confer
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_confer
```
```
In drivers/cpuidle/cpuidle-pseries.c (c000000000c22454)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
```
```
In drivers/cpuidle/cpuidle-powernv.c (c000000000c22a90)
Location: arch/powerpc/include/asm/time.h:105
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
```
</details>
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
