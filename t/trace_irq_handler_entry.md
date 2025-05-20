# Function: <code>trace_irq_handler_entry</code>

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
In kernel/irq/handle.c (ffffffff810da8df)
Location: include/trace/events/irq.h:52
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810de499)
Location: include/trace/events/irq.h:52
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
In kernel/irq/handle.c (ffffffff810dfe93)
Location: include/trace/events/irq.h:52
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810e3de9)
Location: include/trace/events/irq.h:52
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
In kernel/irq/handle.c (ffffffff810e67f0)
Location: include/trace/events/irq.h:52
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810ea913)
Location: include/trace/events/irq.h:52
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
In kernel/irq/handle.c (ffffffff810e5e01)
Location: include/trace/events/irq.h:52
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810e9fcc)
Location: include/trace/events/irq.h:52
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
In kernel/irq/handle.c (ffffffff810ee071)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810f252f)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff810f62d1)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810fa97f)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff81101a41)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8110613f)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8110a25e)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8110f744)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8111662e)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8111ba04)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8112225e)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81127d38)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8111e241)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811238de)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8111e551)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81123c3e)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8113e9f1)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8114422e)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8116201b)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81167d6e)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff81195a8b)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8119c1fe)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff811a745b)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811ae05e)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffffffff811b6fbb)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811bdc5e)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
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
In kernel/irq/handle.c (ffff800010178730)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffff80001017fc34)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (c03c9eac)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (c03cfdb4)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (c0000000001d25d0)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (c0000000001da830)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffe000113142)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffe000117fec)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8110ec0e)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81113fe4)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff810ff95e)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81104cf4)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8110cafe)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81111ed4)
Location: include/trace/events/irq.h:53
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
In kernel/irq/handle.c (ffffffff8111802e)
Location: include/trace/events/irq.h:53
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8111d4c4)
Location: include/trace/events/irq.h:53
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
