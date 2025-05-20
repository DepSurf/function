# Function: <code>sign_extend32</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111d405)
Location: include/linux/bitops.h:162
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff8112b2ff)
Location: include/linux/bitops.h:162
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
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
In kernel/futex.c (ffffffff81134f53)
Location: include/linux/bitops.h:143
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff8114034f)
Location: include/linux/bitops.h:143
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff8114c3bf)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff8115a96e)
Location: include/linux/bitops.h:165
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex.c (ffffffff8115699e)
Location: include/linux/bitops.h:168
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex.c (ffffffff81157dbe)
Location: include/linux/bitops.h:168
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex.c (ffffffff8117cc3e)
Location: include/linux/bitops.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex/waitwake.c (ffffffff811b672c)
Location: include/linux/bitops.h:135
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
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
In kernel/futex/waitwake.c (ffffffff811f787c)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
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
In kernel/futex/waitwake.c (ffffffff8120c2cc)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
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
In kernel/futex/waitwake.c (ffffffff812235cc)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
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
In arch/arm64/kernel/probes/simulate-insn.c (ffff800010da8f88)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_ldrsw_literal
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_ldr_literal
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_tbz_tbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_cbz_cbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_b_bl
```
```
In kernel/futex.c (ffff8000101bb564)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
```
```
In drivers/clk/imx/clk-pllv2.c (ffff8000107d4d74)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv2.c:__clk_pllv2_recalc_rate
```
```
In drivers/thermal/armada_thermal.c (ffff800010adda4c)
Location: include/linux/bitops.h:150
Inline: True
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
In kernel/futex.c (c0400454)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
```
```
In drivers/clk/imx/clk-pllv2.c (c08fc06c)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv2.c:__clk_pllv2_recalc_rate
```
```
In drivers/thermal/armada_thermal.c (c0bbf630)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_read_sensor
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
In kernel/futex.c (c00000000021ca34)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex.c (ffffffe00013e690)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff811449df)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff81137cef)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff8114288f)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff8114ecd3)
Location: include/linux/bitops.h:150
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
</ul>

## Differences
