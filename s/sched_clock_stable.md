# Function: <code>sched_clock_stable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b11b0)
Location: kernel/sched/clock.c:83
Inline: True
Inline callers:
  - kernel/sched/clock.c:__set_sched_clock_stable
  - kernel/sched/clock.c:__clear_sched_clock_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:cpu_clock
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
```
**Symbols:**

```
ffffffff810b1270-ffffffff810b1284: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b3d27)
Location: kernel/sched/clock.c:84
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:__clear_sched_clock_stable
  - kernel/sched/clock.c:__set_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
```
**Symbols:**

```
ffffffff810b3df0-ffffffff810b3e04: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810ba367)
Location: kernel/sched/clock.c:84
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:__clear_sched_clock_stable
  - kernel/sched/clock.c:__set_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
```
**Symbols:**

```
ffffffff810ba430-ffffffff810ba444: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b4e30)
Location: kernel/sched/clock.c:123
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
```
**Symbols:**

```
ffffffff810b4d30-ffffffff810b4d44: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810bc125)
Location: kernel/sched/clock.c:123
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
```
**Symbols:**

```
ffffffff810bc030-ffffffff810bc044: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c37b0)
Location: kernel/sched/clock.c:111
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810c36c0-ffffffff810c36d4: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810cca90)
Location: kernel/sched/clock.c:107
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810cc9a0-ffffffff810cc9b4: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d4e80)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810d4da0-ffffffff810d4dae: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810df440)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810df360-ffffffff810df36e: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e7750)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/ring_buffer.c:rb_handle_timestamp
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810e7650-ffffffff810e765e: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e5390)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/ring_buffer.c:rb_add_timestamp
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810e5290-ffffffff810e529e: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e7340)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810e7240-ffffffff810e724e: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810fe960)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/trace.c:late_trace_init
```
**Symbols:**

```
ffffffff810fe870-ffffffff810fe87b: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81145033)
Location: kernel/sched/clock.c:106
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/trace/trace.c:late_trace_init
```
**Symbols:**

```
ffffffff81144e90-ffffffff81144ea3: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811719f3)
Location: kernel/sched/clock.c:106
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/trace/trace.c:late_trace_init
```
**Symbols:**

```
ffffffff81172380-ffffffff81172393: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81182e00)
Location: kernel/sched/clock.c:106
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/trace/trace.c:late_trace_init
```
**Symbols:**

```
ffffffff81182b90-ffffffff81182ba3: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811916a0)
Location: kernel/sched/clock.c:106
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/trace/ring_buffer.c:rb_add_timestamp
  - kernel/trace/trace.c:late_trace_init
```
**Symbols:**

```
ffffffff81191410-ffffffff81191423: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:2408
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:2408
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:2408
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:2408
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d9630)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810d9550-ffffffff810d955e: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c8010)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810c7f30-ffffffff810c7f3e: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d5970)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810d5890-ffffffff810d589e: sched_clock_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sched_clock_stable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e1260)
Location: kernel/sched/clock.c:108
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:clear_sched_clock_stable
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace.c:tracing_set_default_clock
```
**Symbols:**

```
ffffffff810e1180-ffffffff810e118e: sched_clock_stable (STB_GLOBAL)
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
