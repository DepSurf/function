# Function: <code>bitmap_full</code>

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
In lib/idr.c (ffffffff813e9fa0)
Location: include/linux/bitmap.h:290
Inline: True
Inline callers:
  - lib/idr.c:idr_mark_full
  - lib/idr.c:idr_get_empty_slot
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
In lib/idr.c (ffffffff81430b52)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_mark_full
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
In lib/idr.c (0)
Location: include/linux/bitmap.h:303
Inline: True
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
In lib/idr.c (ffffffff818ecd53)
Location: include/linux/bitmap.h:300
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
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
In lib/idr.c (ffffffff81972d73)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
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
In lib/idr.c (ffffffff819cf357)
Location: include/linux/bitmap.h:349
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
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
In drivers/gpio/gpiolib.c (ffffffff8151fcf6)
Location: include/linux/bitmap.h:350
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffffffff81a08a36)
Location: include/linux/bitmap.h:350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (ffffffff8154de80)
Location: include/linux/bitmap.h:350
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffffffff81a78411)
Location: include/linux/bitmap.h:350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (ffffffff8156f080)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffffffff81aaf6d0)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In lib/idr.c (ffffffff815e9575)
Location: include/linux/bitmap.h:390
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff81613540)
Location: include/linux/bitmap.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In fs/iomap/buffered-io.c (ffffffff813bc4b0)
Location: include/linux/bitmap.h:388
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/idr.c (ffffffff8160e625)
Location: include/linux/bitmap.h:388
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff8163842e)
Location: include/linux/bitmap.h:388
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
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
In fs/iomap/buffered-io.c (ffffffff813c3209)
Location: include/linux/bitmap.h:388
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/idr.c (ffffffff815f1f30)
Location: include/linux/bitmap.h:388
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff8161bf71)
Location: include/linux/bitmap.h:388
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
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
In fs/iomap/buffered-io.c (ffffffff81412b87)
Location: include/linux/bitmap.h:394
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/idr.c (ffffffff8165f0ae)
Location: include/linux/bitmap.h:394
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff8168b452)
Location: include/linux/bitmap.h:394
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
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
In fs/iomap/buffered-io.c (ffffffff81488fff)
Location: include/linux/bitmap.h:414
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/idr.c (ffffffff8177891a)
Location: include/linux/bitmap.h:414
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff817a8884)
Location: include/linux/bitmap.h:414
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
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
In fs/iomap/buffered-io.c (ffffffff8151cc79)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/gpio/gpiolib.c (ffffffff818c1212)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In lib/idr.c (ffffffff820216b5)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In kernel/trace/trace.c (ffffffff8127b1ab)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff8135dac5)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_full
```
```
In fs/iomap/buffered-io.c (ffffffff81554e48)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/gpio/gpiolib.c (ffffffff819041b4)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In lib/idr.c (ffffffff820a16fb)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In kernel/trace/trace.c (ffffffff81295d8b)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff81386865)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_full
```
```
In fs/iomap/buffered-io.c (ffffffff8158afe7)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_free
  - fs/iomap/buffered-io.c:ifs_set_range_uptodate
```
```
In drivers/gpio/gpiolib.c (ffffffff8194bbd8)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In lib/idr.c (ffffffff82179724)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (ffff8000106c4fe4)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffff800010d88fcc)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (c0863118)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (c0e84038)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (c000000000841b38)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (c000000000ec9bc8)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (ffffffe0004a9632)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffffffe0008b2f02)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (ffffffff81564840)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffffffff81a4e520)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (ffffffff81555690)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffffffff81a0b610)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (ffffffff815633b0)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffffffff81aba910)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In drivers/gpio/gpiolib.c (ffffffff8157d2d0)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In lib/idr.c (ffffffff81ac6d60)
Location: include/linux/bitmap.h:374
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
</details>
</li>
</ul>

## Differences
