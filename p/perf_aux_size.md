# Function: <code>perf_aux_size</code>

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
In kernel/events/ring_buffer.c (ffffffff81185882)
Location: kernel/events/internal.h:113
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff81197e40)
Location: kernel/events/internal.h:121
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff811a7820)
Location: kernel/events/internal.h:121
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff811aefc3)
Location: kernel/events/internal.h:121
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff811c2b53)
Location: kernel/events/internal.h:122
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff811e2f19)
Location: kernel/events/internal.h:122
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff811f3370)
Location: kernel/events/internal.h:122
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff8120b071)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff81218351)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/core.c (ffffffff81241a42)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff81243eb8)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/core.c (ffffffff8124c16f)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff8124e548)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/core.c (ffffffff81250318)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff81252e40)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/core.c (ffffffff8128b06a)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff8128e730)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/core.c (ffffffff812df9fe)
Location: kernel/events/internal.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff812e3601)
Location: kernel/events/internal.h:129
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/core.c (ffffffff81347ea8)
Location: kernel/events/internal.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff8134bc91)
Location: kernel/events/internal.h:129
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/core.c (ffffffff81378f56)
Location: kernel/events/internal.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff8137ccd9)
Location: kernel/events/internal.h:129
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/core.c (ffffffff813a2262)
Location: kernel/events/internal.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff813a5f39)
Location: kernel/events/internal.h:129
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffff8000102a2de0)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (c04d2920)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (c000000000355118)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffe0001d0d46)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff812109a1)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff81203731)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff8120e741)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
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
In kernel/events/ring_buffer.c (ffffffff8121d651)
Location: kernel/events/internal.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
</details>
</li>
</ul>

## Differences
