# Function: <code>trace_cpu_frequency</code>

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
In drivers/cpufreq/cpufreq.c (ffffffff816aec4c)
Location: include/trace/events/power.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816ba681)
Location: include/trace/events/power.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
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
In drivers/cpufreq/cpufreq.c (ffffffff8171052c)
Location: include/trace/events/power.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c2e4)
Location: include/trace/events/power.h:138
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_min_pstate
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810d4b97)
Location: include/trace/events/power.h:143
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8174254f)
Location: include/trace/events/power.h:143
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174ec17)
Location: include/trace/events/power.h:143
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_prepare_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d36da)
Location: include/trace/events/power.h:143
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81760bea)
Location: include/trace/events/power.h:143
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d84d)
Location: include/trace/events/power.h:143
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db2a9)
Location: include/trace/events/power.h:144
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d6bad)
Location: include/trace/events/power.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2bcc)
Location: include/trace/events/power.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e34f0)
Location: include/trace/events/power.h:144
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8181f810)
Location: include/trace/events/power.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182be12)
Location: include/trace/events/power.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810edbc0)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184b6b0)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81857e02)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f49b4)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188e754)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189b18a)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100635)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c1274)
Location: include/trace/events/power.h:145
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cd33a)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b175)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819945da)
Location: include/trace/events/power.h:145
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0523)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819974a9)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a327d)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
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
In drivers/cpufreq/cpufreq.c (ffffffff8197c22a)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81987cf8)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
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
In drivers/cpufreq/cpufreq.c (ffffffff81a254a7)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a31ab9)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
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
In drivers/cpufreq/cpufreq.c (ffffffff81b8ee94)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9dd78)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
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
In drivers/cpufreq/cpufreq.c (ffffffff81d2e6e6)
Location: include/trace/events/power.h:167
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3fbcd)
Location: include/trace/events/power.h:167
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
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
In drivers/cpufreq/cpufreq.c (ffffffff81d97696)
Location: include/trace/events/power.h:167
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81daa73d)
Location: include/trace/events/power.h:167
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
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
In drivers/cpufreq/cpufreq.c (ffffffff81e4f316)
Location: include/trace/events/power.h:167
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e62881)
Location: include/trace/events/power.h:167
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffff800010164db4)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1e68c)
Location: include/trace/events/power.h:145
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b13e8)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (c0bf8d14)
Location: include/trace/events/power.h:145
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bbe54)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (c000000000c11164)
Location: include/trace/events/power.h:145
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9945)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81865994)
Location: include/trace/events/power.h:145
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81870f3a)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9b25)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182e647)
Location: include/trace/events/power.h:145
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183bf85)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6b65)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b6724)
Location: include/trace/events/power.h:145
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c27ea)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81101bc5)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d29d4)
Location: include/trace/events/power.h:145
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818deafa)
Location: include/trace/events/power.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
</details>
</li>
</ul>

## Differences
