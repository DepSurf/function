# Function: <code>serial8250_TIOCM_to_MCR</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d55a)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816afaaa)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817609e4)
Location: drivers/tty/serial/8250/8250.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8177ba34)
Location: drivers/tty/serial/8250/8250.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8175f094)
Location: drivers/tty/serial/8250/8250.h:167
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817e25d5)
Location: drivers/tty/serial/8250/8250.h:167
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff819217e5)
Location: drivers/tty/serial/8250/8250.h:212
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7dff5)
Location: drivers/tty/serial/8250/8250.h:214
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac95f5)
Location: drivers/tty/serial/8250/8250.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1c6d5)
Location: drivers/tty/serial/8250/8250.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffff80001088aec4)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (c0988a74)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (c000000000933584)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffe000554d70)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8167551a)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816545fa)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816a38ea)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816bdd7a)
Location: drivers/tty/serial/8250/8250.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
</details>
</li>
</ul>

## Differences
