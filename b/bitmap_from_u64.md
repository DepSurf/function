# Function: <code>bitmap_from_u64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81198e9c)
Location: include/linux/bitmap.h:352
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/events/core.c (ffffffff811a0f7c)
Location: include/linux/bitmap.h:373
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/events/core.c (ffffffff811b4b0c)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/events/core.c (ffffffff811d3a0b)
Location: include/linux/bitmap.h:459
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/events/core.c (ffffffff811e3ddb)
Location: include/linux/bitmap.h:460
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffff811dacc9)
Location: include/linux/bitmap.h:460
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff811fafab)
Location: include/linux/bitmap.h:460
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffff811e72cf)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff8120807b)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffff8120c3a8)
Location: include/linux/bitmap.h:541
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff81230ceb)
Location: include/linux/bitmap.h:541
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffff812078f8)
Location: include/linux/bitmap.h:539
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff8123a8fb)
Location: include/linux/bitmap.h:539
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (0)
Location: include/linux/bitmap.h:539
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitmap.h:539
Inline: True
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
In kernel/bpf/verifier.c (0)
Location: include/linux/bitmap.h:545
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitmap.h:545
Inline: True
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
In kernel/bpf/verifier.c (0)
Location: include/linux/bitmap.h:538
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitmap.h:538
Inline: True
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
In kernel/bpf/verifier.c (0)
Location: include/linux/bitmap.h:566
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitmap.h:566
Inline: True
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
In kernel/bpf/verifier.c (0)
Location: include/linux/bitmap.h:564
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitmap.h:564
Inline: True
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
In kernel/bpf/verifier.c (0)
Location: include/linux/bitmap.h:601
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitmap.h:601
Inline: True
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
In kernel/bpf/verifier.c (ffff80001026ad58)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffff8000102917c0)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (c049ca00)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (c04c272c)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (c000000000310928)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (c00000000033fbf0)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffe0001a54c4)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffe0001c4162)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffff811df8ef)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff8120069b)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffff811d26af)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff811f33eb)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffff811dd6bf)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff811fe46b)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
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
In kernel/bpf/verifier.c (ffffffff811ebacf)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/events/core.c (ffffffff8120d4cb)
Location: include/linux/bitmap.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
```
</details>
</li>
</ul>

## Differences
