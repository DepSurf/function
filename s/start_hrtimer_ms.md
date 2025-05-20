# Function: <code>start_hrtimer_ms</code>

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
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fd210)
Location: drivers/tty/serial/8250/8250_port.c:1477
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
**Symbols:**

```
ffffffff815fd210-ffffffff815fd25d: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81636560)
Location: drivers/tty/serial/8250/8250_port.c:1478
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
**Symbols:**

```
ffffffff81636560-ffffffff816365ad: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654a70)
Location: drivers/tty/serial/8250/8250_port.c:1477
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff81654a70-ffffffff81654abd: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689450)
Location: drivers/tty/serial/8250/8250_port.c:1485
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff81689450-ffffffff816894bd: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816abb70)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff816abb70-ffffffff816abbdd: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81760798)
Location: drivers/tty/serial/8250/8250_port.c:1487
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b618)
Location: drivers/tty/serial/8250/8250_port.c:1488
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175ec90)
Location: drivers/tty/serial/8250/8250_port.c:1493
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e30f0)
Location: drivers/tty/serial/8250/8250_port.c:1494
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923f1e)
Location: drivers/tty/serial/8250/8250_port.c:1481
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a809f6)
Location: drivers/tty/serial/8250/8250_port.c:1481
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acc016)
Location: drivers/tty/serial/8250/8250_port.c:1449
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e7b6)
Location: drivers/tty/serial/8250/8250_port.c:1449
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
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
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff8000108866a8)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffff8000108866a8-ffff800010886724: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0984bbc)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
c0984bbc-c0984c30: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092d340)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
c00000000092d340-c00000000092d408: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe0005518f8)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffe0005518f8-ffffffe000551952: start_hrtimer_ms (STB_LOCAL)
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
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816715e0)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff816715e0-ffffffff8167164d: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816506e0)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff816506e0-ffffffff8165074d: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f9b0)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff8169f9b0-ffffffff8169fa1d: start_hrtimer_ms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void start_hrtimer_ms(struct hrtimer *hrt, long unsigned int msec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9e70)
Location: drivers/tty/serial/8250/8250_port.c:1434
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff816b9e70-ffffffff816b9edd: start_hrtimer_ms (STB_LOCAL)
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
