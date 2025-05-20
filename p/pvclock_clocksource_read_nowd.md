# Function: <code>pvclock_clocksource_read_nowd</code>

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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 pvclock_clocksource_read_nowd(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff82141050)
Location: arch/x86/kernel/pvclock.c:118
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
**Symbols:**

```
ffffffff82141050-ffffffff8214114b: pvclock_clocksource_read_nowd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 pvclock_clocksource_read_nowd(struct pvclock_vcpu_time_info *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff82222f60)
Location: arch/x86/kernel/pvclock.c:118
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
**Symbols:**

```
ffffffff82222f60-ffffffff8222305b: pvclock_clocksource_read_nowd (STB_GLOBAL)
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
