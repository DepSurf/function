# Function: <code>n_tty_receive_char_flagged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff814e5010)
Location: drivers/tty/n_tty.c:1472
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff814e5010-ffffffff814e51b9: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81536200)
Location: drivers/tty/n_tty.c:1444
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81536200-ffffffff81536404: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81562930)
Location: drivers/tty/n_tty.c:1444
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81562930-ffffffff81562b34: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81576930)
Location: drivers/tty/n_tty.c:1444
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81576930-ffffffff81576b27: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff815db2b0)
Location: drivers/tty/n_tty.c:1442
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff815db2b0-ffffffff815db4a7: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff816143c0)
Location: drivers/tty/n_tty.c:1460
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff816143c0-ffffffff816145b2: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81631670)
Location: drivers/tty/n_tty.c:1473
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81631670-ffffffff81631862: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81665660)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81665660-ffffffff81665843: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81687cb0)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81687cb0-ffffffff81687e93: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817398f0)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff817398f0-ffffffff81739ad0: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81755de0)
Location: drivers/tty/n_tty.c:1471
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81755de0-ffffffff81755fc1: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81739b10)
Location: drivers/tty/n_tty.c:1472
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81739b10-ffffffff81739cf1: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817ba5c0)
Location: drivers/tty/n_tty.c:1440
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff817ba5c0-ffffffff817ba7a1: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff818f6b40)
Location: drivers/tty/n_tty.c:1425
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff818f6b40-ffffffff818f6d5a: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a4f680)
Location: drivers/tty/n_tty.c:1448
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff81a4f680-ffffffff81a4f8c9: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a99890)
Location: drivers/tty/n_tty.c:1447
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff81a99890-ffffffff81a99ad1: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, u8 c, u8 flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81aec4f0)
Location: drivers/tty/n_tty.c:1465
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff81aec4f0-ffffffff81aec6f9: n_tty_receive_char_flagged (STB_LOCAL)
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
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffff800010855020)
Location: drivers/tty/n_tty.c:1475
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffff800010855020-ffff800010855200: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (c095fcb0)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
c095fcb0-c095fea8: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (c0000000008f5240)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
c0000000008f5240-c0000000008f54b4: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffe0005310fa)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffe0005310fa-ffffffe00053129a: n_tty_receive_char_flagged (STB_LOCAL)
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
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8164d730)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff8164d730-ffffffff8164d913: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8162db80)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff8162db80-ffffffff8162dd63: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8167baf0)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff8167baf0-ffffffff8167bcd3: n_tty_receive_char_flagged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct *tty, unsigned char c, char flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81696150)
Location: drivers/tty/n_tty.c:1475
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
**Symbols:**

```
ffffffff81696150-ffffffff81696333: n_tty_receive_char_flagged (STB_LOCAL)
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
<code>unsigned char c</code> ➡️ <code>u8 c</code>
</li>
<li>
<b>Param type changed. </b>
<code>char flag</code> ➡️ <code>u8 flag</code>
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
