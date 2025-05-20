# Function: <code>imx_uart_dma_tx</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void imx_uart_dma_tx(struct imx_port *sport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/imx.c (ffff80001089a9d8)
Location: drivers/tty/serial/imx.c:587
Inline: False
Direct callers:
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
**Symbols:**

```
ffff80001089a9d8-ffff80001089ac88: imx_uart_dma_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void imx_uart_dma_tx(struct imx_port *sport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/imx.c (c099791c)
Location: drivers/tty/serial/imx.c:587
Inline: False
Direct callers:
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
**Symbols:**

```
c099791c-c0997c20: imx_uart_dma_tx (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
