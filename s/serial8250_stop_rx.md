# Function: <code>serial8250_stop_rx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81507940)
Location: drivers/tty/serial/8250/8250_port.c:1356
Inline: False
```
**Symbols:**

```
ffffffff81507940-ffffffff8150799b: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81559160)
Location: drivers/tty/serial/8250/8250_port.c:1390
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81559160-ffffffff815591bb: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81585a00)
Location: drivers/tty/serial/8250/8250_port.c:1393
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81585a00-ffffffff81585a56: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815990d0)
Location: drivers/tty/serial/8250/8250_port.c:1409
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff815990d0-ffffffff81599126: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fdf20)
Location: drivers/tty/serial/8250/8250_port.c:1428
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff815fdf20-ffffffff815fdf7c: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81637850)
Location: drivers/tty/serial/8250/8250_port.c:1429
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81637850-ffffffff816378aa: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81655e30)
Location: drivers/tty/serial/8250/8250_port.c:1428
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81655e30-ffffffff81655e8a: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168a000)
Location: drivers/tty/serial/8250/8250_port.c:1436
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff8168a000-ffffffff8168a065: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ac580)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff816ac580-ffffffff816ac5e5: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817613f7)
Location: drivers/tty/serial/8250/8250_port.c:1423
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
**Symbols:**

```
ffffffff8175f490-ffffffff8175f517: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177bf47)
Location: drivers/tty/serial/8250/8250_port.c:1424
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
**Symbols:**

```
ffffffff8177a310-ffffffff8177a397: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175f350)
Location: drivers/tty/serial/8250/8250_port.c:1430
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
**Symbols:**

```
ffffffff8175db90-ffffffff8175dc17: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e29b0)
Location: drivers/tty/serial/8250/8250_port.c:1431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
**Symbols:**

```
ffffffff817e1ae0-ffffffff817e1b67: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81921dba)
Location: drivers/tty/serial/8250/8250_port.c:1418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
**Symbols:**

```
ffffffff81920aa0-ffffffff81920b33: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7e63a)
Location: drivers/tty/serial/8250/8250_port.c:1418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
**Symbols:**

```
ffffffff81a7d1d0-ffffffff81a7d263: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac9c38)
Location: drivers/tty/serial/8250/8250_port.c:1380
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
**Symbols:**

```
ffffffff81ac89e0-ffffffff81ac8a73: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1cd18)
Location: drivers/tty/serial/8250/8250_port.c:1380
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
```
**Symbols:**

```
ffffffff81b1bac0-ffffffff81b1bb53: serial8250_stop_rx (STB_LOCAL)
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
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff8000108872d0)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffff8000108872d0-ffff800010887340: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c09857c0)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
c09857c0-c0985828: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092e530)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
c00000000092e530-c00000000092e5d8: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe0005521ec)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffe0005521ec-ffffffe000552256: serial8250_stop_rx (STB_LOCAL)
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
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671ff0)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff81671ff0-ffffffff81672055: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816510f0)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff816510f0-ffffffff81651155: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a03c0)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff816a03c0-ffffffff816a0425: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void serial8250_stop_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba880)
Location: drivers/tty/serial/8250/8250_port.c:1385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
**Symbols:**

```
ffffffff816ba880-ffffffff816ba8e5: serial8250_stop_rx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
