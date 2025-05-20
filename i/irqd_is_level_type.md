# Function: <code>irqd_is_level_type</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8155c104)
Location: include/linux/irq.h:260
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff810e5ff0)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81588a60)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff810e5640)
Location: include/linux/irq.h:276
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8159cf10)
Location: include/linux/irq.h:276
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff810ed900)
Location: include/linux/irq.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816023b3)
Location: include/linux/irq.h:288
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff810f5d40)
Location: include/linux/irq.h:283
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8163b661)
Location: include/linux/irq.h:283
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff811014d0)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81659891)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff81109cd0)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8168ed73)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff811160a0)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816b15a3)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff81121d50)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81764865)
Location: include/linux/irq.h:293
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffffffff8111ddb0)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8177f785)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffffffff8111dfd0)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817630c7)
Location: include/linux/irq.h:298
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffffffff8113e450)
Location: include/linux/irq.h:300
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817e7327)
Location: include/linux/irq.h:300
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffffffff81161140)
Location: include/linux/irq.h:300
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81926c96)
Location: include/linux/irq.h:300
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffffffff81194750)
Location: include/linux/irq.h:302
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81a83ac6)
Location: include/linux/irq.h:302
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffffffff811a5fb0)
Location: include/linux/irq.h:305
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81acf127)
Location: include/linux/irq.h:305
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffffffff811b5aa0)
Location: include/linux/irq.h:302
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81b221e7)
Location: include/linux/irq.h:302
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffff8000101778fc)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In kernel/irq/proc.c (ffff800010185fec)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffff80001088cc14)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (c03c918c)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In kernel/irq/proc.c (c03d4ee8)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
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
In kernel/irq/irqdesc.c (c0000000001d14a8)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In kernel/irq/proc.c (c0000000001e0794)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
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
In kernel/irq/irqdesc.c (ffffffe000112832)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffe000556190)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
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
In kernel/irq/irqdesc.c (ffffffff8110e680)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81677013)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff810ff360)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816560f3)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff8110c570)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816a53e3)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In kernel/irq/irqdesc.c (ffffffff811176a0)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:type_show
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816bf843)
Location: include/linux/irq.h:287
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
</details>
</li>
</ul>

## Differences
