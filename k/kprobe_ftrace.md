# Function: <code>kprobe_ftrace</code>

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
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:151
Inline: True
```
```
In kernel/kprobes.c (ffffffff8112d33a)
Location: include/linux/kprobes.h:151
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
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
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:151
Inline: True
```
```
In kernel/kprobes.c (ffffffff811354fa)
Location: include/linux/kprobes.h:151
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
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
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:151
Inline: True
```
```
In kernel/kprobes.c (ffffffff8113f27a)
Location: include/linux/kprobes.h:151
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
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
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:152
Inline: True
```
```
In kernel/kprobes.c (ffffffff81140806)
Location: include/linux/kprobes.h:152
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
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
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:152
Inline: True
```
```
In kernel/kprobes.c (ffffffff8114d6a6)
Location: include/linux/kprobes.h:152
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81069425)
Location: include/linux/kprobes.h:152
Inline: True
```
```
In kernel/kprobes.c (ffffffff8115c086)
Location: include/linux/kprobes.h:152
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff81168e37)
Location: include/linux/kprobes.h:145
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff81175ac4)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff81181934)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff811970c8)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff81194248)
Location: include/linux/kprobes.h:134
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff811952c4)
Location: include/linux/kprobes.h:134
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff811be1b4)
Location: include/linux/kprobes.h:126
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff811f15a7)
Location: include/linux/kprobes.h:126
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff81235a8d)
Location: include/linux/kprobes.h:127
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff8124c8aa)
Location: include/linux/kprobes.h:127
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff812667aa)
Location: include/linux/kprobes.h:126
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffff8000101f6c4c)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:arm_kprobe
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
In kernel/kprobes.c (c0436f7c)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:disarm_kprobe
  - kernel/kprobes.c:arm_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (c00000000026d0c4)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81179f54)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff8116d0f4)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff81177d24)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:alloc_aggr_kprobe
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
In kernel/kprobes.c (ffffffff811855e4)
Location: include/linux/kprobes.h:132
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:alloc_aggr_kprobe
```
</details>
</li>
</ul>

## Differences
