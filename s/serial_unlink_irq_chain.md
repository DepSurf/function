# Function: <code>serial_unlink_irq_chain</code>

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
In drivers/tty/serial/8250/8250_core.c (ffffffff815052d5)
Location: drivers/tty/serial/8250/8250_core.c:229
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81556a48)
Location: drivers/tty/serial/8250/8250_core.c:229
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81583248)
Location: drivers/tty/serial/8250/8250_core.c:229
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81597678)
Location: drivers/tty/serial/8250/8250_core.c:229
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815fc2b8)
Location: drivers/tty/serial/8250/8250_core.c:225
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81635628)
Location: drivers/tty/serial/8250/8250_core.c:225
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816538f8)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816882fa)
Location: drivers/tty/serial/8250/8250_core.c:222
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816aa99a)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void serial_unlink_irq_chain(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175d3e0)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
```
**Symbols:**

```
ffffffff8175d3e0-ffffffff8175d464: serial_unlink_irq_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void serial_unlink_irq_chain(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff817782b0)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
```
**Symbols:**

```
ffffffff817782b0-ffffffff81778334: serial_unlink_irq_chain (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8175bf48)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff817dfb58)
Location: drivers/tty/serial/8250/8250_core.c:218
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8191e6e4)
Location: drivers/tty/serial/8250/8250_core.c:218
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7a784)
Location: drivers/tty/serial/8250/8250_core.c:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac5ff4)
Location: drivers/tty/serial/8250/8250_core.c:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81b18ff4)
Location: drivers/tty/serial/8250/8250_core.c:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffff800010884f58)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (c098306c)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (c00000000092c070)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffe000550894)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8167040a)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8164f51a)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8169e7da)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816b8c3a)
Location: drivers/tty/serial/8250/8250_core.c:221
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
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
