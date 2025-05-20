# Function: <code>n_tty_receive_buf_standard</code>

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
In drivers/tty/n_tty.c (ffffffff814e76fe)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff815387a0)
Location: drivers/tty/n_tty.c:1531
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff81564eb0)
Location: drivers/tty/n_tty.c:1531
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff81577d9d)
Location: drivers/tty/n_tty.c:1531
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff815dc720)
Location: drivers/tty/n_tty.c:1529
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff81615a29)
Location: drivers/tty/n_tty.c:1547
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff81632a10)
Location: drivers/tty/n_tty.c:1560
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff816674f1)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81689c41)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void n_tty_receive_buf_standard(struct tty_struct *tty, const unsigned char *cp, char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8173b9e0)
Location: drivers/tty/n_tty.c:1562
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff8173b9e0-ffffffff8173bd30: n_tty_receive_buf_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void n_tty_receive_buf_standard(struct tty_struct *tty, const unsigned char *cp, char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81757b50)
Location: drivers/tty/n_tty.c:1558
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81757b50-ffffffff81757e9f: n_tty_receive_buf_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void n_tty_receive_buf_standard(struct tty_struct *tty, const unsigned char *cp, char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8173bc30)
Location: drivers/tty/n_tty.c:1559
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff8173bc30-ffffffff8173bf7a: n_tty_receive_buf_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void n_tty_receive_buf_standard(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817bc430)
Location: drivers/tty/n_tty.c:1526
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff817bc430-ffffffff817bc598: n_tty_receive_buf_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void n_tty_receive_buf_standard(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff818f8660)
Location: drivers/tty/n_tty.c:1511
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff818f8660-ffffffff818f87de: n_tty_receive_buf_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void n_tty_receive_buf_standard(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count, bool lookahead_done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a51420)
Location: drivers/tty/n_tty.c:1555
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81a51420-ffffffff81a515ca: n_tty_receive_buf_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void n_tty_receive_buf_standard(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count, bool lookahead_done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a9b6f0)
Location: drivers/tty/n_tty.c:1554
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81a9b6f0-ffffffff81a9b87c: n_tty_receive_buf_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void n_tty_receive_buf_standard(struct tty_struct *tty, const u8 *cp, const u8 *fp, size_t count, bool lookahead_done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81aee240)
Location: drivers/tty/n_tty.c:1571
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81aee240-ffffffff81aee3cb: n_tty_receive_buf_standard (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffff80001085811c)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (c0961d74)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (c0000000008f70d8)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffe000532bca)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8164f6c1)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8162fb11)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8167da81)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff816980e1)
Location: drivers/tty/n_tty.c:1562
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *fp</code> ➡️ <code>const char *fp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool lookahead_done</code>
</li>
</ul>
</details>
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
<code>const unsigned char *cp</code> ➡️ <code>const u8 *cp</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *fp</code> ➡️ <code>const u8 *fp</code>
</li>
<li>
<b>Param type changed. </b>
<code>int count</code> ➡️ <code>size_t count</code>
</li>
</ul>
</details>
</li>
</ul>
