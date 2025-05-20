# Function: <code>perf_rotate_context</code>

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
In kernel/events/core.c (ffffffff8117d2ec)
Location: kernel/events/core.c:3073
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff8118f59c)
Location: kernel/events/core.c:3309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff8119eb8c)
Location: kernel/events/core.c:3380
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff811a732c)
Location: kernel/events/core.c:3467
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff811ba979)
Location: kernel/events/core.c:3370
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff811da3f0)
Location: kernel/events/core.c:3687
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff811ea250)
Location: kernel/events/core.c:3682
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff81201030)
Location: kernel/events/core.c:3709
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff8120de70)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool perf_rotate_context(struct perf_cpu_context *cpuctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b080)
Location: kernel/events/core.c:4029
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff8123b080-ffffffff8123b415: perf_rotate_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool perf_rotate_context(struct perf_cpu_context *cpuctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812456a0)
Location: kernel/events/core.c:4106
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff812456a0-ffffffff81245a35: perf_rotate_context (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812494b0)
Location: kernel/events/core.c:4135
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff81285cd0)
Location: kernel/events/core.c:4231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff812da306)
Location: kernel/events/core.c:4130
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool perf_rotate_context(struct perf_cpu_pmu_context *cpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81342210)
Location: kernel/events/core.c:4237
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff81342210-ffffffff81342531: perf_rotate_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool perf_rotate_context(struct perf_cpu_pmu_context *cpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813731d0)
Location: kernel/events/core.c:4237
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff813731d0-ffffffff813735a1: perf_rotate_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool perf_rotate_context(struct perf_cpu_pmu_context *cpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139d450)
Location: kernel/events/core.c:4269
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff8139d450-ffffffff8139d822: perf_rotate_context (STB_LOCAL)
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
In kernel/events/core.c (ffff800010299edc)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (c04c9504)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (c0000000003498e0)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffe0001cca1c)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff81206490)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff811f9210)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff81204260)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
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
In kernel/events/core.c (ffffffff81210fb0)
Location: kernel/events/core.c:3806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
