# Function: <code>uart_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81503fc0)
Location: drivers/tty/serial/serial_core.c:1375
Inline: False
```
**Symbols:**

```
ffffffff81503fc0-ffffffff81504213: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81555600)
Location: drivers/tty/serial/serial_core.c:1464
Inline: False
```
**Symbols:**

```
ffffffff81555600-ffffffff815558b8: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81581c60)
Location: drivers/tty/serial/serial_core.c:1461
Inline: True
```
**Symbols:**

```
ffffffff81581c60-ffffffff81581cf8: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81595e30)
Location: drivers/tty/serial/serial_core.c:1467
Inline: True
```
**Symbols:**

```
ffffffff81595e30-ffffffff81595ecb: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815faa00)
Location: drivers/tty/serial/serial_core.c:1479
Inline: True
```
**Symbols:**

```
ffffffff815faa00-ffffffff815faa9b: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81632740)
Location: drivers/tty/serial/serial_core.c:1486
Inline: True
```
**Symbols:**

```
ffffffff81632740-ffffffff816327d8: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81651ac0)
Location: drivers/tty/serial/serial_core.c:1545
Inline: True
```
**Symbols:**

```
ffffffff81651ac0-ffffffff81651b58: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81686620)
Location: drivers/tty/serial/serial_core.c:1539
Inline: True
```
**Symbols:**

```
ffffffff81686620-ffffffff816866be: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a8d30)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
ffffffff816a8d30-ffffffff816a8dce: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817595c0)
Location: drivers/tty/serial/serial_core.c:1539
Inline: False
```
**Symbols:**

```
ffffffff817595c0-ffffffff8175965e: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81774690)
Location: drivers/tty/serial/serial_core.c:1545
Inline: False
```
**Symbols:**

```
ffffffff81774690-ffffffff8177472e: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8175a3d0)
Location: drivers/tty/serial/serial_core.c:1544
Inline: False
```
**Symbols:**

```
ffffffff8175a3d0-ffffffff8175a46e: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817dd940)
Location: drivers/tty/serial/serial_core.c:1532
Inline: False
```
**Symbols:**

```
ffffffff817dd940-ffffffff817dd9db: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81917cd0)
Location: drivers/tty/serial/serial_core.c:1567
Inline: False
```
**Symbols:**

```
ffffffff81917cd0-ffffffff81917d63: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a735e0)
Location: drivers/tty/serial/serial_core.c:1683
Inline: False
```
**Symbols:**

```
ffffffff81a735e0-ffffffff81a73673: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abeb50)
Location: drivers/tty/serial/serial_core.c:1704
Inline: True
```
**Symbols:**

```
ffffffff81abeb50-ffffffff81abebe3: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b118d0)
Location: drivers/tty/serial/serial_core.c:1740
Inline: True
```
**Symbols:**

```
ffffffff81b118d0-ffffffff81b11960: uart_close (STB_LOCAL)
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
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087f8f0)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
ffff80001087f8f0-ffff80001087f9e8: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097f73c)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
c097f73c-c097f7ec: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c0000000009297b0)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
c0000000009297b0-c0000000009298b4: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054f13e)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
ffffffe00054f13e-ffffffe00054f214: uart_close (STB_LOCAL)
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
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166e790)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
ffffffff8166e790-ffffffff8166e82e: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164c840)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
ffffffff8164c840-ffffffff8164c8d8: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8169cb70)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
ffffffff8169cb70-ffffffff8169cc0e: uart_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void uart_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b4920)
Location: drivers/tty/serial/serial_core.c:1538
Inline: True
```
**Symbols:**

```
ffffffff816b4920-ffffffff816b49b5: uart_close (STB_LOCAL)
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
