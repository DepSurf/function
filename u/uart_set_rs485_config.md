# Function: <code>uart_set_rs485_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8150386c)
Location: drivers/tty/serial/serial_core.c:1184
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81554f6a)
Location: drivers/tty/serial/serial_core.c:1270
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81581b79)
Location: drivers/tty/serial/serial_core.c:1267
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81595b3b)
Location: drivers/tty/serial/serial_core.c:1273
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815fa69b)
Location: drivers/tty/serial/serial_core.c:1285
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff81633df6)
Location: drivers/tty/serial/serial_core.c:1292
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff816515ea)
Location: drivers/tty/serial/serial_core.c:1306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff81686126)
Location: drivers/tty/serial/serial_core.c:1300
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff816a8836)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff8175ab1e)
Location: drivers/tty/serial/serial_core.c:1300
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff81775bfe)
Location: drivers/tty/serial/serial_core.c:1301
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff81759216)
Location: drivers/tty/serial/serial_core.c:1300
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff817dc3f6)
Location: drivers/tty/serial/serial_core.c:1288
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uart_set_rs485_config(struct uart_port *port, struct serial_rs485 *rs485_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:1295
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81917ac0-ffffffff81917ccf: uart_set_rs485_config (STB_LOCAL)
ffffffff81ec1bc6-ffffffff81ec1c3d: uart_set_rs485_config.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uart_set_rs485_config(struct tty_struct *tty, struct uart_port *port, struct serial_rs485 *rs485_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a74480)
Location: drivers/tty/serial/serial_core.c:1420
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81a74480-ffffffff81a74659: uart_set_rs485_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uart_set_rs485_config(struct tty_struct *tty, struct uart_port *port, struct serial_rs485 *rs485_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abec00)
Location: drivers/tty/serial/serial_core.c:1441
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81abec00-ffffffff81abeded: uart_set_rs485_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uart_set_rs485_config(struct tty_struct *tty, struct uart_port *port, struct serial_rs485 *rs485_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b11a80)
Location: drivers/tty/serial/serial_core.c:1470
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81b11a80-ffffffff81b11cbb: uart_set_rs485_config (STB_LOCAL)
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
In drivers/tty/serial/serial_core.c (ffff800010882884)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (c09822e4)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (c00000000092915c)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffe00054ec1a)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff8166e296)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff8164d6e6)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff8169c676)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff816b71b6)
Location: drivers/tty/serial/serial_core.c:1299
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tty_struct *tty</code>
</li>
<li>
<b>Param reordered. </b>
<code>port, rs485_user</code> ➡️ <code>tty, port, rs485_user</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
