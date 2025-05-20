# Function: <code>change_bit</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a5ed)
Location: include/asm-generic/bitops-instrumented.h:113
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff816108a9)
Location: include/asm-generic/bitops/instrumented-atomic.h:55
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff81636c99)
Location: include/asm-generic/bitops/instrumented-atomic.h:55
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff8161a5b9)
Location: include/asm-generic/bitops/instrumented-atomic.h:55
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff81689959)
Location: include/asm-generic/bitops/instrumented-atomic.h:55
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff817a6899)
Location: include/asm-generic/bitops/instrumented-atomic.h:55
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff818be90d)
Location: include/asm-generic/bitops/instrumented-atomic.h:55
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff81901aa9)
Location: include/asm-generic/bitops/instrumented-atomic.h:55
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff819495e9)
Location: include/asm-generic/bitops/instrumented-atomic.h:55
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffff8000106bf9a0)
Location: include/asm-generic/bitops/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083a32c)
Location: arch/powerpc/include/asm/bitops.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffe0004a4bd2)
Location: arch/riscv/include/asm/bitops.h:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff8155fdad)
Location: include/asm-generic/bitops-instrumented.h:113
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff81550bfd)
Location: include/asm-generic/bitops-instrumented.h:113
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff8155e91d)
Location: include/asm-generic/bitops-instrumented.h:113
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
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
In drivers/gpio/gpiolib.c (ffffffff815787ad)
Location: include/asm-generic/bitops-instrumented.h:113
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
```
</details>
</li>
</ul>

## Differences
