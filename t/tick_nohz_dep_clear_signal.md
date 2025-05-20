# Function: <code>tick_nohz_dep_clear_signal</code>

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
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tick_nohz_dep_clear_signal(struct signal_struct *sig, enum tick_dep_bits bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:513
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
**Symbols:**

```
ffffffff821b60c3-ffffffff821b60e1: tick_nohz_dep_clear_signal.cold (STB_LOCAL)
ffffffff8121c990-ffffffff8121c9d1: tick_nohz_dep_clear_signal (STB_GLOBAL)
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tick_nohz_dep_clear_signal(struct signal_struct *sig, enum tick_dep_bits bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811348c0)
Location: kernel/time/tick-sched.c:366
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff811348c0-ffffffff811348de: tick_nohz_dep_clear_signal (STB_GLOBAL)
```
</details>
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
</ul>
<b>Flavor</b>
<ul>
</ul>
