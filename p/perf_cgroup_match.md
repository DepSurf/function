# Function: <code>perf_cgroup_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117b114)
Location: kernel/events/core.c:365
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_aux_ctx
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118d326)
Location: kernel/events/core.c:585
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff8119c966)
Location: kernel/events/core.c:585
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff811a46d5)
Location: kernel/events/core.c:593
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff811b8695)
Location: kernel/events/core.c:675
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff811d7ff9)
Location: kernel/events/core.c:675
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff811e7cc9)
Location: kernel/events/core.c:675
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff811ff318)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff8120c388)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff812330b3)
Location: kernel/events/core.c:682
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff8123ce83)
Location: kernel/events/core.c:686
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff81241903)
Location: kernel/events/core.c:684
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff8127c2f3)
Location: kernel/events/core.c:702
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff812d23ba)
Location: kernel/events/core.c:701
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff8133856a)
Location: kernel/events/core.c:714
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff81368c3b)
Location: kernel/events/core.c:714
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff81391a6b)
Location: kernel/events/core.c:721
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffff800010297ccc)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_task_tick
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
In kernel/events/core.c (c04c5780)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (c0000000003444e0)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffe0001c6f8e)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff812049a8)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff811f7738)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff81202778)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
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
In kernel/events/core.c (ffffffff81212343)
Location: kernel/events/core.c:676
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
```
</details>
</li>
</ul>

## Differences
