# Function: <code>tty_ldisc_reinit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int ldisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff814e9b90)
Location: drivers/tty/tty_ldisc.c:627
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff814e9b90-ffffffff814e9c4d: tty_ldisc_reinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8153afd0)
Location: drivers/tty/tty_ldisc.c:656
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff8153afd0-ffffffff8153b0c6: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81567690)
Location: drivers/tty/tty_ldisc.c:656
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81567690-ffffffff8156777e: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8157ade0)
Location: drivers/tty/tty_ldisc.c:676
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff8157ade0-ffffffff8157aec5: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815df7d0)
Location: drivers/tty/tty_ldisc.c:677
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff815df7d0-ffffffff815df8a8: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81618a50)
Location: drivers/tty/tty_ldisc.c:660
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81618a50-ffffffff81618b28: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81635c60)
Location: drivers/tty/tty_ldisc.c:670
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81635c60-ffffffff81635d38: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81669e10)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81669e10-ffffffff81669edc: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8168c540)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff8168c540-ffffffff8168c60c: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e570)
Location: drivers/tty/tty_ldisc.c:674
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff8173e570-ffffffff8173e63c: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8175a4d0)
Location: drivers/tty/tty_ldisc.c:673
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff8175a4d0-ffffffff8175a59c: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e380)
Location: drivers/tty/tty_ldisc.c:681
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff8173e380-ffffffff8173e44c: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff817be970)
Location: drivers/tty/tty_ldisc.c:666
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff817be970-ffffffff817bea3c: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff818fad40)
Location: drivers/tty/tty_ldisc.c:642
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff818fad40-ffffffff818fae24: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a53f10)
Location: drivers/tty/tty_ldisc.c:642
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81a53f10-ffffffff81a53ff4: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a9e3c0)
Location: drivers/tty/tty_ldisc.c:641
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81a9e3c0-ffffffff81a9e51a: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81af0ee0)
Location: drivers/tty/tty_ldisc.c:641
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81af0ee0-ffffffff81af103a: tty_ldisc_reinit (STB_GLOBAL)
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
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffff80001085ca58)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffff80001085ca58-ffff80001085cb28: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0964a6c)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
c0964a6c-c0964b24: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0000000008fbac0)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
c0000000008fbac0-c0000000008fbc04: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffe000535b62)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffe000535b62-ffffffe000535c18: tty_ldisc_reinit (STB_GLOBAL)
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
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81651fc0)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81651fc0-ffffffff8165208c: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81632400)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81632400-ffffffff816324cc: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81680380)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81680380-ffffffff8168044c: tty_ldisc_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_ldisc_reinit(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8169a9d0)
Location: drivers/tty/tty_ldisc.c:679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff8169a9d0-ffffffff8169aa9c: tty_ldisc_reinit (STB_GLOBAL)
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
<b>Param added. </b>
<code>int disc</code>
</li>
<li>
<b>Param removed. </b>
<code>int ldisc</code>
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
