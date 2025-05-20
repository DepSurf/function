# Function: <code>gpio_get_value</code>

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
Location: include/linux/gpio.h:53
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core.c (ffffffff81679350)
Location: include/linux/gpio.h:53
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
Location: include/linux/gpio.h:53
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core.c (ffffffff816da840)
Location: include/linux/gpio.h:53
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
Location: include/linux/gpio.h:53
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core.c (ffffffff8170ad30)
Location: include/linux/gpio.h:53
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
Location: include/linux/gpio.h:53
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f630)
Location: include/linux/gpio.h:53
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
Location: include/linux/gpio.h:54
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81790590)
Location: include/linux/gpio.h:54
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff81b93f4f)
Location: include/linux/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffffffff81be7eef)
Location: include/linux/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
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
In drivers/mfd/ezx-pcap.c (ffff800010940f00)
Location: include/linux/gpio.h:64
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
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
Location: include/linux/gpio.h:64
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
</details>
</li>
</ul>

## Differences
