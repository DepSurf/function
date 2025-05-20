# Function: <code>serial8250_clear_THRI</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168bdbb)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e55e)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816ae37b)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0b2e)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817602e8)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763f64)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b16a)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177eeb0)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e7e7)
Location: drivers/tty/serial/8250/8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8176280e)
Location: drivers/tty/serial/8250/8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817e2c18)
Location: drivers/tty/serial/8250/8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e68d9)
Location: drivers/tty/serial/8250/8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff819237dd)
Location: drivers/tty/serial/8250/8250.h:189
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925e71)
Location: drivers/tty/serial/8250/8250.h:189
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81a8015d)
Location: drivers/tty/serial/8250/8250.h:189
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a828c1)
Location: drivers/tty/serial/8250/8250.h:189
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81acbc60)
Location: drivers/tty/serial/8250/8250.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acdeef)
Location: drivers/tty/serial/8250/8250.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e404)
Location: drivers/tty/serial/8250/8250.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20fbf)
Location: drivers/tty/serial/8250/8250.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffff8000108880b0)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bf88)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (c0987284)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (c0989974)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (c00000000093111c)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934ab4)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffe000553950)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe00055581e)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81673deb)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8167659e)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816530cb)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8165567e)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816a21bb)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a496e)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816bc84b)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816bedce)
Location: drivers/tty/serial/8250/8250.h:142
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
</ul>

## Differences
