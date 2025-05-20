# Function: <code>serial8250_set_THRI</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff8168c2fd)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e6b7)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816ae8bd)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0c87)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817606bb)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8176409f)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b53b)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177efc6)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8175ebbb)
Location: drivers/tty/serial/8250/8250.h:135
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81762926)
Location: drivers/tty/serial/8250/8250.h:135
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817e301b)
Location: drivers/tty/serial/8250/8250.h:135
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e6a06)
Location: drivers/tty/serial/8250/8250.h:135
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81923da1)
Location: drivers/tty/serial/8250/8250.h:180
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8192602e)
Location: drivers/tty/serial/8250/8250.h:180
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81a808fd)
Location: drivers/tty/serial/8250/8250.h:180
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a82a7d)
Location: drivers/tty/serial/8250/8250.h:180
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81acbf1d)
Location: drivers/tty/serial/8250/8250.h:179
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81ace0ad)
Location: drivers/tty/serial/8250/8250.h:179
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e6bd)
Location: drivers/tty/serial/8250/8250.h:179
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b2117d)
Location: drivers/tty/serial/8250/8250.h:179
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffff80001088863c)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088c100)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (c09879b0)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (c0989aac)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (c000000000931be4)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934ce0)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffe000553f64)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe000555910)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8167432d)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816766f7)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8165360d)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816557d7)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816a26fd)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a4ac7)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816bcd8d)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816bef27)
Location: drivers/tty/serial/8250/8250.h:133
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
</details>
</li>
</ul>

## Differences
