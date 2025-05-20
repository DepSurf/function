# Function: <code>mul_u64_u64_div_u64</code>

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
In arch/x86/events/intel/core.c (ffffffff8100bd20)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/sched/cputime.c (ffffffff810e547e)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
```
```
In kernel/time/timekeeping.c (ffffffff81145985)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff8100c6b0)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/sched/cputime.c (ffffffff810e742e)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
```
```
In kernel/time/timekeeping.c (ffffffff811468bb)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff8100df81)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/sched/cputime.c (ffffffff810fea3e)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
```
```
In kernel/time/timekeeping.c (ffffffff81169f7c)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff8100f3cb)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/sched/build_policy.c (ffffffff8112f857)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
```
```
In kernel/time/timekeeping.c (ffffffff8119db93)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff81012d7b)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/sched/build_policy.c (ffffffff811598f7)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
```
```
In kernel/time/timekeeping.c (ffffffff811dc823)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
```
In block/blk-throttle.c (ffffffff817677c3)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:__tg_update_carryover
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
In arch/x86/events/intel/core.c (ffffffff8101234b)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/sched/build_policy.c (ffffffff81169b07)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
```
```
In kernel/time/timekeeping.c (ffffffff811f0c33)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
```
In block/blk-throttle.c (ffffffff817a6947)
Location: arch/x86/include/asm/div64.h:81
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:__tg_update_carryover
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
In arch/x86/events/intel/core.c (ffffffff81017c6b)
Location: arch/x86/include/asm/div64.h:87
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/sched/build_policy.c (ffffffff81182345)
Location: arch/x86/include/asm/div64.h:87
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cputime_adjust
```
```
In kernel/time/timekeeping.c (ffffffff81206d73)
Location: arch/x86/include/asm/div64.h:87
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
```
In block/blk-throttle.c (ffffffff817e7888)
Location: arch/x86/include/asm/div64.h:87
Inline: True
Inline callers:
  - block/blk-throttle.c:calculate_bytes_allowed
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
