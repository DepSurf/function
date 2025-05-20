# Function: <code>serial8250_rpm_get_tx</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff81508b3c)
Location: drivers/tty/serial/8250/8250_port.c:536
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8155ad0c)
Location: drivers/tty/serial/8250/8250_port.c:638
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81585630)
Location: drivers/tty/serial/8250/8250_port.c:639
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81585630-ffffffff8158564c: serial8250_rpm_get_tx.part.17 (STB_LOCAL)
ffffffff81585670-ffffffff8158569a: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81598db0)
Location: drivers/tty/serial/8250/8250_port.c:655
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81598d70-ffffffff81598d8c: serial8250_rpm_get_tx.part.14 (STB_LOCAL)
ffffffff81598db0-ffffffff81598dda: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fdbc0)
Location: drivers/tty/serial/8250/8250_port.c:674
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff815fdb80-ffffffff815fdb9c: serial8250_rpm_get_tx.part.14 (STB_LOCAL)
ffffffff815fdbc0-ffffffff815fdbec: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81637500)
Location: drivers/tty/serial/8250/8250_port.c:675
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff816374c0-ffffffff816374dc: serial8250_rpm_get_tx.part.14 (STB_LOCAL)
ffffffff81637500-ffffffff8163752b: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81655ae0)
Location: drivers/tty/serial/8250/8250_port.c:675
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81655aa0-ffffffff81655abc: serial8250_rpm_get_tx.part.16 (STB_LOCAL)
ffffffff81655ae0-ffffffff81655b0b: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689c80)
Location: drivers/tty/serial/8250/8250_port.c:683
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81689c80-ffffffff81689cb5: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ac230)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff816ac230-ffffffff816ac265: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81760628)
Location: drivers/tty/serial/8250/8250_port.c:711
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff8175edf0-ffffffff8175ee25: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b4a8)
Location: drivers/tty/serial/8250/8250_port.c:712
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81779c70-ffffffff81779ca5: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175eb28)
Location: drivers/tty/serial/8250/8250_port.c:716
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff8175d5a0-ffffffff8175d5d5: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e2f88)
Location: drivers/tty/serial/8250/8250_port.c:717
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff817e1370-ffffffff817e13a5: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923cf8)
Location: drivers/tty/serial/8250/8250_port.c:704
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81920170-ffffffff819201b9: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a80858)
Location: drivers/tty/serial/8250/8250_port.c:698
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81a7c840-ffffffff81a7c889: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acbe78)
Location: drivers/tty/serial/8250/8250_port.c:642
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81ac7f20-ffffffff81ac7f69: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e618)
Location: drivers/tty/serial/8250/8250_port.c:643
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81b1afd0-ffffffff81b1b019: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010887888)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffff800010886f88-ffff800010886fb8: serial8250_rpm_get_tx.part.0 (STB_LOCAL)
ffff800010887888-ffff8000108878ec: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0985e44)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
c0985470-c0985494: serial8250_rpm_get_tx.part.0 (STB_LOCAL)
c0985e44-c0985e98: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092e020)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
c00000000092e020-c00000000092e090: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551f16)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffe000551eb2-ffffffe000551ee0: serial8250_rpm_get_tx.part.0 (STB_LOCAL)
ffffffe000551f16-ffffffe000551f66: serial8250_rpm_get_tx (STB_GLOBAL)
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
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671ca0)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81671ca0-ffffffff81671cd5: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650da0)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81650da0-ffffffff81650dd5: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a0070)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff816a0070-ffffffff816a00a5: serial8250_rpm_get_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba530)
Location: drivers/tty/serial/8250/8250_port.c:676
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff816ba530-ffffffff816ba565: serial8250_rpm_get_tx (STB_GLOBAL)
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
