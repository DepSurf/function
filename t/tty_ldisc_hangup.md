# Function: <code>tty_ldisc_hangup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff814ea0b0)
Location: drivers/tty/tty_ldisc.c:660
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:__tty_hangup
```
**Symbols:**

```
ffffffff814ea0b0-ffffffff814ea29d: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8153b0d0)
Location: drivers/tty/tty_ldisc.c:700
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:__tty_hangup
```
**Symbols:**

```
ffffffff8153b0d0-ffffffff8153b281: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81567780)
Location: drivers/tty/tty_ldisc.c:701
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:__tty_hangup
```
**Symbols:**

```
ffffffff81567780-ffffffff81567931: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8157aed0)
Location: drivers/tty/tty_ldisc.c:721
Inline: False
```
**Symbols:**

```
ffffffff8157aed0-ffffffff8157b081: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815df8b0)
Location: drivers/tty/tty_ldisc.c:719
Inline: False
```
**Symbols:**

```
ffffffff815df8b0-ffffffff815dfa89: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81618b30)
Location: drivers/tty/tty_ldisc.c:702
Inline: False
```
**Symbols:**

```
ffffffff81618b30-ffffffff81618cfc: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81635d40)
Location: drivers/tty/tty_ldisc.c:713
Inline: False
```
**Symbols:**

```
ffffffff81635d40-ffffffff81635f03: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
ffffffff8166a1dc-ffffffff8166a1ef: tty_ldisc_hangup.cold (STB_LOCAL)
ffffffff81669ee0-ffffffff8166a0b7: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8168c610)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
ffffffff8168c610-ffffffff8168c7e9: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e640)
Location: drivers/tty/tty_ldisc.c:717
Inline: False
```
**Symbols:**

```
ffffffff8173e640-ffffffff8173e84c: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8175a5a0)
Location: drivers/tty/tty_ldisc.c:717
Inline: False
```
**Symbols:**

```
ffffffff8175a5a0-ffffffff8175a7ac: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e450)
Location: drivers/tty/tty_ldisc.c:725
Inline: False
```
**Symbols:**

```
ffffffff8173e450-ffffffff8173e65c: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff817bea40)
Location: drivers/tty/tty_ldisc.c:710
Inline: False
```
**Symbols:**

```
ffffffff817bea40-ffffffff817bec4c: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff818fae30)
Location: drivers/tty/tty_ldisc.c:685
Inline: False
```
**Symbols:**

```
ffffffff818fae30-ffffffff818fb032: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a54010)
Location: drivers/tty/tty_ldisc.c:685
Inline: False
```
**Symbols:**

```
ffffffff81a54010-ffffffff81a54212: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a9e530)
Location: drivers/tty/tty_ldisc.c:684
Inline: False
```
**Symbols:**

```
ffffffff81a9e530-ffffffff81a9e766: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81af1050)
Location: drivers/tty/tty_ldisc.c:684
Inline: False
```
**Symbols:**

```
ffffffff81af1050-ffffffff81af1286: tty_ldisc_hangup (STB_GLOBAL)
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
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffff80001085cb28)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
ffff80001085cb28-ffff80001085cccc: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0964b24)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
c0964b24-c0964cd8: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0000000008fbc10)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
c0000000008fbc10-c0000000008fbe5c: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffe000535c18)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
ffffffe000535c18-ffffffe000535dcc: tty_ldisc_hangup (STB_GLOBAL)
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
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81652090)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
ffffffff81652090-ffffffff81652269: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816324d0)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
ffffffff816324d0-ffffffff816326a9: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81680450)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
ffffffff81680450-ffffffff81680629: tty_ldisc_hangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_ldisc_hangup(struct tty_struct *tty, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8169aaa0)
Location: drivers/tty/tty_ldisc.c:722
Inline: False
```
**Symbols:**

```
ffffffff8169aaa0-ffffffff8169ac79: tty_ldisc_hangup (STB_GLOBAL)
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
<code>bool reinit</code>
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
