# Function: <code>getnstimeofday64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f59a0)
Location: kernel/time/timekeeping.c:676
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
Direct callers:
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/blktrace.c:blk_trace_startstop
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_build
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff810f59a0-ffffffff810f59c7: getnstimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fdd28)
Location: kernel/time/timekeeping.c:681
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
Direct callers:
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/blktrace.c:blk_trace_startstop
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_add_one
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff810fcac0-ffffffff810fcae7: getnstimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100b18)
Location: kernel/time/timekeeping.c:710
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
Direct callers:
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/blktrace.c:blk_trace_startstop
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_add_one
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff810ff9e0-ffffffff810ffa07: getnstimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81102c58)
Location: kernel/time/timekeeping.c:742
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/blktrace.c:blk_trace_startstop
  - fs/kernfs/dir.c:kernfs_add_one
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff811010c0-ffffffff811010cd: getnstimeofday64.part.5 (STB_LOCAL)
ffffffff81101b30-ffffffff81101b4b: getnstimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110dc54)
Location: kernel/time/timekeeping.c:746
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff8110bef0-ffffffff8110befd: getnstimeofday64.part.4 (STB_LOCAL)
ffffffff8110ca30-ffffffff8110ca4b: getnstimeofday64 (STB_GLOBAL)
```
</details>
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
</ul>
