# Function: <code>irqd_is_setaffinity_pending</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff81056818)
Location: include/linux/irq.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff810db5b9)
Location: include/linux/irq.h:213
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/irq/proc.c (ffffffff810e1ed8)
Location: include/linux/irq.h:213
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff810e25b6)
Location: include/linux/irq.h:213
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_move_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81056a98)
Location: include/linux/irq.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff810e0c49)
Location: include/linux/irq.h:221
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/irq/proc.c (ffffffff810e7978)
Location: include/linux/irq.h:221
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff810e8120)
Location: include/linux/irq.h:221
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/xen/events/events_base.c (ffffffff8151918f)
Location: include/linux/irq.h:221
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81059848)
Location: include/linux/irq.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff810e76b6)
Location: include/linux/irq.h:223
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/irq/proc.c (ffffffff810ee2e5)
Location: include/linux/irq.h:223
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff810eeb60)
Location: include/linux/irq.h:223
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/xen/events/events_base.c (ffffffff8154565f)
Location: include/linux/irq.h:223
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81058fd8)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff810e73c9)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/irq/proc.c (ffffffff810edb85)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff810ee690)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff815594ef)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d4b8)
Location: include/linux/irq.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff810ef6b2)
Location: include/linux/irq.h:242
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/irq/proc.c (ffffffff810f65c5)
Location: include/linux/irq.h:242
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff810f70c0)
Location: include/linux/irq.h:242
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff815bd91f)
Location: include/linux/irq.h:242
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/vector.c (ffffffff8105f635)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81060618)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff810f7a92)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff810fe8ed)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff810ff326)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff815f5f9f)
Location: include/linux/irq.h:237
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/vector.c (ffffffff810652a5)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81066468)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff81102f82)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff8110a0bd)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff8110ab06)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff8161105f)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/vector.c (ffffffff81068985)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069b98)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8110b60a)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff811137ae)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff811141b6)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff81644dd0)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/vector.c (ffffffff810692f5)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a458)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8111790a)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff8111f91e)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff81120326)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff81667380)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/vector.c (ffffffff8106ec3c)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071978)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff81123724)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff8112be5e)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff8112c862)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff817171c0)
Location: include/linux/irq.h:247
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/vector.c (ffffffff8107024c)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072878)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8111f574)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff8112787e)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff81128292)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
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
In arch/x86/kernel/apic/vector.c (ffffffff81071f2c)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073598)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8111f324)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff81127c0e)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff8112855a)
Location: include/linux/irq.h:252
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
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
In arch/x86/kernel/apic/vector.c (ffffffff8107dd4c)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107fa98)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8113f7b4)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff8114817e)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff81148b2a)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
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
In arch/x86/kernel/apic/vector.c (ffffffff8108be3b)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108f328)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff81163502)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff8116cafd)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff8116d65a)
Location: include/linux/irq.h:254
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
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
In arch/x86/kernel/apic/vector.c (ffffffff810a033b)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a3bc8)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff81197157)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff811a1bdd)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff811a27fa)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
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
In arch/x86/kernel/apic/vector.c (ffffffff810a32bb)
Location: include/linux/irq.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6c98)
Location: include/linux/irq.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff811a8c70)
Location: include/linux/irq.h:259
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff811b3b7d)
Location: include/linux/irq.h:259
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff811b46fa)
Location: include/linux/irq.h:259
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
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
In arch/x86/kernel/apic/vector.c (ffffffff810aa1fb)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810adcf8)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff811b87d0)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff811c39fd)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff811c457a)
Location: include/linux/irq.h:256
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
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
In kernel/irq/manage.c (ffff80001017aa94)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In drivers/xen/events/events_base.c (ffff800010831108)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In kernel/irq/manage.c (c03cbd20)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (c0000000001d4f88)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In kernel/irq/manage.c (ffffffe00011487e)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
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
In arch/x86/kernel/apic/vector.c (ffffffff81068de5)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069f48)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8110feea)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff81117efe)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff81118906)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff8162d0b0)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/vector.c (ffffffff81059155)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a2a8)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff81100c1a)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff81108f6e)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff81109976)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
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
In arch/x86/kernel/apic/vector.c (ffffffff81069295)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a3f8)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8110ddda)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff81115dee)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff811167f6)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff8165b1c0)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a995)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bb78)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8111932a)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff8112141e)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_list_proc_show
  - kernel/irq/proc.c:irq_affinity_proc_show
```
```
In kernel/irq/migration.c (ffffffff81121e36)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In drivers/xen/events/events_base.c (ffffffff816757b0)
Location: include/linux/irq.h:241
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
</details>
</li>
</ul>

## Differences
