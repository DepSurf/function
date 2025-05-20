# Function: <code>tty_audit_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_audit_push(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff814ed650)
Location: drivers/tty/tty_audit.c:325
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff814ed650-ffffffff814ed723: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8153e040)
Location: drivers/tty/tty_audit.c:156
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff8153e040-ffffffff8153e0b6: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8156a690)
Location: drivers/tty/tty_audit.c:156
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff8156a690-ffffffff8156a706: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8157ecb0)
Location: drivers/tty/tty_audit.c:156
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff8157ecb0-ffffffff8157ed1a: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff815e3820)
Location: drivers/tty/tty_audit.c:154
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff815e3820-ffffffff815e388b: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8161cb00)
Location: drivers/tty/tty_audit.c:154
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff8161cb00-ffffffff8161cb6b: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81639d80)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81639d80-ffffffff81639deb: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (0)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff8166e406-ffffffff8166e412: tty_audit_push.cold (STB_LOCAL)
ffffffff8166e0a0-ffffffff8166e10d: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81690720)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81690720-ffffffff8169078c: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81742f40)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81742f40-ffffffff81742fe9: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8175edd0)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff8175edd0-ffffffff8175ee79: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81742af0)
Location: drivers/tty/tty_audit.c:154
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81742af0-ffffffff81742b99: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff817c3540)
Location: drivers/tty/tty_audit.c:154
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff817c3540-ffffffff817c35e9: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81900130)
Location: drivers/tty/tty_audit.c:154
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81900130-ffffffff819001d8: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81a59bd0)
Location: drivers/tty/tty_audit.c:154
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81a59bd0-ffffffff81a59c78: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81aa4200)
Location: drivers/tty/tty_audit.c:154
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81aa4200-ffffffff81aa42a8: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81af6bc0)
Location: drivers/tty/tty_audit.c:154
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81af6bc0-ffffffff81af6c68: tty_audit_push (STB_GLOBAL)
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
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffff8000108634e0)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffff8000108634e0-ffff80001086355c: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c09691f8)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
c09691f8-c0969278: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c000000000902320)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
c000000000902320-c0000000009023a8: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffe000539f98)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffe000539f98-ffffffe00053a004: tty_audit_push (STB_GLOBAL)
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
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff816561a0)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff816561a0-ffffffff8165620c: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81636530)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81636530-ffffffff8163659c: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81684560)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff81684560-ffffffff816845cc: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_audit_push();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8169eb70)
Location: drivers/tty/tty_audit.c:153
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff8169eb70-ffffffff8169ebdc: tty_audit_push (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct tty_struct *tty</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
