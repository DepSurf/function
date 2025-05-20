# Function: <code>tty_ldisc_unlock</code>

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
In drivers/tty/tty_ldisc.c (ffffffff814e9d75)
Location: drivers/tty/tty_ldisc.c:337
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
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
In drivers/tty/tty_ldisc.c (ffffffff8153b1b0)
Location: drivers/tty/tty_ldisc.c:347
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
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
In drivers/tty/tty_ldisc.c (ffffffff81567860)
Location: drivers/tty/tty_ldisc.c:347
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
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
In drivers/tty/tty_ldisc.c (ffffffff8157afb0)
Location: drivers/tty/tty_ldisc.c:350
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815df996)
Location: drivers/tty/tty_ldisc.c:351
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff815df7b0-ffffffff815df7cc: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81618c27)
Location: drivers/tty/tty_ldisc.c:337
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81618a30-ffffffff81618a4c: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81635a40)
Location: drivers/tty/tty_ldisc.c:342
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81635a40-ffffffff81635a64: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81669bd0)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81669bd0-ffffffff81669bf4: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8168c300)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8168c300-ffffffff8168c324: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e330)
Location: drivers/tty/tty_ldisc.c:346
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8173e330-ffffffff8173e354: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8175a290)
Location: drivers/tty/tty_ldisc.c:345
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8175a290-ffffffff8175a2b4: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e150)
Location: drivers/tty/tty_ldisc.c:346
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8173e150-ffffffff8173e174: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff817be740)
Location: drivers/tty/tty_ldisc.c:331
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff817be740-ffffffff817be764: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff818fab30)
Location: drivers/tty/tty_ldisc.c:321
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff818fab30-ffffffff818fab5a: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a53cd0)
Location: drivers/tty/tty_ldisc.c:321
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81a53cd0-ffffffff81a53cfa: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a9e0e0)
Location: drivers/tty/tty_ldisc.c:320
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81a9e0e0-ffffffff81a9e10a: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81af0c00)
Location: drivers/tty/tty_ldisc.c:320
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81af0c00-ffffffff81af0c2a: tty_ldisc_unlock (STB_GLOBAL)
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
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffff80001085c7d8)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffff80001085c7d8-ffff80001085c85c: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0964860)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
c0964860-c09648a0: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0000000008fb7e0)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
c0000000008fb7e0-c0000000008fb844: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffe000535cde)
Location: drivers/tty/tty_ldisc.c:351
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
```
**Symbols:**

```
ffffffe000535b1e-ffffffe000535b62: tty_ldisc_unlock (STB_GLOBAL)
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
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81651d80)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81651d80-ffffffff81651da4: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816321c0)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff816321c0-ffffffff816321e4: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81680140)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81680140-ffffffff81680164: tty_ldisc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_ldisc_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8169a790)
Location: drivers/tty/tty_ldisc.c:351
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8169a790-ffffffff8169a7b4: tty_ldisc_unlock (STB_GLOBAL)
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
