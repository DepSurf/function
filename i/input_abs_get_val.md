# Function: <code>input_abs_get_val</code>

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
In drivers/input/input.c (ffffffff81669d7e)
Location: include/linux/input.h:458
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
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
In drivers/input/input.c (ffffffff816c9db0)
Location: include/linux/input.h:458
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff816cad07)
Location: include/linux/input.h:458
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff816f7d90)
Location: include/linux/input.h:458
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff816f8cc7)
Location: include/linux/input.h:458
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff8170dcaf)
Location: include/linux/input.h:463
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff8170e7e6)
Location: include/linux/input.h:463
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff8177eef8)
Location: include/linux/input.h:467
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff8177fa26)
Location: include/linux/input.h:467
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff817bfd24)
Location: include/linux/input.h:467
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff817c0b24)
Location: include/linux/input.h:467
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff817e72a7)
Location: include/linux/input.h:467
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff817e8014)
Location: include/linux/input.h:467
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff81827cc0)
Location: include/linux/input.h:464
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff81828abc)
Location: include/linux/input.h:464
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff8185936b)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff8185a02c)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff81929d58)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_abs_event
```
```
In drivers/input/input-mt.c (ffffffff8192cd15)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff819312cf)
Location: include/linux/input.h:494
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_abs_event
```
```
In drivers/input/input-mt.c (ffffffff819341e5)
Location: include/linux/input.h:494
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff8191455b)
Location: include/linux/input.h:494
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_abs_event
```
```
In drivers/input/input-mt.c (ffffffff81917515)
Location: include/linux/input.h:494
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff819b66a6)
Location: include/linux/input.h:494
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_abs_event
```
```
In drivers/input/input-mt.c (ffffffff819b9785)
Location: include/linux/input.h:494
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff81b1639b)
Location: include/linux/input.h:496
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_abs_event
```
```
In drivers/input/input-mt.c (ffffffff81b193cb)
Location: include/linux/input.h:496
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff81ca6efb)
Location: include/linux/input.h:496
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_abs_event
```
```
In drivers/input/input-mt.c (ffffffff81caad5b)
Location: include/linux/input.h:496
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input-mt.c (ffffffff81d12367)
Location: include/linux/input.h:496
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input-mt.c (ffffffff81dc7f67)
Location: include/linux/input.h:496
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffff800010a98374)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffff800010a9a010)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (c0b7af40)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (c0b7bd04)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (c000000000b7909c)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (c000000000b79fc4)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffe0006aa088)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffe0006aa9b2)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff8180e37b)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff8180f03c)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff817d5acb)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff817d678c)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff8184d4fb)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff8184e1bc)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
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
In drivers/input/input.c (ffffffff818686c8)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
```
In drivers/input/input-mt.c (ffffffff8186938c)
Location: include/linux/input.h:485
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
```
</details>
</li>
</ul>

## Differences
