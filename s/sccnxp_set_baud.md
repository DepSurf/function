# Function: <code>sccnxp_set_baud</code>

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
In drivers/tty/serial/sccnxp.c (ffffffff8150f287)
Location: drivers/tty/serial/sccnxp.c:284
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff81561758)
Location: drivers/tty/serial/sccnxp.c:284
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff8158dec8)
Location: drivers/tty/serial/sccnxp.c:284
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff815a1f2e)
Location: drivers/tty/serial/sccnxp.c:284
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff8160768e)
Location: drivers/tty/serial/sccnxp.c:280
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff81640d74)
Location: drivers/tty/serial/sccnxp.c:280
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff8165ef0e)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff81694504)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff816b70a4)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sccnxp_set_baud(struct uart_port *port, int baud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8176a940)
Location: drivers/tty/serial/sccnxp.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8176a940-ffffffff8176ad61: sccnxp_set_baud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sccnxp_set_baud(struct uart_port *port, int baud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81785590)
Location: drivers/tty/serial/sccnxp.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81785590-ffffffff8178594b: sccnxp_set_baud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sccnxp_set_baud(struct uart_port *port, int baud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81768ec0)
Location: drivers/tty/serial/sccnxp.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81768ec0-ffffffff817692bd: sccnxp_set_baud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sccnxp_set_baud(struct uart_port *port, int baud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff817edfc0)
Location: drivers/tty/serial/sccnxp.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff817edfc0-ffffffff817ee404: sccnxp_set_baud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sccnxp_set_baud(struct uart_port *port, int baud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8192dfe0)
Location: drivers/tty/serial/sccnxp.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8192dfe0-ffffffff8192e479: sccnxp_set_baud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sccnxp_set_baud(struct uart_port *port, int baud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81a8c280)
Location: drivers/tty/serial/sccnxp.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81a8c280-ffffffff81a8c719: sccnxp_set_baud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sccnxp_set_baud(struct uart_port *port, int baud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81ad8270)
Location: drivers/tty/serial/sccnxp.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81ad8270-ffffffff81ad8706: sccnxp_set_baud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sccnxp_set_baud(struct uart_port *port, int baud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81b2b560)
Location: drivers/tty/serial/sccnxp.c:303
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81b2b560-ffffffff81b2b9f6: sccnxp_set_baud (STB_LOCAL)
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
In drivers/tty/serial/sccnxp.c (ffff8000108a06bc)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (c099a54c)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (c00000000093d644)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffe00055ccc6)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff8167cb04)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff8165bbf4)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff816aaee4)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
In drivers/tty/serial/sccnxp.c (ffffffff816c5344)
Location: drivers/tty/serial/sccnxp.c:307
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
