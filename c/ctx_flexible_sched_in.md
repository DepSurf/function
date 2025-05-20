# Function: <code>ctx_flexible_sched_in</code>

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
In kernel/events/core.c (ffffffff8117cc42)
Location: kernel/events/core.c:2752
Inline: True
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
In kernel/events/core.c (ffffffff8118ef06)
Location: kernel/events/core.c:2975
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff8119e4aa)
Location: kernel/events/core.c:3046
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff811a6a64)
Location: kernel/events/core.c:3129
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff811ba1f4)
Location: kernel/events/core.c:3027
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff811d336e)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff811e370e)
Location: kernel/events/core.c:3339
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff811fa8be)
Location: kernel/events/core.c:3366
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff8120798e)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff81239b8e)
Location: kernel/events/core.c:3669
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff81244c2e)
Location: kernel/events/core.c:3738
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff812465d9)
Location: kernel/events/core.c:3760
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff8128578e)
Location: kernel/events/core.c:3853
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff812d9d4c)
Location: kernel/events/core.c:3764
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ctx_flexible_sched_in(struct perf_event_context *ctx, struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8134268a)
Location: kernel/events/core.c:3845
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
```
**Symbols:**

```
ffffffff81342140-ffffffff813421ff: ctx_flexible_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ctx_flexible_sched_in(struct perf_event_context *ctx, struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81373700)
Location: kernel/events/core.c:3845
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
```
**Symbols:**

```
ffffffff81373100-ffffffff813731bf: ctx_flexible_sched_in (STB_LOCAL)
```
</details>
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
In kernel/events/core.c (ffff800010292234)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (c04c4764)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (c0000000003423a0)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffe0001c63ee)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff811fffae)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff811f2cfe)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff811fdd7e)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
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
In kernel/events/core.c (ffffffff8120cdde)
Location: kernel/events/core.c:3451
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
