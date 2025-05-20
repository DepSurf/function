# Function: <code>trace_cpu_idle_rcuidle</code>

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
In arch/x86/kernel/process.c (ffffffff81038dd4)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
```
```
In kernel/sched/idle.c (ffffffff810c3e74)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bb9ae)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81038016)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff810c7b6a)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d270)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff818d3b7f)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff818d3d9b)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174fe50)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8190acbf)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff8190aefb)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176e90b)
Location: include/trace/events/power.h:34
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8199502f)
Location: include/trace/events/power.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff8199526b)
Location: include/trace/events/power.h:35
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e414d)
Location: include/trace/events/power.h:35
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff819f15af)
Location: include/trace/events/power.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff819f17cb)
Location: include/trace/events/power.h:35
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d3bd)
Location: include/trace/events/power.h:35
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81a2c9e1)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff81a2cc6d)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8185939e)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81a9cb3f)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff81a9cddb)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cce2)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81ad438f)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff81ad462b)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf002)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81bcc47b)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff81bcc69b)
Location: include/trace/events/power.h:36
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a17e7)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
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
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/kernel/process.c (ffff800010088e40)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
```
```
In kernel/sched/idle.c (ffff800010da7190)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26d88)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/arm/mach-omap2/pm34xx.c (c033d650)
Location: include/trace/events/power.h:36
Inline: True
```
```
In kernel/sched/idle.c (c0e9eda4)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (c0c01be4)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/sched/idle.c (c000000000ee9a40)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1dea8)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/sched/idle.c (ffffffe0008c920a)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
</details>
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
In arch/x86/kernel/process.c (ffffffff81a731ff)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff81a7349b)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872ac2)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81a2f5bf)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff81a2f82b)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c8a2)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81adf60f)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff81adf8ab)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c44b2)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81aebd9f)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In kernel/sched/idle.c (ffffffff81aec07b)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0832)
Location: include/trace/events/power.h:36
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
</li>
</ul>

## Differences
