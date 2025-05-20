# Function: <code>uart_do_autoconfig</code>

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
In drivers/tty/serial/serial_core.c (ffffffff8150350e)
Location: drivers/tty/serial/serial_core.c:1025
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
In drivers/tty/serial/serial_core.c (ffffffff81554a8c)
Location: drivers/tty/serial/serial_core.c:1097
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
In drivers/tty/serial/serial_core.c (ffffffff8158165c)
Location: drivers/tty/serial/serial_core.c:1092
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
In drivers/tty/serial/serial_core.c (ffffffff815953c5)
Location: drivers/tty/serial/serial_core.c:1098
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
In drivers/tty/serial/serial_core.c (ffffffff815fa14b)
Location: drivers/tty/serial/serial_core.c:1108
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
In drivers/tty/serial/serial_core.c (ffffffff81633a18)
Location: drivers/tty/serial/serial_core.c:1115
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
In drivers/tty/serial/serial_core.c (ffffffff816516bf)
Location: drivers/tty/serial/serial_core.c:1129
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
In drivers/tty/serial/serial_core.c (ffffffff816861ff)
Location: drivers/tty/serial/serial_core.c:1123
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
In drivers/tty/serial/serial_core.c (ffffffff816a890f)
Location: drivers/tty/serial/serial_core.c:1122
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uart_do_autoconfig(struct tty_struct *tty, struct uart_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8175a910)
Location: drivers/tty/serial/serial_core.c:1123
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff8175a910-ffffffff8175aa5d: uart_do_autoconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uart_do_autoconfig(struct tty_struct *tty, struct uart_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817759f0)
Location: drivers/tty/serial/serial_core.c:1124
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff817759f0-ffffffff81775b3d: uart_do_autoconfig (STB_LOCAL)
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
In drivers/tty/serial/serial_core.c (ffffffff817592dc)
Location: drivers/tty/serial/serial_core.c:1123
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
In drivers/tty/serial/serial_core.c (ffffffff817dc4bc)
Location: drivers/tty/serial/serial_core.c:1111
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff8191b266)
Location: drivers/tty/serial/serial_core.c:1118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff81a77201)
Location: drivers/tty/serial/serial_core.c:1124
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff81ac1aab)
Location: drivers/tty/serial/serial_core.c:1145
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff81b1526b)
Location: drivers/tty/serial/serial_core.c:1139
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffff8000108829ac)
Location: drivers/tty/serial/serial_core.c:1122
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
In drivers/tty/serial/serial_core.c (c0982404)
Location: drivers/tty/serial/serial_core.c:1122
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
In drivers/tty/serial/serial_core.c (c00000000092928c)
Location: drivers/tty/serial/serial_core.c:1122
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
In drivers/tty/serial/serial_core.c (ffffffe00054ecc4)
Location: drivers/tty/serial/serial_core.c:1122
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
In drivers/tty/serial/serial_core.c (ffffffff8166e36f)
Location: drivers/tty/serial/serial_core.c:1122
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
In drivers/tty/serial/serial_core.c (ffffffff8164d7bf)
Location: drivers/tty/serial/serial_core.c:1122
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
In drivers/tty/serial/serial_core.c (ffffffff8169c74f)
Location: drivers/tty/serial/serial_core.c:1122
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
In drivers/tty/serial/serial_core.c (ffffffff816b728f)
Location: drivers/tty/serial/serial_core.c:1122
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
