# Function: <code>irq_move_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_move_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810e2680)
Location: kernel/irq/migration.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:ack_dynirq
```
**Symbols:**

```
ffffffff810e2680-ffffffff810e26da: irq_move_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_move_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810e8110)
Location: kernel/irq/migration.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff810e8110-ffffffff810e816a: irq_move_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_move_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810eeb50)
Location: kernel/irq/migration.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff810eeb50-ffffffff810eebaa: irq_move_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_move_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810ee680)
Location: kernel/irq/migration.c:81
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff810ee680-ffffffff810ee6da: irq_move_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_move_irq(struct irq_data *idata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/migration.c (ffffffff810f70b0)
Location: kernel/irq/migration.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff810f70b0-ffffffff810f7116: irq_move_irq (STB_GLOBAL)
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
In arch/x86/kernel/apic/vector.c (ffffffff8105f635)
Location: include/linux/irq.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff810652a5)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81068985)
Location: include/linux/irq.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff810692f5)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8106ec3c)
Location: include/linux/irq.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
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
In arch/x86/kernel/apic/vector.c (ffffffff8107024c)
Location: include/linux/irq.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
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
In arch/x86/kernel/apic/vector.c (ffffffff81071f2c)
Location: include/linux/irq.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
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
In arch/x86/kernel/apic/vector.c (ffffffff8107dd4c)
Location: include/linux/irq.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
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
In arch/x86/kernel/apic/vector.c (ffffffff8108be3b)
Location: include/linux/irq.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
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
In arch/x86/kernel/apic/vector.c (ffffffff810a033b)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
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
In arch/x86/kernel/apic/vector.c (ffffffff810a32bb)
Location: include/linux/irq.h:642
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
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
In arch/x86/kernel/apic/vector.c (ffffffff810aa1fb)
Location: include/linux/irq.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/apic/vector.c (ffffffff81068de5)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81059155)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81069295)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a995)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
