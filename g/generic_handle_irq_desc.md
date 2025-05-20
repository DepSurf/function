# Function: <code>generic_handle_irq_desc</code>

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
In arch/x86/kernel/irq_64.c (ffffffff81031157)
Location: include/linux/irqdesc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In kernel/irq/irqdesc.c (ffffffff810d9fcc)
Location: include/linux/irqdesc.h:138
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq_64.c (ffffffff81030217)
Location: include/linux/irqdesc.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In kernel/irq/irqdesc.c (ffffffff810df48c)
Location: include/linux/irqdesc.h:145
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq_64.c (ffffffff810301c7)
Location: include/linux/irqdesc.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In kernel/irq/irqdesc.c (ffffffff810e5acc)
Location: include/linux/irqdesc.h:148
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq_64.c (ffffffff8102e427)
Location: include/linux/irqdesc.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In kernel/irq/irqdesc.c (ffffffff810e50dc)
Location: include/linux/irqdesc.h:155
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq_64.c (ffffffff810302a4)
Location: include/linux/irqdesc.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In kernel/irq/irqdesc.c (ffffffff810ed33c)
Location: include/linux/irqdesc.h:157
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq_64.c (ffffffff81031533)
Location: include/linux/irqdesc.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In kernel/irq/irqdesc.c (ffffffff810f56fc)
Location: include/linux/irqdesc.h:152
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq_64.c (ffffffff810327d3)
Location: include/linux/irqdesc.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In kernel/irq/irqdesc.c (ffffffff81100e8c)
Location: include/linux/irqdesc.h:152
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq_64.c (ffffffff810344e3)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In kernel/irq/irqdesc.c (ffffffff8110968f)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq.c (ffffffff81c01e6c)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In kernel/irq/irqdesc.c (ffffffff81115a5f)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In kernel/irq/irqdesc.c (ffffffff81121433)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In kernel/irq/irqdesc.c (ffffffff8111d413)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq.c (ffffffff81038467)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In kernel/irq/irqdesc.c (ffffffff8111d793)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq.c (ffffffff8103d546)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In kernel/irq/irqdesc.c (ffffffff8113db1d)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
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
In arch/x86/kernel/irq.c (ffffffff81045129)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In kernel/irq/irqdesc.c (ffffffff81161a53)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
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
In arch/x86/kernel/irq.c (ffffffff8104efd9)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In kernel/irq/irqdesc.c (ffffffff81195153)
Location: include/linux/irqdesc.h:156
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
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
In arch/x86/kernel/irq.c (ffffffff8104f989)
Location: include/linux/irqdesc.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In kernel/irq/irqdesc.c (ffffffff811a6ae3)
Location: include/linux/irqdesc.h:159
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
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
In arch/x86/kernel/irq.c (ffffffff81056bf8)
Location: include/linux/irqdesc.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In kernel/irq/irqdesc.c (ffffffff811b6603)
Location: include/linux/irqdesc.h:159
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
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
In kernel/irq/irqdesc.c (ffff80001017729c)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In kernel/irq/irqdesc.c (c03c8ef4)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In kernel/irq/irqdesc.c (c0000000001d0bcc)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In kernel/irq/irqdesc.c (ffffffe000112174)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq.c (ffffffff81c01e4c)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In kernel/irq/irqdesc.c (ffffffff8110e03f)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq.c (ffffffff81c01cfc)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In kernel/irq/irqdesc.c (ffffffff810fed9f)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq.c (ffffffff81c01e2c)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In kernel/irq/irqdesc.c (ffffffff8110bf2f)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
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
In arch/x86/kernel/irq.c (ffffffff81c01e8c)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In kernel/irq/irqdesc.c (ffffffff8111745f)
Location: include/linux/irqdesc.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
```
</details>
</li>
</ul>

## Differences
