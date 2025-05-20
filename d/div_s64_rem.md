# Function: <code>div_s64_rem</code>

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
In kernel/time/time.c (ffffffff810eb0c4)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (0)
Location: include/linux/math64.h:27
Inline: True
```
```
In lib/vsprintf.c (ffffffff813f3422)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/rtc/rtc-lib.c (ffffffff81673025)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8168a056)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
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
In kernel/time/time.c (ffffffff810f1d97)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff810fea50)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff81100b56)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In lib/vsprintf.c (ffffffff8143b0ba)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/rtc/rtc-lib.c (ffffffff816d3815)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff816eae6c)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In kernel/time/time.c (ffffffff810f8f17)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff81101840)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff811038f6)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In lib/vsprintf.c (ffffffff8145808e)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/rtc/rtc-lib.c (ffffffff817034f5)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8171bd8c)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In kernel/time/time.c (ffffffff810fb1bb)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff81103942)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff81105a26)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In drivers/rtc/rtc-lib.c (ffffffff81718ce5)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8173401b)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff818f9c04)
Location: include/linux/math64.h:27
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810c9e3e)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/time/time.c (ffffffff81105b5b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff8110e9d2)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff81110a96)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In drivers/rtc/rtc-lib.c (ffffffff81789ec5)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff817a51dd)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81980882)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810d1e7a)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/time/time.c (ffffffff81110e1e)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff8111a41d)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff8111c4a5)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In drivers/rtc/rtc-lib.c (ffffffff817cafe5)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff817ecc8b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff819dc8fb)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810db7de)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
```
```
In kernel/time/time.c (ffffffff8111c5f0)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff8112591d)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff81127c55)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff813c975b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/rtc/lib.c (ffffffff817f2695)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff81818db1)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81a14dfa)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810db779)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (ffffffff81126f23)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff81130349)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff81132675)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff813f42fb)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816902eb)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81833365)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8185aeda)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81a84668)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810e5e33)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (ffffffff81132ec3)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff8113c289)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff8113e5c5)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff8140e1cb)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b2d2b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81864ca5)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8188c9ea)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81abb8cc)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810eceec)
Location: include/linux/math64.h:39
Inline: True
```
```
In kernel/time/ntp.c (ffffffff8114aeea)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:ntp_update_offset
```
```
In kernel/time/timeconv.c (ffffffff8114d7f5)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff8145bf95)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In lib/vsprintf.c (ffffffff815f7419)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81765318)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81938565)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8195b35f)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffffffff810eacea)
Location: include/linux/math64.h:39
Inline: True
```
```
In kernel/time/ntp.c (ffffffff8114731a)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:ntp_update_offset
```
```
In kernel/time/timeconv.c (ffffffff81149945)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff81477e95)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In lib/vsprintf.c (ffffffff8161b844)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81780278)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff8193e8a2)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81962020)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffffffff810ecb73)
Location: include/linux/math64.h:39
Inline: True
```
```
In kernel/time/ntp.c (ffffffff811480dc)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff8114ae15)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff8147d906)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81763b98)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81922095)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8194561f)
Location: include/linux/math64.h:39
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffffffff811057c3)
Location: include/linux/math64.h:40
Inline: True
```
```
In kernel/time/ntp.c (ffffffff8116bfb9)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:ntp_update_offset
```
```
In kernel/time/timeconv.c (ffffffff8116ec85)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff814d5186)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e8018)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff819c5005)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d73ce)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff819dafd0)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819ea04f)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/time/ntp.c (ffffffff8119ff71)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:ntp_update_offset
```
```
In kernel/time/timeconv.c (ffffffff811a2fa5)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff815621c3)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81927bd7)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81b25585)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39f56)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3e7af)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4fd03)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/time/ntp.c (ffffffff811ded6a)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:ntp_update_offset
```
```
In kernel/time/timeconv.c (ffffffff811e2565)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff81604933)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a84b08)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81cb8b05)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf8d6)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd4a95)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce7c53)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/time/ntp.c (ffffffff811f31b6)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:ntp_update_offset
```
```
In kernel/time/clocksource.c (ffffffff811f4dcc)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/timeconv.c (ffffffff811f6ac5)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff8163c843)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad01be)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81d20265)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d379cf)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3c6f5)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d50433)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffffffff8116bc8a)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:avg_vruntime
```
```
In kernel/time/ntp.c (ffffffff812092f6)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:ntp_update_offset
```
```
In kernel/time/clocksource.c (ffffffff8120af23)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/timeconv.c (ffffffff8120cc65)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In mm/ksm.c (ffffffff8148cef6)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - mm/ksm.c:scan_time_advisor
```
```
In fs/fat/misc.c (ffffffff81675dd3)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b2401e)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb5683)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
```
```
In drivers/rtc/lib.c (ffffffff81dd5f95)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedc4f)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df3035)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e07288)
Location: include/linux/math64.h:40
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010145594)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (ffff80001019a1f0)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffff8000101a6590)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffff8000101a82f8)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffff8000104eed0c)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088e4b0)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffff800010aa647c)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffff800010adb62c)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/armada_thermal.c (ffff800010ade164)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In lib/vsprintf.c (ffff800010d98784)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s64 div_s64_rem(s64 dividend, s32 divisor, s32 *remainder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/math/div64.c (c07e0898)
Location: lib/math/div64.c:71
Inline: False
Direct callers:
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
  - kernel/time/timeconv.c:time64_to_tm
  - fs/fat/misc.c:fat_truncate_time
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_read_sensor
  - drivers/thermal/armada_thermal.c:armada_read_sensor
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
c07e0898-c07e0954: div_s64_rem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001969ec)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (c0000000001fab74)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (c0000000002088dc)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (c00000000020b1b0)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (c00000000062ddc4)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000936d40)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (c000000000b86f90)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (c000000000bc31a0)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (c000000000edbe84)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f03c2)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (ffffffe00012a8d8)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffe0001326c0)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffe000134104)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffe00035ee30)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe00055828e)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffe0006b28c4)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d571c)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffe0008c0092)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
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
In kernel/sched/fair.c (ffffffff810dffe3)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (ffffffff8112b673)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff81134a39)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff81136d75)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff814067ab)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8167878b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81817955)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8183286a)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81a5a71c)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810cefe3)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (ffffffff8111dee3)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff81127499)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff811297c5)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff813f722b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165787b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff817df045)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff817f9efa)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81a177fc)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810dc363)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (ffffffff81129393)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff81132759)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff81134a95)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff81403b2b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a6b6b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81858e35)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff81881e9a)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a1a3d)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In lib/vsprintf.c (ffffffff81ac6b0c)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810e8083)
Location: include/linux/math64.h:38
Inline: True
```
```
In kernel/time/time.c (ffffffff811359e3)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_timeval
```
```
In kernel/time/ntp.c (ffffffff8113f179)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:second_overflow
  - kernel/time/ntp.c:second_overflow
```
```
In kernel/time/timeconv.c (ffffffff811414b5)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In fs/fat/misc.c (ffffffff8141979b)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c0fcb)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
```
```
In drivers/rtc/lib.c (ffffffff81873f15)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8189d905)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81ad2fec)
Location: include/linux/math64.h:38
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
