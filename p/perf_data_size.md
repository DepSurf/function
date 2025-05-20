# Function: <code>perf_data_size</code>

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
In kernel/events/core.c (0)
Location: kernel/events/internal.h:108
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:108
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
In kernel/events/core.c (ffffffff81192fb0)
Location: kernel/events/internal.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff81198119)
Location: kernel/events/internal.h:116
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff811a2790)
Location: kernel/events/internal.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff811a7af9)
Location: kernel/events/internal.h:116
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff811a9e02)
Location: kernel/events/internal.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff811af2b0)
Location: kernel/events/internal.h:116
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff811bd6f2)
Location: kernel/events/internal.h:117
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff811c2e70)
Location: kernel/events/internal.h:117
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff811dd940)
Location: kernel/events/internal.h:117
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff811e31e6)
Location: kernel/events/internal.h:117
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff811edd40)
Location: kernel/events/internal.h:117
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff811f369b)
Location: kernel/events/internal.h:117
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff812057b6)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff8120b37f)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff81212b46)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff8121865f)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff8123ebce)
Location: kernel/events/internal.h:119
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff81244220)
Location: kernel/events/internal.h:119
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff81248fbe)
Location: kernel/events/internal.h:119
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff8124e8c1)
Location: kernel/events/internal.h:119
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff8124d18e)
Location: kernel/events/internal.h:119
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff812531de)
Location: kernel/events/internal.h:119
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff81286d9e)
Location: kernel/events/internal.h:119
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff8128eadf)
Location: kernel/events/internal.h:119
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff812db679)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff812e39dd)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff81343946)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff8134c08d)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff813749a9)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff8137d0dd)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff8139dcd9)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff813a633d)
Location: kernel/events/internal.h:124
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffff80001029cf34)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffff8000102a3100)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (c04cc5c4)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (c04d2c24)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (c00000000034d88c)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (c00000000035550c)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cdfb4)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffe0001d1992)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff8120b196)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff81210caf)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff811fdf66)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff81203a3f)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff81208f36)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff8120ea4f)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In kernel/events/core.c (ffffffff81217cc6)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (ffffffff8121d95f)
Location: kernel/events/internal.h:118
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
</details>
</li>
</ul>

## Differences
