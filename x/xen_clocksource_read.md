# Function: <code>xen_clocksource_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
cycle_t xen_clocksource_read();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81023510)
Location: arch/x86/xen/time.c:155
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
**Symbols:**

```
ffffffff81023510-ffffffff81023527: xen_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
cycle_t xen_clocksource_read();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8102299d)
Location: arch/x86/xen/time.c:42
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
**Symbols:**

```
ffffffff810228e0-ffffffff810228f7: xen_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810230ed)
Location: arch/x86/xen/time.c:42
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
**Symbols:**

```
ffffffff81023030-ffffffff81023047: xen_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101ad94)
Location: arch/x86/xen/time.c:42
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
**Symbols:**

```
ffffffff8101ad10-ffffffff8101ad27: xen_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101b694)
Location: arch/x86/xen/time.c:43
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
**Symbols:**

```
ffffffff8101b610-ffffffff8101b627: xen_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101c18a)
Location: arch/x86/xen/time.c:43
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
**Symbols:**

```
ffffffff8101c000-ffffffff8101c017: xen_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff82889168)
Location: arch/x86/xen/time.c:45
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff828a0416)
Location: arch/x86/xen/time.c:45
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff828a3506)
Location: arch/x86/xen/time.c:45
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810209d2)
Location: arch/x86/xen/time.c:45
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
Direct callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
```
**Symbols:**

```
ffffffff81020410-ffffffff81020427: xen_clocksource_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81021412)
Location: arch/x86/xen/time.c:46
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
Direct callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
```
**Symbols:**

```
ffffffff81020e40-ffffffff81020e57: xen_clocksource_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810237b4)
Location: arch/x86/xen/time.c:46
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
Direct callers:
  - arch/x86/xen/time.c:xen_init_time_common
```
**Symbols:**

```
ffffffff810231e0-ffffffff810231f7: xen_clocksource_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81027a54)
Location: arch/x86/xen/time.c:46
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
Direct callers:
  - arch/x86/xen/time.c:xen_init_time_common
```
**Symbols:**

```
ffffffff810273f0-ffffffff81027407: xen_clocksource_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8102be4e)
Location: arch/x86/xen/time.c:46
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
Direct callers:
  - arch/x86/xen/time.c:xen_init_time_common
```
**Symbols:**

```
ffffffff8102b600-ffffffff8102b63a: xen_clocksource_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff83e6af45)
Location: arch/x86/xen/time.c:46
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8368b9e5)
Location: arch/x86/xen/time.c:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff838bb5a5)
Location: arch/x86/xen/time.c:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff82891506)
Location: arch/x86/xen/time.c:45
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff828a4506)
Location: arch/x86/xen/time.c:45
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 xen_clocksource_read();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e1b0)
Location: arch/x86/xen/time.c:45
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
**Symbols:**

```
ffffffff8101e1b0-ffffffff8101e1de: xen_clocksource_read (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>cycle_t</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
</ul>
