# Function: <code>stop_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0250)
Location: drivers/tty/tty_io.c:983
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff814e0250-ffffffff814e02ba: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81531ae0)
Location: drivers/tty/tty_io.c:989
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81531ae0-ffffffff81531b4a: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155e210)
Location: drivers/tty/tty_io.c:989
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff8155e210-ffffffff8155e27a: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81574250)
Location: drivers/tty/tty_io.c:754
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81574250-ffffffff815742ba: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d73d0)
Location: drivers/tty/tty_io.c:766
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff815d73d0-ffffffff815d743d: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610380)
Location: drivers/tty/tty_io.c:775
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81610380-ffffffff816103e2: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162d180)
Location: drivers/tty/tty_io.c:776
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff8162d180-ffffffff8162d1e2: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660de0)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81660de0-ffffffff81660e48: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683430)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81683430-ffffffff81683498: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81734dd0)
Location: drivers/tty/tty_io.c:779
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81734dd0-ffffffff81734e38: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81750d50)
Location: drivers/tty/tty_io.c:777
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81750d50-ffffffff81750db8: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81734bc0)
Location: drivers/tty/tty_io.c:793
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81734bc0-ffffffff81734c28: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:789
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81cf8765-ffffffff81cf8779: stop_tty.cold (STB_LOCAL)
ffffffff817b57e0-ffffffff817b5852: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:779
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81ec0898-ffffffff81ec08ad: stop_tty.cold (STB_LOCAL)
ffffffff818f1790-ffffffff818f180a: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:773
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff82094f8e-ffffffff82094fa3: stop_tty.cold (STB_LOCAL)
ffffffff81a49810-ffffffff81a4988a: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:774
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff82115dac-ffffffff82115dc1: stop_tty.cold (STB_LOCAL)
ffffffff81a93a40-ffffffff81a93aba: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:772
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff821f3ab3-ffffffff821f3ac8: stop_tty.cold (STB_LOCAL)
ffffffff81ae64b0-ffffffff81ae652a: stop_tty (STB_GLOBAL)
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
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084ffc8)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffff80001084ffc8-ffff800010850088: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095c14c)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
c095c14c-c095c1b0: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f03e0)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
c0000000008f03e0-c0000000008f0480: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052e026)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffe00052e026-ffffffe00052e086: stop_tty (STB_GLOBAL)
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
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81648eb0)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81648eb0-ffffffff81648f18: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629310)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81629310-ffffffff81629378: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677270)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81677270-ffffffff816772d8: stop_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void stop_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81691990)
Location: drivers/tty/tty_io.c:778
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/vt/keyboard.c:fn_hold
```
**Symbols:**

```
ffffffff81691990-ffffffff816919f8: stop_tty (STB_GLOBAL)
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
