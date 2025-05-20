# Function: <code>perf_output_sample_ustack</code>

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
In kernel/events/core.c (ffffffff81183347)
Location: kernel/events/core.c:5131
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff81195256)
Location: kernel/events/core.c:5448
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff811a4cb6)
Location: kernel/events/core.c:5546
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff811ac36c)
Location: kernel/events/core.c:5638
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff811bfcfc)
Location: kernel/events/core.c:5588
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff811dfdfe)
Location: kernel/events/core.c:5945
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff811f024e)
Location: kernel/events/core.c:5954
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff81207aa3)
Location: kernel/events/core.c:6032
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff81214e13)
Location: kernel/events/core.c:6148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_output_sample_ustack(struct perf_output_handle *handle, u64 dump_size, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81232070)
Location: kernel/events/core.c:6415
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81232070-ffffffff81232202: perf_output_sample_ustack (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8124bbcc)
Location: kernel/events/core.c:6494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff8124fcca)
Location: kernel/events/core.c:6605
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff8128aa21)
Location: kernel/events/core.c:6729
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff812df478)
Location: kernel/events/core.c:6637
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff8134737c)
Location: kernel/events/core.c:6895
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff81378722)
Location: kernel/events/core.c:6895
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff813a1a24)
Location: kernel/events/core.c:6968
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
void perf_output_sample_ustack(struct perf_output_handle *handle, u64 dump_size, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010298388)
Location: kernel/events/core.c:6148
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffff800010298388-ffff800010298678: perf_output_sample_ustack (STB_LOCAL)
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
In kernel/events/core.c (c04ceb3c)
Location: kernel/events/core.c:6148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_output_sample_ustack(struct perf_output_handle *handle, u64 dump_size, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000342740)
Location: kernel/events/core.c:6148
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
c000000000342740-c000000000342a18: perf_output_sample_ustack (STB_LOCAL)
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
In kernel/events/core.c (ffffffe0001ce96c)
Location: kernel/events/core.c:6148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff8120d463)
Location: kernel/events/core.c:6148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff81200233)
Location: kernel/events/core.c:6148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff8120b203)
Location: kernel/events/core.c:6148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/events/core.c (ffffffff8121a013)
Location: kernel/events/core.c:6148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
