# Function: <code>trace_irq_handler_exit</code>

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
In kernel/irq/handle.c (ffffffff810da882)
Location: include/trace/events/irq.h:82
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810de4a9)
Location: include/trace/events/irq.h:82
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
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
In kernel/irq/handle.c (ffffffff810dfea4)
Location: include/trace/events/irq.h:82
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810e3df9)
Location: include/trace/events/irq.h:82
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
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
In kernel/irq/handle.c (ffffffff810e6801)
Location: include/trace/events/irq.h:82
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810ea92c)
Location: include/trace/events/irq.h:82
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
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
In kernel/irq/handle.c (ffffffff810e5e12)
Location: include/trace/events/irq.h:82
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810e9fe5)
Location: include/trace/events/irq.h:82
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
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
In kernel/irq/handle.c (ffffffff810ee087)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810f254d)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
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
In kernel/irq/handle.c (ffffffff810f62e7)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810fa99d)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
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
In kernel/irq/handle.c (ffffffff81101a57)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8110615d)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
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
In kernel/irq/handle.c (ffffffff8110a275)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8110f760)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff81116645)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8111ba20)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff81122275)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81127d57)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff8111e258)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811238fc)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff8111e568)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81123c5c)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff8113ea05)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81144249)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff81162032)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81167d8c)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff81195aa2)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8119c21c)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff811a7472)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811ae07c)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff811b6fd2)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811bdc7c)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffff800010178744)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffff80001017fc58)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (c03c9edc)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (c03cfdec)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (c0000000001d25f0)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (c0000000001da854)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffe000113158)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffe000118012)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff8110ec25)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81114000)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff810ff975)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81104d10)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff8110cb15)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81111ef0)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff81118045)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8111d4e0)
Location: include/trace/events/irq.h:83
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
</details>
</li>
</ul>

## Differences
