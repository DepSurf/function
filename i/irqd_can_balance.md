# Function: <code>irqd_can_balance</code>

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
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/irq.h:223
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810dbec3)
Location: include/linux/irq.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_can_set_affinity
  - kernel/irq/manage.c:setup_affinity
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
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/irq.h:231
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e16be)
Location: include/linux/irq.h:231
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/irq.h:233
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e801e)
Location: include/linux/irq.h:233
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/linux/irq.h:247
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e7720)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff810efaa0)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff810f7ece)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff8110361e)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff8110c047)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff81118477)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff81123d67)
Location: include/linux/irq.h:257
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff8111fbc7)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff8111fe7e)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff8114038e)
Location: include/linux/irq.h:264
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff81163cee)
Location: include/linux/irq.h:264
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff81197a0e)
Location: include/linux/irq.h:266
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff811a96ce)
Location: include/linux/irq.h:269
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff811b922e)
Location: include/linux/irq.h:266
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffff80001017acdc)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (c03cbef0)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (c0000000001d5250)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffe0001149fa)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff81110a57)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff81101787)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff8110e947)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
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
In kernel/irq/manage.c (ffffffff81119e77)
Location: include/linux/irq.h:251
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_can_set_affinity_usr
  - kernel/irq/manage.c:irq_can_set_affinity
```
</details>
</li>
</ul>

## Differences
