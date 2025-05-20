# Function: <code>serial_link_irq_chain</code>

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
In drivers/tty/serial/8250/8250_core.c (ffffffff81505407)
Location: drivers/tty/serial/8250/8250_core.c:179
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81556ba3)
Location: drivers/tty/serial/8250/8250_core.c:179
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815833a3)
Location: drivers/tty/serial/8250/8250_core.c:179
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815977a5)
Location: drivers/tty/serial/8250/8250_core.c:179
Inline: True
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815fc3e0)
Location: drivers/tty/serial/8250/8250_core.c:175
Inline: True
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8163576a)
Location: drivers/tty/serial/8250/8250_core.c:175
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81653a38)
Location: drivers/tty/serial/8250/8250_core.c:171
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81688441)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816aaadf)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int serial_link_irq_chain(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175d4c0)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
**Symbols:**

```
ffffffff8175d4c0-ffffffff8175d658: serial_link_irq_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int serial_link_irq_chain(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81778390)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
**Symbols:**

```
ffffffff81778390-ffffffff81778528: serial_link_irq_chain (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8175c089)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int serial_link_irq_chain(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff817dfbd0)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
**Symbols:**

```
ffffffff817dfbd0-ffffffff817dfd68: serial_link_irq_chain (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8191e83d)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7a83f)
Location: drivers/tty/serial/8250/8250_core.c:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac60af)
Location: drivers/tty/serial/8250/8250_core.c:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81b190af)
Location: drivers/tty/serial/8250/8250_core.c:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffff800010885328)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (c0983fe0)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
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
In drivers/tty/serial/8250/8250_core.c (c00000000092c250)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffe0005509ce)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8167054f)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8164f65f)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8169e91f)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816b8d82)
Location: drivers/tty/serial/8250/8250_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
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
