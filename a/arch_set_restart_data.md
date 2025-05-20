# Function: <code>arch_set_restart_data</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143b1c)
Location: arch/x86/include/asm/thread_info.h:224
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114b3df)
Location: arch/x86/include/asm/thread_info.h:224
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fe4f)
Location: arch/x86/include/asm/thread_info.h:224
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
```
In kernel/futex.c (ffffffff81157941)
Location: arch/x86/include/asm/thread_info.h:224
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In fs/select.c (ffffffff8133b45d)
Location: arch/x86/include/asm/thread_info.h:224
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
```
</details>
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
