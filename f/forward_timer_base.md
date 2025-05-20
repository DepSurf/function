# Function: <code>forward_timer_base</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8189df36)
Location: kernel/time/timer.c:892
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff818d2df8)
Location: kernel/time/timer.c:892
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81909f36)
Location: kernel/time/timer.c:858
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81109af0)
Location: kernel/time/timer.c:865
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81115106)
Location: kernel/time/timer.c:880
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff81120746)
Location: kernel/time/timer.c:879
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff8112b033)
Location: kernel/time/timer.c:874
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff81136fd3)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81145c74)
Location: kernel/time/timer.c:886
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8114226d)
Location: kernel/time/timer.c:890
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8114345d)
Location: kernel/time/timer.c:892
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81166a20)
Location: kernel/time/timer.c:892
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8119a147)
Location: kernel/time/timer.c:945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff811d8849)
Location: kernel/time/timer.c:945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff811ecc79)
Location: kernel/time/timer.c:945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffffffff81202dd9)
Location: kernel/time/timer.c:966
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
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
In kernel/time/timer.c (ffff8000101a02f0)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (c03e9f60)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (c0000000002012a8)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffe0008c86dc)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
</details>
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
In kernel/time/timer.c (ffffffff8112f783)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81122203)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d4a3)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81139dba)
Location: kernel/time/timer.c:878
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
</details>
</li>
</ul>

## Differences
