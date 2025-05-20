# Function: <code>fwnode_dev_initialized</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112691c)
Location: include/linux/fwnode.h:174
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
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
In kernel/irq/irqdomain.c (ffffffff81146f19)
Location: include/linux/fwnode.h:179
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
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
In kernel/irq/irqdomain.c (ffffffff8116b306)
Location: include/linux/fwnode.h:185
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
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
In kernel/irq/irqdomain.c (ffffffff811a00d9)
Location: include/linux/fwnode.h:198
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
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
In kernel/irq/irqdomain.c (ffffffff811b1f99)
Location: include/linux/fwnode.h:198
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In drivers/gpio/gpiolib.c (ffffffff818fe88c)
Location: include/linux/fwnode.h:198
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
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
In kernel/irq/irqdomain.c (ffffffff811c1d49)
Location: include/linux/fwnode.h:200
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In drivers/gpio/gpiolib.c (ffffffff81945ebc)
Location: include/linux/fwnode.h:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
