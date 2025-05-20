# Function: <code>perf_event_update_time</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3070)
Location: kernel/events/core.c:638
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811b3070-ffffffff811b3102: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d2870)
Location: kernel/events/core.c:638
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811d2870-ffffffff811d28fb: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e2b70)
Location: kernel/events/core.c:638
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811e2b70-ffffffff811e2bfb: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f9d00)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811f9d00-ffffffff811f9d86: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81206dd0)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81206dd0-ffffffff81206e56: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81232580)
Location: kernel/events/core.c:645
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_context_sched_out
```
**Symbols:**

```
ffffffff81232580-ffffffff81232606: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123c090)
Location: kernel/events/core.c:649
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_context_sched_out
```
**Symbols:**

```
ffffffff8123c090-ffffffff8123c116: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812406e0)
Location: kernel/events/core.c:647
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_set_state
  - kernel/events/core.c:perf_event_set_state
```
**Symbols:**

```
ffffffff812406e0-ffffffff81240773: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127b0b0)
Location: kernel/events/core.c:648
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffffffff8127b0b0-ffffffff8127b175: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cead0)
Location: kernel/events/core.c:647
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff812cead0-ffffffff812cebb0: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81336bb0)
Location: kernel/events/core.c:641
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81336bb0-ffffffff81336c90: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81367920)
Location: kernel/events/core.c:641
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81367920-ffffffff81367a00: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81390840)
Location: kernel/events/core.c:642
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81390840-ffffffff81390920: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010290b80)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffff800010290b80-ffff800010290bf4: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04bfc50)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
c04bfc50-c04bfd14: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033d5d0)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
c00000000033d5d0-c00000000033d668: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c3108)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffe0001c3108-ffffffe0001c3168: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff3f0)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811ff3f0-ffffffff811ff476: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2140)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811f2140-ffffffff811f21c6: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd1c0)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811fd1c0-ffffffff811fd246: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120be90)
Location: kernel/events/core.c:639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff8120be90-ffffffff8120bf16: perf_event_update_time (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
