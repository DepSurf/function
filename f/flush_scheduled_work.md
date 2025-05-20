# Function: <code>flush_scheduled_work</code>

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
In drivers/md/dm.c (ffffffff816a0226)
Location: include/linux/workqueue.h:557
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817015b6)
Location: include/linux/workqueue.h:558
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81733316)
Location: include/linux/workqueue.h:572
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/acpi/ec.c (ffffffff8150402a)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
```
In drivers/md/dm.c (ffffffff8174c116)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/acpi/ec.c (ffffffff8154634a)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
```
In drivers/md/dm.c (ffffffff817be4a6)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/acpi/ec.c (ffffffff8157c2fa)
Location: include/linux/workqueue.h:597
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
```
In drivers/md/dm.c (ffffffff818067e5)
Location: include/linux/workqueue.h:597
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/acpi/ec.c (ffffffff81593f7a)
Location: include/linux/workqueue.h:597
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff81805ca6)
Location: include/linux/workqueue.h:597
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffffffff81832915)
Location: include/linux/workqueue.h:597
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/acpi/ec.c (ffffffff815c4fba)
Location: include/linux/workqueue.h:575
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff8184799e)
Location: include/linux/workqueue.h:575
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffffffff81875115)
Location: include/linux/workqueue.h:575
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/media/cec/cec-adap.c (ffffffff818792a3)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffffffff818a6ee5)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/md/dm.c (ffffffff81976e25)
Location: include/linux/workqueue.h:595
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/acpi/osl.c (ffffffff8169e568)
Location: include/linux/workqueue.h:595
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197ba55)
Location: include/linux/workqueue.h:595
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/acpi/osl.c (ffffffff81681228)
Location: include/linux/workqueue.h:595
Inline: True
```
```
In drivers/md/dm.c (ffffffff8195fc55)
Location: include/linux/workqueue.h:595
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/acpi/osl.c (ffffffff816f6308)
Location: include/linux/workqueue.h:589
Inline: True
```
```
In drivers/md/dm.c (ffffffff81a07c25)
Location: include/linux/workqueue.h:589
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/media/cec/cec-adap.c (ffff800010ac0d8c)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffff800010afc14c)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/media/cec/cec-adap.c (c0ba2ba4)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (c0bdc654)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/media/cec/cec-adap.c (c000000000ba309c)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (c000000000bea230)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/media/cec/cec-adap.c (ffffffe0006c2374)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffffffe0006ed388)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/media/cec/cec-adap.c (ffffffff81821813)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffffffff8184cd65)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/media/cec/cec-adap.c (ffffffff817e8eb3)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffffffff81814385)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/media/cec/cec-adap.c (ffffffff8186e753)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffffffff8189c395)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
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
In drivers/media/cec/cec-adap.c (ffffffff818886d3)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
```
In drivers/md/dm.c (ffffffff818b8555)
Location: include/linux/workqueue.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:local_exit
```
</details>
</li>
</ul>

## Differences
