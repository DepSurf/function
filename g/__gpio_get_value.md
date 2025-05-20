# Function: <code>__gpio_get_value</code>

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
In drivers/mfd/ezx-pcap.c (ffffffff8158b97d)
Location: include/asm-generic/gpio.h:93
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core.c (ffffffff81679350)
Location: include/asm-generic/gpio.h:93
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
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
In drivers/mfd/ezx-pcap.c (ffffffff815e0bfd)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core.c (ffffffff816da840)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
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
In drivers/mfd/ezx-pcap.c (ffffffff8160d89d)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core.c (ffffffff8170ad30)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
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
In drivers/mfd/ezx-pcap.c (ffffffff8162199d)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f630)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
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
In drivers/mfd/ezx-pcap.c (ffffffff8168a1cd)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81790590)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
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
In drivers/mfd/ezx-pcap.c (ffffffff816c62dd)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff816e76dd)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff81720e9a)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff8174501a)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff818026f3)
Location: include/asm-generic/gpio.h:96
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff81813583)
Location: include/asm-generic/gpio.h:96
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff817f7d41)
Location: include/asm-generic/gpio.h:96
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff818810a1)
Location: include/asm-generic/gpio.h:96
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff819c97bf)
Location: include/asm-generic/gpio.h:96
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff81b40bdf)
Location: include/asm-generic/gpio.h:74
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/ezx-pcap.c (ffff800010940f00)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/tty/serial/omap-serial.c (c099fc68)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
```
```
In drivers/mfd/ezx-pcap.c (c0a2a8d0)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (c0000000009ea240)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffe0005b4988)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff817030ba)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff816d6ebe)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff817384da)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff81753a6a)
Location: include/asm-generic/gpio.h:98
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
</details>
</li>
</ul>

## Differences
