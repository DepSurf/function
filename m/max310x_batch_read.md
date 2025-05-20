# Function: <code>max310x_batch_read</code>

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
In drivers/tty/serial/max310x.c (ffffffff8163fc40)
Location: drivers/tty/serial/max310x.c:612
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff8163fc40-ffffffff8163fcb8: max310x_batch_read.isra.8 (STB_LOCAL)
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
In drivers/tty/serial/max310x.c (ffffffff8165de50)
Location: drivers/tty/serial/max310x.c:618
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff8165de50-ffffffff8165dec8: max310x_batch_read.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81692aa0)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff81692aa0-ffffffff81692b19: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816b5640)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff816b5640-ffffffff816b56b9: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817681a0)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff817681a0-ffffffff8176827c: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81782fe0)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff81782fe0-ffffffff817830bf: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817668d0)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff817668d0-ffffffff817669b2: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817eb2a0)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff817eb2a0-ffffffff817eb382: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8192b890)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff8192b890-ffffffff8192b999: max310x_batch_read (STB_LOCAL)
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
In drivers/tty/serial/max310x.c (ffffffff81a8917d)
Location: drivers/tty/serial/max310x.c:657
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff81ad4887)
Location: drivers/tty/serial/max310x.c:662
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff81b27d72)
Location: drivers/tty/serial/max310x.c:678
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
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
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffff800010898e28)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffff800010898e28-ffff800010898edc: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (c09943b0)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
c09943b0-c099448c: max310x_batch_read (STB_LOCAL)
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
Location: drivers/tty/serial/max310x.c:639
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffe00055b88e)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffe00055b88e-ffffffe00055b8f2: max310x_batch_read (STB_LOCAL)
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
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8167b0a0)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff8167b0a0-ffffffff8167b119: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165a190)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff8165a190-ffffffff8165a209: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816a9480)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff816a9480-ffffffff816a94f9: max310x_batch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port *port, u8 *rxbuf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816c38e0)
Location: drivers/tty/serial/max310x.c:639
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff816c38e0-ffffffff816c3959: max310x_batch_read (STB_LOCAL)
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
