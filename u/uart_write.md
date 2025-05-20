# Function: <code>uart_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81500f70)
Location: drivers/tty/serial/serial_core.c:519
Inline: False
```
**Symbols:**

```
ffffffff81500f70-ffffffff81501083: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81553710)
Location: drivers/tty/serial/serial_core.c:553
Inline: False
```
**Symbols:**

```
ffffffff81553710-ffffffff815538cd: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81580330)
Location: drivers/tty/serial/serial_core.c:545
Inline: False
```
**Symbols:**

```
ffffffff81580330-ffffffff815804ed: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81595c10)
Location: drivers/tty/serial/serial_core.c:546
Inline: False
```
**Symbols:**

```
ffffffff81595c10-ffffffff81595e24: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815fa7e0)
Location: drivers/tty/serial/serial_core.c:554
Inline: False
```
**Symbols:**

```
ffffffff815fa7e0-ffffffff815fa9f4: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816327e0)
Location: drivers/tty/serial/serial_core.c:561
Inline: False
```
**Symbols:**

```
ffffffff816327e0-ffffffff81632a17: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81650840)
Location: drivers/tty/serial/serial_core.c:576
Inline: False
```
**Symbols:**

```
ffffffff81650840-ffffffff81650ab9: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:573
Inline: False
```
**Symbols:**

```
ffffffff816853b0-ffffffff816855e1: uart_write (STB_LOCAL)
ffffffff8168701f-ffffffff81687038: uart_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a7a70)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
ffffffff816a7a70-ffffffff816a7ca6: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8175b710)
Location: drivers/tty/serial/serial_core.c:575
Inline: False
```
**Symbols:**

```
ffffffff8175b710-ffffffff8175b8c1: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817767f0)
Location: drivers/tty/serial/serial_core.c:576
Inline: False
```
**Symbols:**

```
ffffffff817767f0-ffffffff817769a1: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81759c20)
Location: drivers/tty/serial/serial_core.c:576
Inline: False
```
**Symbols:**

```
ffffffff81759c20-ffffffff81759de7: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817dd150)
Location: drivers/tty/serial/serial_core.c:559
Inline: False
```
**Symbols:**

```
ffffffff817dd150-ffffffff817dd317: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8191c370)
Location: drivers/tty/serial/serial_core.c:557
Inline: False
```
**Symbols:**

```
ffffffff8191c370-ffffffff8191c54d: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a78310)
Location: drivers/tty/serial/serial_core.c:563
Inline: False
```
**Symbols:**

```
ffffffff81a78310-ffffffff81a784ed: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81ac2de0)
Location: drivers/tty/serial/serial_core.c:584
Inline: False
```
**Symbols:**

```
ffffffff81ac2de0-ffffffff81ac2fb9: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t uart_write(struct tty_struct *tty, const u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b13cb0)
Location: drivers/tty/serial/serial_core.c:580
Inline: False
```
**Symbols:**

```
ffffffff81b13cb0-ffffffff81b13eaf: uart_write (STB_LOCAL)
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
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff8000108818e8)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
ffff8000108818e8-ffff800010881ba8: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c0981428)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
c0981428-c0981640: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000927dd0)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
c000000000927dd0-c0000000009280e0: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054efb0)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
ffffffe00054efb0-ffffffe00054f13e: uart_write (STB_LOCAL)
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
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166d4d0)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
ffffffff8166d4d0-ffffffff8166d706: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164c600)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
ffffffff8164c600-ffffffff8164c836: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8169b8b0)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
ffffffff8169b8b0-ffffffff8169bae6: uart_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uart_write(struct tty_struct *tty, const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b63f0)
Location: drivers/tty/serial/serial_core.c:574
Inline: False
```
**Symbols:**

```
ffffffff816b63f0-ffffffff816b6626: uart_write (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *buf</code> ➡️ <code>const u8 *buf</code>
</li>
<li>
<b>Param type changed. </b>
<code>int count</code> ➡️ <code>size_t count</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
