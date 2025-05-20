# Function: <code>__get_cpu_context</code>

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
In kernel/events/core.c (ffffffff8117a100)
Location: kernel/events/core.c:341
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_aux_ctx
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff8118e7c0)
Location: kernel/events/core.c:143
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8119e210)
Location: kernel/events/core.c:143
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811a5520)
Location: kernel/events/core.c:147
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811b7b10)
Location: kernel/events/core.c:147
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811d97a0)
Location: kernel/events/core.c:147
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811e8e50)
Location: kernel/events/core.c:147
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81200990)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff812126d0)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8123ea90)
Location: kernel/events/core.c:153
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81248e80)
Location: kernel/events/core.c:156
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8124d050)
Location: kernel/events/core.c:157
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81289c20)
Location: kernel/events/core.c:158
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff812dd475)
Location: kernel/events/core.c:158
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:event_function
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029cb68)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (c04cc184)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (c00000000034d2c4)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffe0001d008a)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8120ad20)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811fdb00)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81208ac0)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81217850)
Location: kernel/events/core.c:146
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:event_function
```
</details>
</li>
</ul>

## Differences
