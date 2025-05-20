# Function: <code>kprobe_gone</code>

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
In kernel/kprobes.c (0)
Location: include/linux/kprobes.h:133
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kprobes.h:133
Inline: True
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
In kernel/kprobes.c (0)
Location: include/linux/kprobes.h:133
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kprobes.h:133
Inline: True
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
In kernel/kprobes.c (0)
Location: include/linux/kprobes.h:133
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kprobes.h:133
Inline: True
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
In kernel/kprobes.c (0)
Location: include/linux/kprobes.h:134
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kprobes.h:134
Inline: True
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
In kernel/kprobes.c (0)
Location: include/linux/kprobes.h:134
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/kprobes.h:134
Inline: True
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
In kernel/kprobes.c (ffffffff8115c8e3)
Location: include/linux/kprobes.h:134
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6b1a)
Location: include/linux/kprobes.h:134
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff811695f3)
Location: include/linux/kprobes.h:127
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b4f89)
Location: include/linux/kprobes.h:127
Inline: True
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
In kernel/kprobes.c (ffffffff8117649d)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c3cdc)
Location: include/linux/kprobes.h:114
Inline: True
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
In kernel/kprobes.c (ffffffff811823bd)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811cf0bf)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff8119535f)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb341)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff81191fff)
Location: include/linux/kprobes.h:116
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811e9491)
Location: include/linux/kprobes.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff81192ed3)
Location: include/linux/kprobes.h:116
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ea321)
Location: include/linux/kprobes.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff811bbc8d)
Location: include/linux/kprobes.h:108
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121b161)
Location: include/linux/kprobes.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff811ef28d)
Location: include/linux/kprobes.h:108
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125a3f2)
Location: include/linux/kprobes.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff81235aad)
Location: include/linux/kprobes.h:109
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/trace_kprobe.c (ffffffff812aa812)
Location: include/linux/kprobes.h:109
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff8124c8c7)
Location: include/linux/kprobes.h:109
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ccfd3)
Location: include/linux/kprobes.h:109
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff812667c7)
Location: include/linux/kprobes.h:108
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ea9c3)
Location: include/linux/kprobes.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffff8000101f6c10)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffff80001024f900)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (c0436f38)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (c048293c)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (c00000000026d070)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (c0000000002ed040)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff8117a9dd)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c76df)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff8116db7d)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ba4bf)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff811787ad)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c54af)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
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
In kernel/kprobes.c (ffffffff8118607d)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d370f)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
</details>
</li>
</ul>

## Differences
