# Function: <code>uart_port_shutdown</code>

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
In drivers/tty/serial/serial_core.c (ffffffff81501e07)
Location: drivers/tty/serial/serial_core.c:1532
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/serial/serial_core.c (ffffffff81550f49)
Location: drivers/tty/serial/serial_core.c:1630
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157d740)
Location: drivers/tty/serial/serial_core.c:1609
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff8157d740-ffffffff8157d789: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81591970)
Location: drivers/tty/serial/serial_core.c:1615
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81591970-ffffffff815919b9: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f6450)
Location: drivers/tty/serial/serial_core.c:1626
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff815f6450-ffffffff815f649f: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8162f650)
Location: drivers/tty/serial/serial_core.c:1633
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff8162f650-ffffffff8162f69f: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164d7d0)
Location: drivers/tty/serial/serial_core.c:1692
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff8164d7d0-ffffffff8164d81f: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81682320)
Location: drivers/tty/serial/serial_core.c:1686
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81682320-ffffffff8168236f: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a49b0)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff816a49b0-ffffffff816a49ff: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81756fd0)
Location: drivers/tty/serial/serial_core.c:1686
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81756fd0-ffffffff81757022: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81772150)
Location: drivers/tty/serial/serial_core.c:1692
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81772150-ffffffff817721a2: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81755c10)
Location: drivers/tty/serial/serial_core.c:1691
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81755c10-ffffffff81755c62: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d9340)
Location: drivers/tty/serial/serial_core.c:1690
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff817d9340-ffffffff817d9392: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff819178f0)
Location: drivers/tty/serial/serial_core.c:1724
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff819178f0-ffffffff81917950: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a73260)
Location: drivers/tty/serial/serial_core.c:1841
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81a73260-ffffffff81a732c0: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abdb20)
Location: drivers/tty/serial/serial_core.c:1862
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81abdb20-ffffffff81abdb80: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b10970)
Location: drivers/tty/serial/serial_core.c:1898
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81b10970-ffffffff81b109d0: uart_port_shutdown (STB_LOCAL)
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
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087ce08)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffff80001087ce08-ffff80001087ce60: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097e08c)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
c097e08c-c097e0dc: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000923900)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
c000000000923900-c000000000923980: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054b920)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffe00054b920-ffffffe00054b974: uart_port_shutdown (STB_LOCAL)
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
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166a410)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff8166a410-ffffffff8166a45f: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81649580)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81649580-ffffffff816495cf: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816987f0)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff816987f0-ffffffff8169883f: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b2e00)
Location: drivers/tty/serial/serial_core.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff816b2e00-ffffffff816b2e4f: uart_port_shutdown (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
