# Function: <code>fintek_8250_set_termios</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81601f00)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff81601f00-ffffffff8160208c: fintek_8250_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8163b1c0)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff8163b1c0-ffffffff8163b33e: fintek_8250_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816593f0)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff816593f0-ffffffff8165956e: fintek_8250_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff8168ea50-ffffffff8168eba7: fintek_8250_set_termios (STB_LOCAL)
ffffffff8168efc0-ffffffff8168efe2: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff816b1280-ffffffff816b13d7: fintek_8250_set_termios (STB_LOCAL)
ffffffff816b17f0-ffffffff816b1812: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:312
Inline: False
```
**Symbols:**

```
ffffffff81764460-ffffffff81764633: fintek_8250_set_termios (STB_LOCAL)
ffffffff81764d75-ffffffff81764d97: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:312
Inline: False
```
**Symbols:**

```
ffffffff8177f380-ffffffff8177f553: fintek_8250_set_termios (STB_LOCAL)
ffffffff81c07eea-ffffffff81c07f0c: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:312
Inline: False
```
**Symbols:**

```
ffffffff81762cc0-ffffffff81762e93: fintek_8250_set_termios (STB_LOCAL)
ffffffff81bf9aaa-ffffffff81bf9acc: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:293
Inline: False
```
**Symbols:**

```
ffffffff817e6dd0-ffffffff817e70a3: fintek_8250_set_termios (STB_LOCAL)
ffffffff81cfa023-ffffffff81cfa045: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:293
Inline: False
```
**Symbols:**

```
ffffffff819267a0-ffffffff81926a4f: fintek_8250_set_termios (STB_LOCAL)
ffffffff81ec22d7-ffffffff81ec22f9: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81a83460)
Location: drivers/tty/serial/8250/8250_fintek.c:279
Inline: False
```
**Symbols:**

```
ffffffff81a83460-ffffffff81a8372d: fintek_8250_set_termios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81aceac0)
Location: drivers/tty/serial/8250/8250_fintek.c:279
Inline: False
```
**Symbols:**

```
ffffffff81aceac0-ffffffff81aced8d: fintek_8250_set_termios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81b21b80)
Location: drivers/tty/serial/8250/8250_fintek.c:279
Inline: False
```
**Symbols:**

```
ffffffff81b21b80-ffffffff81b21e4d: fintek_8250_set_termios (STB_LOCAL)
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
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffff80001088c848)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffff80001088c848-ffff80001088c9dc: fintek_8250_set_termios (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffe0005564ec)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffe0005564ec-ffffffe000556670: fintek_8250_set_termios (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff81676cf0-ffffffff81676e47: fintek_8250_set_termios (STB_LOCAL)
ffffffff81677260-ffffffff81677282: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff81655dd0-ffffffff81655f27: fintek_8250_set_termios (STB_LOCAL)
ffffffff81656340-ffffffff81656362: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff816a50c0-ffffffff816a5217: fintek_8250_set_termios (STB_LOCAL)
ffffffff816a5630-ffffffff816a5652: fintek_8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fintek_8250_set_termios(struct uart_port *port, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (0)
Location: drivers/tty/serial/8250/8250_fintek.c:306
Inline: False
```
**Symbols:**

```
ffffffff816bf520-ffffffff816bf677: fintek_8250_set_termios (STB_LOCAL)
ffffffff816bfa90-ffffffff816bfab2: fintek_8250_set_termios.cold (STB_LOCAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ktermios *old</code> ➡️ <code>const struct ktermios *old</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
