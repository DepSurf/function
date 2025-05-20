# Function: <code>uart_flush_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815011b0)
Location: drivers/tty/serial/serial_core.c:587
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff815011b0-ffffffff8150125b: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81553470)
Location: drivers/tty/serial/serial_core.c:620
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81553470-ffffffff81553599: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157fed0)
Location: drivers/tty/serial/serial_core.c:612
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff8157fed0-ffffffff8157fff2: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81594310)
Location: drivers/tty/serial/serial_core.c:613
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81594310-ffffffff81594413: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f9030)
Location: drivers/tty/serial/serial_core.c:621
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff815f9030-ffffffff815f9136: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81631cb0)
Location: drivers/tty/serial/serial_core.c:628
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81631cb0-ffffffff81631dac: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164ff20)
Location: drivers/tty/serial/serial_core.c:645
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff8164ff20-ffffffff8165001c: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:642
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81684a10-ffffffff81684af0: uart_flush_buffer (STB_LOCAL)
ffffffff8168700c-ffffffff8168701f: uart_flush_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a7180)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff816a7180-ffffffff816a7266: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81758f30)
Location: drivers/tty/serial/serial_core.c:644
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81758f30-ffffffff81759012: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81773ff0)
Location: drivers/tty/serial/serial_core.c:645
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81773ff0-ffffffff817740d2: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817575e0)
Location: drivers/tty/serial/serial_core.c:645
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff817575e0-ffffffff817576c9: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817dae20)
Location: drivers/tty/serial/serial_core.c:628
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff817dae20-ffffffff817daf09: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8191a2e0)
Location: drivers/tty/serial/serial_core.c:626
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff8191a2e0-ffffffff8191a3dc: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a76020)
Location: drivers/tty/serial/serial_core.c:632
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81a76020-ffffffff81a76122: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81ac0870)
Location: drivers/tty/serial/serial_core.c:653
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81ac0870-ffffffff81ac0972: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b136e0)
Location: drivers/tty/serial/serial_core.c:646
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff81b136e0-ffffffff81b137e2: uart_flush_buffer (STB_LOCAL)
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
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087f280)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffff80001087f280-ffff80001087f418: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c09804e4)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
c09804e4-c0980620: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000927010)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
c000000000927010-c0000000009271b0: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054d226)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffe00054d226-ffffffe00054d316: uart_flush_buffer (STB_LOCAL)
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
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166cbe0)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff8166cbe0-ffffffff8166ccc6: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164bf90)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff8164bf90-ffffffff8164c076: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8169afc0)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff8169afc0-ffffffff8169b0a6: uart_flush_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uart_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b5a50)
Location: drivers/tty/serial/serial_core.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_hangup
```
**Symbols:**

```
ffffffff816b5a50-ffffffff816b5b36: uart_flush_buffer (STB_LOCAL)
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
