# Function: <code>mid8250_set_termios</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mid8250_set_termios(struct uart_port *p, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_mid.c (0)
Location: drivers/tty/serial/8250/8250_mid.c:209
Inline: False
```
**Symbols:**

```
ffffffff81a87e10-ffffffff81a87f78: mid8250_set_termios (STB_LOCAL)
ffffffff82096182-ffffffff820961a8: mid8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mid8250_set_termios(struct uart_port *p, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_mid.c (0)
Location: drivers/tty/serial/8250/8250_mid.c:209
Inline: False
```
**Symbols:**

```
ffffffff81ad3500-ffffffff81ad3668: mid8250_set_termios (STB_LOCAL)
ffffffff82117094-ffffffff821170ba: mid8250_set_termios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mid8250_set_termios(struct uart_port *p, struct ktermios *termios, const struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_mid.c (0)
Location: drivers/tty/serial/8250/8250_mid.c:207
Inline: False
```
**Symbols:**

```
ffffffff81b22be0-ffffffff81b22d47: mid8250_set_termios (STB_LOCAL)
ffffffff821f4d33-ffffffff821f4d59: mid8250_set_termios.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
