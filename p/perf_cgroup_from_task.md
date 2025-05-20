# Function: <code>perf_cgroup_from_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100db2e)
Location: include/linux/perf_event.h:701
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__conflict_event
  - arch/x86/events/intel/cqm.c:__conflict_event
```
```
In kernel/events/core.c (ffffffff8117aeeb)
Location: include/linux/perf_event.h:701
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100e549)
Location: include/linux/perf_event.h:813
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__conflict_event
  - arch/x86/events/intel/cqm.c:__conflict_event
```
```
In kernel/events/core.c (ffffffff8118c3d0)
Location: include/linux/perf_event.h:813
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100e609)
Location: include/linux/perf_event.h:836
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__conflict_event
  - arch/x86/events/intel/cqm.c:__conflict_event
```
```
In kernel/events/core.c (ffffffff8119b9ad)
Location: include/linux/perf_event.h:836
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811a32e5)
Location: include/linux/perf_event.h:835
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811b76d9)
Location: include/linux/perf_event.h:818
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811d70ca)
Location: include/linux/perf_event.h:836
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811e74fa)
Location: include/linux/perf_event.h:841
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811feb2e)
Location: include/linux/perf_event.h:854
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff8120bb8e)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff81234eec)
Location: include/linux/perf_event.h:915
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff8123f33c)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dca34)
Location: include/linux/perf_event.h:933
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/events/core.c (ffffffff8124350c)
Location: include/linux/perf_event.h:933
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f1558)
Location: include/linux/perf_event.h:927
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/events/core.c (ffffffff8127ddc9)
Location: include/linux/perf_event.h:927
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110d956)
Location: include/linux/perf_event.h:941
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/events/core.c (ffffffff812daa2b)
Location: include/linux/perf_event.h:941
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81134676)
Location: include/linux/perf_event.h:1035
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/events/core.c (ffffffff81342e04)
Location: include/linux/perf_event.h:1035
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81143874)
Location: include/linux/perf_event.h:1051
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/events/core.c (ffffffff81373e64)
Location: include/linux/perf_event.h:1051
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114ed94)
Location: include/linux/perf_event.h:1056
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/events/core.c (ffffffff8139cd0f)
Location: include/linux/perf_event.h:1056
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffff800010295c14)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (c04c5c64)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (c000000000343458)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffe0001c6aae)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff812041ae)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811f6f3e)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff81201f7e)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff812117c8)
Location: include/linux/perf_event.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
</ul>

## Differences
