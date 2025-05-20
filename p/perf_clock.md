# Function: <code>perf_clock</code>

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
In kernel/events/core.c (ffffffff81178798)
Location: kernel/events/core.c:330
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff81188bf8)
Location: kernel/events/core.c:572
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
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
In kernel/events/core.c (ffffffff81197fd8)
Location: kernel/events/core.c:572
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
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
In kernel/events/core.c (ffffffff8119fb08)
Location: kernel/events/core.c:580
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
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
In kernel/events/core.c (ffffffff811b34f8)
Location: kernel/events/core.c:580
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff811d2c60)
Location: kernel/events/core.c:580
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff811e2f70)
Location: kernel/events/core.c:580
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff811fa140)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff81207210)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff81230700)
Location: kernel/events/core.c:587
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff8123a360)
Location: kernel/events/core.c:591
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff8123eb90)
Location: kernel/events/core.c:589
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff812795a0)
Location: kernel/events/core.c:590
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff812cc645)
Location: kernel/events/core.c:589
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff81334495)
Location: kernel/events/core.c:583
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff813651e5)
Location: kernel/events/core.c:583
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff8138e205)
Location: kernel/events/core.c:584
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffff800010294150)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (c04c053c)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (c00000000033e5f8)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffe0001c3782)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff811ff830)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff811f2580)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff811fd600)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
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
In kernel/events/core.c (ffffffff8120c360)
Location: kernel/events/core.c:581
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
</details>
</li>
</ul>

## Differences
