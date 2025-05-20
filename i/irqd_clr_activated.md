# Function: <code>irqd_clr_activated</code>

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
In kernel/irq/irqdomain.c (ffffffff810edd22)
Location: include/linux/irq.h:327
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
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
In kernel/irq/irqdomain.c (ffffffff810ed6d3)
Location: include/linux/irq.h:355
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
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
In kernel/irq/irqdomain.c (ffffffff810f6103)
Location: include/linux/irq.h:367
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff810f8154)
Location: include/linux/irq.h:367
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff810fe472)
Location: include/linux/irq.h:362
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff81100536)
Location: include/linux/irq.h:362
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff81109c42)
Location: include/linux/irq.h:363
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff8110bd06)
Location: include/linux/irq.h:363
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff81113212)
Location: include/linux/irq.h:363
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff811153dc)
Location: include/linux/irq.h:363
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff8111f4b2)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff811215ee)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff8112b9ee)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff8112db79)
Location: include/linux/irq.h:382
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811274ae)
Location: include/linux/irq.h:392
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff81129749)
Location: include/linux/irq.h:392
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff8112776e)
Location: include/linux/irq.h:392
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff81129a1a)
Location: include/linux/irq.h:392
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff81147cde)
Location: include/linux/irq.h:394
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff8114a347)
Location: include/linux/irq.h:394
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff8116c1a6)
Location: include/linux/irq.h:394
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff8116f548)
Location: include/linux/irq.h:394
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811a10e6)
Location: include/linux/irq.h:396
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff811a4b78)
Location: include/linux/irq.h:396
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811b2f46)
Location: include/linux/irq.h:399
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff811b6aa7)
Location: include/linux/irq.h:399
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811c2d66)
Location: include/linux/irq.h:396
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff811c6976)
Location: include/linux/irq.h:396
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffff800010185144)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffff800010187890)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (c03d4200)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (c03d650c)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/manage.c (c0000000001d4a50)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
```
```
In kernel/irq/chip.c (c0000000001d99f4)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
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
In kernel/irq/irqdomain.c (ffffffe00011beca)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffe00011d43e)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff81117a92)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff81119bce)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff81108782)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff8110ac3e)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff81115982)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff81117abe)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff81120fb2)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
```
```
In kernel/irq/msi.c (ffffffff8112314e)
Location: include/linux/irq.h:366
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
</details>
</li>
</ul>

## Differences
