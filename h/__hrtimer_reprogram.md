# Function: <code>__hrtimer_reprogram</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8116794f)
Location: kernel/time/hrtimer.c:655
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
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
In kernel/time/hrtimer.c (ffffffff8119b300)
Location: kernel/time/hrtimer.c:655
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
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
In kernel/time/hrtimer.c (ffffffff811d9b70)
Location: kernel/time/hrtimer.c:655
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
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
In kernel/time/hrtimer.c (ffffffff811edca0)
Location: kernel/time/hrtimer.c:657
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
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
In kernel/time/hrtimer.c (ffffffff81204000)
Location: kernel/time/hrtimer.c:657
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
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
