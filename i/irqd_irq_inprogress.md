# Function: <code>irqd_irq_inprogress</code>

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
In kernel/irq/manage.c (ffffffff810daaac)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810dd463)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff810e00bc)
Location: include/linux/irq.h:285
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810e2c23)
Location: include/linux/irq.h:285
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff810e6a0c)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810e9523)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff810e605c)
Location: include/linux/irq.h:315
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810e89ef)
Location: include/linux/irq.h:315
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff810ee2dc)
Location: include/linux/irq.h:327
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810f0dc3)
Location: include/linux/irq.h:327
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff810f66c2)
Location: include/linux/irq.h:322
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810f9012)
Location: include/linux/irq.h:322
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff81101e32)
Location: include/linux/irq.h:323
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811047b4)
Location: include/linux/irq.h:323
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff8110a666)
Location: include/linux/irq.h:323
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff8110d9d7)
Location: include/linux/irq.h:323
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff81116a36)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81119c97)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff811253f6)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81125bc7)
Location: include/linux/irq.h:342
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff81121256)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811218d7)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff81121536)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81121bb7)
Location: include/linux/irq.h:352
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff81141ab6)
Location: include/linux/irq.h:354
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81142157)
Location: include/linux/irq.h:354
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff81165586)
Location: include/linux/irq.h:354
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81165c8a)
Location: include/linux/irq.h:354
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff81199496)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81199c5a)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff811ab176)
Location: include/linux/irq.h:359
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811ab88a)
Location: include/linux/irq.h:359
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff811badb6)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811bb48a)
Location: include/linux/irq.h:356
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In arch/arm64/kernel/machine_kexec.c (ffff8000100aa000)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_crash_shutdown
```
```
In kernel/irq/manage.c (ffff8000101794e8)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffff80001017ccb8)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In arch/arm/kernel/machine_kexec.c (c031540c)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_shutdown
```
```
In kernel/irq/manage.c (c03ca1e8)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (c03cd82c)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In arch/powerpc/kernel/machine_kexec.c (c000000000070210)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec.c:machine_kexec_mask_interrupts
```
```
In kernel/irq/manage.c (c0000000001d2a00)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (c0000000001d76a8)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffe000113406)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffe000115edc)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff8110f016)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81112277)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff810ffd56)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81102fa7)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff8110cf06)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81110167)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
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
In kernel/irq/manage.c (ffffffff81118466)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff8111b6d9)
Location: include/linux/irq.h:326
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
```
</details>
</li>
</ul>

## Differences
