# Function: <code>uart_port_dtr_rts</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f6ff0)
Location: drivers/tty/serial/serial_core.c:155
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff815f6ff0-ffffffff815f706f: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81630270)
Location: drivers/tty/serial/serial_core.c:155
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81630270-ffffffff816302ef: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164e420)
Location: drivers/tty/serial/serial_core.c:158
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff8164e420-ffffffff8164e49f: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81682f80)
Location: drivers/tty/serial/serial_core.c:155
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81682f80-ffffffff81683002: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a5620)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff816a5620-ffffffff816a56a2: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81759300)
Location: drivers/tty/serial/serial_core.c:157
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81759300-ffffffff81759414: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817743d0)
Location: drivers/tty/serial/serial_core.c:158
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff817743d0-ffffffff817744e4: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81757770)
Location: drivers/tty/serial/serial_core.c:158
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81757770-ffffffff81757887: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817dafb0)
Location: drivers/tty/serial/serial_core.c:158
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff817dafb0-ffffffff817db0c7: uart_port_dtr_rts (STB_LOCAL)
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
In drivers/tty/serial/serial_core.c (ffffffff81919781)
Location: drivers/tty/serial/serial_core.c:170
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
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
In drivers/tty/serial/serial_core.c (ffffffff81a753f1)
Location: drivers/tty/serial/serial_core.c:172
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
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
In drivers/tty/serial/serial_core.c (ffffffff81abfcd1)
Location: drivers/tty/serial/serial_core.c:194
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
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
In drivers/tty/serial/serial_core.c (ffffffff81b12b51)
Location: drivers/tty/serial/serial_core.c:193
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087e878)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffff80001087e878-ffff80001087e92c: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097f528)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
c097f528-c097f5cc: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000924960)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
c000000000924960-c000000000924a54: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054c34c)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffe00054c34c-ffffffe00054c3e6: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166b080)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff8166b080-ffffffff8166b102: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164a1f0)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff8164a1f0-ffffffff8164a272: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81699460)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff81699460-ffffffff816994e2: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void uart_port_dtr_rts(struct uart_port *uport, int raise);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b3fe0)
Location: drivers/tty/serial/serial_core.c:156
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff816b3fe0-ffffffff816b4062: uart_port_dtr_rts (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
