# Function: <code>pvclock_clocksource_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
cycle_t pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81065190)
Location: arch/x86/kernel/pvclock.c:74
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81065190-ffffffff81065258: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
cycle_t pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81064f20)
Location: arch/x86/kernel/pvclock.c:74
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81064f20-ffffffff81064fd0: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81068450)
Location: arch/x86/kernel/pvclock.c:74
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81068450-ffffffff81068500: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81067780)
Location: arch/x86/kernel/pvclock.c:76
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81067780-ffffffff81067830: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8106b9e0)
Location: arch/x86/kernel/pvclock.c:78
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff8106b9e0-ffffffff8106ba90: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8106e670)
Location: arch/x86/kernel/pvclock.c:78
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff8106e670-ffffffff8106e72e: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81074690)
Location: arch/x86/kernel/pvclock.c:78
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81074690-ffffffff8107474e: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810781f0)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff810781f0-ffffffff810782ab: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81079260)
Location: arch/x86/kernel/pvclock.c:67
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
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81079260-ffffffff8107931b: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81080540)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81080540-ffffffff810805fe: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81080150)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81080150-ffffffff8108020e: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81080fe0)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81080fe0-ffffffff810810a1: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pvclock.c (0)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81c9f258-ffffffff81c9f2a4: pvclock_clocksource_read.cold (STB_LOCAL)
ffffffff8108ff70-ffffffff8109004b: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pvclock.c (0)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81e4e99e-ffffffff81e4e9ea: pvclock_clocksource_read.cold (STB_LOCAL)
ffffffff810a0ec0-ffffffff810a0fa7: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pvclock.c (0)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
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
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff82054519-ffffffff82054565: pvclock_clocksource_read.cold (STB_LOCAL)
ffffffff810b8d30-ffffffff810b8e17: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pvclock.c (0)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff820d2b0a-ffffffff820d2b56: pvclock_clocksource_read.cold (STB_LOCAL)
ffffffff810bbf00-ffffffff810bbfe4: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pvclock.c (0)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff821ad96c-ffffffff821ad9b8: pvclock_clocksource_read.cold (STB_LOCAL)
ffffffff810c3080-ffffffff810c3164: pvclock_clocksource_read (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81078260)
Location: arch/x86/kernel/pvclock.c:67
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
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81078260-ffffffff8107831b: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81067b10)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81067b10-ffffffff81067bcb: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81078210)
Location: arch/x86/kernel/pvclock.c:67
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
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff81078210-ffffffff810782cb: pvclock_clocksource_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8107a310)
Location: arch/x86/kernel/pvclock.c:67
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_clocksource_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_read
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
```
**Symbols:**

```
ffffffff8107a310-ffffffff8107a3cb: pvclock_clocksource_read (STB_GLOBAL)
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
