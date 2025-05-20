# Function: <code>serial8250_em485_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81557850)
Location: drivers/tty/serial/8250/8250_port.c:620
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff81557850-ffffffff81557898: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81584050)
Location: drivers/tty/serial/8250/8250_port.c:621
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff81584050-ffffffff81584098: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815984e0)
Location: drivers/tty/serial/8250/8250_port.c:637
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff815984e0-ffffffff8159852d: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fd1c0)
Location: drivers/tty/serial/8250/8250_port.c:656
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff815fd1c0-ffffffff815fd20d: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81636510)
Location: drivers/tty/serial/8250/8250_port.c:657
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff81636510-ffffffff81636558: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816547d0)
Location: drivers/tty/serial/8250/8250_port.c:657
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff816547d0-ffffffff81654818: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816891b0)
Location: drivers/tty/serial/8250/8250_port.c:665
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff816891b0-ffffffff816891f8: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab8d0)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff816ab8d0-ffffffff816ab918: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175f29e)
Location: drivers/tty/serial/8250/8250_port.c:644
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff8175e530-ffffffff8175e57b: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177a11e)
Location: drivers/tty/serial/8250/8250_port.c:645
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff817793b0-ffffffff817793fb: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175d82c)
Location: drivers/tty/serial/8250/8250_port.c:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff8175cc70-ffffffff8175ccbb: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e173c)
Location: drivers/tty/serial/8250/8250_port.c:650
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff817e0ad0-ffffffff817e0b1b: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff819206ea)
Location: drivers/tty/serial/8250/8250_port.c:637
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff8191f8e0-ffffffff8191f933: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7ce09)
Location: drivers/tty/serial/8250/8250_port.c:639
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff81a7be70-ffffffff81a7bec3: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac8429)
Location: drivers/tty/serial/8250/8250_port.c:582
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff81ac7160-ffffffff81ac71b3: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1b4d9)
Location: drivers/tty/serial/8250/8250_port.c:583
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff81b1a200-ffffffff81b1a253: serial8250_em485_destroy (STB_GLOBAL)
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
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010886420)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffff800010886420-ffff800010886468: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0984914)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
c0984914-c098495c: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092cfb0)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
c00000000092cfb0-c00000000092d020: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe0005516b2)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffe0005516b2-ffffffe000551700: serial8250_em485_destroy (STB_GLOBAL)
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
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671340)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff81671340-ffffffff81671388: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650440)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff81650440-ffffffff81650488: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f710)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff8169f710-ffffffff8169f758: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void serial8250_em485_destroy(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9bd0)
Location: drivers/tty/serial/8250/8250_port.c:658
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
```
**Symbols:**

```
ffffffff816b9bd0-ffffffff816b9c18: serial8250_em485_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
