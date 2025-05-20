# Function: <code>uart_set_info</code>

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
In drivers/tty/serial/serial_core.c (ffffffff81503020)
Location: drivers/tty/serial/serial_core.c:729
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
In drivers/tty/serial/serial_core.c (ffffffff81554628)
Location: drivers/tty/serial/serial_core.c:786
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
In drivers/tty/serial/serial_core.c (ffffffff815811f8)
Location: drivers/tty/serial/serial_core.c:778
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
In drivers/tty/serial/serial_core.c (ffffffff81595100)
Location: drivers/tty/serial/serial_core.c:779
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
In drivers/tty/serial/serial_core.c (ffffffff815f9c48)
Location: drivers/tty/serial/serial_core.c:787
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
In drivers/tty/serial/serial_core.c (ffffffff81633533)
Location: drivers/tty/serial/serial_core.c:794
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81650f95)
Location: drivers/tty/serial/serial_core.c:810
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81685a30)
Location: drivers/tty/serial/serial_core.c:804
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff81685a30-ffffffff81685fea: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a80f0)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff816a80f0-ffffffff816a86fc: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8175a1f0)
Location: drivers/tty/serial/serial_core.c:806
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff8175a1f0-ffffffff8175a80f: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817752d0)
Location: drivers/tty/serial/serial_core.c:807
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff817752d0-ffffffff817758ef: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81758800)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff81758800-ffffffff81758dd4: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817dc9d0)
Location: drivers/tty/serial/serial_core.c:788
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff817dc9d0-ffffffff817dcfa4: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8191b7d0)
Location: drivers/tty/serial/serial_core.c:800
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff8191b7d0-ffffffff8191bda8: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a776b0)
Location: drivers/tty/serial/serial_core.c:806
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff81a776b0-ffffffff81a77c40: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81ac1fe0)
Location: drivers/tty/serial/serial_core.c:827
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff81ac1fe0-ffffffff81ac2570: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b157a0)
Location: drivers/tty/serial/serial_core.c:821
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff81b157a0-ffffffff81b15d30: uart_set_info (STB_LOCAL)
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
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff800010881118)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffff800010881118-ffff800010881670: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c0981c5c)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
c0981c5c-c09821d0: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000928930)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
c000000000928930-c000000000928fe8: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054e364)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffe00054e364-ffffffe00054e7d8: uart_set_info (STB_LOCAL)
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
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166db50)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff8166db50-ffffffff8166e15c: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164cfa0)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff8164cfa0-ffffffff8164d5ac: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8169bf30)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff8169bf30-ffffffff8169c53c: uart_set_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct *tty, struct tty_port *port, struct uart_state *state, struct serial_struct *new_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b6a70)
Location: drivers/tty/serial/serial_core.c:805
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff816b6a70-ffffffff816b707c: uart_set_info (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
