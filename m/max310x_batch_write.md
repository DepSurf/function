# Function: <code>max310x_batch_write</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8163f9d0)
Location: drivers/tty/serial/max310x.c:597
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/max310x.c:max310x_wq_proc
```
**Symbols:**

```
ffffffff8163f9d0-ffffffff8163fa4b: max310x_batch_write.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165dbe0)
Location: drivers/tty/serial/max310x.c:603
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/max310x.c:max310x_wq_proc
```
**Symbols:**

```
ffffffff8165dbe0-ffffffff8165dc5b: max310x_batch_write.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81692870)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
ffffffff81692870-ffffffff816928e9: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816b5410)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
ffffffff816b5410-ffffffff816b5489: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81768280)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
**Symbols:**

```
ffffffff81768280-ffffffff8176835c: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81782f00)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
**Symbols:**

```
ffffffff81782f00-ffffffff81782fdf: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817667e0)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
**Symbols:**

```
ffffffff817667e0-ffffffff817668c2: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817eb1b0)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
**Symbols:**

```
ffffffff817eb1b0-ffffffff817eb292: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8192b780)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
**Symbols:**

```
ffffffff8192b780-ffffffff8192b889: max310x_batch_write (STB_LOCAL)
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
In drivers/tty/serial/max310x.c (ffffffff81a8948f)
Location: drivers/tty/serial/max310x.c:650
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
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
In drivers/tty/serial/max310x.c (ffffffff81ad4c4c)
Location: drivers/tty/serial/max310x.c:655
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
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
In drivers/tty/serial/max310x.c (ffffffff81b2810c)
Location: drivers/tty/serial/max310x.c:671
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffff800010898bb8)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
ffff800010898bb8-ffff800010898c6c: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (c0994138)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
c0994138-c0994210: max310x_batch_write (STB_LOCAL)
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
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:624
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffe00055b6b6)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
ffffffe00055b6b6-ffffffe00055b71a: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8167ae70)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
ffffffff8167ae70-ffffffff8167aee9: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81659f60)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
ffffffff81659f60-ffffffff81659fd9: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816a9250)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
ffffffff816a9250-ffffffff816a92c9: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void max310x_batch_write(struct uart_port *port, u8 *txbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816c36b0)
Location: drivers/tty/serial/max310x.c:624
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_tx_proc
```
**Symbols:**

```
ffffffff816c36b0-ffffffff816c3729: max310x_batch_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
