# Function: <code>irqd_irq_masked</code>

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
In arch/x86/kernel/irq.c (0)
Location: include/linux/irq.h:272
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810dc516)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (0)
Location: include/linux/irq.h:272
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:272
Inline: True
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
In arch/x86/kernel/irq.c (0)
Location: include/linux/irq.h:280
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e1c22)
Location: include/linux/irq.h:280
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (0)
Location: include/linux/irq.h:280
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:280
Inline: True
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
In arch/x86/kernel/irq.c (0)
Location: include/linux/irq.h:282
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e8550)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (0)
Location: include/linux/irq.h:282
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:282
Inline: True
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
In kernel/irq/manage.c (ffffffff810e7a6a)
Location: include/linux/irq.h:310
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff810e9c5f)
Location: include/linux/irq.h:310
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:310
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:310
Inline: True
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
In kernel/irq/manage.c (ffffffff810efdea)
Location: include/linux/irq.h:322
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff810f21ad)
Location: include/linux/irq.h:322
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irq.h:322
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:322
Inline: True
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
In kernel/irq/manage.c (ffffffff810f8230)
Location: include/linux/irq.h:317
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff810fa5f1)
Location: include/linux/irq.h:317
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (ffffffff810ff411)
Location: include/linux/irq.h:317
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:317
Inline: True
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
In kernel/irq/manage.c (ffffffff811039d0)
Location: include/linux/irq.h:318
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81105db1)
Location: include/linux/irq.h:318
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (ffffffff8110abf1)
Location: include/linux/irq.h:318
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:318
Inline: True
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
In kernel/irq/manage.c (ffffffff8110c41e)
Location: include/linux/irq.h:318
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8110f254)
Location: include/linux/irq.h:318
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (ffffffff811142a1)
Location: include/linux/irq.h:318
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:318
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a525)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff811187fe)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8111b524)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (ffffffff81120411)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:321
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81071a4a)
Location: include/linux/irq.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff811240ee)
Location: include/linux/irq.h:337
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811276c4)
Location: include/linux/irq.h:337
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff8112c951)
Location: include/linux/irq.h:337
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:337
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81072945)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8111ff4e)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811232c4)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff81128381)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:347
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81073665)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8112020e)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81123624)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff81128641)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:347
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107fb65)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8114073e)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81143bf4)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff81148c11)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:349
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108f404)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8116412f)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811680da)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff8116d751)
Location: include/linux/irq.h:349
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:349
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a3ca4)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff81197ecf)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8119c59a)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff811a2901)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:351
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6d74)
Location: include/linux/irq.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff811a9b8f)
Location: include/linux/irq.h:354
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811ae427)
Location: include/linux/irq.h:354
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff811b4801)
Location: include/linux/irq.h:354
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:354
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810addb8)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff811b96ef)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811be027)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
```
```
In kernel/irq/migration.c (ffffffff811c4681)
Location: include/linux/irq.h:351
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:351
Inline: True
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
In kernel/irq/manage.c (ffff80001017b150)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffff80001017ed60)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:321
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
In kernel/irq/manage.c (c03cc280)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (c03cf78c)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:321
Inline: True
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
In kernel/irq/manage.c (c0000000001d5794)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (c0000000001d9e20)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:321
Inline: True
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
In kernel/irq/manage.c (ffffffe000114d30)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffe000117a36)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a015)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff81110dde)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81113b04)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (ffffffff811189f1)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:321
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a375)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff81101b0e)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81104814)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (ffffffff81109a61)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:321
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a4c5)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8110ecce)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811119f4)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (ffffffff811168e1)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:321
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bc45)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In kernel/irq/manage.c (ffffffff8111a1fe)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8111cfb4)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
```
In kernel/irq/migration.c (ffffffff81121f21)
Location: include/linux/irq.h:321
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:321
Inline: True
```
</details>
</li>
</ul>

## Differences
