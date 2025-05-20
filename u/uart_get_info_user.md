# Function: <code>uart_get_info_user</code>

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
In drivers/tty/serial/serial_core.c (ffffffff815032a2)
Location: drivers/tty/serial/serial_core.c:718
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
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
In drivers/tty/serial/serial_core.c (ffffffff81554998)
Location: drivers/tty/serial/serial_core.c:773
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81581568)
Location: drivers/tty/serial/serial_core.c:765
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815952a1)
Location: drivers/tty/serial/serial_core.c:766
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f9f2b)
Location: drivers/tty/serial/serial_core.c:774
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816339d0)
Location: drivers/tty/serial/serial_core.c:781
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164d970)
Location: drivers/tty/serial/serial_core.c:801
Inline: False
```
**Symbols:**

```
ffffffff8164d970-ffffffff8164d98d: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816824d0)
Location: drivers/tty/serial/serial_core.c:795
Inline: False
```
**Symbols:**

```
ffffffff816824d0-ffffffff816824ed: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a4b60)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
ffffffff816a4b60-ffffffff816a4b7d: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81757190)
Location: drivers/tty/serial/serial_core.c:797
Inline: False
```
**Symbols:**

```
ffffffff81757190-ffffffff817571ad: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81772310)
Location: drivers/tty/serial/serial_core.c:798
Inline: False
```
**Symbols:**

```
ffffffff81772310-ffffffff8177232d: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81755da0)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
ffffffff81755da0-ffffffff81755dbd: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d94d0)
Location: drivers/tty/serial/serial_core.c:779
Inline: False
```
**Symbols:**

```
ffffffff817d94d0-ffffffff817d94ed: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81917a90)
Location: drivers/tty/serial/serial_core.c:791
Inline: False
```
**Symbols:**

```
ffffffff81917a90-ffffffff81917ab5: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a735a0)
Location: drivers/tty/serial/serial_core.c:797
Inline: False
```
**Symbols:**

```
ffffffff81a735a0-ffffffff81a735c5: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abdce0)
Location: drivers/tty/serial/serial_core.c:818
Inline: False
```
**Symbols:**

```
ffffffff81abdce0-ffffffff81abdd05: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b10b40)
Location: drivers/tty/serial/serial_core.c:812
Inline: False
```
**Symbols:**

```
ffffffff81b10b40-ffffffff81b10b65: uart_get_info_user (STB_LOCAL)
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
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087cf88)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
ffff80001087cf88-ffff80001087cfc8: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097ea0c)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
c097ea0c-c097ea38: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000923af0)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
c000000000923af0-c000000000923b30: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054bad4)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
ffffffe00054bad4-ffffffe00054bb12: uart_get_info_user (STB_LOCAL)
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
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166a5c0)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
ffffffff8166a5c0-ffffffff8166a5dd: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81649730)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
ffffffff81649730-ffffffff8164974d: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816989a0)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
ffffffff816989a0-ffffffff816989bd: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b3060)
Location: drivers/tty/serial/serial_core.c:796
Inline: False
```
**Symbols:**

```
ffffffff816b3060-ffffffff816b307d: uart_get_info_user (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
