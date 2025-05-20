# Function: <code>perf_event_set_state</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811c15d2)
Location: kernel/events/core.c:656
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:list_del_event
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffffffff811b5870-ffffffff811b58c1: perf_event_set_state.part.67 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e18f6)
Location: kernel/events/core.c:656
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_del_event
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffffffff811d47e0-ffffffff811d4822: perf_event_set_state.part.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811f1d66)
Location: kernel/events/core.c:656
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_del_event
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffffffff811e44a0-ffffffff811e44e2: perf_event_set_state.part.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81209932)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_del_event
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffffffff811fb7a0-ffffffff811fb7ee: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81216ca2)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81208b50-ffffffff81208b9e: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81240d28)
Location: kernel/events/core.c:663
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
Direct callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffffffff812349a0-ffffffff81234a76: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8124b2d9)
Location: kernel/events/core.c:667
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
Direct callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffffffff8123e9b0-ffffffff8123ea86: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_set_state(struct perf_event *event, enum perf_event_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812416b0)
Location: kernel/events/core.c:665
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffffffff812416b0-ffffffff81241707: perf_event_set_state (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8128a276)
Location: kernel/events/core.c:666
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff812dec83)
Location: kernel/events/core.c:665
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff81346e82)
Location: kernel/events/core.c:659
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff81377f7c)
Location: kernel/events/core.c:659
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff813a125c)
Location: kernel/events/core.c:660
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
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
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffff80001029eafc)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
Direct callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
```
**Symbols:**

```
ffff800010292358-ffff8000102923a8: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c04ce448)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
c04c3704-c04c374c: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c000000000352f8c)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
c000000000340720-c0000000003407b8: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffe0001d0138)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffe0001c4868-ffffffe0001c48c6: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120f2f2)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81201170-ffffffff812011be: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120209c)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff811f3ec0-ffffffff811f3f0e: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120d092)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff811fef40-ffffffff811fef8e: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8121be43)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8120dfd0-ffffffff8120e01e: perf_event_set_state.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
