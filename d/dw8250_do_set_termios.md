# Function: <code>dw8250_do_set_termios</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dw8250_do_set_termios(struct uart_port *p, struct ktermios *termios, struct ktermios *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff819261f0)
Location: drivers/tty/serial/8250/8250_dwlib.c:78
Inline: False
```
**Symbols:**

```
ffffffff819261f0-ffffffff8192622d: dw8250_do_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dw8250_do_set_termios(struct uart_port *p, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81a82c60)
Location: drivers/tty/serial/8250/8250_dwlib.c:95
Inline: False
```
**Symbols:**

```
ffffffff81a82c60-ffffffff81a82cb9: dw8250_do_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dw8250_do_set_termios(struct uart_port *p, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81ace290)
Location: drivers/tty/serial/8250/8250_dwlib.c:95
Inline: False
```
**Symbols:**

```
ffffffff81ace290-ffffffff81ace2e9: dw8250_do_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dw8250_do_set_termios(struct uart_port *p, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81b21360)
Location: drivers/tty/serial/8250/8250_dwlib.c:95
Inline: False
```
**Symbols:**

```
ffffffff81b21360-ffffffff81b213b9: dw8250_do_set_termios (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
